---
layout: post.html
title: "Networks – Extended"
tags: [network]
url: "/~drafts/networks/extended/"
---

Networks used in real life, and where to go from here.

### In action

Some popular companies and applications that use Twisted:

* [ITA Software](http://en.wikipedia.org/wiki/ITA_Software) developed an airline reservation system for Air Canada that uses Twisted extensively
* [Twilio](www.twilio.com) – cloud telephony provider
* Apple’s [Calendar Server](http://trac.calendarserver.org/)
* [LucasFilm](http://twistedmatrix.com/trac/wiki/SuccessStories#Lucasfilm) – film and TV production company
* [Launchpad](http://twistedmatrix.com/trac/wiki/SuccessStories#Launchpad) – application that allows developers to develop and maintain software
* [HipChat](http://twistedmatrix.com/trac/wiki/SuccessStories#HipChat) – hosted group chat that uses [XMPP](http://en.wikipedia.org/wiki/XMPP) (Jabber)
* [Justin.tv](http://twistedmatrix.com/trac/wiki/SuccessStories#Justin.tv) – live video streaming
* [Tweetdeck](http://twistedmatrix.com/trac/wiki/SuccessStories#TweetDeck) – Twitter client for the browser
* [NASA](http://twistedmatrix.com/trac/wiki/SuccessStories#NASA)
* [BuildBot](http://en.wikipedia.org/wiki/BuildBot) – a continuous integration system

More success stories are on Twisted’s [website](http://twistedmatrix.com/trac/wiki/SuccessStories).

### Where to go from here

Twisted’s documentation contains a number of howtos, including [web servers and clients](http://twistedmatrix.com/documents/current/web/howto/), [SMTP (mail) clients](http://twistedmatrix.com/documents/current/mail/tutorial/smtpclient/smtpclient.html), [DNS servers](http://twistedmatrix.com/documents/current/names/howto/names.html), and [SSH servers](http://twistedmatrix.com/documents/current/conch/howto/conch_client.html).  Complete list of tutorials and examples are listed [here](http://twistedmatrix.com/documents/current/).

There are a number of excellent [tutorials](http://krondo.com/?page_id=1327) written by Dave Peticolas that don’t assume existing knowledge about networking or concurrency.

Gordon McMillan wrote a [socket programming](http://docs.python.org/2/howto/sockets.html) tutorial that makes use of Python’s socket library instead of Twisted.

##### Challenge yourself

* Serve static content with a Twisted server.  A how-to [here](http://jcalderone.livejournal.com/47954.html).
* Code a simple HTTP Proxy server using Twisted. An example [here](http://wiki.python.org/moin/Twisted-Examples).
* Write an RSS feed aggregator with Python/Twisted.  An example [here](http://code.activestate.com/recipes/277099-rss-aggregator-with-twisted/).

##### Additional Python Libraries

There are a couple other popular network libraries written in Python:

* [Gevent](http://sdiehl.github.io/gevent-tutorial/)
* [Eventlet](http://eventlet.net/doc/examples.html)
* [Tornado](http://www.tornadoweb.org/en/stable/)

##### Books, readings, presentations

* Book: [Twisted Networking Programming Essentials](http://www.amazon.com/Twisted-Network-Programming-Essentials-McKellar/dp/1449326110/ref=pd_sim_b_5)
* Book: [Foundations of Python Network Programming](http://www.amazon.com/Foundations-Python-Network-Programming-comprehensive/dp/1430230037/ref=pd_sim_b_3)
* Book: [Violent Python: A Cookbook for Hackers, Forensic Analysts, Penetration Testers and Security Engineers](http://www.amazon.com/Violent-Python-Cookbook-Penetration-Engineers/dp/1597499579/ref=pd_sim_b_2)
* Presentation: [Intro to Python Networking - UDP](http://www.youtube.com/watch?v=vNVMlXLGrTE)
* Presentation: [Twisted Logic: Endpoints and why you shouldn’t be scared of Twisted](http://pyvideo.org/video/1740/twisted-logic-endpoints-and-why-you-shouldnt-be)
* Tutorial: [Intermediate Twisted: Test-driven Networking Software](http://pyvideo.org/video/1715/intermediate-twisted-test-driven-networking-soft)
* Presentation: [Twisted Matrix High Scores](http://pyvideo.org/video/692/2-twisted-matrix-high-scores)