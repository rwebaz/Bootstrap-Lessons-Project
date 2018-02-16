---
title: Blockquote Footer
layout: default
excerpt: Place the introducing line of text ie.) the 'lead' here ...
version: Page Template md Dtd 02-15-18
navigation_weight: 8
categories: template
---
# {{ page.title }}

{{ page.excerpt }}

{% include toc.md %}

## First Subtitle

Place the introducing line of text ie.) the 'tagline' here ...

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

## Import Code

More to come ...

## Last Subtitle

**Note**. The above synopsis was derived from an article written by Ohan Emmanuel [[2](#OHAN){:.red}].

### Raw Code Block

```liquid
{% raw %}
Enjoy the successful output!
{% endraw %}
```

{% include sources-and-uses.md %}

1. {:#OHAN}The [Understanding Bootstrap 4](https://medium.freecodecamp.org/bootstrap-4-everything-you-need-to-know-c750991f6784){:title='Click to Visit the Landing page for Understanding Bootstrap 4: Everything You Need To Know by Ohan Emmanuel'}{:target='_blank'}: Everything You Need To Know by Ohan Emmanuel. Published by © 2017 [Medium.com](https://medium.freecodecamp.org/){:title='Click to Visit the Home page of Medum Free Code Camp'}{:target='_blank'}.

### External Sources

- {:#SOURCELINKS}The [Project Source Links](https://mminail.github.io/Bootstrap/Source-Bootstrap-Links.htm){:title="Click to Visit the Source Links page of the Bootstrap Lessons Project at GitHub pages"}{:target="_blank"} page of the Bootstrap Lessons Project. Published by © 2017 - 2018 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.

**Note**. This page crafted with {{ page.version }}.
