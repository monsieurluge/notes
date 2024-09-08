# notes

Personal static notes and knowledge base using [Memex](https://github.com/kormyen/memex).

## Constraints

By design the content is stored in a human readable flat file, `/content/data.ndtl`, and is intended to be edited in a text editor. This is to keep the system simple and to avoid the need for a database or other complex setup. By extension, no compilation or build step is required to generate the site which uses only static files.

The file format is called [Indental](https://wiki.xxiivv.com/#indental) and was created by Devine Lu Linvega, the programmer and artist of the [Hundred Rabbits](https://100r.co/site/home.html) collective.

## Indental Syntax

These keys can be used to structure the content:

- AUTH: author
- DATE: date
- FILE: path to the file relative to _content/media/_ (example: `FILE: image.jpg`)
- LINK: external link
- NOTE: personal note
- PERS:
- PROG: progress value (example: `PROG: 50%` or `PROG: 1/3`)
- PROJ: project name
- QOTE: quote
- TAGS: tags list separated by commas (example: `TAGS: tag1, tag2, tag3`)
- TERM:
- TYPE: type of content (see below)

### types

These types can be used to categorize the content and may change the way to display it.

- article
- author
- book
- dash
- date
- encyclopedia
- false
- file
- game
- image
- inspiration
- lecture
- link
- list
- music
- note
- podcast
- progress
- project
- quote
- service
- tags
- term
- tool
- true
- video
