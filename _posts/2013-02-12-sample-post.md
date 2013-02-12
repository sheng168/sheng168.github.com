---
layout: post
title: Open Source Blog
---

{{ page.title }}
================

I recently discovered http://parse.com/ and started to use it for my mobile developments.  Up until this point, I've been using Google AppEngine, but parse.com is better.

* you can still get started for free
* the documentation is great and contains plenty for examples
* the API are generally well designed

{% highlight java linenos %}

// save
ParseObject gameScore = new ParseObject("GameScore");
gameScore.put("score", 1337);
gameScore.put("playerName", "Sean Plott");
gameScore.put("cheatMode", false);
gameScore.saveInBackground();

{% endhighlight %}
