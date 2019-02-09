### Day 1: Friday, Feb 1, 2019

**Today's Progress**: Restarted development on a pro-bono site redesign I was doing for a volunteer group I'm part of ([Coder Brixton](http://coderbrixton.com/), they're cool!). Had to put it on hold for a couple of weeks but it works out to be a good project to use for \#100DaysOfCode. 

**Thoughts**: I just finished a boot camp after leaving my job. It's safe to say that job hunting itself is a miserable pit of despair. But the one thing that actually takes my mind off it and I find enjoyment in is coding. So I figured committing to the 100 days would be a good way to fend off the blues. Also, it means that I get to improve my skillset which is great.
I also realise that I actually really like front end. I originally found it quite intimidating but the recent changes to CSS are amazing. 

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 2: Saturday, Feb 2, 2019

**Today's Progress**: More work done on the Coder Brixton site. Concentrated on getting the Vimeo embed to be responsive.

**Thoughts**: After a fair amount of frustration trying different approaches, CSS grid once again came to the rescue. The solution ended up being a 3x3 grid and placing the video in the central container. The trick to keeping the aspect ratio at 16:9 of the video was to actually use a width of 80vw and a height of 45vw (NOT vh). I managed to find this aspect ratio trick from a codepan trying to solve the same problem (but with a different implementation). 

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [Codepen: A less awful responsive vimeo embed (by Liz)](https://codepen.io/lixelart/pen/eyZNeX)

### Day 3: Sunday, Feb 3, 2019

**Today's Progress**: Started re-designing the way quotations looked like on the site. Went for a card format that looks a lot nicer.

**Thoughts**: A fair bit of time was spent getting responsive behaviour to work correctly using `@media`. It went okay, but it did feel like trial and error at times. If anybody reading this has and advice on methodology and approaches on responsive behaviour, please reach out to me on Twitter via [@BrotherKaif](http://twitter.com/brotherkaif)! 

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 4: Monday, Feb 4, 2019

**Today's Progress**: Fixed a bug with the responsive cards. Also added in some FontAwesome icons.

**Thoughts**: Fixing bugs with responsive elements is horrible. At first I attempted to redo the entire card only to totally revert back to what I had originally and just tweak it slightly. Lesson learned, it's not worth tearing it all down just to resolve an edge case that can be fixed with minor tweaks. Also added in some Font Awesome icons, because who doesn't like Font Awesome?!

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [Font Awesome](https://fontawesome.com/)

### Day 5: Tuesday, Feb 5, 2019

**Today's Progress**: A bit more work on styling the rest of the sections.

**Thoughts**: Didn't have a huge amount of time to code today so tackled some of the low hanging fruit of marking up the sections. Also started a project kanban on GitHub to start keeping track of the tasks that still need to be done.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 6: Wednesday, Feb 6, 2019

**Today's Progress**: Loads of stuff. Got the photo gallery sorted out and started making the sections responsive.

**Thoughts**: Had a lot more time to code today. Got the photo gallery sorted thanks to a wonderful tutorial (linked below). Also started work on making the main sections responsive. Nearly there but will continue tomorrow. Another side note, it's becoming clear that CSS grid and flex pretty much negate the need for frameworks like Bootstrap. So I've slowly been pulling out the Bootstrap classes so that I can strip the thing out entirely by the end of it.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [Mosaic Layouts with CSS Grid | Axel Valdez](https://axelvaldez.mx/blog/2018/05/mosaic-layout-with-css-grid/)

### Day 7: Thursday, Feb 7, 2019

**Today's Progress**: Finally got the responsive sections to work correctly.

**Thoughts**: Getting the responsive behaviour to work well using CSS Grid is a bit of a challenge but I managed to track down where a lot of the bugs were coming from (it was a simple syntax error). Found a great guide which got me through some of the tough bits which I've linked below. Just a couple of more components left and then I can get onto the fun stuff of choosing fonts, colours and other little tweaks.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

### Day 8: Friday, Feb 8, 2019

**Today's Progress**: Worked on the cards for the mentors

**Thoughts**: Things are starting to come together! Today I worked on the mentor cards. The main components of the site are pretty much complete. I feel the next few days will be spent doing layout tweaks.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 9: Saturday, Feb 9, 2019

**Today's Progress**: Rebuilt the cards using CSS grid.

**Thoughts**: I wanted to have a nice gradient to overlay on the mentor avatar, but the way I built the cards yesterday meant I'd have to do some complex absolute/relative placement. Re-did the cards in (wait for it...) CSS grid. Once again, I'm convinced that this is *the* solution to about 90% of CSS layout work. The card took me about an 30 mins to re-do; whereas yesterday it took me 3 hours to put together a pretty complex and difficult to manage layout using `position: relative;` and `position: absolute;`.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)