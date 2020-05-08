---
layout: post
title:      "My Rails Project"
date:       2020-05-08 18:27:04 +0000
permalink:  my_rails_project
---


About a week before starting my rails project I started thinking of ideas for the application I wanted to build. I had thought of a “Renters Review” app. In this app, there would be two different types of users (Landlords and Tenants). I had to research on how to keep one user class but have two different types of users with different attributes/ relationships to other models. With the help of a friend from my cohort, we thought it would be best to make the class polymorphic. This means that there would be different variations of the user class. After about 3 days of doing this project, I decided it was best for me to put it on the back burner and try to finish it some other time. The polymorphic relationship was causing me to have a lot of trouble using OmniAuth and I didn’t want to risk falling behind and not having my project done in time!

After letting go of the Renters Review, I jumped right into my backup project, The IPA Reviewer.  This project idea was a lot less complex and met all the requirements the are suppose to be met. To my surprise, I found little complications in creating this project and had a really fun time doing. The associations were simple, a user has many IPAs through reviews and a IPA has many users through reviews. Reviews was my join table that also had a title and content attribute. I decided to add an Admin attribute with a default of false to add authorizations into the app. Only admins would be able to delete and edit IPAs and reviews. Regular users would only be able to edit reviews they have created. Although this application was more on the simpler side, I found that it solidified a majority of what was taught in the curriculum while giving me the opportunity to learn a few more little things as well.

Overall, my takeaways from the rails project was to always have an MVP backup idea if you plan trying something new. It was a lot of fun trying to get my first idea to work, and I'm sure with a little more tinkering I can get it up and running!


