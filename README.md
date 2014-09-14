scrollme+modernizr
========

Integration of Modernizr on Scrollme to avoid the execution on touchable devices

There are no stable workarounds to subsane iOS DOM-freeze on scrolling events, it's better to avoid parallax effects through Scrollme on touchable devices.

Waiting for jQuery workaround (http://api.jquerymobile.com/scrollstart/)
>> Note that iOS devices freeze DOM manipulation during scroll, queuing them to apply when the scroll finishes. We're currently investigating ways to allow DOM manipulations to apply before a scroll starts.

Scrollme site: http://scrollme.nckprsn.com
Modernizr site: http://modernizr.com
