---
title: Notable
publishDate: 2025-02-12
img: /assets/work/notable/notable-main.png
img_alt: Screenshot of Notable application landing page
description: A project made with Laravel and Livewire that allows you to upload scans of handwritten notes that get converted to markdown and formatted to display nicely. Uses Google Generative AI API to produce semantically correct output. Dockerized deployment.
tags:
  - API
  - Application
  - Gemini AI
  - PHP
  - Laravel
  - Tailwind CSS
  - Postgres
  - Docker Compose
featured: true
index: 1
---

## Notable - Smartly converts scanned handwritten notes to markdown

> This project is an excercise in making static site feel like SPA application, thanks to Laravel+Livewire leveraging modern approach to Ajax.

<a href="https://notable.tomgora.online">Live Site &nbsp; <svg xmlns="http://www.w3.org/2000/svg" style="margin-bottom:-4px;" width="1em" height="1em" viewBox="0 0 512 512"><path fill="currentColor" d="M32 96c-17.7 0-32 14.3-32 32s14.3 32 32 32h208V96zm160 192c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm-64-64c0 17.7 14.3 32 32 32h48c17.7 0 32-14.3 32-32s-14.3-32-32-32h-48c-17.7 0-32 14.3-32 32m96 160c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm88-96h-.6c5.4 9.4 8.6 20.3 8.6 32c0 13.2-4 25.4-10.8 35.6c24.9 8.7 42.8 32.5 42.8 60.4c0 11.7-3.1 22.6-8.6 32h8.6c88.4 0 160-71.6 160-160v-61.7c0-42.4-16.9-83.1-46.9-113.1l-11.6-11.6C429.5 77.5 396.9 64 363 64h-27c-35.3 0-64 28.7-64 64v88c0 22.1 17.9 40 40 40s40-17.9 40-40v-56c0-8.8 7.2-16 16-16s16 7.2 16 16v56c0 39.8-32.2 72-72 72"/></svg></a>
<a href="https://github.com/tom-gora/notable" style="margin-left: 4rem;">Source Code &nbsp; <svg xmlns="http://www.w3.org/2000/svg" style="margin-bottom:-4px;" width="1em" height="1em" viewBox="0 0 512 512"><path fill="currentColor" d="M32 96c-17.7 0-32 14.3-32 32s14.3 32 32 32h208V96zm160 192c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm-64-64c0 17.7 14.3 32 32 32h48c17.7 0 32-14.3 32-32s-14.3-32-32-32h-48c-17.7 0-32 14.3-32 32m96 160c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm88-96h-.6c5.4 9.4 8.6 20.3 8.6 32c0 13.2-4 25.4-10.8 35.6c24.9 8.7 42.8 32.5 42.8 60.4c0 11.7-3.1 22.6-8.6 32h8.6c88.4 0 160-71.6 160-160v-61.7c0-42.4-16.9-83.1-46.9-113.1l-11.6-11.6C429.5 77.5 396.9 64 363 64h-27c-35.3 0-64 28.7-64 64v88c0 22.1 17.9 40 40 40s40-17.9 40-40v-56c0-8.8 7.2-16 16-16s16 7.2 16 16v56c0 39.8-32.2 72-72 72"/></svg></a>

#### Why?

The base rerquirements was a Laravel-based CRUD website. This balooned into this nice slightly more ambitious project.

#### What principles?

- Exploring a modern Ajax based technology (Livewire) to enhance basic Laravel assignment
- Implementing an interesting use case for AI generative technology that isn't yet another chatbot
- Learning to deploy a dockerized application (PHP dependency hell made me do it ;)
- Leverage modern PHP to create an actual MVP of an application rather than static site from 20 years ago

#### Features

- Dynamic theme

![Store logo designs in dark and light variants](/assets/work/phonezone/phonezone-1.png)

- Fully responsive design.

- Dark mode, with persistent state.
- Custom style with clear accent colors palette, inspired by neubrutalist "blockiness" but with classier, toned down colors.

![Mobile view with dark and light modes](/assets/work/phonezone/phonezone-2.apng)

- Custom animations, with reduced-motion included.
- Custom Admin Panel with Admin and Owner roles scoped and validated both on server and client.

![admin-panel](/assets/work/phonezone/phonezone-3.apng)

- Error and messages handling with feedback for the user.

![store-logo](/assets/work/phonezone/phonezone-4.apng)  
![store-logo](/assets/work/phonezone/phonezone-5.apng)

- Two options for third-party authorisation: Google and Github.

![store-logo](/assets/work/phonezone/phonezone-6.apng)

- Custom components: Navigation as top-bar or sidebar on mobile, Home page Hero Section, Pagination, Breadcrumbs Navigation, Working cart with persistent per-user state stored in the database, an array of dialogs for edits confirmation etc. and more...
