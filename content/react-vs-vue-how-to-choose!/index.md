---
title: "React vs Vue — How to Choose!"
description: "Every generation has a major technology choice to make that will impact their products and companies for years to come. Java vs. .Net…"
date: "2019-03-28T02:23:53.456Z"
categories: []
published: true
canonical_link: https://medium.com/@scottcreynolds/react-vs-vue-how-to-choose-d8485fbf514b
redirect_from:
  - /react-vs-vue-how-to-choose-d8485fbf514b
---

![](./asset-1.png)

Every generation has a major technology choice to make that will impact their products and companies for years to come. Java vs. .Net. MySql vs Postgres. Tabs vs Spaces. Angular vs just jumping off a cliff and letting the ocean take you. These are all hard choices with a lot of great pros and cons on every side (except the Angular one — cliff all the way).

Here in the year of our lord two thousand one-niner, many people are trying to choose between React and Vue for their actually-turns-out-JavaScript-is-good? project needs. But how do you decide?

Any major tech choice needs to weigh multiple factors, and I like to break them down along three general categories:

-   The Tech — what’s it like to write code in on or the other ecosystem? What is the tooling like? The open source community? These are all important factors.
-   The Non-tech — what are the non-technical factors to consider and weigh?
-   The intangibles — what are the wild-card factors that might tip a decision one way or another?

Let’s dive in.

### The Technical Factors

Vue and React are both primarily “front-end” frameworks written in JavaScript. They have similar tooling (bundlers, transpilers, ESlint, prettier, VScode, etc). You deploy them the same way, you build them basically the same way, they have near-parity in projects (want server rendering? Try Next.js or Nuxt.js. You get to say which one is the Bizarro.) and libraries.

React is a _little_ more mature. React has somewhat more community around it but there’s no shortage in Vue. React is backed by a megacorporation which is good and bad. Vue is backed by nobody which is good and bad.

What’s it like to write code? Let’s take a look at the most basic example from the React and Vue docs, respectively:

Off the bat, we’ve got some stylistic differences. Whereas you just mount the React component into a DOM node, it seems like you have to do a kind of two-way binding on the Vue end.

Exploring further, it seems like React has a little more of a “javascripty” feel where Vue has a more “templatey” feel and these are just my personal observations. You may attach different labels.

Either way, there’s a good chance one calls out to you more than another, and if you weren’t hurt by Angular in the past, one doesn’t immediately trigger you.

Maybe you can make a decision with this info alone. Maybe you need to spike up a few components and see what feels right. Or, maybe you’re still on the fence. If so, it’s time to consider the non-technical factors.

### The Non-technical Factors

It’s important to consider some bigger-picture things when making a choice as important and life-changing as “which Javascript framework should I use?”

I have a brief checklist that I run through to test some assumptions and flag things that might be important to consider. Items include:

-   What is the skill-level of the other people on the team?
-   Does anyone already have experience with either technology?
-   What else is being built in the company and how might this choice impact that?
-   Is this framework long-lived enough to see my company into the future where there will [potentially be no fish](https://www.smithsonianmag.com/videos/category/science/the-ocean-is-running-out-of-fish-heres-the/) but whatever my startup is the “Uber” of will still be important?
-   Will this be performant enough to continue to run on current hardware [after we run out of Helium](https://www.nationalgeographic.com/science/2018/08/news-helium-mri-superconducting-markets-reserve-technology/) and can no longer etch new computer chips?
-   When [rising seas flood the city where the WeWork is that houses my company](https://www.theverge.com/2018/10/2/17924052/new-york-sea-level-rise-city-flooding-climate-change-science), will I be able to use the latest JavaScript language features with this framework?
-   [Will this company be around long enough](https://www.forbes.com/sites/neilpatel/2015/01/16/90-of-startups-will-fail-heres-what-you-need-to-know-about-the-10/) to require ever having to rewrite this in another language or framework? Will you be there long enough to have to deal with it?
-   Developer productivity is important so is this framework agile enough to get a MVP of the product out before we run out of funding?
-   Are there enough blog posts out there that I won’t have to post on StackOverflow under my alias that I use so nobody knows it’s me?
-   Do I really want to put myself through all this mental anguish and stress over choosing between two things that I know for a fact can accomplish the job for a corporation that basically is trying to figure out a better way to monetize clicks and to whom I am just a cog (but like part of the cog FAMILY) and that probably tried to get me to take a reduced salary for stock options that will be as underwater as my coastal home in a few years?

These are just a sampling of the kinds of questions you can ask yourself around the non-technical, more big-picture things that might impact your decision.

If you still can’t decide, let’s look at some of the intangibles and see if we can’t put React or Vue over the finish line.

### The Intangibles

Once you’ve examined the technical context, and the non-technical context, it’s time to think about the intangible, but still _extremely_ important things, such as:

-   Which thing has more jobs?
-   Which thing could I get more blog traffic or Twitter followers from talking about?
-   Which thing has more celebrity programmers using it?
-   Which thing did I point at after being blindfolded and spun around a bunch of times?

When all is said and done, you’re going to have to decide. The best you can do is weigh all the factors and go with your heart. But be warned. This is the highest of high-stakes. Getting it wrong can be disastrous. Just ask anyone who picked any JavaScript framework that existed before 2012. Oh right, you can’t. They were all raptured, leaving us here to deal with this shit.
