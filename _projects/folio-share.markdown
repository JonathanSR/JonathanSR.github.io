---
layout: post
title: Folio Share
categories: ruby rails postgresql twilio rspec
---
Folio Share is a Dropbox clone that mimics its file uploading downloading and sharing functionality. This gives the user the ability to register for an account, upload its own files, download its files and folders and share them with other registered users. This application also has a guest mode that allows unregristered users the ability to view files and folders that have been made public. There is an admin mode that gives it permissions to activate/deactivate users and delete content. 
<br>
This was a four team project broken up into multiple 3day sprints over a two week period. My main focus was the creation of the admin role, permissions for the admin, registered users and guests. Also I implemented a two step factor authentication for resetting ones forgotten password using the Twilio Service.
<br>
This app was built using the following: Ruby, HTML, CSS, Materialize, SASS, Rspec, Capybara, PostgreSQL, Twilio.

<br>
<br>
![folio-image](images/folio-image.png){:class="img-responsive"}
<br>
Check out the live site <a href="https://folio-share.herokuapp.com/">here</a>.
<br>
Source code <a href="https://github.com/JonathanSR/folio-share">here</a>.
<br>