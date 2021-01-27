---
title: "Hello World"
layout: post
---

I'm setting up this blog partially because I need to do something with my domain name that I just bought, but also because I sometimes have thoughts on cryptocurrencies and programming that are too long for Discord messages.
This blog is intended for technical audiences, but I'll try to explain complex topics as well as I can.


## Setting Up the Blog

I've set this blog up using GitHub Pages and
[the contrast Jekyll theme](https://github.com/niklasbuschmann/contrast).
I decided on this setup because it's simple, I can write posts as markdown,
I still retain unlimited flexibility with custom HTML, it's free,
and it won't have any scalability problems
if one of my posts becomes popular.

So far I haven't changed anything from the theme, but I might in the future.
I've been particularly looking at changing the background color on desktop,
but I haven't found a better one yet.

I also have redirects to this blog from plasmapower.dev and
www.plasmapower.dev via a Google Cloud server running nginx.
That server also will host my personal projects on subdomains.
It's not a powerful server, and it's not free,
but I'm hosting this blog subdomain with a CNAME DNS record.
That means requests to the blog subdomain don't go through the server,
so the server shouldn't get too much load, and I'm fine if it goes down.

**Edit 2021-01-26:**
I've decided to pass my domain through Cloudflare.
This improves speed a bit,
enables Cloudflare's "always online" technology in case GitHub Pages goes down,
and gives me some basic analytics (nothing individual, I'm not tracking you,
it's just generic numbers of unique visitors and such).
I've also effectively replaced my server's redirects with ones from Cloudflare,
but my server is still responsible for hosting personal projects.

## Plans for this Blog

So far, this blog is just this post and [the About page](/about).
I'm not entirely sure what I'll write about next.
I've considered writing about my thoughts on Nano PoW improvements,
but that might be better suited for [the Nano Forum](https://forum.nano.org/).
I've also heard people asking what was going on with the recent Nano spam attack
and the existence of an exploit, but I'd prefer not to get into that again, and
we likely won't ever know exactly what happened.

Currently, you can only subscribe to this blog [via RSS](/feed.xml).
While there are a number of sites that'll send you an email for new RSS items,
I personally enjoy being able to subscribe via email directly on websites.
I would like to add that in the future,
but it would conflict with this being a static website.
There's probably some 3rd party service that'll handle this from my RSS feed,
but I have yet to look into that.
