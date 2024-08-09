# [Algo Group Personal Website Template](https://algo-group-uchicago.github.io/personal-site-template/)

<div align="center">
  <br>
  <img src="images/algo_group_logo.jpg"
      width="200" 
      height="auto">
  <br><br>
  https://algo-group-uchicago.github.io/personal-site-template/
  <br><br>
</div>

This repo is a template for Algo Group UChicago students to use for making their own personal site with relatively little effort. Simply clone the repo and edit the links, text, and colors to get started.

If you're feeling up for it, try adding stuff to the template to make the site more personalized. An example of this kind of customization can be found here: https://kathirm.com.

## Repo Structure
```
├── README.md
├── images
│   ├── README.md
│   ├── algo_group_logo.jpg
│   ├── github-colored.png
│   ├── github-white.png
│   ├── linkedin-colored.png
│   ├── linkedin-white.png
│   ├── mail-colored.png
│   ├── mail-white.png
│   ├── resume-colored.png
│   └── resume-white.png
├── index.html  // start here to make basic changes
├── resume.pdf
├── script.js  // add any new scripts for the page here
├── structure.txt
└── styles
    ├── custom_additions.css  // add new styling (change colors, button appearances, etc.) here
    └── default_style.css
```

## Hosting on GitHub
- First, it's recommended that you host the code in your GitHub root repo, i.e. you should clone this code into a repository called `[your-username].github.io` so that the hosted page is called `[username].github.io` and not `[username].github.io/[repo-name]`.
- In order for the code to reflect as a web page, we need to turn on pages for the repo in question.
  - Navigate to `Settings` in your repo.
  - Find `Pages` on the left bar.
  - Under `Branch`, set it to the branch you want to deploy (probably main or master).
  - Save, and wait for the build to run.
- Wait and see if the link works by navigating to the link that the prompt tells you (ideally, if the repo in question is the special `[your-username].github.io` repo, just visit `[username].github.io`)

## Reaching Out
- Contact your Algo Group mentor or one of the board members with any questions.
- Feel free to shared deployed sites with us! We definitely want to see what directions people take with the template.
