---
title: Chinook Music Store Album Managament System
publishDate: 2024-03-29
img: /assets/work/demo-chinook/demo-chinook-main.png
img_alt: Screenshot of the login page for the admin system
description: Custom made by me during my bachelor's year at the University of West of Scotland. Featuring .NET.
tags:
  - C#
  - Razor
  - Entity Framework
  - CRUD
  - SQLite
  - Admin Page
featured: true
index: 3
---

## Chinook Album Management System

> A university project where I built a simple CRUD interface and got my chance to experience the Microsoft Java, I mean C# 😉

<a href="https://github.com/tom-gora/school-csharp-stuff/tree/main/final_project/ChinoookMusicStore">Source Code &nbsp; <svg xmlns="http://www.w3.org/2000/svg" style="margin-bottom:-4px;" width="1em" height="1em" viewBox="0 0 512 512"><path fill="currentColor" d="M32 96c-17.7 0-32 14.3-32 32s14.3 32 32 32h208V96zm160 192c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm-64-64c0 17.7 14.3 32 32 32h48c17.7 0 32-14.3 32-32s-14.3-32-32-32h-48c-17.7 0-32 14.3-32 32m96 160c-17.7 0-32 14.3-32 32s14.3 32 32 32h64c17.7 0 32-14.3 32-32s-14.3-32-32-32zm88-96h-.6c5.4 9.4 8.6 20.3 8.6 32c0 13.2-4 25.4-10.8 35.6c24.9 8.7 42.8 32.5 42.8 60.4c0 11.7-3.1 22.6-8.6 32h8.6c88.4 0 160-71.6 160-160v-61.7c0-42.4-16.9-83.1-46.9-113.1l-11.6-11.6C429.5 77.5 396.9 64 363 64h-27c-35.3 0-64 28.7-64 64v88c0 22.1 17.9 40 40 40s40-17.9 40-40v-56c0-8.8 7.2-16 16-16s16 7.2 16 16v56c0 39.8-32.2 72-72 72"/></svg></a>

#### Background

The starting point for this project was using the received SQLite .db file to crerate a CRUD app that will allow fictional employees to manage the album stock.

#### What goals?

- Gaining experience with C# and .NET to produce viable server side applications.
- Templating markup with Razor and/or MVC model.
- Working with ORM abstractions rather than raw SQL queries.
- Using VSCode but also learning to install Omnisharp language server and configure .editorconfig in the environment which is an important skill for keeping the coding style consistent with a team's preferences.
- Spicing up work on the design process to look into modern CSS nesting patterns available native without preprocessors.

#### Features

- Basic authentication with email and password being birthday (to allow teacher access, yet making it a little bit unguessable). Passwords are not stored, simple compared against formatted string based on DoB.
- All basic CRUD operations for albums list.
- Simple responsive UI.
- Dedicated logic based on whether the Album or Artist exists in the database, has 0, 1 or more entries per Artist etc.

![Recording of the Chinook app operation](/assets/work/demo-chinook/demo-chinook-1.apng)  
