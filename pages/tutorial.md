---
layout: post
title: Tutorial
permalink: /tutorial
---
In 'Tutorial' we will show how this web site being built, you can build web site by yourself. **Preparation** is for common steps, after common steps, go on to build the web site.

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

This is my [advice](/blog/domainname)

#### Markdown File

You can search internet for 'markdown cheatsheet', follow the format the cheatsheet show you.

#### How To Change Gmail Password

Go click Google web account avitar icon on top right of web browser,click `Manage Google Account`,then `Google Account UI` appeared, on left column, click `Security` ,then sroll down to `Password` ,enter original password and the password you want to change.

### To build the site with [Jekyll](/tutorial/jekyll)
