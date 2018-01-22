+++
date = "2018-01-14T22:42:32-04:00"
subtitle = "To unravel how technical design is intertwined with economic and aesthetic objectives, look to past failures."
tags = []
title = "Errors in Conceptual Design"
+++

<p class="lede">
To unravel how technical design is intertwined with economic and aesthetic
objectives, look to past failures.
</p>

<h2>Learning from the Poor Judgment of Paconius</h2>

In "<a href="https://www.goodreads.com/book/show/16247.Design_Paradigms">Design
Paradigms</a>: Case Histories of Error and Judgment in Engineering," Henry
Petroski details several civil engineering failures throughout history. The text
also includes candid analysis of the reasoning that led to each failure.
Petroski begins his discussion of errors in conceptual design with the story of
[Paconius and the Pedestal of
Apollo](http://www.kuhf.org/programaudio/engines/eng1101_64k.m3u). 

Let's explore how this civil engineering lesson can be applied to the design and
development of software. If you're not familiar with the story, listen to the
radio program linked above or read [this
transcript](http://www.uh.edu/engines/epi1101.htm).

Paconius sought an innovative solution to moving a massive pedestal from a
quarry to the building site at the temple of Apollo at Selinous. The factors
that contributed to his design appear to be primarily economic and aesthetic in
hindsight. His solution, rather like a spool unwinding from the top, was
apparently easier to construct, and allowed for heavier loads to be pulled with
fewer oxen. Moreover, in contrast to the standard wooden frame solution,
Paconius' innovation required no holes to be drilled in either end of the
pedestal (to be fitted with iron and lead inserts). The spool approach also kept
the pedestal more protected from the road and elements.

These all seem like big wins. Therein lies the problem, it's a trap, and a
seductive one at that. There are two fundamental flaws with Paconius' spool:

<ol class="tabular-figures">
  <li>
    As the oxen pull the spool forward, they distance themselves equally from the
   spool.
  </li>
  <li>
    After the rope runs out, you have to set the whole damn thing back up.
  </li>
</ol>

<p class="no-indent">
  As the oxen distanced themselves from the spool, it became less stable and was
  prone to running off the road, undercutting the economic efficiency of using
  fewer oxen. The problem of scaling the solution over long distances made things
  even worse for Paconius. He ended up in financial ruin.
</p>

<h2>The Folly of Competing Objectives</h2>

Every consumer facing software project has economic and aesthetic objectives
that are weighted to varying degrees. How do we balance these aims with
technical design?

There are clearly many [examples of software projects run off
course](http://en.wikipedia.org/wiki/Anti-pattern), similar to Paconius' failed
endeavour. However, I'm going to focus on how technical, economic and aesthetic
objectives can be acheived harmoniously per an article I read on "[Designing for
Performance](http://webdesign.tutsplus.com/articles/user-experience-articles/designing-for-performance/),"
by [P.J. Onori](https://twitter.com/somerandomdude).

<blockquote
cite="http://webdesign.tutsplus.com/articles/user-experience-articles/designing-for-performance/">
&ldquo;Designing for performance requires a commitment to maximize the
necessities and strip out superfluous luxuries. A more utilitarian approach
towards design is needed where each element has a tangible and net-positive
impact on the end result. This does not negate the importance of aesthetics,
rather it means that it should not given a blank check.&rdquo; </blockquote>

*No blank checks* doesn't mean letting the engineering team make all the
decisions, it means regardless of your role, embrace an engineer's mindset. One
reason why [VCs are insistent on startups having technical
founders](http://allthingsd.com/20130305/seven-more-questions-for-andreessen-horowitz-enterprise-dude-peter-levine/?mod=tweet)
is their ability to assess the implications of conceptual design. Think
carefully about how early design decisions impact technical architecture and
performance. At the end of the day, we're all trying to solve problems, and this
leads into my favorite part of P.J.'s article:

<blockquote
cite="http://webdesign.tutsplus.com/articles/user-experience-articles/designing-for-performance/">
&ldquo;…aesthetics should always support the problems we are asked to solve….
Looking at design through this lens will help create a goal-driven approach and
focus our thinking.&rdquo; </blockquote>

<h2>In Summary</h2>

Goals alone aren't enough to keep a project on track. To spare future
generations the humor of reading about your own spectacular failures:

- Recognize competing objectives and resolve them as early as possible.
- Explore novel problems and potential solutions with users, designers and
  engineers.
- Question and attack your own ideas, but don't stop having them.
