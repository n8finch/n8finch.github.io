---
layout: post
title:  "Monday Checkin: Concat and minify using Grunt"
date:   2015-09-14 19:06:21
categories: checkin, grunt, development
---

##Main GTD for the Day##

- Concat and minify GTS.com files on local server using Grunt.

####Did I do this?####

- Yes!

###What Else Did I Accomplish?###

- Got a new contract for a web application and site build. Due in November
- Read through several chapters of WordPress Professional Design and Development
- Got the GTS.com site on a CDN, instantly speeding up the site.

Here are the Grunt tasks I'm currently using for the GTS.com site:

{% highlight javascript %}
grunt.loadNpmTasks('grunt-contrib-concat');
grunt.loadNpmTasks('grunt-contrib-uglify');
grunt.loadNpmTasks('grunt-contrib-cssmin');
{% endhighlight %}

===

You can find my portfolio [here][FPSportfolio].


[FPSportfolio]: http://finchproservices.com/portfolio
