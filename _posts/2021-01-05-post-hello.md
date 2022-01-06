---
title: "Post: Hello"
categories:
  - Blog
tags:
  - Post Formats
  - notice
---

<div class="notice--primary" markdown="1">
**Primary Notice with code block:** Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. [Praesent libero](#). Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.

```html
<html>
  <body>Some body.<body>
</html>
```
</div>


**Danger Notice:** The content of this website is not representative of the views of individual members of the `Church of Wifi` or its leadership.
{: .notice--danger}

**Success Notice:** Remember we are all here to have fun, be good to each other.
{: .notice--success}

Sorry I blew up the website, it will be fixed, and it won't happen again.

- Evil Mog

<div class="notice">
  {{ notice-2 | markdownify }}
</div>
