---
title: Mid Life Dev *Front End Crisis
publishDate: 2023-11-15
img: /assets/work/demo-blog/demo-blog-main.png
img_alt: Screenshot of the Blog landing page
description: Custom made by me during my bachelor's year at the University of West of Scotland. Featuring ReactJS.
tags:
  - React
  - Strapi
  - Docker
  - CMS
  - Blog
featured: true
index: 4
---

## Simple CMS backed personal blog - Mid Life Dev \*Front End Crisis

> An assignment for Professionalism in Creative Technologies class.

<a href="https://midlifedevdemo.tomgora.online/">Live Site &nbsp; <svg xmlns="http://www.w3.org/2000/svg" style="margin-bottom:-4px;" width="1em" height="1em" viewBox="0 0 512 512"><path fill="currentColor" d="M32 96c-17.7 0-32 14.3-32 32s14.3 32 32 32h208V96zm160 192c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm-64-64c0 17.7 14.3 32 32 32h48c17.7 0 32-14.3 32-32s-14.3-32-32-32h-48c-17.7 0-32 14.3-32 32m96 160c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm88-96h-.6c5.4 9.4 8.6 20.3 8.6 32c0 13.2-4 25.4-10.8 35.6c24.9 8.7 42.8 32.5 42.8 60.4c0 11.7-3.1 22.6-8.6 32h8.6c88.4 0 160-71.6 160-160v-61.7c0-42.4-16.9-83.1-46.9-113.1l-11.6-11.6C429.5 77.5 396.9 64 363 64h-27c-35.3 0-64 28.7-64 64v88c0 22.1 17.9 40 40 40s40-17.9 40-40v-56c0-8.8 7.2-16 16-16s16 7.2 16 16v56c0 39.8-32.2 72-72 72"/></svg></a>
<a href="https://github.com/tom-gora/mid-life-dev" style="margin-left: 4rem;">Source Code &nbsp; <svg xmlns="http://www.w3.org/2000/svg" style="margin-bottom:-4px;" width="1em" height="1em" viewBox="0 0 512 512"><path fill="currentColor" d="M32 96c-17.7 0-32 14.3-32 32s14.3 32 32 32h208V96zm160 192c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm-64-64c0 17.7 14.3 32 32 32h48c17.7 0 32-14.3 32-32s-14.3-32-32-32h-48c-17.7 0-32 14.3-32 32m96 160c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm88-96h-.6c5.4 9.4 8.6 20.3 8.6 32c0 13.2-4 25.4-10.8 35.6c24.9 8.7 42.8 32.5 42.8 60.4c0 11.7-3.1 22.6-8.6 32h8.6c88.4 0 160-71.6 160-160v-61.7c0-42.4-16.9-83.1-46.9-113.1l-11.6-11.6C429.5 77.5 396.9 64 363 64h-27c-35.3 0-64 28.7-64 64v88c0 22.1 17.9 40 40 40s40-17.9 40-40v-56c0-8.8 7.2-16 16-16s16 7.2 16 16v56c0 39.8-32.2 72-72 72"/></svg></a>

#### Background

The class mixed people from different digital creative courses, thus the task was focused on content and allowed publishing texts on the assigned topics on any platform. As a web developer I mostly supplied content that is quite "filler-like" in character consciously.
Instead I took the chance to practice some React skills and explore the great substitute for WordPress - open source CMS project called Strapi. With the CMS endpoints exposed on my server, I fetch the posts and render them as React app.

#### What goals?

- Strengthening skills in working with REST APIs returning JSON data.
- Getting experience managing basic state in an SPA app.
- Purely challenge driven. I am well aware a simple blog does not need the overhead of reactivity, virtual DOM and such.
- Exploring work with CMS backend as this is a common solution when buiulding for clients.
- Seeing what solutions alternative to WordPress look like.

#### Features

- Simple personal branding

![Screenshot of the blog](/assets/work/demo-blog/demo-blog-1.png)

- Responsive design.
- Light/dark mode, content carousel and pagination from npm packages integrated into the app.

<video class="animated-demo"  autoplay loop muted playsinline poster="/assets/work/demo-blog/demo-blog-2-preview.png">
    <source src="/assets/work/demo-blog/demo-blog-2.mp4" type="video/mp4">
</video>

UPDATE: \*

- For new server setup strapi CMS configured to run propely in a node image docker environment, with correct dependencies versions, persistent database (default SQLite) setup and hidden behind a reverse proxy.
  Backend service made ready to potentially serve more content other than just this simple blog demo.
