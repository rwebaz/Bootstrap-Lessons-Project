---
title: Blockquote Footer
layout: default
excerpt: Place the introducing line of text ie.) the 'lead' here ...
hint: Place the intro paragraph ie.) the 'hypothesis' here ...
repo: Bootstrap-Lessons-Project
ver_date: 11-26-19
navigation_weight: 8
categories: page
---
{% include toc.md %}

## First Subtitle

> **Hint**. {{ page.hint }}

More to come ...

```html
{% raw %}
<blockquote class="blockquote">
  <span>Ohan has written a very nice book!</span>
  <span class="blockquote-footer">by ~Ohan Emmanuel</span>
</blockquote>
{% endraw %}
```

Renders,

**Note**. To view a rendering of the above Html snippet, visit the [Bootstrap 4](https://mminail.github.io/Bootstrap/Bootstrap-4.htm){:title='Click to Visit the Bootstrap 4 page of the Concept Library at MMINAIL'}{:target='_blank'} page of the Concept Library at MMINAIL.

## Visual Studio Code Snippet

```html
{% raw %}
"Add: Blockquote": {
  "prefix": "add-blockquote",
    "body": [
      "<blockquote class='blockquote'>",
      "<span>Ohan has written a very nice book!</span>",
      "<span class='blockquote-footer'>by ~Ohan Emmanuel</span>",
      "</blockquote>"
    ],
  "description": "Add Blockquote"
},
{% endraw %}
```

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by Ohan Emmanuel [[2](#OHAN){:.red}].

1. {:#OHAN}The [Understanding Bootstrap 4](https://medium.freecodecamp.org/bootstrap-4-everything-you-need-to-know-c750991f6784){:title='Click to Visit the Landing page for Understanding Bootstrap 4: Everything You Need To Know by Ohan Emmanuel'}{:target='_blank'}: Everything You Need To Know by Ohan Emmanuel. Published by © 2017 [Medium.com](https://medium.freecodecamp.org/){:title='Click to Visit the Home page of Medum Free Code Camp'}{:target='_blank'}.

***

{% include patreon-link.md %}
