+++
categories = ["personal","IT","propaganda"]
slug = "hello-hugo"
tags = ["hugo", "typo3"]
title = "Goodbye Typo, hello Hugo!"
description = "A short note about personal web sites"
date = "2021-02-15T00:00:00-01:00"
showpagemeta = true
comments = false
showcomments = false
+++

It is time to retire my old Typo3 website.
It was up for over 10 years now.
I still kinda like the old green style.
But I want to become a bit more serious as I grew up over this period - at least a little bit.

Let me take a screenshot to keep the good memories:

{{< figure src="img/old-typo3-website.png" alt="Old Typo3 Page" width="650px" >}}

I replace it with this fancy new hugo blog.
I think it is a good tech choice for this kind of website.
Hopefully it will also last longer than 10 years.

The first issue can be viewed on this page.
Images can not be scaled with markdown syntax.

Turned out that hugo has a buildin figure shorthand syntax for images:
{{< highlight go >}}{{</* figure src="img/image.png" alt="Description" width="650px" */>}}{{< /highlight >}}

Note that the curly braces have be escaped by `</* */>`.

So as it is fun to learn new things I am curious to dig into it!


