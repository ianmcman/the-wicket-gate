---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true  # Start as draft by default

# Metadata
author: "Ian McManus"
description: ""

# SEO & Indexing
canonicalURL: ""
searchHidden: false

# Taxonomies
tags: []
categories: []

# Table of Contents
showToc: true
TocOpen: false
UseHugoToc: true

# Post Features
ShowReadingTime: true
ShowWordCount: true
ShowPostNavLinks: true
ShowBreadCrumbs: true
ShowRssButtonInSectionTermList: false

# UI/UX Settings
comments: true
hidemeta: false
hideSummary: false

# Code Highlighting
disableHLJS: false

# Sharing & Editing
disableShare: false
editPost:
    URL: "https://github.com/ianmcman/the-wicket-gate/tree/main/content/{{ .File.Path }}"
    Text: "Edit this post"
    appendFilePath: true

# Cover Image
cover:
    image: ""  # Image path/url
    alt: ""  # Alt text
    caption: ""  # Caption under cover
    relative: false  # Set to true for page bundles
    hidden: true  # Hide cover only on this single post
---
