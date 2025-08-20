---
title: Creating docs and frontmatter
---
This is an example doc. Docs are Markdown files inside the `content/` directory.

---

## Creating new docs

Creating a new knowledge base doc is easy:

1. Using Obsidian, Visual Studio Code, iA Writer, any text editor, or via your computer's operating system file manager, create a new file with any name and ending with the `.md` file extension.
2. If this new file was created in the `content/` directory, then it is now a part of your knowledge base docs.

---
## Frontmatter/properties in docs

Because docs are all Markdown files, you can include additional metadata information at the top of them. 

This additional information is added as YAML frontmatter and placed between a pair of triple-dashed lines (an upper `---` and lower `---`).

> [!CAUTION]
> 
> 1. YAML frontmatter MUST be the first thing in a Markdown file.
> 2. YAML frontmatter MUST be placed between the triple-dashed lines (`---`).
> 

> [!TIP] Obsidian calls frontmatter `Properties`
> 
> *If you use Obsidian to edit your Markdown docs, YAML frontmatter is referred to as `Properties` or `File properties`*.
### Supported frontmatter

The knowledge base docs website is powered by [Quartz](https://quartz.jzhao.xyz/, a static-site generator for turning Markdown docs into websites.

#### Common frontmatter fields

These are the most common frontmatter fields:

- `title`: Title of the page. If it isn't provided, Quartz will use the name of the file as the title.
- `description`: Description of the page used for link previews.
- `permalink`: A custom URL for the page that will remain constant even if the path to the file changes.
- `aliases`: Other names for this note. This is a list of strings.
- `tags`: Tags for this note.
- `draft`: Whether to publish the page or not. This is one way to make [[private pages|pages private]] in Quartz.
- `date`: A string representing the day the note was published. Normally uses `YYYY-MM-DD` format.

(list via [the Quartz docs](https://github.com/jackyzha0/quartz/blob/v4/docs/authoring%20content.md))
#### Supported frontmatter fields

These are all of the frontmatter fields supported for your knowledge base docs website:

Quartz supports the following frontmatter:

- title
  - `title`
- description
  - `description`
- permalink
  - `permalink`
- comments
  - `comments`
- lang
  - `lang`
- publish
  - `publish`
- draft
  - `draft`
- enableToc
  - `enableToc`
- tags
  - `tags`
  - `tag`
- aliases
  - `aliases`
  - `alias`
- cssclasses
  - `cssclasses`
  - `cssclass`
- socialDescription
  - `socialDescription`
- socialImage
  - `socialImage`
  - `image`
  - `cover`
- created
  - `created`
  - `date`
- modified
  - `modified`
  - `lastmod`
  - `updated`
  - `last-modified`
- published
  - `published`
  - `publishDate`
  - `date`

(list via [the Quartz docs](https://github.com/jackyzha0/quartz/blob/v4/docs/plugins/Frontmatter.md))

--- 

## Markdown references

Here are some helpful references for the type of Markdown you can use in your knowledge base docs:

- [Basic formatting syntax](https://help.obsidian.md/syntax)
- [Obsidian Flavored Markdown](https://help.obsidian.md/obsidian-flavored-markdown)
- [GitHub Flavored Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
