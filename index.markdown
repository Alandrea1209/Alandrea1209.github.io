---
layout: page
title: Alan Lee
---

Hi, my name is Alan. I’m a Software Engineer in YongMing Technology Consulting from 2013. In this position, I have been developing Hemodialysis Information System for NTHU which is based on web form. Furthermore, I excuted some projects, such as developing enterprise website and social community application for intracompany (Android App).I'm also a Android developer freelancer.

I'm a Starter on GitHub. Currently, I spend some my free time developing some projects in Android and Java, some of which are open source and available on my GitHub account: [https://github.com/alandrea1209](https://github.com/alandrea1209)

You can also find my Android apps in Google Play:[https://play.google.com/store/apps/developer?id=Alandrea.dev](https://play.google.com/store/apps/developer?id=Alandrea.dev)

<iframe width="480" height="360" src="https://www.youtube.com/embed/WO82PoAczTc" frameborder="0"> </iframe>

<iframe src="https://appetize.io/embed/3yjbw6afvy68h06t5f6a2hatqm?device=nexus5&scale=75&autoplay=false&orientation=portrait&deviceColor=black" width="300px" height="597px" frameborder="0" scrolling="no"></iframe>

<!-- ## Heading Level 2

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% highlight scss %}
  .header {
    font-size: 100px;
  }
{% endhighlight %}

### Heading Level 3

> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. -->

<br>
<br>
<br>

# Recent articles

{% for post in site.posts limit:4 %}
   <div class="post-preview">
   <h3><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
   <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
   {{ post.content | split:'<!--break-->' | first }}
   {% if post.content contains '<!--break-->' %}
      <a href="{{ post.url }}">Read more</a>
   {% endif %}
   </div>
   <hr>
{% endfor %}
