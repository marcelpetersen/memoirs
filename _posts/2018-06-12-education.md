---
toc: true
beforetoc: Prism highlighter is a very powerful thing. In this article I'm going
  to show you what you can actually do with it, some tricks and tips while
  editing your post. Tocs is also enabled as you can see in summary.
date: 2020-05-02T15:04:46.000Z
layout: post
title: locatie, locatie, locatie
author: marcel
categories:
  - Lifestyle
tags:
  - code
image: /assets/images/3.jpg
rating: ""
---
Fotograferen is locatie, locatie, locatie


#### HTML

```html
<li class="ml-1 mr-1">
    <a target="_blank" href="#">
    <i class="fab fa-twitter"></i>
    </a>
</li>
```

#### CSS

```css
.highlight .c {
    color: #999988;
    font-style: italic;
}
.highlight .err {
    color: #a61717;
    background-color: #e3d2d2;
}
```

#### JS

```js
// alertbar later
$(document).scroll(function () {
    var y = $(this).scrollTop();
    if (y > 280) {
        $('.alertbar').fadeIn();
    } else {
        $('.alertbar').fadeOut();
    }
});
```

#### Python

```python
print("Hello World")
```

#### Ruby

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

#### C

```c
printf("Hello World");
```
