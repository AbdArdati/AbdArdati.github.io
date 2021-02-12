---
layout: project
type: project
image: images/home-STA.jpg
title: Getting Onboard with Wikipedia
permalink: projects/wikipedia-onbarding
# All dates must be YYYY-MM-DD format!
date: 2020-04-27
labels:
  - Wikipedia
  - Research
  - Senior Honours Project Supervision
  - University of St Andrews
  - ReactJs
  - Browser Extensions
summary: A Firefox extension to reduce the barrier to entry for new Wikipedia users.
---

<div class="ui medium rounded images">
  <img class="ui image" src="../images/SH-J-1.4.png">
  <img class="ui image" src="../images/SH-J-1.6.png">
  <img class="ui image" src="../images/SH-J-2.1.png">
  <img class="ui image" src="../images/build.png">
</div>

## Description

Wikipedia has suffered from a decline in new active editors since 2007, and attempts at successfully onboarding new editors to become active contributors have yet to make a considerable impact. Creating an onboarding experience to increase new editor numbers and diversification is becoming a more important issue to tackle as Wikipedia's popularity grows with active contribution declining. 

This project by Jack Leslie and suppervised by Alexander Voss & Abd Alsattar Ardati assesses previous onboarding project attempts and presents a prototype for a new onboarding experience to tackle the pitfalls of its predecessors. Our proposed solution is a browser extension with a direct and interactive onboarding experience to facilitate the transition of new editors to continuous, active editors.

## Objectives

- Develop a browser extension to guide a user in completing tasks that new editors of
Wikipedia typically need to accomplish.
- Provide a curated set of links and information in the browser extension as a reference for
the user provided in a context-sensitive manner to provide guidance as the user goes
about a task spanning multiple Wikipedia pages.
- Provide functionality in the browser extension to highlight important page content
required for the accomplishment of the tasks through DOM manipulation.
- Provide functionality to perform tasks through mouse interaction with highlighted page
elements.

## Conclusions

Before implementing a new onboarding experience for Wikipedia we had to discuss what previous onboarding attempts had done well and what their limitations were. From this discussion we were able to derive an exciting new idea for onboarding which involved using a sidebar extension as a way to deliver content and incorporating the key aspects for successful onboarding. These key aspects included a focus on being introduced early in the editor lifecycle with a clear overview of the onboarding process itself and a way to access specific information with ease during onboarding. The persistence of the extension in the current browser context for the user, rather than being in a separate window or tab, provided an even more direct and effective experience for users. The project was built using sound design principles and with industry standard libraries, frameworks and tooling in the JavaScript ecosystem. Through scenario testing and heuristic evaluation the extension shows great promise as an effective new onboarding experience, however would benefit greatly from real user feedback in order to measure the effectiveness. The focus on software quality with respect to high reusability, as well as self documentation with tools such as Storybook, mean that the project could easily be picked up and iterated on to benefit from in response to real user feedback, which could be gathered in a more suitable climate.


