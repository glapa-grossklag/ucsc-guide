---
title: "Introduction to the Shell"
linkTitle: "Shell"
weight: 1
icon:
draft: true
description: >
  Introduction to navigating the shell.
---

# Prerequisites

This introduction assumes you are on a UNIX-like system (ideally Linux) and are
using the bash shell. This introduction also assumes you have some knowledge of
programming for the purposes of comparison. If you don't, you'll probably be
okay, but it wouldn't hurt.

# Introduction

Hello and welcome to the shell! This section, surprisingly, won't actually have
you using the shell at all. Many first-time users of the shell feel out of their
element and unfamiliar with the environment -- hopefully we'll change that.

When you want to get something done inside of the shell, you'll run a
**command**. A command is extremely similar to a function in a typical
programming language. Let's compare Python's `print` function with the shell's
`echo` command. We're going to perform a pretty common task, printing something
to the screen without a trailing newline.

In Python, we have

```python
print('Hello, world!', end='')
```

And using `echo`, we have

```sh
echo -n 'Hello, world!'
```

As you can see, they're pretty similar -- but let's look at the differences.

- Python:
    - The arguments are separated by commas.
    - Optional arguments look like `keyword=value`
- Python:
    - The arguments are separated by whitespace.
    - Optional arguments look like `--keyword`

# Commands

If you haven't already, open up a terminal.

