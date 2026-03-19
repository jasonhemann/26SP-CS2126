# CS2126 Course Website

Course site built with Jekyll (GitHub Pages toolchain) and based on Minimal Mistakes.

## Required Toolchain

For local development and testing, install:

1. Ruby `3.3.4` (see [`.ruby-version`](.ruby-version))
2. Bundler
3. Git

## Local Setup

Install Ruby dependencies:

```bash
bundle install
```

Run locally with live reload:

```bash
bundle exec jekyll serve --livereload
```

Then open: `http://127.0.0.1:4000/26SP-CS2126/`

## Contributor Workflow

### 1) Update site author / people-page information

This repo does not use a separate personnel data file.

The People page at [`people.md`](people.md) renders the instructor contact information directly from [`_config.yml`](_config.yml), especially the `author.*` fields.

Typical edits here are:

- `author.name`
- `author.email`
- `author.emailaddr`
- `author.office_hours`
- `author.office_hours_location`

### 2) Update syllabus content

Primary syllabus source: [`syllabus.md`](syllabus.md)

Typical loop:

1. Edit `syllabus.md`
2. Run `bundle exec jekyll serve --livereload`
3. Review `http://127.0.0.1:4000/26SP-CS2126/syllabus/`

### 3) Update schedule and assignment materials

Schedule data lives in [`_data/schedule.yml`](_data/schedule.yml), and the page template is [`schedule.md`](schedule.md).

Starter files and assignment descriptions live under [`_starter_code/`](_starter_code/).

Typical loop:

1. Edit `_data/schedule.yml` and/or `_starter_code/*`
2. Run local server (`bundle exec jekyll serve --livereload`)
3. Review `http://127.0.0.1:4000/26SP-CS2126/schedule/`

## Notes

- Assignment links on the schedule page may point at `_starter_code/` paths in the source repository rather than generated website pages.
- The local Ruby/Jekyll toolchain is pinned in [`Gemfile`](Gemfile) and [`.ruby-version`](.ruby-version).
- The first `jekyll serve` on a new machine needs internet access to download the remote theme.
