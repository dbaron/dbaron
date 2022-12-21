I'm currently (since March 2021) a software engineer at [Google](https://www.google.com/) working on rendering in [Blink](https://www.chromium.org/blink).

I was a software engineer at [Mozilla](https://www.mozilla.org) from 2003-2020, working on the [Gecko layout engine](https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Introduction), with a focus on implementing new CSS and layout features, making architectural changes to improve speed and memory use, building tools to debug memory use and memory leaks, analyzing automated crash report submissions, general debugging and bug fixing, driving projects to successful completion, and mentoring of both junior and senior engineers in many of these areas.

I've also been a longtime participant in work on Web standards: this includes participation in the W3C's [CSS Working Group](https://wiki.csswg.org/), being an elected member of the W3C's [Technical Architecture Group](https://tag.w3.org/), longtime involvement at a technical and standards policy level in both the [W3C](https://www.w3.org/) and [WHATWG](https://whatwg.org/), and helping others at Mozilla interact with these standards bodies and with other companies participating in them. 

<div align="center">

<strong><a rel="me" href="https://dbaron.org">Homepage</a></strong> ● <strong><a rel="me" href="https://w3c.social/@dbaron">Mastodon</a></strong> ● <strong><a rel="me" href="https://twitter.com/davidbaron">Twitter</a></strong> ● <strong><a rel="me" href="https://www.linkedin.com/in/ldavidbaron/">Linkedin</a></strong>

</div>

### Code hosted here

The code I host in this github account (not counting forks of other repositories) falls into a few categories:

Proposals for Web standards:
* [**container-queries-implementability**](https://github.com/dbaron/container-queries-implementability) - Proposal for container queries designed to be implementable in web browsers (in progress)
* [**css-line-spacing**](https://github.com/dbaron/css-line-spacing/blob/main/explainer.md) - Specification of features for even spacing of lines in CSS. (in progress, though not active)
* [**css-supports-functions**](https://github.com/dbaron/css-supports-functions/blob/main/explainer.md) - Proposal for new functions for css @supports rules (now [part of spec draft](https://drafts.csswg.org/css-conditional-4/#at-supports-ext))
* [**css-intrinsic-isize-props**](https://github.com/dbaron/css-intrinsic-isize-props) - Proposed additions to css-sizing for properties to override CSS intrinsic sizes
* [**css-intrinsic-sizing-one-axis**](https://github.com/dbaron/css-intrinsic-sizing-one-axis) - A proposal to avoid having CSS intrinsic sizes start depending on layout

Tools used within the W3C:
* [**wgmeeting-github-ircbot**](https://github.com/dbaron/wgmeeting-github-ircbot) -  IRC bot to make github comments with relevant sections of Working Group Meeting IRC minutes
* [**gather-doc-email**](https://github.com/dbaron/gather-doc-email) - Python script to gather email for a W3C disposition of comments

Documentation about CSS:
* [**inlines-and-floats**](https://github.com/dbaron/inlines-and-floats) - Document describing interaction of inline layout and wrapping around floats

Code related to timezones:
* [**tz.js**](https://github.com/dbaron/tz.js) - A library for working with timezones in JavaScript
* [**tzmap.js**](https://github.com/dbaron/tzmap.js) - A library for working with the geography of timezones in JavaScript
* [**timezone-map**](https://github.com/dbaron/timezone-map) - A [Web-based map](https://dbaron.org/maps/timezone-map/) of timezones as they are at a point in time, using both `tz.js` and `tzmap.js`.
* [**meeting-scheduler**](https://github.com/dbaron/meeting-scheduler) - Web application for figuring out what time a meeting is in multiple timezones. (A demonstration of `tz.js` use.)

Some mapping-related code I've written:
* [**osm-satellite-scripts**](https://github.com/dbaron/osm-satellite-scripts) -  Scripts for processing satellite images for use in mapbox studio for tracing with OpenStreetMap iD editor
* [**osm-area-diff**](https://github.com/dbaron/osm-area-diff) - Diff OpenStreetMap changes in a time period to help understand and revert vandalism
* [**walk-maps**](https://github.com/dbaron/walk-maps) - A leaflet-based map of GPX traces of walks I've taken (without the private data)
* [**backpacking-maps**](https://github.com/dbaron/backpacking-maps) - A leaflet-based map of GPX traces of backpacking trips I've taken
* [**rail-network-quizzes**](https://github.com/dbaron/rail-network-quizzes) - code to use OpenStreetMap data to build rail network quizzes for JetPunk

Some other simple Web applications I've written:
* [**sf-elections-rcv**](https://github.com/dbaron/sf-elections-rcv) - [Web application](https://dbaron.org/sf-elections-rcv/) to analyze the Ranked Choice Voting (RCV) of 2008-2019 San Francisco elections
* [**ssa-names-data**](https://github.com/dbaron/ssa-names-data) - [Web application](https://dbaron.org/ssa-names-data/national-data) to analyze some aspects of the Social Security Administration's baby name data
* [**president-ages**](https://github.com/dbaron/president-ages) - [Web-based graph](https://dbaron.github.io/president-ages/) of the age of US presidents over time, plus 2020 candidates

Some Mozilla extensions I've written:
* [**char-identifier**](https://github.com/dbaron/char-identifier) - [Character Identifier](https://dbaron.org/mozilla/char-identifier/) is a Web Extension (runs in multiple browsers) that adds a browser context menu item for selected text that provides more information (from the Unicode database) about the characters selected.
* [**leak-monitor**](https://github.com/dbaron/leak-monitor) - [Leak Monitor extension](https://dbaron.org/mozilla/leak-monitor/) for all Toolkit apps (Firefox, Thunderbird, SeaMonkey, etc.) to detect some classes of leaks in the Javascript code in which the browser and other apps were written.
* [**about-accessibilityenabled**](https://github.com/dbaron/about-accessibilityenabled) - [about:accessibilityenabled extension](https://dbaron.org/mozilla/about-accessibilityenabled/)

A Mercurial extension I wrote:
* [**qfixdrift**](https://github.com/dbaron/qfixdrift) - Mercurial extension to clean up patch drift in an mq patch queue

My Gecko patch development from 2007 to 2018 lives in these [Mercurial Queue](https://www.mercurial-scm.org/wiki/MqExtension) repositories:
* [**patches**](https://github.com/dbaron/patches)
* [**patches-clean**](https://github.com/dbaron/patches-clean)
* [**patches-aurora**](https://github.com/dbaron/patches-aurora)
* [**patches-beta**](https://github.com/dbaron/patches-beta)

My Gecko patch development from 2019-2020 lives on branches in [my fork of **gecko**](https://github.com/dbaron/gecko).

I also have a Mercurial Queue repository of patches to the [CSS Working Group's specs](https://github.com/w3c/csswg-drafts/):
* [**csswg-specs-patches**](https://github.com/dbaron/csswg-specs-patches)

Other Mozilla-related repositories:
* [**nightly-topcrash-generator**](https://github.com/dbaron/nightly-topcrash-generator) - code used to generate [Firefox nightly build crashes, by build](https://dbaron.org/mozilla/crashes-by-build), which is a set of links to Firefox crashes in nightly builds, separated by build
* [**mozconfigs**](https://github.com/dbaron/mozconfigs) - mozconfig files I use for building Mozilla apps in different configurations

Other code I've written:
* [**sort-vcalendar**](https://github.com/dbaron/sort-vcalendar) - Sort a vCalendar file by the UID of the events

### Code hosted elsewhere

Most of the code I've written is not hosted in this GitHub account; it lives elsewhere.  This includes contributions to:
* the [Gecko](https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Introduction) layout engine used in Firefox ([1998-2003](https://github.com/mozilla/mozilla-history/commits?author=dbaron%25fas.harvard.edu), [2003-2011](https://github.com/mozilla/mozilla-history/commits?author=dbaron), [2008-2020](https://github.com/mozilla/gecko-dev/commits?author=dbaron))
* [code contributions](https://chromium-review.googlesource.com/q/owner:dbaron%2540chromium.org+is:merged) and [code reviews](https://chromium-review.googlesource.com/q/label:Code-Review%253DANY%252Cuser%253Ddbaron%2540chromium.org) in the [Chromium](https://www.chromium.org/) project, the open source project behind the [Google Chrome](https://www.google.com/chrome) browser
* CSS working group specifications hosted in [csswg-drafts](https://github.com/w3c/csswg-drafts/) and also a little bit in [fxtf-drafts](https://github.com/w3c/fxtf-drafts/) and [css-houdini-drafts](https://github.com/w3c/css-houdini-drafts/)
* contributions to the W3C TAG [Web Platform Design Principles](https://w3ctag.github.io/design-principles/), [Design Reviews](https://github.com/w3ctag/design-reviews), and other repositories
* [contributions](https://github.com/mozilla/standards-positions/commits?author=dbaron) to Mozilla's [Specification Positions](https://mozilla.github.io/standards-positions/)
* [contributions](https://github.com/web-platform-tests/wpt/commits?author=dbaron) to [Web Platform Tests](https://web-platform-tests.org/)
