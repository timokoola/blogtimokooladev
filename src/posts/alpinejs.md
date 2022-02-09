---
title: Testing out Alpine.js
description: Adding Alpine.js to Blog
author: Timo Koola
date: 2022-02-10
tags:
  - created
---

The template I used to create the site basics included [Alpine.js](https://alpinejs.dev/) that according to their own words is:

> Alpine is a rugged, minimal tool for composing behavior directly in your markup. Think of it like jQuery for the modern web. Plop in a script tag and get going.

Let's try it with a simple button counter example

<div x-data="{count: 0}">
<button x-on:click="count = count + 1">Add</button>
<div x-text="count"></div>
</div>

and that as code is surprisingly simple:

```javascript
<div x-data="{count: 0}">
    <button x-on:click="count = count + 1">Add</button>
    <div x-text="count"></div>
</div>
```

Yes, it feels positively jQuery like. From reading a tutorial to this in 15 minutes.

Oh, and one more thing to my to-do list: fix syntax highlighting.