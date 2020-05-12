---
layout: post
title:      "Ruby on Rails Project Mode"
date:       2020-05-12 22:07:34 +0000
permalink:  ruby_on_rails_project_mode
---

Using the Ruby on Rails framework, I created a web application for beer connoisseurs! DEAD is an acronym for "Drop Everything And Drink!" The app allows users to create an account, rate beers and add them to their profile. A user can add a beer name, it's brewery, style, ABV, write a description of the beer, and attach a photo. 

To begin, I generated a resource for my app - a handy shortcut provided by rails to set up my controllers, models, views, routes, and database table migrations. With these steps out of the way, I was able to dive right into coding for my models. I started with establishing my has_many, belongs_to, and has_many_through relationships, as well as some basic validations I knew I would need (i.e, has_secure_password - a validation for my user model).

From there, I took steps slowly, adding each piece of functionality at a time and testing as I go. This involved properly associating my controller actions to my views and establishing routes that a user would navigate to in order to display the desired information.

It took me about a week and a half to complete, starting off very organized and testing very frequently. As I filled the app with more information, I became disorganized, tested less; resulting in bugs in my code, and had to revert my project back to a prior github commit to solve the problem. After the revert, I took things slowly again, step by step. This project tested my coding knowledge, patience, and challenged me as a developer - I'm excited to continue learning the magic of Rails!
