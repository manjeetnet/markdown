![Showdown][sd-logo]

Showdown is a Javascript Markdown to HTML converter, based on the original works by John Gruber. It can be used client side (in the browser) or server side (with Node or io). 


# Installation

## Download tarball

You can download the latest release tarball directly from [releases][releases]

## Bower

    bower install showdown

## npm (server-side)

    npm install showdown

## CDN

You can also use one of several CDNs available: 

* rawgit CDN

        https://cdn.rawgit.com/showdownjs/showdown/<version tag>/dist/showdown.min.js

* cdnjs

        https://cdnjs.cloudflare.com/ajax/libs/showdown/<version tag>/showdown.min.js


[sd-logo]: https://raw.githubusercontent.com/showdownjs/logo/master/dist/logo.readme.png
[releases]: https://github.com/showdownjs/showdown/releases
[atx]: http://www.aaronsw.com/2002/atx/intro
[setext]: https://en.wikipedia.org/wiki/Setext

---------

# Syntax


## Table of contents

- [Introduction](#introduction)
- [Paragraphs](#paragraphs)
- [Headings](#headings)
  * [Atx Style](#atx-style)
  * [Setext style](#setext-style)
  * [Header IDs](#header-ids)
- [Blockquotes](#blockquotes)
- [Bold and Italic](#bold-and-italic)
- [Strikethrough](#strikethrough)
- [Emojis](#emojis)
- [Code formatting](#code-formatting)
  * [Inline formats](#inline-formats)
  * [Multiple lines](#multiple-lines)
- [Lists](#lists)
  * [Unordered lists](#unordered-lists)
  * [Ordered lists](#ordered-lists)
  * [TaskLists (GFM Style)](#tasklists--gfm-style-)
  * [List syntax](#list-syntax)
  * [Nested blocks](#nested-blocks)
  * [Nested lists](#nested-lists)
  * [Nested code blocks](#nested-code-blocks)
- [Links](#links)
  * [Simple](#simple)
  * [Inline](#inline)
  * [Reference Style](#reference-style)
- [Images](#images)
  * [Inline](#inline-1)
  * [Reference Style](#reference-style-1)
  * [Image dimensions](#image-dimensions)
  * [Base64 encoded images](#base64-encoded-images)
- [Tables](#tables)
- [Mentions](#mentions)
- [Handling HTML in markdown documents](#handling-html-in-markdown-documents)
- [Escaping entities](#escaping-entities)
  * [Escaping markdown entities](#escaping-markdown-entities)
  * [Escaping html tags](#escaping-html-tags)
- [Known differences and Gotchas](#known-differences-and-gotchas)