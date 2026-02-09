---  
title: J-SOON  
publishDate: 2026-02-08  
img: /assets/work/jsoon/jsoon-main.png  
img_alt: Screenshot of Web Demo for JSOON binary  
description: The big return  
tags:  
  - Golang  
  - Service  
  - CLI tool  
  - Unix Philosophy  
  - Calendar and Events  
  - Notifications  
  - Astro + Svelte  
  - Smart Work With AI  
featured: true  
index: 1  
---  

## JSOON. Upcoming events from iCal.

> This tool is my small personal helper for self organization and a project to return to coding from the depths of the void()  

<span style="display: flex; justify-content: space-between;">  
<a href="https://jsoon.tomgora.online">Online Demo&nbsp; <svg xmlns="http://www.w3.org/2000/svg" style="margin-bottom:-4px;" width="1em" height="1em" viewBox="0 0 512 512"><path fill="currentColor" d="M32 96c-17.7 0-32 14.3-32 32s14.3 32 32 32h208V96zm160 192c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm-64-64c0 17.7 14.3 32 32 32h48c17.7 0 32-14.3 32-32s-14.3-32-32-32h-48c-17.7 0-32 14.3-32 32m96 160c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm88-96h-.6c5.4 9.4 8.6 20.3 8.6 32c0 13.2-4 25.4-10.8 35.6c24.9 8.7 42.8 32.5 42.8 60.4c0 11.7-3.1 22.6-8.6 32h8.6c88.4 0 160-71.6 160-160v-61.7c0-42.4-16.9-83.1-46.9-113.1l-11.6-11.6C429.5 77.5 396.9 64 363 64h-27c-35.3 0-64 28.7-64 64v88c0 22.1 17.9 40 40 40s40-17.9 40-40v-56c0-8.8 7.2-16 16-16s16 7.2 16 16v56c0 39.8-32.2 72-72 72"/></svg></a>  
<a href="https://github.com/tom-gora/j-soon" style="margin-left: 4rem;">Source Code &nbsp; <svg xmlns="http://www.w3.org/2000/svg" style="margin-bottom:-4px;" width="1em" height="1em" viewBox="0 0 512 512"><path fill="currentColor" d="M32 96c-17.7 0-32 14.3-32 32s14.3 32 32 32h208V96zm160 192c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm-64-64c0 17.7 14.3 32 32 32h48c17.7 0 32-14.3 32-32s-14.3-32-32-32h-48c-17.7 0-32 14.3-32 32m96 160c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm88-96h-.6c5.4 9.4 8.6 20.3 8.6 32c0 13.2-4 25.4-10.8 35.6c24.9 8.7 42.8 32.5 42.8 60.4c0 11.7-3.1 22.6-8.6 32h8.6c88.4 0 160-71.6 160-160v-61.7c0-42.4-16.9-83.1-46.9-113.1l-11.6-11.6C429.5 77.5 396.9 64 363 64h-27c-35.3 0-64 28.7-64 64v88c0 22.1 17.9 40 40 40s40-17.9 40-40v-56c0-8.8 7.2-16 16-16s16 7.2 16 16v56c0 39.8-32.2 72-72 72"/></svg></a>  
</span>  

<br>  

#### Disclaimers

- 1: While seeing the web demo use some public `*.ics` files to play around with online demo. You have to trust me that the exact code from gihub is running in prod and my little toy is not stealing you personal calendar data 😉 Jokes aside there is zero CRUD. Web demo is a front that calls the go binary on the backend in a docker container and instantly presents the json output on a page. Some sample public calendars to play around are provided.  

- 2: AI has been used. Heavily controlled to learn to tame the clankers, but in a manner of precise control. Not just opening IDE and happily tabbing away. No Cursor nor any other VSCode family offshoots. No one-shotting the app. Small steps, lots of instructions running via `opencode` hooked up to `openrouter`. Lots of chat usage for inspiration or as a tutor/helper with pointing to current docs for accuracy. Almost all of the go code that started as a refactor of a small tool I found and cloned from GH written by hand. Front end base build with AI, then had to be heavily rewritten and tidied up by me as well because of course Gemini produced a small static 3-pages website using nothing but React components (Yeah... still waiting for this AGI to arrive). Refactored to plain Astro and the dynamic toast notifications system changed to Svelte because it's quicker, lighter and is easier workign with component state without bringing in entire package of virtual DOM or writing custom state machine in Vanilla JS. Tests all written by AI but designed and guided one by one by me.  

#### Why?

This is build to stretch those atrophied coding muscles. JSOON is a GO cli tool (No TUI. Flags and Pipes for scripting only) that extracts ucoming events from iCal (\*.ics) files.  
Developed for myself to power simple system notification system for upcoming events and reminders, simply because gnome-calendar on Linux is like most of Gnome. All fluff and opinions and no substance or helpful workflow. Meaning it does not work with remote calendars too well if at all. In TUI Calcure does it but it does not live sync or provide reminders/notifications.  

JSOON is minimal. Pipe in data, or configure calendars with config file. Tell it with flag or config file how far ahead to look for events in those calendars and it will return a json string with things that are lined up soon. By default to stdout, but can be set to write to a file. Feed output to json. Use on a web page, for a discord bot... Hell, use it even for your agentic flows, but I will not take responsibility for broken relationships if your clanker hallucinates a date with Sarah your wife has no idea about!  

#### What principles?

- Simple. Unix philosophy, script and pipe data. Just a tool for my needs that does one thing. Satya and his SlopOS not welcome. If you know your way around go you should be also able to build for mac and use it as it's just dead simple with no os libs and integrations.  
- Meant to return to coding and go beyond plain webdev box I boxed myself up in.  
- Write at least most basic tests this time. Browser forgives everything. Things run on OS and meant for integration not necessarily.  

#### Features

- It's dead simple has just a few features and hopefully does the job.  

---  

**In action on my system:**  

<video width="100%" controls>  
  <source src="/assets/work/jsoon/jsoon-demo.mp4" type="video/mp4">  
  Your browser does not support the video tag.  
</video>
