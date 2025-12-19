## Edit page content

(1) Go to the folder where you want to store your project, and clone the new repository:
```
git clone https://github.com/<username>/<username>.github.io.git
```
The directory structure is as follows:

```.
.
├── contents
└── static
    ├── assets
    │   └── img
    ├── css
    └── js
```

(2) Modify the content of each section, which corresponds to `contents/*.md`.

(3) Adjust the title, copyright information, and other text of the website in `contents/config.yml`

(4) Replace background image and photo with new ones for your web pages in `static/assets/img/`

(5) Push it: 
```
git commit -am 'init'
git push
```

## Setup
(1) Under your repository name, click `Settings`.

(2) In the "Code and automation" section of the sidebar, click `Pages`.

(3) Under "Build and deployment", under "Source", select Deploy from a branch. Then, use the branch dropdown menu and select a publishing source.

## Enjoy

Fire up a browser and go to `https://<username>.github.io`

> Note that it can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub.