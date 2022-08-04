---
layout: post
title:  "GSoC-22"
author: anjishnu
categories: [ GSoC ]
tags: [ GSoC 2022 ]
image: assets/images/gsoc-22/project dashboard gsoc.png
description: "Contributed to 🔥LIT from Google PAIR as part of the GSoC 2022 program!"
featured: true
hidden: true
---

> Contributed to 🔥LIT from Google PAIR as part of
> the GSoC 2022 program!

I participated in GSoC for the first time in 2020. It was a fun experience and
eventually was helpful during the process of me landing my first job in software
development as well. After spending about a year in that role, I decided to go
for something that I have always wanted to do, a PhD in Computer Science. I am
starting as a PhD student at George Mason University this Fall (2022). But
before I start my graduate journey, I wanted to re-experience GSoC one last time
(you can be a GSoC contributor only twice). When I saw
[🔥LIT](https://pair-code.github.io/lit/) offering
projects for this year's GSoC, I knew I had to atleast try.

And so I did! I wanted to apply for a lightweight project because that would give me
sufficient space to enjoy my time as a contributor, while I prepared to move
across continents towards the end of my project. The [🔥LIT Tutorials
project](https://github.com/PAIR-code/lit/issues/664) fit this description
perfectly. I took some time to understand basic 🔥LIT components and created a
project proposal. This year's proposal was only 10 pages long
(compared to the 40 page behemoth from my previous gsoc application), but it was
fundamentally solid. I submitted this and waited for about a month for the
results. I was very happy to be selected, because this meant I could spend the
summer working on something closely related to my PhD topic. I reached out to my
mentor and we had an orientation call soon after. I also met other members of
the 🔥LIT team and one of my fellow contributors as well during the community
bonding period.

The "coding period" is a bit unique this time, because some of my contributions
aren't exactly "code". To explain, this basically means that I went through the
development and feedback process for the tutorials mostly in a google docs
environment and then converted it to markdown for rendering in the 🔥LIT website.
Also during this entire process, I had to ideate and run multiple experiments
using 🔥LIT, which sometimes led me to discover bugs. As per feedback on my
midterm evals, all of this was helpful to the 🔥LIT team in making 🔥LIT a more
robust and accessible OSS project :)

Since I will be linking to this blog as my final work product submission, I will
link to the relevant issues and PRs below, and add in a short description for
them.

Tabular Feature Attribution Tutorial :

- Focuses on Tabular Feature Attribution based on the Kernel SHAP method.
- Uses the penguins demo from the LIT website to illustrate the different ideas.

Text Salience Maps Tutorial :

- Focuses on Text Salience Maps, specificially Grad L2 Norm, Grad · Input,
  Integrated Gradients and LIME.
- Uses the GLUE demo from the LIT website to illustrate the different ideas.

Issues :

- [Tabular Feature Attribution Tutorial](https://github.com/PAIR-code/lit/issues/755)
- [Text Salience Maps Tutorial](https://github.com/PAIR-code/lit/issues/812)

Pull Requests :

- [Tabular Feature Attribution Tutorial](https://github.com/PAIR-code/lit/pull/801)
- [Text Salience Maps Tutorial](https://github.com/PAIR-code/lit/pull/815)

Workflow :

- We (me and Ryan) had regular weekly meetings. For these meetings we kept a
  google doc for meeting notes, where we noted down action items for the next
  week and brief notes on items discussed in the current week. The meetings
  covered a wide range of discussions from solving queries in the tutorial
  creation process, to reviews and feedback, to brainstorming and more.
- For brainstorming, I used a google doc to explore each of the two modules of
  interest in depth. I noted down possible questions that different types of
  users might have. And then I created a draft outline by organizing those
  questions into a structured flow.
- From the outline, I expanded the content into the final draft, which was
  reviewed multiple times by many people on the LIT team. I incorporated all the
  feedback into the draft before starting with the PR process.
- For the PR process, I created a branch from ```dev``` for each of the 2 PRs.
- Within the branch, I added the content within a markdown file. Converting from
  google docs to markdown seemed a very time-consuming task at first, but a
  google docs extension helped me out with this ([Docs to
  Markdown](https://workspace.google.com/marketplace/app/docs_to_markdown/700168918607)
  by [Ed Bacher](https://github.com/evbacher)).
- I downloaded the google doc file as a website, to get all my images in one
  place. But this downloads the images with a slightly arbitrary filenaming
  system. So, then I went through the HTML file to rename the images in a better
  readable format for my PR. I added these images and the modified markdown
  output to my branch. And boom, done!
- A google UXD team would be adding in some final touches to the images
  (adding annotations and converting some of them to gifs) once the review
  process is complete, and then the tutorials would be hosted on the live
  website for LIT.

Overall, this GSoC was amazing! My mentor, Ryan is absolutely the G.O.A.T.
Couldn't have completed this smoothly without all his help!

<div align="center">
<img src="../assets/images/gsoc-22/goat.png">
<p><b><i>Ryan is the G.O.A.T. (image generated using Dalle-mini)</i> 👀</b></p>
<p></p>
</div>

Thank you to everyone at 🔥LIT, for considering me for this project. Couldn't have
asked for a better way to spend this summer.

See you soon! Bye 👋🏻👋🏻
