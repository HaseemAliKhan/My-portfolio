# Personal Portfolio - Haseem Ali Khan

CS344 Web Engineering - Lab 3: HTML Advanced - Personal Portfolio II

## About

A 5-page personal portfolio (Home, Skills, Hobbies, Gallery, Contact Me) built with
plain HTML and a single external stylesheet. Layout (navigation, image placement,
card rows, and the gallery grid) is done with CSS `float` and `clear`, no
flexbox/grid frameworks or JavaScript.

## Folder Structure

```
portfolio/
├── index.html
├── hobbies.html
├── contact.html
├── gallery.html
├── skills.html
├── css/
│   └── style.css
├── images/
│   ├── pfp_logo.png
│   ├── pfp.png
│   ├── Campus.jpeg
│   ├── dashboard.png
│   ├── coding.png
│   └── travel.png
└── README.md
```

## Deploying with GitHub Pages

1. Create a new repository on GitHub, e.g. `portfolio`.
2. In this project folder, initialize Git and push:
   ```
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/portfolio.git
   git push -u origin main
   ```
3. On GitHub, go to the repository's **Settings > Pages**.
4. Under "Build and deployment", set the source branch to `main` and the folder
   to `/ (root)`, then save.
5. GitHub will publish the site at:
   ```
   https://<your-username>.github.io/portfolio/
   ```
   (this can take a minute or two to go live).
6. Submit both the GitHub repository link and the live Pages link along with
   your zipped source files.
