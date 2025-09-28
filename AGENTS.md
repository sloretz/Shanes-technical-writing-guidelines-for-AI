# Instructions for AI Agents

This document provides instructions on how to create a new style guideline page for this repository. Follow these instructions carefully to ensure consistency across all guidelines.


## Core Principles

* **Syntax**: Every style guideline page must use [CommonMark Markdown](https://commonmark.org/).
* **Audience**: The page is for an audience familiar with technical writing, including both human writers and other AI agents. The goal is to clearly state a guideline and demonstrate its application.
* **Scope**: Each Markdown file must contain only one style guideline. If you need to reference another guideline, use a relative link, like [active voice](./active-voice).
* **Organization**: Every style guideline page is in the `style-guide` folder. There are no sub-folders.

## Page Structure and Content 

Every style guideline page must adhere to the following structure and include these specific elements.

### File Header

Every page must begin with this exact YAML front matter block. Replace `NAME OF STYLE GUIDELINE` with the title of the rule.

```
---
title: NAME OF STYLE GUIDELINE
parent: Guidelines
---
```

### Guideline Content

The body of the page must contain:

* **The Style Guideline**: A clear and concise statement of the rule.
* **Correct Examples**: Exactly three examples that correctly follow the rule in *italics*.
* **Incorrect Examples**: Exactly three examples that do not follow the rule in *italics*.

The body of the page should contain:

* **References for the guideline**: A URL of another style guide where this guideline was borrowed from, and the date that the URL was accessed.

### File Footer

The file must end with a **single new line**.

## Recommended Template

Use the following template to structure your style guideline page. This ensures consistency and makes the rules easy for all audiences to understand.

```
---
title: Name of Guideline
parent: Guidelines
---

# Name of Guideline

State the rule in a single, clear sentence.

Provide a brief paragraph explaining the rule in more detail. Explain why the rule is important and in what contexts it should be applied. If there are common exceptions to the rule, mention them here.

## Examples

### 👍 Correct

* *A complete sentence or code snippet that correctly follows the rule.*
* *A complete sentence or code snippet that correctly follows the rule.*
* *A complete sentence or code snippet that correctly follows the rule.*

### 👎 Incorrect

* *A complete sentence or code snippet that breaks the rule.*
* *A complete sentence or code snippet that breaks the rule.*
* *A complete sentence or code snippet that breaks the rule.*

## References

This guideline was inspired by [18F's style guide on personal names](https://github.com/18F/guides/blob/main/content/content-guide/our-style/names.md) as of June 25th, 2023.
```