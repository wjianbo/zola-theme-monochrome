# zola-theme-still

**Still** is a minimal Zola theme focused on calm reading, typography, and intentional silence.

No visual noise.
No unnecessary navigation.
Just words, spacing, and time.

This theme is designed for personal blogs, essays, and long-form writing.

A live demo is not available yet.
You can preview the visual style on the author’s blog:
[https://wjianbo.github.io](https://wjianbo.github.io)

---

## Features

* Clean, monochrome design
* Focused reading experience
* No homepage navigation by default
* Designed for internal linking between posts
* Suitable for long-form writing

---

## Installation

Make sure you have created a Zola site:

```bash
zola init myblog
cd myblog
```

Then add the theme to the `themes` directory.

Using git submodule:

```bash
git submodule add https://github.com/wjianbo/zola-theme-still themes/still
```

Or clone directly:

```bash
git clone https://github.com/wjianbo/zola-theme-still themes/still
```

---

## Configuration

Edit `config.toml` and set the theme:

```toml
theme = "still"
build_search_index = false
```

---

## Philosophy

Still is not about *less features*,
but about *less distraction*.

Each page should feel complete on its own,
yet quietly connected to others through links.

Reading should feel slow.
