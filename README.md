# simple-websockets-demo
set up a super basic websocket server &amp; a browser client to consume that service


Project Impetus
---------------

* I was [reading about websockets](http://blog.chromium.org/2009/12/web-sockets-now-available-in-google.html), thinking about using [reaveal.js](https://github.com/hakimel/reveal.js/) for presentations.

* maybe we can use websockets to broadcast browser state of a presentor showing a reveal.js slideshow
  * assuming the slideshow is in an public/accessable gh-pages branch,
  * and presentees already have the slideshow content loaded in their browser,
  * all we'd need to transmit to keep all parties in sync would be a slide number

* on normal days, i'm frequently bereft of modern video conferencing facilities
  * and so have reverted to communication via git/github


create a websocket service (server side)
----------------------------------------

* looks like google has [published a nice tool](https://github.com/google/pywebsocket) on creating websocket services
  * IN_PROGRESS
  * I'LL STOP SHOUTING NOW

create a websocket consumer (client side)
------------------------------------------

* there are [tons of neat websocket demos](http://www.tutorialspoint.com/html5/html5_websocket.htm) available
* but we always need good taste
* 
