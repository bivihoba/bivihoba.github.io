---
layout: post
title: Super text
tags: [super text, R]
---

One of my late tasks was to add [(R)](http://en.wikipedia.org/wiki/Registered_trademark_symbol) symbol on a site. What can be easily? I was wrong in my estimates.

```html
&reg;
```

Symbol (R) should has a superscript style.

```html
<sup>&reg;</sup>
```

Also, this symbol may positioned in different contexts…

we will use relative units in CSS.

…in particular inside a links. And links has an underline. Standard underline via plain old “text-decoration” property.

	- Okay.

In Webkit-based browsers we have a problem.
