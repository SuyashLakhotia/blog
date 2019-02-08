---
layout: page
title: Projects
permalink: /projects/
---

- **[Machine Learning Research](#machine-learning-research)**
    - [Deep Learning for Text Categorization](#deep-learning-for-text-categorization)
    - [Rotten Tomatoes Movie Reviews Classifier](#rotten-tomatoes-movie-reviews-classifier)
- **[Applied Machine Learning](#applied-machine-learning)**
    - [CommandPlus](#commandplus)
    - [Rossmann Store Sales](#rossmann-store-sales)
    - [CodeBot](#codebot)
- **[Web Development](#web-development)**
    - [TripBuddy.SG](#tripbuddysg)
    - [BootstrapCards](#bootstrapcards)
    - [InstaFeast](#instafeast)
- **[Android Development](#android-development)**
    - [When We Meet Again](#when-we-meet-again)
    - [WWMAPulse](#wwmapulse)
    - [WhyBills](#whybills)

### Machine Learning Research

##### Deep Learning for Text Categorization

[GitHub Repo](https://github.com/SuyashLakhotia/TextCategorization) &nbsp;\|&nbsp; [Research Paper](https://ieeexplore.ieee.org/abstract/document/8590017) &nbsp;\|&nbsp; [Project Report]({{ site.baseurl }}/files/Final%20Year%20Project%20Report.pdf) &nbsp;\|&nbsp; September 2017 - May 2018

My undergraduate thesis on deep learning for text categorization explored the recently enhanced deep learning techniques of convolutional neural networks and their fusion with graph analysis (i.e. graph convolutional neural networks) in the field of text categorization and compared their performance to established baseline models and simpler multilayer perceptrons. We showed through experiments on three major text classification datasets (Rotten Tomatoes Sentence Polarity, 20 Newsgroups and Reuters Corpus Volume 1) that graph convolutional neural networks can naturally work in the space of words represented as a graph and perform with greater or similar test accuracy when compared to standard convolutional neural networks and simpler baseline models.

<small>**Research Areas:** <code>Text Classification</code> <code>Neural Networks</code> <code>CNNs</code> <code>Graph CNNs</code></small>

<small>**Tech Stack:** <code>TensorFlow</code> <code>scikit-learn</code> <code>NumPy</code></small>

##### Rotten Tomatoes Movie Reviews Classifier

[GitHub Repo](https://github.com/SuyashLakhotia/RottenTomatoesCNN) &nbsp;\|&nbsp; [Blog Post]({{ site.baseurl }}{% post_url 2018-01-14-movie-reviews-classifier %}) &nbsp;\|&nbsp; September 2017 - December 2017

This project compared several machine learning techniques for classifying movie reviews from Rotten Tomatoes and served as the initial stage of my undergraduate thesis. You can read more about this project and its results in my [blog post]({{ site.baseurl }}{% post_url 2018-01-14-movie-reviews-classifier %}).

<small>**Tech Stack:** <code>TensorFlow</code> <code>scikit-learn</code> <code>NumPy</code></small>

### Applied Machine Learning

##### Context News Bot

[GitHub Repo](https://github.com/SuyashLakhotia/ContextNewsBot) &nbsp;\|&nbsp; [Blog Post]({{ site.baseurl }}{% post_url 2018-01-30-context-news-bot %}) &nbsp;\|&nbsp; [DevPost](https://devpost.com/software/contextnewsbot) &nbsp;\|&nbsp; NUS Hack&Roll 2018 &nbsp;\|&nbsp; January 2018

'Context News Bot' is a Chrome extension that attaches itself to one's Twitter timeline and aims to provide more context to tweets. It does this by displaying relevant news articles and Wikipedia entries based on a tweet's content in an attempt to give the user a more rounded perspective and an easy-to-use tool for fact-checking. The client-side Chrome extension is written in JavaScript while the server is built on top of Flask in Python. The server-side natural language pipeline makes use of the Google Cloud Natural Language API combined with our custom heuristics. The project won a Top 8 prize and Most Socially Useful Hack at NUS Hack&Roll 2018.

<small>**Tech Stack:** <code>Flask</code> <code>Google Cloud Natural Language API</code> <code>Twitter API</code> <code>News API</code> <code>Chrome Extension</code></small>

##### CommandPlus

[GitHub Repo](https://github.com/SuyashLakhotia/CommandPlus) &nbsp;\|&nbsp; [DevPost](https://devpost.com/software/commandplus-k70x1m) &nbsp;\|&nbsp; NUS Hack&Roll 2017 &nbsp;\|&nbsp; January 2017

'CommandPlus' is a Chrome extension that provides hand gesture based control of one's browser. It does this by interacting with the user's webcam and sending video frames from the live feed to a Python server running OpenCV for gesture detection. If one of the predefined gestures is detected, it triggers the respective action in the browser (e.g. scroll up or zoom in). The extension is aimed at helping individuals who are limited in their movement or fine motor skills and won the People's Choice Award at NUS Hack&Roll 2017.

<small>**Tech Stack:** <code>OpenCV</code> <code>Chrome Extension</code></small>

##### Rossmann Store Sales

[GitHub Repo](https://github.com/SuyashLakhotia/RossmannStoreSales) &nbsp;\|&nbsp; Kaggle Competition / Course Assignment &nbsp;\|&nbsp; April 2017

Rossmann Store Sales was a Kaggle competition to predict the daily sales for a chain of drug stores in Germany based on features like the date, store type, distance to the nearest competitor etc. My team and I solved the challenge by applying feature engineering and implementing various machine learning models for the problem, including regression models from scikit-learn and boosted decision trees from XGBoost. Our best model ranked 414<sup>th</sup> out of 3,303 submissions on Kaggle's private leaderboard. This project was done as part of an introductory course to machine learning at NTU.

<small>**Tech Stack:** <code>scikit-learn</code> <code>XGBoost</code> <code>pandas</code></small>

##### CodeBot

[GitHub Repo](https://github.com/SuyashLakhotia/CodeBot) &nbsp;\|&nbsp; Facebook Singapore Hackathon 2016 &nbsp;\|&nbsp; September 2016

'CodeBot' is a chatbot that helps beginners learn how to code. To make the otherwise daunting task of learning how to code for the first time easier, CodeBot incorporates witty replies, GIFs & human-friendly error messages to create an incredibly fun experience for a complete novice. Currently, it goes through a few elementary exercises in Python while answering user questions using basic NLP. The back-end is built on top of Node.js, MongoDB & API.AI (now DialogFlow) while the front-end is written in vanilla HTML, CSS & JavaScript.

<small>**Tech Stack:** <code>HTML5 + CSS3 + JS</code> <code>Bootstrap 3</code> <code>Node.js</code> <code>Dialogflow</code> <code>MongoDB</code></small>

### Web Development

##### TripBuddy.SG

[Static Demo](http://tripbuddysg.github.io/TripBuddySG-FrontEnd/) &nbsp;\|&nbsp; [GitHub Org](https://github.com/TripBuddySG) &nbsp;\|&nbsp; Company &nbsp;\|&nbsp; September 2015 - September 2016

'TripBuddy.SG' is an online platform that aims to bridge the gap between international students & local students in tertiary institutes in an attempt to promote cultural exchange. It does this by providing a space where local students can host short trips to authentic local destinations for international students. The working beta of the online platform was built using Django, PostgreSQL, Bootstrap, jQuery & various social media APIs and was deployed on a DigitalOcean droplet.

<small>**Tech Stack:** <code>HTML5 + CSS3 + JS</code> <code>jQuery</code> <code>Bootstrap 3</code> <code>Django</code> <code>Social Media APIs</code> <code>PostgreSQL</code></small>

##### InstaFeast

[GitHub Repo](https://github.com/SuyashLakhotia/InstaFeast) &nbsp;\|&nbsp; [DevPost](https://devpost.com/software/instafeast) &nbsp;\|&nbsp; NUS Hack&Roll 2016 &nbsp;\|&nbsp; January 2016

'InstaFeast' is a simple web application that allows users to check the top Instagram posts of food & beverages at their desired location. Using the Google Maps API, Facebook Graph API, Instagram API & an external face detection API, the app filters through recent Instagram posts from the user-defined location and returns the top posts of food & drinks. The back-end is built on top of Django while the front-end is written in vanilla HTML, CSS & JavaScript with Bootstrap.

<small>**Tech Stack:** <code>HTML5 + CSS3 + JS</code> <code>jQuery</code> <code>Bootstrap 3</code> <code>Django</code> <code>Google Maps API</code> <code>Social Media APIs</code></small>

##### BootstrapCards

[Demo](http://suyashlakhotia.com/BootstrapCards/) &nbsp;\|&nbsp; [GitHub Repo](https://github.com/SuyashLakhotia/BootstrapCards) &nbsp;\|&nbsp; Bootstrap Template &nbsp;\|&nbsp; May 2015 - Present

'BootstrapCards' is a Boostrap 3 template that I had initially created for my (old) personal website. It implements card-based web design and consists of templates that can be used for one-pagers as well as multi-page blogs. A demo of the template can be found [here](http://suyashlakhotia.com/BootstrapCards/).

<small>**Tech Stack:** <code>HTML5 + CSS3 + JS</code> <code>jQuery</code> <code>Bootstrap 3</code></small>

### Android Development

##### When We Meet Again

[DevPost](http://devpost.com/software/when-we-meet-again) &nbsp;\|&nbsp; NUS Hack&Roll 2015 &nbsp;\|&nbsp; January 2015

'When We Meet Again' is an Android application that uses the relative distance between users, determined using the phone's Bluetooth, to trigger a reminder/push notification. This allows users to set reminders that trigger when they are near a particular person. My team and I built a working prototype of the app during NUS Hack&Roll 2015, where it fetched us the Best Freshmen Award. It was also featured & staff-picked on [DevPost](http://devpost.com/software/when-we-meet-again).

<small>**Tech Stack:** <code>Android</code> <code>Android Bluetooth APIs</code></small>

##### WWMAPulse

[GitHub Repo](https://github.com/SuyashLakhotia/WWMAPulse) &nbsp;\|&nbsp; Hackathon@SG 2015 &nbsp;\|&nbsp; July 2015

'WWMAPulse' is the second iteration of 'When We Meet Again' that my team and I built during Hackathon@SG 2015. WWMAPulse is also an Android app that triggers a push notification based on the proximity of users, however, instead of using Bluetooth to determine proximity, it uses *Pulse*, a proprietary feature of the Razer Nabu X (wearable by Razer).

<small>**Tech Stack:** <code>Android</code> <code>Razer Nabu SDK</code></small>

##### WhyBills

[GitHub Repo](https://github.com/SuyashLakhotia/WhyBills) &nbsp;\|&nbsp; Facebook Singapore Hackathon 2015 &nbsp;\|&nbsp; February 2015

'WhyBills' is a system that aims to eliminate the need for printed bills/receipts at retail outlets. The POS Java app combined with the consumer-side Android app allows the entire bill to be transferred to the consumer's phone via a simple QR Code. In addition to being a convenient way for the consumer to store his/her bills, the Android app also acts as an effective expense tracker.

<small>**Tech Stack:** <code>Android</code> <code>Java</code> <code>JFrame</code></small>
