---
layout: page
title: Home
tagline: abutcher@redhat.com
---
{% include JB/setup %}


## Contact
- AIM: [archnemesivii](aim:goim?screenname=archnemesivii)
- IRC: [freenode.net](irc://chat.freenode.net)
- Twitter: [akbutcher](http://twitter.com/#!/akbutcher)

## Keys
- OpenPGP: [56BBFF27](http://pgp.mit.edu:11371/pks/lookup?op=vindex&search=0x73D3A0DA56BBFF27)
- SSH: [abutcher@player](assets/content/authorized_keys)

## Code
- [github.com/abutcher](http://github.com/abutcher)

## WVU Loud
- [Launchpad](https://launchpad.net/~abutcher)

## Docs
- [Regular Expression Basics](http://peopleareducks.com/docs/regexp-basics/output/regular-expressions.html)
- [Setting up an OpenGL project using Apple Xcode](http://peopleareducks.com/docs/opengl-in-xcode/)
- [Your First Debian Package](http://loud.wvuopensource.org/?page_id=41)

## Club Stuff
- [WVU ACM](http://wvu.acm.org)
- [LOUD Platform Project](http://loud.wvuopensource.org)

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
