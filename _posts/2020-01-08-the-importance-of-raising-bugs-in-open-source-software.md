---
layout: post
title: The importance of raising bugs in open source software
description: Where I talk about a bug report I submitted to an open source project
image: the-importance-of-raising-bugs-in-open-source-software
---

Open source software is great. What makes it great is the fact that anyone can contribute in some way, be it fixing bugs, raising bugs, testing etc. It&rsquo;s important to remember this when we find problems with the software we use. As users and developers of open source software we have the power to effect change.

I recently came across a problem with an open source project which resulted in me raising a bug and subsequently having it fixed. It was a fairly painless process and resulted in making positive change in a well known product.

## The problem

For work I use a 13" laptop with a resolution of 1920px &times; 1080px. By default this makes text a bit too hard to read for me. Luckily Ubuntu, the OS I use, has a large text option in it&rsquo;s accessibility settings. This scales everything about to 1.25 it&rsquo;s default size. Most applications respect the large text option and scale accordingly but there are a few that don&rsquo;t.

Whilst trying to make the switch from Chrome to Firefox as my primary development browser I found that Firefox wasn&rsquo;t respecting the large text setting. I did some googleing to try and find a solution but couldn&rsquo;t find anything.

## Raising the bug

As Firefox is a widely used browser with a large community I assumed that someone else must have raised this issue and there was a reason why the large text setting didn&rsquo;t have any effect. It turns out I was wrong.

I arrived at [Bugzilla](https://bugzilla.mozilla.org/) and searched to see if anything remotely like the issue I was facing had been raised before. I couldn&rsquo;t find anything so I [reported a bug](https://bugzilla.mozilla.org/show_bug.cgi?id=1604761). The team at Mozilla were quick to respond and before I knew it were working on a solution.

## The solution

Yesterday I received [notification of a comment](https://bugzilla.mozilla.org/show_bug.cgi?id=1604761#c14) asking me to verify that the bug has been fixed. I installed [v73.0b2](https://www.mozilla.org/en-US/firefox/73.0beta/releasenotes/) and verified that the issue I raised was indeed fixed. I&rsquo;m now looking forward to the release of Firefox 73 which will fix this issue for me and anyone else using Ubuntu/Gnome with large text enabled.

## Takeway

If you find a bug in a piece of open source software, never assume that someone else has reported it. Raising a bug for a problem you&rsquo;ve found which then gets fixed helps everyone who uses that software. The value of that should never be underestimated.
