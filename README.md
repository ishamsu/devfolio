# [A simple and responsive portfolio website:-](https://github.com/ishamsu/devfolio)

I wanted a website to showcase my projects and articles and I wanted it to be simple & responsive.

<p><a href="https://github.com/ishamsu/devfolio/archive/master.zip">Download</a></p>


![index-gif](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/indexgif.gif)


##### *Feel free to play around and make this as your own!*

## Getting Started

In this section i will tell you how to make a simple responsive portfoilio website of your own and how to host it on firebase.
## Table of contents:-

- [Landing page](#landing-page)
- [What's included?](#whats-included)
- [Categories](#categories)
- [Tools used](#tools-used)
- [Fireabse hosting](#firebase-hosting)
- [Copyright and license](#copyright-and-license)


## Landing page

First we need a landing page.
 
*The mobile view of the landing page*

<div style="text-align: center"><img src="https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/mobile-home.png" width="" /></div>

<!-- ![index-gif](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/mobile-home.png) -->

*bottom view*

<div style="text-align: center"><img src="https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/mobile-home-bottom.png" width="" /></div>

<!-- ![index-gif](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/mobile-home-bottom.png) -->

*navbar*

<div style="text-align: center"><img src="https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/mobile-nav.png" width="" /></div>

<!-- ![index-gif](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/mobile-nav.png) -->

*footer*

<div style="text-align: center"><img src="https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/mobile-footer.png" width="" /></div>

<!-- ![index-gif](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/mobile-footer.png) -->

## What's included?

Within the download archive you'll find the following directories and files. You'll see something like this,

```
devfolio/
├── Public/
│   └── index.html
│   └── articles.html
│   └── programingskills.html
│   └── projects.html
│   └── contactme.html
│   └── assets/
│       ├── bootstrap/
│       │   └── css
│       │   └── js
│       ├── css/
│       │   └── lightbox.min.css
│       │   └── styles.min.css
│       ├── fonts/
│       ├── img/
│       ├── js/
│       │   └── jquery.min.css
│       │   └── lightbox-plus-jquery.min.css
│       │   └── script.min.css
│       │   └── smart-forms.min.js
└──  screenshots
└── .DS_Store //firebase files
└── .firebaserc 
└── .gitignore
└── firebase.json

```

## Categories

- Projects
- Articles
- Skills
- Contact me

## Tools used
![Design Blocks](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/toolsused.png)

## Firebase hosting
Firebase hosting is a Google hosting service which provides impressively fast & free service.The following things are required for firebase Hosting
#### Google Account
For accessing firebase you need a firebase account. You can login to firebase using your google account.
#### Firebase-CLI
Before you can install the Firebase CLI, you will need to install Node.js on your machine.
Once you've installed NodeJs, you can install the Firebase CLI using npm (the Node Package Manager) by running the following command:
```
npm install -g firebase-tools
```

### Step 1:- Create a Firebase project
Go to firebase and sign in with your Google account.

![Design Blocks](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/firebase-newproject.png)

then create new project, enter your project name

<!-- ![Design Blocks](https://raw.githubusercontent.com/ishamsu/DevPortfolio/master/firebase-demo.png) -->

### Step 2:- Firebase Login
Now come back to the command line and go to your project folder (porthost is my project name)
```
cd porthost
```
First we have to login into firebase from command line. Type in the following command.
```
firebase login
```
It will take you to the sign-in page in the browser, once you’ve successfully logged in it will show you something like this

![Design Blocks](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/firebase-cli-successful.png)

### Step 3: Initialization
To initialize firebase project you have to enter the command
```
firebase init
```
Then you have to select Hosting feature and click enter

![Design Blocks](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/firebase-host.png)

Then it will ask you to select firebase project, select project which we created in step 1 (porthost in my case)

![Design Blocks](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/firebase-existingproject.png)

Then it will ask you enter the main folder in which all your website assets are present. (public folder in my case)

![Design Blocks](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/firebase-hostingsetup.png)

It will ask you whether your application is single page or not, for now enter **n**

It will try to override your index.html file, to avoid doing that enter **n**

![Design Blocks](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/firebase-hostsetup1.png)

### Step 4: Setup
If everything goes right you can check you website locally by running command
```
firebase serve
```
It will run you website locally on http://localhost:5000 by default.

![Design Blocks](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/firebase-serve.png)

### Step 5: Deployment
For deployment of your project you have to run command
```
firebase deploy
```
![Design Blocks](https://raw.githubusercontent.com/ishamsu/devfolio/master/screenshots/firebase-deploy.png)

Congratulations! your website is now live, you can check by going to url which is provided in the command line in my case it is https://portfol-3ccbb.firebaseapp.com (you can add your custom domain later)

## Copyright and license
Code and documentation copyright 2020 [Shamsu Musthafa](https://ishamsu.me/). Code released under the [MIT License](https://raw.githubusercontent.com/ishamsu/devfolio/master/LICENSE).

## Show your love*❤️*
- Follow me on [Github](https://github.com/ishamsu)
- Star the [Github Repository](https://github.com/ishamsu/devfolio)
- Open [issues](https://github.com/ishamsu/devfolio/issues/new) with suggestion of ideas