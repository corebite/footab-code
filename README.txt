This is an extension for chromium which prevents restored tabs from fully loading up at startup, eg. lazy loading until the tab gets focus.
The tabs are still loading something though(partially, without javascript
running?)

originally from: git://git.code.sf.net/p/footab/code
or: http://sourceforge.net/projects/footab/


original description from sf.net:
------------
Description

This Chrome/Iron extension is inspired by the excellent Firefox extension - BarTab, although it's much less sophisticated and powerful.

I've written it over a weekend while learning Chrome's API, so it might be a bit unpolished ;) I just couldn't believe it's not possible to do something about Chrome's startup tab loading mess.

Turns out it's possible, but results are pretty unstable depending on OS, Chrome version and computer's speed.

I didn't publish it on Web Store, because I don't have a developer account and don't want to pay entry fee to publish a free extension.

It works for 10 secs on Chrome/Iron start, blocking tabs that are not active from any web requests.

After those 10 seconds the web traffic is restored and the extension only monitors the tabs that were previously blocked to reload them when they are activated.

It's 10 secs so that non-SSD boxes manage to finish loading. I plan to make it configurable when I'll have some time. Feel free to contribute!


