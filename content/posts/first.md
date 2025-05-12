---
date:  2025-05-07T12:39:18-05:00
draft: false
title: First
---

### Header

Here is some **text.**

[Here is a link to a post using a hugo relref shortcode (safe)]({{< relref "/posts/second.md" >}}).

[Here is a link to a post using a hugo ref shortcode (safe)]({{< ref "/posts/second.md" >}}).

[Here is a link to a post using an absolute URL (unsafe, not checked by ci link checks)](https://nandstand.github.io/hugo-sandbox/posts/second/).

[Here is a link to a post using a root-relative link](/posts/second/).

[Here is a link to a post using a page-relative link](../../posts/second/).
