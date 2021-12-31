# gvwiki-cont

## About

This repository contains the content files for [Greenville Wiki](https://greenville.wiki), the place for everything Greenville. Our goal is to make the wiki as graspable and complete as possible, and we rely on contributors for this task.

## Contributing

You can create new pages and edit existing ones without prior approval. Open a pull request once complete, or, if you are unable to fully finish a page, open a pull request as a draft.

For major changes, please open an [issue](https://github.com/gvwiki/cont/issues) first.

### Commit messages

To ease the navigation through git logs, we use our own version of [semantic commit messages](https://www.conventionalcommits.org/), which works as follows.

```
<type>: <subject>
^----^  ^-------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: cont, style, docs, conf or chore
```

- cont: major content changes (i.e., new page, overhaul, new section)
- style: minor content changes (i.e., formatting, missing commas, grammar)
- docs: repo documentation (i.e., README)
- conf: Grundgesetz/Gatsby configuration (i.e., sidebar)
- chore: updating tasks (i.e., actions)

i.e.:

- cont: add changelog
- cont: rewrite dealership
- style: add missing comma
- ...