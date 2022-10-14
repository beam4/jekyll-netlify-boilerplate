---
layout: post
title: Tutorial
permalink: /tutorial
---


### Preparation

We will use a sample church name: Good News Church Nepal,suppose the format of email address is goodnewschurchnp@gmail.com, website url suppose to be:goodnewschurchnp.netlify.app

First collect the information of the church, such as the name of the church, the name of the Pastor..., then sign up to github.com and netlify.com, there suppose to be many tutorials on internet, finally, go to netlify.com to build the website, as planned, we will build 3 or 4 types of templates, according to static site generator name, first we will use Jekyll, then 11ty,then Next,js, then maybe Jigsaw.

#### Step 1 Register a gmail account 

Under format for example, church name: Good News Church Nepal, email like goodnewschurchnp@gmail.com, not use your private email,may need someone other than the Pastor to cooperate, the church site update not often, do not need check daily.

#### Step 2 Collect informations

Church name, Pastor's name, church address, Pastor's phone number, whatever may need for church.

An email address dedicated for website use only, it is better an gmail email, we will use it to register for Google Analytics, github.com and netlify.com later. 

#### Step 3 Sign up github.com and netlify.com accounts

Sign up for github.com and netlify.com, there are many online howto, the purpose to sign up github.com and netlify.com is to make the template editable in github.com and host in netlify.com

#### Step 4 Sigh up and login Google Analytics

Register in Google Analytics, sign up an account for Google Analytics in https://analytics.google.com ,there is a tutorial you can refer to ,  https://www.e2msolutions.com/blog/setup-google-analytics-4/ ,also you can search internet. [There are detail](/tutorial/google-analytics)

#### Print screen software and Online photo editor

I am using Respberry Pi Plus3 B Single board computer as desktop, I installed Respberry Pi Desktop,it is actually Debian Linux.

##### The Screen Print 

The software to capture print screen I use is `scrot`, the `scrot` installed by defult, Everytime you click 'Print Screen' button on upper right of the keyboard, there save a current screen in 'Home' folder with a format yearmounthdate.png.

you can check it installed or not by 

$ apt list --installed

##### Online Photo Editor
 
And use online photo editor with https://fotoflexer.com/editor/ .

#### Domain Name

If you want to replace your net address from yourchurchnamenp.netlify.app to yourchurchnamenp.org to make it more easy remember and easy spread, that is where the Domain Name works. Domain Name is actually a short net address converter.

In our case, to replace yourchurchnamenp.netlify.com to yourchurchnamenp.org cost about 10 USD per year. There are many companies doing this business, you can search internet to find one. 

This is my [advice](https://buildchurchsite.netlify.app/blog/domainname)

### To build the site with Jekyll Static Site Generator

![jekyll](/assets/img/homepage.png)

#### Jekyll template

Before we start to build website, let us log in github.com to make system remember github.com login, then folk the template in github.com, `folk` means `copy`, click on `folk` button on top of home page, to make the repository your own and editable.

![folk button](/tutorial/img/folkbutton.png) 

#### To folk the github Repository

This site use (jekyll-netlify-boilerplate) Github Repository at (https://github.com/danurbanowicz/jekyll-netlify-boilerplate), though there are some changes from original, the best way to copy and edit is to folk the [good news church Nepal](https://github.com/goodnewschurchnp/jekyll-netlify-boilerplate), the github Repository at: **(https://github.com/goodnewschurchnp/jekyll-netlify-boilerplate)**.
 
#### Log in netlify.com to build the site

To log in netlify.com at https://www.netlify.com

`Add new site` `>` `Import an existing project` > `github.com` > `target github Repository` > `Deploy site`

#### Change site name

You can change site name to yourchurchnamenp.netlify.app

`site settings` > `change site name` under `Site details` --> `Site information` 

#### site name

'site name' is in _config.yml,under site github repository's root, you will find "title: xxxxxx"

#### navigation

'navigation' you can edit `_data` `>` `navigation.yml`, click the 'edit' icon to edit.

#### hero image

'hero image' is in `_includes` > `"hero.html"`, another in site root > `Assert` `>` `style.css`, "background-image:  url(hero1.jpeg);". If you have question, we can assist. The `hero1.jpeg` is our file name, you can replace with your image. 

#### Facebook link

You can make your Facebook account or your Facebook group, all pictures about church go there.

#### Home page

Home page is in site root > pages > index.md, this is a markdown file.

#### Contact

Contact page is in site root > pages > contact.md, this is a markdown file.

#### Markdown File

You can search internet for 'markdown cheatsheet', follow the format the cheatsheet show you.
