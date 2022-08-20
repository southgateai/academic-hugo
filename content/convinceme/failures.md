---
widget: blank
widget_id: failures
headless: true
weight: 2000
title: The list of things that won't work or that we can't do
active: true
design:
  columns: "1"
  background:
    text_color_light: false
    image_darken: 0
    color: ""
---

A brief and incomplete list of ways to fail, just so we know we're on the same page.

 - **Create a good superintelligent AI.**  Due to the Alignment Problem[\[@wiki\]](https://en.wikipedia.org/wiki/AI_alignment) this ends badly.
 - **Create a good superintelligent AI to combat any bad superintelligent AI.**  At the risk of saying "See above", for various reasons, mostly the Alignment Problem again, this doesn't work.  The one caveat is that maybe this is an easier alignment problem to solve, but let's not count on it.
 - **Try to not create powerful AI at all.**  We show no signs of resisting that temptation, nor any clear way to do so.
 - **Allow the superintelligent AI to get full knowledge of the defences it's facing, and the knowledge that it has full knowledge.**  Once it knows it has all the information it can formulate a plan to escape.
 - **Use a static, unchanging set of rules in your defences to determine whether the AI should be allowed to continue**.  If you do this, the AI will eventually get knowledge of full knowledge as above.
 - **Use rules running exclusively on the same hardware as the AI.**  Again the AI can gain full knowledge.
 - **Allow the AI multiple attempts to probe the rules of the defence.**  This allows the AI to discover the rules by trial and error.  This includes allowing the AI to replicate and fail to stop all of the replicas when one breaks the rules.
 - **Allow the AI to learn from other AIs (that don't care about being stopped) breaking the rules until eventually, one finds a way to escape without being stopped, and the original AI knows it faces the same rules.**  Either rule updates or different sets of rules can help here.
 - **Allow anything, including the AI, to compromise the rule enforcing system.**  A successful attempt to disable the rule system leads to trouble, although obviously, any attempt to do that against the rules too.
 - **Use just a single method or a handful of methods to detect bad behaviour**.  This runs the risk of the AI predicting what you've done.
