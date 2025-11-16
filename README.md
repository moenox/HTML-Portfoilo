# Mohamed's Portfolio

Welcome to my personal portfolio! I'm Mohamed, a web developer passionate about building creative and functional web projects. This repository showcases some of the projects I have created as part of my learning journey and personal development.

## Table of Contents
- [About](#about)
- [Projects](#projects)
- [Technologies Used](#technologies-used)
- [How to View Locally](#how-to-view-locally)
- [Contact](#contact)

## About

This portfolio includes samples of my work in web development. You can find direct links to project pages, as well as screenshots for preview.

## Projects

- **[Movie Ranking Project](./public/movie-ranking.html):** A web application where I share my top movie picks.
- **[Birthday Invite Project](./public/birthday-invite.html):** A fun interactive birthday invitation web page.

Screenshots of these projects are available below.
  
![Movie Ranking Screenshot](./assets/images/Screenshot%20from%202025-11-06%2014-15-22.png)
  
![Birthday Invite Screenshot](./assets/images/Screenshot%20from%202025-11-06%2013-38-02.png)

## Technologies Used

- HTML
- CSS

## How to View Locally

1. Clone the repository:
   ```sh
   git clone https://github.com/moenox/My-Portfolio.git
   ```
2. Open `index.html` (or run using a local web server for best results):
   - For example, using Python:
     ```sh
     python3 -m http.server
     ```
   - Then open [http://localhost:8000](http://localhost:8000) in your browser.

## Directory Structure

```
My-Portfolio/
│
├── public/
│   ├── movie-ranking.html
│   ├── birthday-invite.html
│   ├── contact.html
│   └── about.html
├── assets/
│   └── images/
│        ├── Screenshot from 2025-11-06 14-15-22.png
│        └── Screenshot from 2025-11-06 13-38-02.png
├── README.md
└── ...
```

## Contact

Feel free to reach out to me via the [Contact Me](./public/contact.html) page for collaboration or feedback!

---

<!-- Original HTML content for portfolio preview below: -->

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
</head>

<body>
    <h1>Mohamed's Portfolio</h1>
    <h2>I'm a web developer</h2>
    <hr>
    <h2>My Projects</h2>
    <h3><a href="./public/movie-ranking.html">Movie Ranking Project</a></h3>
    <img src="./assets/images/Screenshot from 2025-11-06 14-15-22.png" height="550" alt="Movie Ranking">
    <h3><a href="./public/birthday-invite.html">Birthday Invite Project</a></h3>
    <img src="./assets/images/Screenshot from 2025-11-06 13-38-02.png" height="550"alt="birthday-invite">
    <hr>
    <a href="./public/contact.html">Contact Me</a>
    <br>
    <a href="./public/about.html">About Me</a>
</body>
</html>
