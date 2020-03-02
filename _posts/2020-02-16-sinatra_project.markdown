---
layout: post
title:      "Sinatra Project"
date:       2020-02-16 22:43:25 -0500
permalink:  sinatra_project
---


I have always gotten emotional whenever I saw those sarah mclachlan ASPCA commercials and when I read that one of the things the sinatra project would be good for was keeping track of things that are important to you, I thought to myself “Why not shelter owners and pets?”. People could login and see which shelters needed more space and needed to get rid of some animals before people went to the shelter!

Where to start?
	I had to know what I wanted my code to do, but it evolved as time went by. First i started by typing ”gem install corneal” then  “corneal new in-browser-sinatra '' and my file structure was generated for me.

File Structure
I had a Model View Controller structure where the majority of my code will fall inside of. People will interact with the views and we will use the model and controllers to build what needs to be built.

New Users?!
 Before I knew how to get the users to create a new account that would be remembered in the user database i had to create a new user using “rake console” to test if the program was only allowing existing users into the logged_in homepage. Once I saw that it worked I had to figure out a way to use the forms to create a new user that would be saved into the Users table.

Creating a new user!
	I used params to find the new user and isaved those params into a new instance of User which would then be saved into the database with their password_digest.

Problems
	There were several problems I had encountered during the creation of my application. I kept forgetting to have the controllers added into the config.ru folder and i wouldn’t be able to create new controllers without trouble shooting why they weren’t working (should’ve made a sticky note telling me to remember). My posts were being created without having a user.id to find them by. New posts would be allowed to have empty space. Creating a new account would allow you to use the same email as an existing user.

End
In the end I got my code to work and I am very proud of the work I did! I never would have thought that I could make a basic application like the sinatra project but here I am with a completed project. There were times I definitely wanted to quit but i had to keep on pushing forward if I wanted to succeed and succeed i did!

