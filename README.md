App Developer Club Connect Site
===============================

The App Developer Club connect website is the chat network for ADC. This site is run off of Rocket.Chat, which is a Slack-like clone built using Meteor. This allows for real-time two-way data binding so that messages can be properly propagated from the servers to users. We will create the proper channels for the club (designing, developing, ios, android, etc).


Table of Contents
-----------------

- [Features](#features)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Deployment](#deployment)
- [Changelog](#changelog)
- [Contributing](#contributing)
- [License](#license)


Features
--------

- **OAuth 2.0 Authentication** via Github
- BYOS (bring your own server)
- Multiple Rooms
- Direct Messages
- Private Groups
- Public Channels
- Desktop Notifications
- Mentions
- Avatars
- Markdown
- Emojis
- Sent Message Edit and Deletion
- Transcripts / History
- File Upload / Sharing
- I18n - Supports 22 Languages
- Media Embeds
- Link Previews


Prerequisites
-------------

- [MongoDB](http://www.mongodb.org/downloads)
- [Node.js](http://nodejs.org)
- [Meteor.js](https://www.meteor.com/install)

**Note:** There will be many more packages and plugins necessary to run the application. I suggest reading through which errors are raised when compiling either the web or mobile end and installing those necessary plugins into your computer. Note that you will probably need to install certain versions of python/rvm in order for some packages to work properly.


Getting Started
---------------

Get started by first cloning the repository:

```bash
# Get the latest version:
$ git clone https://github.com/appdeveloperclub/ADC_Connect_Website.git
$ cd ADC_Connect_Website

# To run the app, simply execute:
$ meteor
```

Deployment
----------

This section is WAY too complicated because there is a ton of configuration that I barely remember. I will get back to this section at a later time.

Changelog
---------

### 0.0.1 (August 21, 2015)
- Working on CSS styling to match theme of all ADC sites.
- Messaging works, added in Github OAuth.


Contributing
------------

If something is unclear, confusing, or needs to be refactored, please let me know.
Pull requests are always welcome, but due to the opinionated nature of this
project, I cannot accept every pull request. Please open an issue before
submitting a pull request. This project uses
[Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript) with a
few minor exceptions. If you are submitting a pull request that involves
Jade templates, please make sure you are using *spaces*, not tabs.

License
-------

The MIT License (MIT)

Copyright (c) 2014-2015 App Developer Club

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
