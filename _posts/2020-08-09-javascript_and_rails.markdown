---
layout: post
title:      "JavaScript And Rails"
date:       2020-08-09 15:26:04 -0400
permalink:  javascript_and_rails
---


For my JavaScript project I designed a single page web application where users can create states and associate them with National Parks. My JS code communicates with a Ruby on Rails backend program to persist data to my database. 

Users can create a state with a name and a state flower through a form, and submit that form to create a new state instance. Once a state is created, users can add National Parks that are located in that state - this form allows a user to end the park name and it's location within the state.

You can edit a state name and flower, as well as delete a state entirely. This will delete any associated parks with the state as well. 

I utilized OO JavaScript, creating classes for each object and within those classes creating methods and arrow functions that bind the this keyword to my class object instances. I also created Adapters to handle my fetch calls that grab information from my Rails backend and persist them to my frontend for users.

Overall, I had a really hard time with this project and understanding concepts like *this* and binding. I'm excited to move forward with the program and experience the power of the React framework.
