# CREST Statistics PhD Seminar

Website for the CREST Statistics PhD Seminar.

## Editing the program

Talks, organizers, and practical information are stored in `_data/seminar.yml`.

To add a talk, add an entry under the relevant academic year:

```yml
schedule:
  - year: 2026-2027
    sessions:
      - date: "2026-10-15"
        speaker: "Firstname Lastname"
        title: "Talk title"
        room: "ENSAE, room TBA"
        abstract: "Optional short abstract."
```

## Local preview

```sh
bundle install
bundle exec jekyll serve
```
