Cookie Monster
==============

Strip cookies from XMLHttpRequests in Mozilla Firefox, using JavaScript and XUL.

Features
--------

Well, the Cookie Monster allows you to strip any cookies from [XMLHttpRequests](https://developer.mozilla.org/en/XmlHttpRequest) in Mozilla Firefox.  What else did you expect?


Usage
-----

Include the cookiemonster.js file and then use it as follows in your own code:

    var request = new XMLHttpRequest();
    request.open(...);
    
    // other code of yours
    
    new CookieMonster(request); // cookie monster will make sure no cookies will survive!
    
    // other code of yours
    
    request.send(); // actually send the XMLHttpRequest

Documentation
-------------

My blog article [Cookie Monster for XMLHttpRequest](http://www.michael-noll.com/tutorials/cookie-monster-for-xmlhttprequest/) works you through the usage and implementation details.


License
-------

The code is licensed to you under version 2 of the GNU General Public License.

Copyright
---------

Copyright 2006-2011 Michael G. Noll <http://www.michael-noll.com/>

