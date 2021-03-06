---
layout: post
title:  "Nodejs - Unsplash Crawler"
date:  2015-12-02 16:36:00 +0700
category: nodejs
tags: nodejs, crawler
---

# unsplash-crawler

A simple script by Node.js to crawl all images from unsplash.com. Dump it to mongodb database.

Github: [https://github.com/duyetdev/unsplash-crawler](https://github.com/duyetdev/unsplash-crawler)

# Install and use

Require Nodejs, Npm, MongoDb

1 - Clone the script 
{% highlight bash %}
git clone https://github.com/duyetdev/unsplash-crawler && cd unsplash-crawler
{% endhighlight %}

2 - Install node.js packages
{% highlight bash %}
npm install
{% endhighlight %}

3 - Config the crawler
Open the *config.js* file and custom your config.
{% highlight bash %}
nano config.js # Open the config.js file 
{% endhighlight %}

<img src="http://i.imgur.com/b9jZtYi.png" />

4 - Let's do it!
{% highlight bash %}
node index.js
{% endhighlight %}

<img src="http://i.imgur.com/R3vX2D3.png" />


# How to contribute

1. Fork the project on Github
2. Create a topic branch for your changes
3. Ensure that you provide documentation and test coverage for your changes (patches won’t be accepted without)
4. Create a pull request on Github (these are also a great place to start a conversation around a patch as early as possible)

# License
MIT License

Copyright (c) 2015 Van-Duyet Le

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and 
