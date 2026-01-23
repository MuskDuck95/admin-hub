# Admin Hub

Admin Hub is a lightweight, fully customisable, frontend-only website that's designed to serve as a dashboard for system administrators.

It lets sysadmins see the health of each site in their environment and quickly access other admin portals and tools.

Admin Hub only needs a few megabytes of space on a web server to run (e.g. on an Apache or IIS server).

## Getting started

### Quick links
Follow the links below:

* [Install and configure](https://stuartgarner.au/admin-hub/setup/)
* [User guide](https://stuartgarner.au/admin-hub/help/)
* [Live demo](https://stuartgarner.au/admin-hub/demo/)

## FAQs

### Why does Admin Hub exist?

TODO

### What can Admin Hub show me about my environment?

TODO

### If it's 'frontend-only', where does all the data about my environment come from?

That's up to you!

Admin Hub doesn't have any backend code - it's just HTML, CSS and JavaScript (and some images and config files) sitting on a web server.
When a user navigates to Admin Hub from a web browser, it'll look for some specific JSON files on your web server to get data about your environment (and will continually checks these files for any updates and changes).

The data Admin Hub shows about your environment comes from these JSON files. You can populate the data in the JSON files any way you want.

For example: say you're running a primarily Windows Server-based environment. You could create a PowerShell script to test the latency to each site on your network. Your script can then export the results of those latency tests the sites.json file on the web server. Set that up as a scheduled.

### What web browsers does Admin Hub support?

I built Admin Hub to work on Microsoft Edge and Google Chrome (i.e. Chromium-based browsers).

I try to support Firefox as best as I can however some features may not work perfectly (check the release notes).

Please don't use IE. You're probably working in an enterprise environment with bespoke, legacy software… trust me, I get it… but you should at least have a modern web browser installed.

### Do you ever plan to build a backend?

No, not at this stage.

### Can I modify Admin Hub? …or build my own backend for it?

Yes, go for it!

Admin Hub is issued under an MIT Licence and you are free to use, modify and redistribute as you see fit (provided you attribute :)).

P.S. don't forget to attribute [Flaticon](https://www.flaticon.com/uicons) as well if you intend to use the icons that come with Admin Hub.