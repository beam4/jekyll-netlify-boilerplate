---
layout: page
title: Tutorial
permalink: /tutorial
---

## Tutorials

TOC

### Preparation

We will use a sample church name: Good News Church Nepal,suppose the format of email address is goodnewschurchnp@gmail.com, website url suppose to be:goodnewschurchnp.netlify.app  [good news church nepal](goodnewschurchnp.netlify.app)

First collect the information of the church, such as the name of the church, the name of the Pastor..., then sign up to github.com and netlify.com, there suppose to be many tutorials on internet, finally, go to netlify.com to build the website, as planned, we will build 3 or 4 types of templates, according to static site generator name, first we will use Jekyll, then 11ty,then Next,js, then maybe Jigsaw.

#### Step 1 Collect informations

Church name, Pastor's name, church address, Pastor's phone number, whatever may need for church.

An email address dedicated for website use only, it is better an gmail email, we will use it to register for Google Analytics, github.com and netlify.com later. 

#### Step 2 Sign up

Sign up for github.com and netlify.com, there are many online howto, the purpose to sign up github.com and netlify.com is to make the template editable in github.com and host in netlify.com

Register in Google Analytics, sign up an account for Google Analytics in https://analynics.google.com/

About Google Analytics, there is a tutorial you can refer to , also you can search internet. https://www.e2msolutions.com/blog/setup-google-analytics-4/

#### Print screen software and Oline photo editor

I am using Respberry Pi Plus3 B Single board computer as desktop, I installed Respberry Pi Desktop,it is actually Debian Linux, the software to capture print screen I use is `scrot`, the `scrot` installed by defult, you can check it installed or not by 

$ apt list --installed

You can search internet also.Everytime you press `Print Screen` botton on Keyboard, in `Home` folder, automaticly save a sreenshot in a format YearMounthDate.png,You can edit with online photo editor next.
 
And use online photo editor with https://fotoflexer.com/editor/ to make the tutorial.

#### Domain Name

If you want to replace your net address from yourchurchnamenp.netlify.app to yourchurchnamenp.org to make it more easy remember and easy spread, that is where the Domain Name works. Domain Name is actually a short net address converter.

In our case, to replace yourchurchnamenp.netlify.com to yourchurchnamenp.org cost about 10 USD per year. There are many companies doing this business, you can search internet to find one. 

![jekyll](/tutorial/img/homepage.png)

### To build the site with Jekyll Statuc Site Generator

- Jekyll template

Before we start to build website, let us log in github.com to make system remember github.com login, then folk the template in github.com, `folk` means `copy`, click on `folk` button on top of home page, to make the repository your own and editable.

![folk button](/tutorial/img/folkbutton.png) 

#### To folk the github Repository

This site use (jekyll-netlify-boilerplate) Github Repository at (https://github.com/danurbanowicz/jekyll-netlify-boilerplate),though there are some changes from original, the best way to copy and edit is to folk the (good news church Nepal), the github Repository at: (https://github.com/goodnewschurchnp/jekyll-netlify-boilerplate).
 
#### Log in netlify.com to build the site

To log in netlify.com at https://www.netlify.com

`add new site` > `import an existing project` > `github.com` > `target github Repository` > `Deploy site`

#### Change site name

You can change site name to yourchurchnamenp.netlify.app

`site settings` > `change site name` under `Site details` --> `Site information` 

#### site name

'site name' is in _config.yml,under site github repository's root, you will find "title: xxxxxx"

#### navigation

'navigation' you can edit data > navigation, click the 'edit' icon to edit.

#### hero image

'hero image' is in _includes, "hero.html", in site root > assert folder > style.css, "background-image:  url(hero1.jpeg);". If you have question, we can assist. The `hero1.jpeg` is our file name, you can replace with your image. 

#### Facebook link

You can make your Facebook account or your Facebook group here, all pictures about church go there.

#### Home page

Home page is in site root > pages > index.md, this is a markdown file.

#### Contact

Contact page is in site root > pages > contact.md, this is a markdown file.

#### Regarding Markdown File

You can search internet for 'markdown cheatsheet', follow the format the cheatsheet show you.
