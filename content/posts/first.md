---
date:  2025-05-07T12:39:18-05:00
draft: false
title: First
---

### Header

Here is some **text.**

[Here is a link to a post using a hugo relref shortcode (checked at compile).]({{< relref "/posts/second.md" >}})

[Here is a link to a post using a hugo ref shortcode (checked at compile).]({{< ref "/posts/second.md" >}})

[Here is a link to a post using an absolute URL (checked at ci + deploy by link checker).](https://nandstand.github.io/hugo-sandbox/posts/second/).

[Here is a link to a post using a root-relative link (checked at ci + deploy by link checker).](/hugo-sandbox/posts/second/)

[Here is a link to a post using a page-relative link (also checked by the link checker).](../second/)
