---
layout: post
title: "COSI News - August 8: Mirror History"
categories: news
---

Morning,

As many of you probably know, Mirror has been one of our longest running
services, and as of today, we can be fairly certain that it now has existed
for about 14 years with the earliest knowledge of it existing as of October
2002. As part of the COSI History project, I have been looking through the
archives of different pages including past MP* presentations, and archived
websites on the wayback machine. With this, let's take a journey back all the
way to the beginning of Mirror and see it's progress over the years.

We start in December 2001. In [this archive](https://web.archive.org/web/20011205100928/http://cosi.clarkson.edu/) of cosi.clarkson.edu, there is a
section on the right titled Distributions which lists a few distros as well
as plans of wanting to make a Clarkson University Linux distro. Below that
it states that COSI would like to pursue mirroring other distributions on the
same server as the website. This is the first time that we have evidence of
people wanting to have a Mirror in COSI.

Jump forward to February 2003 with this [archive](https://web.archive.org/web/20030213164427/http://mirror.clarkson.edu/) on
mirror.clarkson.edu. At this time, we see that there is now a set of machines
actually running just for mirroring. According to the site, the storage was
donated by Winchester Systems while the website was running on a SUN Ultra
60 workstaion which was loaned out by Mathematics Prof. Scott Fulton.
Looking through the site, we were hosting a decent amount of versions of Linux,
BSD, and even the kernel (v2.6).

Jump ahead to 2009, and the labs have looked at getting a new server for Mirror. On
[Mathew McCarrell's MP* Page](http://web2.clarkson.edu/projects/cosi/sp2009/students/mccarrms/), it
was recorded that the server had been obtained and he and Roger Ignazio had
worked on trying to install CentOS onto the machine, but ran into some issues.
They then tried going over to Open Solaris so they could use ZFS as the filesystem
for Mirror (Which actually is the filesystem being used on the current Mirror).
After a bit of tweaking they got CentOS working on Mirror and begun syncing again.
Through the history, we can consider this the 2nd iteration of Mirror.

Progressing into the 2010s and there were minor software tweaks and changes
where we eventually switched over to Debian around 2013. And this brings us
up to the fairly modern day. The end of Mirror 2 had about 8TB of usuable
storage, and we were filling it up to almost max capacity. The drives were
aging as well, and around Spring 2015, we begun plans on the 3rd iteration of
Mirror. After successfully fundraising for the new mirror in Fall 2015, we
purchased the hardware for the machine in December 2015. Through spring 2016,
we set up the machine and retired the 2nd iteration of Mirror (although it has
been now repurposed for [The-Internet](http://the-internet.cslabs.clarkson.edu/)).
Now, Mirror has ~30TB of usuable space in the ZFS pool, and as of this evening,
we're only using ~13TB so far. Over the summer, Bobby and I put up a schedule for
when distros and other projects are synced down which can be found on this docs page.

As servers come and go, there has always been one server for almost the entirety
of COSI's existence that has been used as our Mirror. This journey is only a
small fraction of the upcoming COSI website, COSI History, where I am going to
try to document as many historical topics of the labs through the 15 years we've
been around for.

Stay tuned,<br>
Benjamin Lannon