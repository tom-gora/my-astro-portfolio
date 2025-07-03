---
title: Java Gym App
publishDate: 2023-14-05
img: /assets/work/demo-gym/demo-gym-main.png
img_alt: Screenshot of the main page for the app
description: Custom made by me during my final year at the Edinburgh College. Featuring Java and Spring Boot.
tags:
  - Java
  - Spring Boot
  - Thymeleaf
  - CRUD
  - MySQL
  - Admin Page
  - Docker
featured: false
index: 5
---

## Java Gym App

> A college project where I built a simple CRUD interface using Java to render a simple in-browser experience.

<a href="https://javagym.tomgora.online">Live Site &nbsp; <svg xmlns="http://www.w3.org/2000/svg" style="margin-bottom:-4px;" width="1em" height="1em" viewBox="0 0 512 512"><path fill="currentColor" d="M32 96c-17.7 0-32 14.3-32 32s14.3 32 32 32h208V96zm160 192c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm-64-64c0 17.7 14.3 32 32 32h48c17.7 0 32-14.3 32-32s-14.3-32-32-32h-48c-17.7 0-32 14.3-32 32m96 160c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm88-96h-.6c5.4 9.4 8.6 20.3 8.6 32c0 13.2-4 25.4-10.8 35.6c24.9 8.7 42.8 32.5 42.8 60.4c0 11.7-3.1 22.6-8.6 32h8.6c88.4 0 160-71.6 160-160v-61.7c0-42.4-16.9-83.1-46.9-113.1l-11.6-11.6C429.5 77.5 396.9 64 363 64h-27c-35.3 0-64 28.7-64 64v88c0 22.1 17.9 40 40 40s40-17.9 40-40v-56c0-8.8 7.2-16 16-16s16 7.2 16 16v56c0 39.8-32.2 72-72 72"/></svg></a>
<a href="https://github.com/tom-gora/spring-boot-gym-app-college" style="margin-left: 4rem;">Source Code &nbsp; <svg xmlns="http://www.w3.org/2000/svg" style="margin-bottom:-4px;" width="1em" height="1em" viewBox="0 0 512 512"><path fill="currentColor" d="M32 96c-17.7 0-32 14.3-32 32s14.3 32 32 32h208V96zm160 192c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm-64-64c0 17.7 14.3 32 32 32h48c17.7 0 32-14.3 32-32s-14.3-32-32-32h-48c-17.7 0-32 14.3-32 32m96 160c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm88-96h-.6c5.4 9.4 8.6 20.3 8.6 32c0 13.2-4 25.4-10.8 35.6c24.9 8.7 42.8 32.5 42.8 60.4c0 11.7-3.1 22.6-8.6 32h8.6c88.4 0 160-71.6 160-160v-61.7c0-42.4-16.9-83.1-46.9-113.1l-11.6-11.6C429.5 77.5 396.9 64 363 64h-27c-35.3 0-64 28.7-64 64v88c0 22.1 17.9 40 40 40s40-17.9 40-40v-56c0-8.8 7.2-16 16-16s16 7.2 16 16v56c0 39.8-32.2 72-72 72"/></svg></a>

#### Background

The project was a personal idea and somehow challenge driven. The received task was extremely simple (in my personal view, given nearly 2 years of college have passed by then) and involved writing a simple terminal application.
The requirements? Read and write data from a .txt file, allow adding club members and displaying a mock "monthly receipt". And it has to be Java. I approached this differently, given that at that point I already knew I git extremely passionate about Web and had zero interest in writing yet another collection of
`System.out.println();` calls. And so I read the docs to learn Spring, MVC model, templating system and working with an ORM to create a basic app that is made in Java and stores data remotely, yet meets the requirements.

#### What goals?

- Expanding Java knowlegde beyong printing lines to CLI.
- Using a framework to do some MVC, as at that point we mainly used PHP echo statements and jQuery.
- Challenging myself to go an extra mile.

#### Features

- Simple webpage UI to deliver features that were required.
- Basic responsiveness.
- CRUD operations. Well, maybe CRD only. Edition was not implemented as the requirements did not ask for it.

UPDATE: \*

- For new server setup deployed neatly and nicely in a containerized form from openjdk alpine image and mariadb:latest

<video class="animated-demo"  autoplay loop muted playsinline poster="/assets/work/demo-gym/demo-gym-main.png">
    <source src="/assets/work/demo-gym/demo-gym-1.mp4" type="video/mp4">
</video>

<video class="animated-demo"  autoplay loop muted playsinline poster="/assets/work/demo-gym/demo-gym-2-preview.png">
    <source src="/assets/work/demo-gym/demo-gym-2.mp4" type="video/mp4">
</video>
