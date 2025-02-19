---
title: PhoneZone
publishDate: 2024-02-02
img: /assets/work/phonezone/phonezone-main.png
img_alt: Screenshot of PhoneZone landing page
description: Custom made by me during my bachelor's year at the University of West of Scotland. Featuring TailwindCSS and PHP.
tags:
  - Design
  - Front End
  - Back End
  - PHP
  - MySQL
  - Tailwind CSS
featured: true
index: 2
---

## PhoneZone - Online Smartphone Butique

> Project that evolved from a simple PHP class assignment into something much bigger.

<a href="https://phonezone.tomgora.online">Live Site &nbsp; <svg xmlns="http://www.w3.org/2000/svg" style="margin-bottom:-4px;" width="1em" height="1em" viewBox="0 0 512 512"><path fill="currentColor" d="M32 96c-17.7 0-32 14.3-32 32s14.3 32 32 32h208V96zm160 192c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm-64-64c0 17.7 14.3 32 32 32h48c17.7 0 32-14.3 32-32s-14.3-32-32-32h-48c-17.7 0-32 14.3-32 32m96 160c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm88-96h-.6c5.4 9.4 8.6 20.3 8.6 32c0 13.2-4 25.4-10.8 35.6c24.9 8.7 42.8 32.5 42.8 60.4c0 11.7-3.1 22.6-8.6 32h8.6c88.4 0 160-71.6 160-160v-61.7c0-42.4-16.9-83.1-46.9-113.1l-11.6-11.6C429.5 77.5 396.9 64 363 64h-27c-35.3 0-64 28.7-64 64v88c0 22.1 17.9 40 40 40s40-17.9 40-40v-56c0-8.8 7.2-16 16-16s16 7.2 16 16v56c0 39.8-32.2 72-72 72"/></svg></a>
<a href="https://github.com/tom-gora/phonezone" style="margin-left: 4rem;">Source Code &nbsp; <svg xmlns="http://www.w3.org/2000/svg" style="margin-bottom:-4px;" width="1em" height="1em" viewBox="0 0 512 512"><path fill="currentColor" d="M32 96c-17.7 0-32 14.3-32 32s14.3 32 32 32h208V96zm160 192c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm-64-64c0 17.7 14.3 32 32 32h48c17.7 0 32-14.3 32-32s-14.3-32-32-32h-48c-17.7 0-32 14.3-32 32m96 160c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm88-96h-.6c5.4 9.4 8.6 20.3 8.6 32c0 13.2-4 25.4-10.8 35.6c24.9 8.7 42.8 32.5 42.8 60.4c0 11.7-3.1 22.6-8.6 32h8.6c88.4 0 160-71.6 160-160v-61.7c0-42.4-16.9-83.1-46.9-113.1l-11.6-11.6C429.5 77.5 396.9 64 363 64h-27c-35.3 0-64 28.7-64 64v88c0 22.1 17.9 40 40 40s40-17.9 40-40v-56c0-8.8 7.2-16 16-16s16 7.2 16 16v56c0 39.8-32.2 72-72 72"/></svg></a>

#### Why?

Since I was bound by the class requirements to use plain old PHP in this project I decided to improve upon provided base and add some modern spin to it, while learning a lot about integrating approaches and working with data across various technologies. The core marriage of old and new is plain PHP working in tandem with Tailwind CSS to create modern custom look to a plain old static site.

#### What principles?

- Redesigned database structure that is simple but neat and normalized.
- Rather than hardcoding things in markup, I store components as HTML files fetch them, modifying them dynamically with data either on the server, or on the client with fetched data.
- Neater project structure follows the above. Markup, js, php scripts and php pages that effectively serve as view components are separated.
- Apart from a minimal composer package preparing api urls for oAuth, no frameworks, components or libraries were used. All dynamic elements, styles, server functions and validations are written by me without third party code. Yes, this was mundane, but was intentional and served as a great learning experience on working with both PHP and JavaScript.

#### Features

- Custom svg logos and graphics made in Inkscape.

![Store logo designs in dark and light variants](/assets/work/phonezone/phonezone-1.png)

- Fully responsive design.

- Dark mode, with persistent state.
- Custom style with clear accent colors palette, inspired by neubrutalist "blockiness" but with classier, toned down colors.

<video class="animated-demo"  autoplay loop muted playsinline poster="/assets/work/phonezone/phonezone-2-preview.png">
    <source src="/assets/work/phonezone/phonezone-2.mp4" type="video/mp4">
</video>

- Custom animations, with reduced-motion included.
- Custom Admin Panel with Admin and Owner roles scoped and validated both on server and client.

<video class="animated-demo"  autoplay loop muted playsinline poster="/assets/work/phonezone/phonezone-3-preview.png">
    <source src="/assets/work/phonezone/phonezone-3.mp4" type="video/mp4">
</video>

- Error and messages handling with feedback for the user.

<video class="animated-demo"  autoplay loop muted playsinline poster="/assets/work/phonezone/phonezone-4-preview.png">
    <source src="/assets/work/phonezone/phonezone-4.mp4" type="video/mp4">
</video>

<video class="animated-demo"  autoplay loop muted playsinline poster="/assets/work/phonezone/phonezone-5-preview.png">
    <source src="/assets/work/phonezone/phonezone-5.mp4" type="video/mp4">
</video>

- Two options for third-party authorisation: Google and Github.

<video class="animated-demo"  autoplay loop muted playsinline poster="/assets/work/phonezone/phonezone-6-preview.png">
    <source src="/assets/work/phonezone/phonezone-6.mp4" type="video/mp4">
</video>

- Custom components: Navigation as top-bar or sidebar on mobile, Home page Hero Section, Pagination, Breadcrumbs Navigation, Working cart with persistent per-user state stored in the database, an array of dialogs for edits confirmation etc. and more...

UPDATE: \*

- For new server setup deployed neatly with docker containers pulled from php-fpm and mariadb.
