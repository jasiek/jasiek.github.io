---
layout: post
title: "Welcome to My Blog: A Theme Demo"
date: 2026-02-24
---

This is the first post on this blog. It also serves as a demonstration of the
theme's typography and code styling. Everything below exercises a different
aspect of the Markdown rendering pipeline.

## Code Blocks

Here is a Ruby method with syntax highlighting:

```ruby
def fibonacci(n)
  return n if n <= 1
  fibonacci(n - 1) + fibonacci(n - 2)
end

# Print the first 10 Fibonacci numbers
10.times { |i| puts fibonacci(i) }
```

And some JavaScript:

```javascript
async function fetchData(url) {
  const response = await fetch(url);
  if (!response.ok) {
    throw new Error(`HTTP error: ${response.status}`);
  }
  return response.json();
}
```

Inline code looks like this: use `bundle exec jekyll serve` to preview the site
locally.

## Lists

Unordered:

- First item
- Second item with `inline code`
- Third item
  - Nested item
  - Another nested item

Ordered:

1. Step one
2. Step two
3. Step three

## Blockquotes

> Good software, like wine, takes time.
> -- Joel Spolsky

## Tables

| Command | Description |
|---------|-------------|
| `jekyll build` | Builds the site |
| `jekyll serve` | Starts a local server |
| `jekyll new` | Creates a new site |

## Typography

Regular paragraph text at 18px with a 1.7 line height. This line length is
optimized for readability at roughly 65-75 characters per line. The font stack
uses system fonts so there is no flash of unstyled text and no external network
requests.

**Bold text** and *italic text* and ~~strikethrough text~~ all work as expected.

---

That covers the basics. Future posts will contain actual technical content.
