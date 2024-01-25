---
layout: post
tags: blog
title: Developing the Pitchford website
tags: weaverdice pitchford worm gamemaster website
---

So, I'm starting to make progress on the 
[Pitchford website](https://wellwick.github.io/Pitchford), adding in images and 
setting down the layout for the character page. I think I'm going to need to go 
digging for some nice css for the tables, because right now I'm not a massive 
fan of the layout.

I'm also having an issue with how Jekyll handles for loops. I was hopeful that 
I could pass in variables to the page about a characters stats, then parse 
those into something nice and readable. Turns out that managing variables is 
more of a faff than I realised. Creating an array to loop through seems 
awkward. Beyond that, I'm not sure how well comparisons of variables which 
should be numbers will work, since I can't be sure they are being parsed that 
way in the backend.

Honestly, I've been pretty lazy up to this point. I've been letting Github 
build the website every time, when I could be building and testing this stuff 
locally instead. That would help debug and figure out the issues a lot quicker. 

---

I'm continuing the lazy approach and avoiding using for loops for now. I have 
an idea about how I could recreate the array by printing out the variable 
values, but it seems like a messy approach to simply then loop through them 
again, so I've just manually placed them into the table, which looks tidier 
than generating the array would have been.

It might be a better idea to have all of the capes stored as data in a single 
file, so that I can't muck anything up creating dozens of pages. It would 
possibly also help when listing all the characters on the main character page. 
Currently, I'm thinking that I'm going to lay out the characters page 
with sections for groups like Wards, Protectorate or Salvation.

A part of me wants to get on with filling out all of the character sheets, but 
I know I need to prep more of the formatting for Background, Personality, 
Disposition and the possible Skills the cape might have. Abilities are likely 
to be relatively unique, so a fixed layout won't make sense. It's likely that 
any perks or flaws will also be unique, but the layout will probably stay the 
same.

There is lot of stuff listed out that each cape can have and with a pool of 27 
capes, I'm realising it is days and days of work to get done. Even if I just do 
bullet points for backstory and personality, we're looking at a few hundred 
words per page, forgetting the time it will take to make the character images. 
