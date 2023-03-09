---
title: 'Sample technology integration'
excerpt: 'This is an article about how to write a technology integration for Threat Jammer.'
coverImage: ''
created: '2023-03-01'
updated: '2023-03-01'
readTime: 5
version: '1.0.0'
navigation:
  github: https://github.com/threatjammer/markdown-integrations/blob/main/sample-technology-integrations.md
  home: /integrations/main
  previous: 
  next: 
authors:
  - name: Diego Parrilla
    link: 'https://github.com/orgs/threatjammer/people/diegoparrilla'
ogImage:
  url: ''
tags: tutorial, sample, integration, variables
---

## Format types

# `#` H1: Title 
## `##` H2: Subtitle
### `###` H3: Subsubtitle
#### `####` H4: Subsubsubtitle

Normal text

**`**`Bold text`**`**

*`*`Italic text`*`*

~ `~` Strikethrough text `~`

* `*` List item 1
* `*` List item 2
* `*` List item 3

1. `1.` List item 1
2. `2.` List item 2
3. `3.` List item 3

## Code block

```
` ``` `
Code block
` ``` `
```

## Blockquote

> `>` Blockquote


## Images

![Images](https://picsum.photos/200/300)
`![Images](https://picsum.photos/200/300)`

## Tables

| Right | Left | Default | Center |
|------:|:-----|---------|:------:|
|   12  |  12  |    12   |    12  |
|  123  |  123 |   123   |   123  |
|    1  |    1 |     1   |     1  |


```
| Right | Left | Default | Center |
|------:|:-----|---------|:------:|
|   12  |  12  |    12   |    12  |
|  123  |  123 |   123   |   123  |
|    1  |    1 |     1   |     1  |
```

## Horizontal rule

---
`---`

## Links

[title](https://www.example.com)

`[title](https://www.example.com)`

## Footnotes

Here's a sentence with a footnote. [^1]
[^1]: This is the footnote.

`Here's a sentence with a footnote. [^1]`

`[^1]: This is the footnote.`


## Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

`- [x] Write the press release`

`- [ ] Update the website`

`- [ ] Contact the media`


## Variables

| Scope variable | Access | Value |
|:---------------|:-------|:------|
| User API Key | `{userApiKey}` | {userApiKey} |
| User API URL | `{userApiUrl}` | {userApiUrl} |
| Region City  | `{regionCity}` | {regionCity} |
| Region Name  | `{regionName}` | {regionName} |
| Region ID    | `{regionId}` | {regionId} |
| Region Index | `{regionIndex}` | {regionIndex} |
| Title        | `{title}` | {title} |
| Excerpt  | `{excerpt}` | {excerpt} |
| Cover Image  | `{coverImage}` | {coverImage} |
| Created  | `{created}` | {created} |
| Updated  | `{updated}` | {updated} |
| Read Time  | `{readTime}` | {readTime} |
| Version  | `{version}` | {version} |
| tags  | `{tags}` | {tags} |
| Author name  | `{authors[0].name}` | {authors[0].name} |
| Author link  | `{authors[0].link}` | {authors[0].link} |
| Github  | `{navigation.github}` | {navigation.github} |
| Return Home  | `{navigation.home}` | {navigation.home} |

