---
layout: post
title:      "Project One: Gem Portfolio Project"
date:       2020-03-06 15:41:12 +0000
permalink:  project_one_gem_portfolio_project
---


Leading up to my first project, I was feeling anxious, nervous and excited at the same time. It’s crazy to this that a month ago I had no coding background, and now I'm tasked with creating a project based off the knowledge I've learned in the past month. I felt that I could do it and was excited to put my knowledge to the test. 

I decided to scrape the Formula Drift schedule webpage and give the user the option to select which event they would like to learn more info on. I then created my plan on how I wanted the structure of my program to be based on a user’s point of view. I watched Avi’s CLI walkthrough and liked how he didn’t focus on every issue that he thought he would need to solve, but instead one issue at a time starting from the what he wanted his program to do. Once I decided on how I wanted the CLI to work, I then built the CLI with fake information. This allowed me to establish a functional CLI so I could then worry about the logic the rest of the program. From there I started inspecting the web page to get an understanding of how I would need to go about retrieving the information that I needed. After poking around a bit, I finally discovered the correct css selector that captured the entire table of event information. This was great because it allowed me to only have to scrape the website once for all the attributes of every event. After that I established my scraper class and created a class method that scraped the website and organized the scrape information into a hash of event with attribute keys pointing to the event specific values. I stored this hash in an array to then iterate through and create new instance of the event class for each event with the appropriate attributes. I found that to be difficult, and constantly wonder if there is a simpler way to do it. When an instance of the event class is instantiated, each instance is pushed into the class variable ‘all’ which stores every instance of the event class. I used that to iterate through for the information I need in certain parts of the CLI. 

Overall I found the project to be challenging and fun at the same time. I particularly had trouble with the actual logic of certain things and constantly found myself not liking my original code and searching for a “dryer” way. However I did really enjoy doing it and find it really satisfying that I completed it. It definitely gave me a confidence boost that I needed! 


	

	

