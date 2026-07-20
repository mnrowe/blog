---
title: "{{ replace .File.ContentBaseName `-` ` ` | title }}"
date: {{ .Date }}
draft: true
tags: []
summary: ""
ShowToc: true
TocOpen: false
---

<!-- draft: true keeps this private (buildDrafts is false). Flip to draft: false to publish. -->
<!-- summary shows on the blog list/home page — write one sharp sentence. -->

## The problem

What was I trying to do, and why is it worth reading? One or two paragraphs, no throat-clearing.

## Setup

The relevant context — tools, environment, constraints. Keep it to what a reader needs.

## What I did

Walk it through. Show real code/config, but **sanitized** — the pattern, not my employer's actual rules, IPs, secrets, or architecture.

```
# code / config
```

## Why it works (the mental model)

The part most posts skip. Explain the underlying idea so a reader could apply it somewhere else, not just copy it.

## Takeaway

The one thing to remember. Optionally: what I'd do differently, or where to go next.
