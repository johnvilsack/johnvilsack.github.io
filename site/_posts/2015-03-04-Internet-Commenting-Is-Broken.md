---
layout: post
title: Commenting on the Internet is Broken
section: Blog
postdate: February 16th, 2015
---
I frequent [HackerNews](https://news.ycombinator.com) as part of my daily dose of tech happenings. It was there that I began to realize that the Internet is not a very good place to have discussions with people who may not agree with you.  This is probably not a revelation to anyone who has ever 
accidentally scrolled down in the comments section of a YouTube video, but I find it somewhat disconcerting that this trickles up even into civilized discussions.

Case in point, I made a comment about a post on HN that linked to [this article](https://sourcegraph.com/blog/live/gopherconindia/112656568167) about a blog post that outlined one team's experiences on switching a portion of their architecture from Ruby to Go.  The article makes many great points outlining the benefit of 
favoring microservices over monolithic application architecture but the central frothing point of the commentators naturally centered around "Which programming language (that I happen to use) is best."

I wrote (what I felt to be) a fairly sensible comment about how any sort of  refactorization will yield benefits through experience gained and lessons learned.  Unfortunately I opened with the line, "Ruby enthusiasts seem to get apoplectic at any mention of a posting where someone chooses another language over Ruby.  I'm sure Ruby is just great at what it does, but aren't we always talking about the right tool for the job?" and less than a minute after I posted my comment, someone downvoted my comment.

On HackerNews, comments are naturally sorted by how many upvotes a comment receives.  Get enough people to click the up button, you become the top comment.  Get a few downvotes and your comment actually becomes invisible to the discussion because it's deemed irrelevant to the conversation.

This works reasonably well to ensure that most of the time the top comments usually are articulated well, but through using popularity voting, the top comment will also tend to be the one that most reflects the bias of the community.  Discourse may be had within, but ultimately you have to scroll not on the merits of the voice, but on the consensus of the echo chamber.

In another example, here is a comment thread about [Dependencies and vendoring in Go](https://news.ycombinator.com/item?id=9138844).  The commentary in the discussion is largely valid, but the sorting of the discussion is based on upvotes.  13 of the 27 comments in the thread happened under a question I asked, but because nobody clicked the up arrow before replying, the conversation appears at the bottom of the discussion page.  People cared enough about the topic to discuss it, but HackerNews sorts it below (certainly valid) anecdotes and comments that received replies that have been downvoted as well.

I'm picking on HackerNews, but the problem exists throughout the web anywhere that you has comment voting.  People use the buttons for different reasons, and this creates a byproduct of confirmation bias through popular outcome.  [Reddit](http://reddit.com) is perhaps the largest example, but even sites like [Stack Overflow](http://stackoverflow.com) even suffer the same problem when legitimate answers are downvoted simply because people may not agree that the answer someone else provides is in line with the way they would have done it.

The only way to fix this is to find a way to capture the "value" of a comment through how often it's read and engaged. Instead of Up and Down arrows that mean something arbitrary to each person, additional options need to be considered.  Perhaps:

* I agree (an up thumb)
* I disagree (a down thumb)
* This adds to the conversation (+ sign?)
* This is off topic (- sign)
* Add weight based on how often the comment is hit
* Add weight based on how often the comment is responded to

This clearly will not solve all issues with Internet fighting, but at least it might help to introduce dissenting opinions a bit higher up on the food chain than they sit currently.
