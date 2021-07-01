# HTML Lists

## Overview

In this lesson we will do a quick review of HTML lists from the video lecture in the prior lesson.

## What's Covered in This Lesson

1. Unordered List
2. Ordered List
3. Definition List

### Lists

Lists allow us to group text into a structure that ties their meaning together into a whole.

#### Ordered List

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>
```

Ordered lists by default appear as numeric lists with numbers identifying each list item.

#### Unordered List

```html
<ul>
  <li>First item</li>
  <li>Second item</li>
</ul>
```

Unordered lists by default appear as bulleted lists with bullets identifying each list item.

#### Definition List

```html
<dl>
  <dt>First term</dt>
  <dd>First definition</dd>
  <dt>Second term</dt>
  <dd>Second definition</dd>
</dl>
```

Definition lists display similar to a traditional dictionary allowing us to state a term and provide a definition for each corresponding term.

## Summary

- HTML text can be formatted using a variety of lists.
- An unordered list uses parent `<ul>` element and produces bulleted `<li>` list items.
- An ordered list uses parent `<ol>` element and produces numbered `<li>` list items.
- A definition list uses parent `<dl>` element and produces a list of terms `<dt>` and their corresponding `<dd>` definitions.

## Resources

- [Mozilla Dev Network - Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML Element Lookup Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [HTML Element Cheatsheet](http://overapi.com/html-dom/)
