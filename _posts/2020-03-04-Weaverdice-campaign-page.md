---
layout: post
title: Creating a webpage for a Weaverdice campaign
tags: weaverdice pitchford worm gamemaster website
---

If you've ever met me, you know I'm very into the web serial 
[Worm](https://parahumans.wordpress.net/). I talk about it a lot, I'm a 
moderator on a Discord server dedicated to it's authors works and I've run a 
fair few Weaverdice games in my time, a tabletop game in the style of 
Dungeons and Dragons, but set in the world of Worm.

Today I'm attempting to take the existing website work that Jekyll allows for
and make a campaign frontpage for a Weaverdice campaign I'm designing for other 
GMs to pick up and run. The initial setup is quite easy, because I can reuse 
a lot of the same assets, such as style sheets and launch off from that. I can 
modify the existing layouts to create a separate default for the 
[Pitchford](https://wellwick.github.io/Pitchford) website, but I've already 
hit my first issue.

I need to make it so that when a user reaches a bad page, they get a 404 error. 
This already works for this website (try typing in some gobbledeegook at the 
end of the URL), but underneath Pitchford, it is still falling back to the same 
404 page. Without being able to see under the hood what Jekyll is doing, I may 
need to repurpose the 404 page for being more general, or altenatively, put 
this blog under a subdirectory of it's own.
