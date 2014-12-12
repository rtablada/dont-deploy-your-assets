![Image](http://2.bp.blogspot.com/-vzgXgxkC3rw/UxokeRNYj1I/AAAAAAAACK0/SUFqTffmWEQ/s1600/wizard-behind-curtain1.jpg) <!-- .element: width="100%" -->



# Caching


# Local Caching


# HTTP Cache
## Cache-Control:"max-age=20" <!-- .element: class="fragment" data-fragment-index="2" -->
## Cache-Control:"no-cache" <!-- .element: class="fragment" data-fragment-index="3" -->


![What am I doing](http://weknowgifs.com/wp-content/uploads/2013/11/i-have-no-idea-what-im-doing-dog-gif.gif) <!-- .element: width="100%" -->


# Solution


# Fingerprinting

* app.js <!-- .element: class="fragment" data-fragment-index="2" -->
* app-0364f57fbff2fabbe941ed20c328ef1a.js <!-- .element: class="fragment" data-fragment-index="3" -->
* app-eb399bcaca686f8609137153307eecf1.js <!-- .element: class="fragment" data-fragment-index="4" -->


# How does this effect our strategies?


# Asset Pipeline
## Not really fingerprinting a single build <!-- .element: class="fragment" data-fragment-index="2" -->


# Git Deploy
## Lots of delete file & new file commits <!-- .element: class="fragment" data-fragment-index="2" -->


# All Strategies
## Keep the view template up to date with the latest build fingerprints <!-- .element: class="fragment" data-fragment-index="2" -->



# Web Server Load


![Load Balanced Servers](http://i.stack.imgur.com/m69Bq.png)



# Testing and CI


# Everything is tied to the server deployments


# Unnecessary Tests and Work


# Split Test Suites for Client and Server


# Would you tie a native app to your server?
