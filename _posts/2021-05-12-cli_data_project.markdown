---
layout: post
title:      "CLI DATA PROJECT"
date:       2021-05-12 14:56:04 -0400
permalink:  cli_data_project
---


The great thing about this project is that we had free range to build our program off on any topic. So of course my first inclination was to base it off of one of my hobbies and passion, "Comicbooks". A lifelong journey through the pages of superheroes before it was "cool" to like superheroes. Every week new comics are released from dozens of publishers, so this was the blueprint for my CLI project, one which would tell the user all of the new comics coming out this week and future releases!

I was able to find a comicbook API from api.shortboxed.com which is perfect for this poject. The great thing about APIs is they are more reliable than scarpping a website. If the owner of a website designs to change the page and settings, your scrapper may no longer be effective. APIs are not perfect in themselves, they have limitation into what the APIs overall functionality is, but typically over-time the information and functionality grows of an API vs being completely changed. 

What I liked bested about the shortboxed API was having access to current, future and previous releases. So I am able to allow the user to select different releases for comics. The difficult part, was orgianzing all the data! Running the API this is what you get: ![](https://imgur.com/a/3E5YPA9)
Dealing with embedded arrays and hashes inside hashes!
A lot of great information but no way a user would want to sort through all the jumbled information to find out the newest comicbook releases. I had to find a way to organize the information and make it easy to read. 

I figured the easiest way would be to organize by publisher. Most people know Marvel and DC Comics as the two biggest titans in the comicbook industry. So i figured it would be "easier" to sort out individual comics released by publisher. This could also introduce users to new publishers they may not have known or heard of. 

This leads my CLI into a "second level" of inquiry, first, the user selects "new release" vs "future release" vs "previous release". From there, the user selects the "publisher"! Great the plan is in place! Now, how do I itterate through all these Hashes and Arrays! This was the part of the project which took a lot of growning pains and blank stares at the screen. Being able to decipher each "Key" and "Value" for each hash. Also just accepting the fact that Ruby is smart enough to decipher through the API and match the "publisher" of each comic just based upon coding. Same with "Title", "Author", "Description" ect. It just knows!

Ultimately, after much trial and error, I was able to organize my Hash and Array data with this: ![](https://imgur.com/wLPR2hJ)
It was a challenge but rewarding in the end to have all the data, organized and understandable, all at my finger tips! Even I will be enjoying my own CLI program weekly to get list of the newest comicbook releases!
