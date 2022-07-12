    updated: Saturday, 25th June 2022

<div align=center>
    <a href="https://memories-pritam.netlify.app/">
        <img width=200 src="assets/icon.png" alt="Euphoria">
    </a>
    <p style="font-family: roboto, calibri; font-size:12pt; font-style:italic"> Cherishing the past with love </p>
    <a href="https://app.netlify.com/sites/memories-pritam/deploys">
    <img src="https://api.netlify.com/api/v1/badges/db24b02d-0b1f-4b4a-a07c-fe3b8318abe7/deploy-status" alt="Netlify Status">
    </a>
</div>

# [Memories](https://memories-pritam.netlify.app)

## What's new?

-   Comment Delete Buttons
-   Now Post Owners can regulate comments on their posts

## Table of Contents

-   [Introduction](#introduction)
-   [Acknowledgement](#acknowledgement)
-   [Featues](#features)
-   [Tech Stack Used](#tech-stack-used)
-   [Previews](#previews)
-   [Demo](#demo)
-   [License](#license)

---

## Introduction

-   In earlier days people used to store their valuable memories in Diaries.
-   Days have changed, but needs of people still remain the same.
-   This is a WebApp helps suffice the need for a Digital Diary and help improve the user Experience.
-   The Anime [Kimi no Na wa](https://en.wikipedia.org/wiki/Your_Name) gave me inspiration to improve this project every bit.

---

## Acknowledgement

-   Thanks to JS Mastery for this wonderful tutorial.
-   I have added more refined features on top of this project.

---

## Features

-   Minimalist Look, TransLucent Card Type Posts
-   CRUD based Operations, Post Search Functionality with Tags
-   Details Page of each Post Card, Recommended Posts
-   Image Compression (compresses every image under 1MB)
-   Like - Comment - Tag functionality and 2 Way Authentication (JWT Token & Google OAuth)
-   Random Custom User Avatar
-   Image Drag and Drop functionality in Preview while creation
-   Private Post and Comment Deletion Functionality
-   Attention to detail features like comment circular progress, custom Private button gives it the wow factor
-   Post Owners can regulate comments in their posts
-   While deleting comment TrashCan icon turns CircularProgress
-   Comments section only visible if at least 1 comment exist in a post.

## Tech Stack Used

-   Material UI: Styling & Icons
-   MongoDB: For DataBase Management
-   ExpressJs: For BaackEnd Routing
-   React: FrontEnd Developement
-   NodeJS: For BackEnd developement
-   Netlify: For hosting the frontEnd
-   Heroku: Hosting the backEnd

---

## Previews

-   Desktop Preview ![Desktop-Preview](assets/desktop-preview.png)

-   Mobile Preview  
    ![Mobile-Preview](assets/mobile-preview.png)

---

## Demo

![Customizations](assets/demo.gif)

---

## Upcomming

-   Comment Deletion feature for comment Authors. Currently making changes in Database postMessages Schema in the Comments array to add new fields for better comment regulation in future.
-   Known Bugs: Same comments from same user posted multiple times gets deleted all at once while deleting single one of them

---

## License

-   see [LICENSE]

**Pritam, 2022**

[license]: https://github.com/warmachine028/memories/blob/main/LICENSE