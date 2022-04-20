---
title: "Plaintext workflow"
date: 202204219
author: Ian Spangler
---

# A plain text workflow for academic writing

## Goals

The purpose of this lab is to:

  * provide a better sense of why one would choose to do scholarly work in plain text;
  * highlight key languages/softwares associated with writing in plain text;
  * teach you how to:
    - set up a plain text writing environment;
    - execute basic document conversion tasks;
    - use Zotero to manage citations in plain text;

The purpose of this lab is NOT to convince you that plain text writing is the only way to go -- on the contrary! What we hope most is that this lab introduces you to tools that will prompt reflection about your writing process. For example, what considerations should you take when approaching scholarly writing in geography? What habits have you developed that you didn't even realize, and what affordances do you rely on that you didn't know you need?

## Table of Contents

  | Section | Title                       |
  | ------- | --------------------------- |
  |    1    | [Getting started](#1-getting-started) |
  |    2    |                             |
  |    3    |                             |
  |    4    |                             |

## 1. Getting started

### 1.1. What is plain text, anyway?

#### Rich Text

You're probably familiar with **[rich text](https://en.wikipedia.org/wiki/Rich_Text_Format)**, a shorthand for file formats (`.rtf`, `.doc`) that natively support features like formatting, inline images, and track changes. Microsoft's Word and Apple's Pages are among the most common rich text word processing apps. There's a lot going on under the hood of word processors (code, functions) that makes stuff like font families, alignment, and color just a button click away.

| ![Screenshot of MS Word's rich text features](assets/msword.png) |
| ---------------------------------------------------------------- |
| *screenshot of the MS word interface, with rich text formatting options highlighted in the red box*                            |

If the upshot of processors like these is functionality, then the downsides are busyness, opacity, and propriety. [Dennis Tenen and Grant Wythoff](http://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown#philosophy) have done a good job, I think, of articulating the problems with rich text editors:

>When you use MS Word, Google Docs, or Open Office to write documents, what you see is not what you get. Beneath the visible layer of words, sentences, and paragraphs lies a complicated layer of code understandable only to machines. Because of that hidden layer, your .docx and .pdf files depend on proprietary tools to be rendered correctly. Such documents are difficult to search, to print, and to convert into other file formats.

Moreover, an important point: **formatting is *not* writing**. The very functionality that makes MS Word distinct and comfortable has got, arguably, very little to do with the actual process of writing! Enter plain text.

#### Plain text

Rich text can be contrasted with **[plain text](https://en.wikipedia.org/wiki/Plain_text)**, a shorthand for file formats (`.txt`) that contain no formatting features. This includes files written in [Markdown](https://www.markdownguide.org/getting-started/), a language that allows you to add formatting elements to plain text files with minor alterations such as enclosing text in asterisks. For example, in Markdown, `this text is normal, and **this text is bold**`.

Normally, you compose plain text in **[text editors](https://en.wikipedia.org/wiki/Text_editor)** such as [Atom](https://atom.io/) or [VS Code](https://code.visualstudio.com/insiders). In these interfaces, and [what you see is what you get](https://en.wikipedia.org/wiki/WYSIWYG). There are few, if any, exclusively machine-readable layers of code between you and the words you typed. Graphical elements like font size and boldness are marked explicitly in the document:

| ![Screenshot of the text editor Atom](assets/atom.png) |
| ------------------------------------------------------ |
| *Screenshot of the text editor Atom, showing from left to right 1) the file tree, 2) a plain text Markdown file, and 3) a rendered Markdown file preview*                   |

To borrow again from Tenen and Wythoff, the idea behind Markdown:

>... is to identify units that are meaningful to humans, like titles, sections, subsections, footnotes, and illustrations. At the very least, your files will always remain comprehensible to you, even if the editor you are currently using stops working or “goes out of business.”

Writing in this way, they go on:

>... liberates the author from the tool. Markdown can be written in any plain text editor and offers a rich ecosystem of software that can render that text into beautiful looking documents. For this reason, Markdown is currently enjoying a period of growth, not just as as means for writing scholarly papers but as a convention for online editing in general.

### 1.2. Why write in plain text?

In my view, there are five main benefits of writing prose in plain text:

  1. Separate writing from formatting
  2. Keep writing agnostic to file format and platform
  3. Facilitate easy document conversion
  4. Fully open source
  5.

The primary benefit of writing in plain text is to **isolate the writing process from the tasks of editing and formatting.**

Rich text editors like MS Word and Google Docs bundle writing (e.g., typing words) and formatting (e.g., choosing fonts, adding italics, and so on) into the same interface.





Practically, this means that when we write in Microsoft Word et al., we're often faced with distractions from writing.


### 1.3.

As academics, we have a complicated relationship to writing. We are constantly doing it. Sometimes we write for six hours and produce a paragraph; sometimes we write for an hour and produce six. We write papers for class, notes for seminars, letters of recommendation, lengthy emails, short emails, emails that never get sent, feedback for our students, grants, proposals, exams, exam answers, research materials, theses, dissertations... the list goes on.

All of this falls more or less into the broad category of "scholarly writing," at least insofar as it's stuff that we have to do for our jobs as scholars. Especially the Big Things---grants, dissertations, and journal manuscripts, for example---require some kind of established workflow.

In this lab, you'll be introduced to one such workflow: **plain text writing**.
