[//]: # (header-start)


<h1 align="center">
	<a href="https://blog.axway.com/mobile-apps/prepare-your-apps-for-appcelerator-end-of-support">
		Preparing for end of Axway
	</a>	
</h1>
<h2 align="center">
	👇 &nbsp; support for Amplify Cloud and Mobile   &nbsp; 👇
</h2>	

<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		<img src="https://cdn.secure-api.org/images/RIP-Axway-Amplify-Titanium.png" alt="RIP Axway Amplify Titanium (2010 - 2022)" width="80%" />
	</p>
</a>	
<p align="center">
	<a href="https://blog.axway.com/mobile-apps/changes-to-application-development-services">
			🪦 &nbsp; RIP Axway Amplify Titanium (2010 - 2022)
	</a>
</p>
<p align="center">
	<a href="https://blog.axway.com/mobile-apps/prepare-your-apps-for-appcelerator-end-of-support">
			🪦 &nbsp; RIP Axway Amplify Cloud Services (2012 - 2022)
	</a>
</p>
<p align="center">
	<a href="https://blog.axway.com/mobile-apps/prepare-your-apps-for-appcelerator-end-of-support">
			🪦 &nbsp; RIP Axway Amplify Crash Analytics (2015 - 2022)
	</a>
</p>

<hr>
<a href="https://blog.axway.com/mobile-apps/prepare-your-apps-for-appcelerator-end-of-support">
	<h4 align="center">
🛑 &nbsp;&nbsp; <a href="https://blog.axway.com/mobile-apps/prepare-your-apps-for-appcelerator-end-of-support">Axway has already shut down support</a> for most of their Amplify products related to mobile and cloud. 
</h4>

<h4 align="center">
A few of the open-source versions of Axway Amplify products will live on after Axway Amplify End-of-Life (EOL) announcements.  However, all closed-source projects and most open-source projects are now dead.  
	</h4>

<p>&nbsp;</p>

> 👉 &nbsp;&nbsp; A group of Axway employees, ex-Axway employees, and some developers from Titanium community have created a legal org and now officially decide all matters related to future of these products.  

<p>&nbsp;</p>
<hr>


## API FAQ:

* [API Best Practices](https://brenton.house)
* [What is API Security?](https://brenton.house/what-is-api-security-5ca8117d4911)
* [OWASP Top 10 List for API Security](https://www.youtube.com/watch?v=GLVHDj0Cpg4)
* [What is API Security?](https://brenton.house/what-is-api-security-5ca8117d4911)
* [Top API Trends for 2022](https://brenton.house/top-10-api-integration-trends-for-2022-49b05f2ef299)
* [What is a Frankenstein API?](https://brenton.house/what-is-a-frankenstein-api-4d6e59fca6)
* [What is a Zombie API?](https://brenton.house/what-is-a-zombie-api-6e5427c39b6a)
* [API Developer Experience](https://brenton.house/keys-to-winning-with-an-awesome-api-developer-experience-62dd2fa668f4)
* [API Cybersecurity 101](https://brenton.house/what-is-api-security-5ca8117d4911)
* [YouTube API Videos](https://youtube.com/brentonhouse)
* [YouTube API Shorts Videos](https://youtube.com/apishorts)

&nbsp;

[![Click to watch on Youtube](https://img.youtube.com/vi/GLVHDj0Cpg4/0.jpg)](https://www.youtube.com/watch?v=GLVHDj0Cpg4&list=PLsy9MwYlG1pew6sktCAIFD5tbrXy9HUQ7  "Click to watch on YouTube")


> &nbsp; [↑ Watch video on YouTube ↑](https://www.youtube.com/watch?v=GLVHDj0Cpg4&list=PLsy9MwYlG1pew6sktCAIFD5tbrXy9HUQ7)

&nbsp;



<p>&nbsp;</p>
<hr>

<p>&nbsp;</p>
<p>&nbsp;</p>

[//]: # (header-end)

# Titanium CLI

---
## *Modified from Appcelerator Titanium CLI to update dependencies and apply security patches.*

---


> [Titanium CLI](https://github.com/appcelerator/titanium) is a
[Command Line Tool](http://en.wikipedia.org/wiki/Command-line_interface)
for creating and building Titanium Mobile applications and modules. It's
open-source and easy to use. [We've](https://github.com/appcelerator)
designed Titanium to be suitable for command line beginners, but still be
powerful and extensible enough for production usage.

[![@titanium/titanium](https://img.shields.io/npm/v/@titanium/titanium.png)](https://www.npmjs.com/package/@titanium/titanium)
[![@titanium/titanium](https://snyk.io/advisor/npm-package/@titanium/titanium/badge.svg)](https://snyk.io/advisor/npm-package/@titanium/titanium)

## Prerequisites

The Titanium CLI requires [Node.js 0.10.x](http://nodejs.org/dist/) or newer.

## Installation

    [sudo] npm install -g titanium

## Bleeding Edge

You can download the latest and greatest *unstable* Titanium CLI code by
running the following:

    [sudo] npm install -g git://github.com/appcelerator/titanium.git

## Obtaining a Titanium SDK

You will need to download a Titanium SDK 3.0 or newer:

    # stable release (recommended)
    titanium sdk install --default

There are times when the latest stable release has an issue or lacks a feature
in which case you may want to try an unstable Titanium SDK build. These builds
are not recommended for production use, but should work for development.

    # unstable next release
    titanium sdk install --branch 3_1_X --default

    # bleeding edge
    titanium sdk install --branch master --default

## Setting up the Titanium CLI

Before you begin using the Titanium CLI, you should configure it by running the
"setup" command:

    titanium setup

It will prompt you with a number of questions such as your e-mail address (for
logging into the Appcelerator Network), the location of your Android SDK, and so on.

## Usage

    titanium <command> [options]

## Built-in Commands

### config

Configure your CLI settings.

**Implementation not complete**

    titanium config <setting> <value>

### help

Displays help or help for a specific command.

    titanium

    titanium help

    titanium --help

    titanium help <command>

    titanium <command> --help

### login

Logs into the Appcelerator Network

**Implementation not complete**

Login requires both user and password options to be passed in.

    titanium login <username> <password>

If you omit an option, the CLI will prompt you for the value.

    titanium login

### logout

Logs out of the Appcelerator Network

**Implementation not complete**

    titanium logout

### sdk

Download and install Titanium SDKs

#### sdk install

Installs a specific version of the Titanium SDK. If no version is specified, it assumes the latest.

    titanium sdk install

    titanium sdk install <version>

    titanium sdk install <version> --force

Download, install <version>, and set as default SDK.

    titanium sdk install <version> --default

Download and install the latest version for the specified branch

    titanium sdk install --branch master

#### sdk uninstall

Uninstalls a Titanium SDK.

    titanium sdk uninstall <version>

#### sdk list

Lists all installed Titanium SDKs. Optionally lists all branches and releases.

    titanium sdk list

    titanium sdk list -b
    titanium sdk list --branches

    titanium sdk list -r
    titanium sdk list --releases

    titanium sdk list -br
    titanium sdk list --branches --releases

### setup

Reconfigures the Titanium CLI by asking you a series of questions.

    titanium setup

### status

Indicates whether you are logged in or not.

    titanium status

    titanium status --output json

### version

Displays the current version of the CLI and exits.

    titanium -v

    titanium --version

### info

Displays information about your development environment including Xcode installs,
iOS SDKs, Android SDKs, and so on.

    titanium info

    titanium info -o json

## Hacking the Titanium CLI

In order to begin hacking on the Titanium CLI, you need to download and install
[git](http://git-scm.com/).

If you have already installed a previous version of the Titanium CLI, it's
recommended you uninstall the old one first:

    [sudo] npm uninstall -g titanium

The Titanium CLI is essentially pure JavaScript, so there is no build process.
You just need to pull the code and resolve the dependendencies.

    git clone git@github.com:appcelerator/titanium.git
    cd titanium
    npm install
    sudo npm link

### Running Unit Tests

To run the unit tests, simply run:

    node forge test

### Running Code Coverage

To generate the code coverage, you first must install
[node-jscoverage](https://github.com/visionmedia/node-jscoverage). The easist
way to do this is run:

    git clone git@github.com:visionmedia/node-jscoverage.git
    cd node-jscoverage
    ./configure
    make
    sudo make install

Then run:

	node forge test-cov

It will generate a file called _coverage.html_ in the Titanium CLI directory.

## Looking for the really old CLI?

Don't worry, it's still around. You can install it by running:

    [sudo] npm install –g titanium@0.0.26

## Contributing

Titanium is an open source project. Titanium wouldn't be where it is now without
contributions by the community. Please consider forking this repo to improve,
enhance or fix issues. If you feel like the community will benefit from your
fork, please open a pull request.

To protect the interests of the Titanium contributors, Appcelerator, customers
and end users we require contributors to sign a Contributors License Agreement
(CLA) before we pull the changes into the main repository. Our CLA is simple and
straightforward - it requires that the contributions you make to any
Appcelerator open source project are properly licensed and that you have the
legal authority to make those changes. This helps us significantly reduce future
legal risk for everyone involved. It is easy, helps everyone, takes only a few
minutes, and only needs to be completed once.

[You can digitally sign the CLA](http://bit.ly/app_cla) online. Please indicate
your e-mail address in your first pull request so that we can make sure that
will locate your CLA. Once you've submitted it, you no longer need to send one
for subsequent submissions.

## License

This project is open source and provided under the Apache Public License
(version 2). Please make sure you see the `LICENSE` file included in this
distribution for more details on the license.  Also, please take notice of the
privacy notice at the end of the file.

#### (C) Copyright 2012-2013, [Appcelerator](http://www.appcelerator.com/) Inc. All Rights Reserved.
