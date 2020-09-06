---
layout: entry
title: The Twisted Cubic
author: David Hilbert
categories: ["algebraic geometry"]
date: 1900-01-01
---

<script>
// You can define LaTeX macros like this:
macros = {
  "\\P": "\\mathbb{P}",
  "\\PP": "\\P^#1", // the number of arguments is deduced automatically
}
</script>

<script>
// Further macros can be added like this:
katex.renderToString("\\gdef\\PP#1{\\P^#1}", {macros: macros});
</script>

# Section 1

## Subsection 1.1
You can write stuff in _italics_, **bold**, or even ~~strikethrough~~.

Next paragraph should start like this. Do not indent.

The function $ \nu $ is written inline, but can also be in a block:

$$ \nu: \R\P^1 \to \P^3. $$

\\[ \nu: \R\PP1 \to \PP3. \\]

Multiple math formats work:
- `$5\times 5$` gives $5\times 5$
- `\\(5\times 5\\)` gives \\(5\times 5\\)
- `\\[5\times 5.\\]` gives: \\[5\times 5.\\]

**Note:** while `$$ 5\times 5 $$` technically works, it will enclose the math in a script tag, which is undesirable[^katex].


[^katex]:
    This will change once this [issue](https://github.com/github/pages-gem/pull/545) is fixed.

*[function]: you know what a function is, don't you?
