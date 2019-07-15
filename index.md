---
layout: home
author: "INDEX Author"
---
<hr>
# [Tutorial](../tutorial/) -- [About](../about/) -- [Test Page](../test/) -- [Test 404](xyzzy) -- [GitHub](https://github.com/webjekyll/WebWeb03)
<hr>
<h1>To Whom It May Concern</h1>
I am just following 
[Mike Dane](https://www.mikedane.com/)'s
[tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB).
It is a really really great tutorial! 
<ul>
{% for post in site.posts %}
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
My two cents tips would be:
<ol><li>  Do not give up! What is not understood might be explained later.
</li><li> Do not mess with GitHub Page until the end of this tutorial.
</li><li> This is a Jekyll tutorial. 
          It will not cover in details the problems of installing 
          Jekyll, Gems, Bundler, mismatched Versions, and sometimes... 
          antivirus interference!
</li><li> Neither will it cover the problems of minima theme on GitHub Page.
</li></ol>
Last, it is a <b>free</b> tutorial using <b>free</b> software. 
<b>BUT</b>, you will need a lot of <b>FREE</b> time! 
<br>
Thank you 
**[Mike](https://www.mikedane.com/)**,
may Jekyll be with you!
<br><br>
<h2>{{ site.author }}</h2>
<br>
<hr>

