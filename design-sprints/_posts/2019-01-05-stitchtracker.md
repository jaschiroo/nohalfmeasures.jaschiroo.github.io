---
layout: post
title: "Design Sprint: Stitch Tracker"
date: 2019-01-05
---

 Whenever I start a new knitting or crochet pattern, the first thing I do is print it out so that I can cross off rows as I complete them. I recently had the frustrating experience of deciding to make a second hat right after completing the first, only to realize that my pattern was all scratched out and difficult to read, let alone scratch out again for the second hat. Why not have an app for this?

 <img style="max-width:90%;height:auto;border:1px solid black;"
  src="/assets/sprints/stitch/splash.png"
  title="Splash screen">

 As a recurring crafter, I am familiar with patterns that come as PDF files, websites and word documents, so the input method doesn't need to be complicated to grab the pattern.

<img style="max-width:90%;height:auto;border:1px solid black;"
src="/assets/sprints/stitch/addpattern.png"
title="Add a pattern">

During import, ideally some text scraping will be used to get the pattern into the right shape. Rows are consistently labeled or numbered, and that provides the basic structure; repeat sections will usually contain the word "repeat" as a trigger.

An important consideration here is to allow some editing of the pattern within the app. Sections of knitting will have headers and there may be repeat sections missed by the import. To have a useful pattern, the user must be able to fix any errors easily.

<img style="max-width:90%;height:auto;border:1px solid black;"
src="/assets/sprints/stitch/pattern.png"
title="Knitting pattern">

Once the pattern is edited, the user can begin working. The basic actions available are checking off a row and counting a repeat.

<img style="max-width:90%;height:auto;border:1px solid black;"
src="/assets/sprints/stitch/completed.png"
title="Pattern with progress">

As rows are completed and the user checks them off, they are still available for view through a "see completed" menu, in case the user wants to double-check their work or go back.

Upon completion of the pattern, an option is available in the menu to reset the completed rows, in case the user is making duplicates of the pattern, such as socks, sleeves or a second hat for a friend.

<img style="max-width:90%;height:auto;border:1px solid black;"
src="/assets/sprints/stitch/menu.png"
title="App menu screen">
