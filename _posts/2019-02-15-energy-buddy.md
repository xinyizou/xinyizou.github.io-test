---
layout: post
title:  Using K-Means Clustering for Renewable Energy
date:   2019-02-15 18:07:19
categories: [project]
comments: false
---

![The landing page for EnergyBuddy]({{ "/img/energybuddy1.png" | absolute_url }})
<center>Figure 1: The landing page for EnergyBuddy</center>

Me and my team members created EnergyBuddy for ConUHacks, a hackathon in Montreal, over the course of 24 hours. It’s a web application that predicts whether solar panels or wind turbines are a more suitable form of energy for a given user-entered city. It determines this via a k-means clustering  machine learning model I built based off of each city’s climate and geographic data. The application also outputs the main factors involved in determining the result for the chosen city (given as an average of the city’s data over the course of a year).

![The results pop-up with all relevant factors after the city is selected]({{ "/img/energybuddy2.png" | absolute_url }})
<center>Figure 2: The results pop-up with all relevant factors after the city is selected</center>

The objective was for the user, who could be an environment-conscious individual installing an energy source on their property, a business, or even a policy-maker, to have a clear understanding of which renewable energy source they should be using for their city and why. 

The kind of problem solved was an environmental one. On a more technical level, the project was solving a clustering analysis problem. From the start, we knew we wanted to develop a solution for sustainability and renewable energy issues. After doing some research on what kind of data we could get out hands on online, we came up with our idea. 

![A view of our k-means clustering process, with the points 
representing the cities being separated into the two groups.]({{ "/img/energybuddy4.png" | absolute_url }})
<center>Figure 3: A view of our k-means clustering process, with the points representing the cities being separated into the two groups</center>
