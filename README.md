# Salesforce Security Mobile SDK for Android
<!-- [![CircleCI](https://circleci.com/gh/forcedotcom/SalesforceMobileSDK-Android/tree/dev.svg?style=svg)](https://circleci.com/gh/forcedotcom/workflows/SalesforceMobileSDK-Android/tree/dev)
[![Known Vulnerabilities](https://snyk.io/test/github/forcedotcom/SalesforceMobileSDK-Android/badge.svg)](https://snyk.io/test/github/forcedotcom/SalesforceMobileSDK-Android)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/forcedotcom/SalesforceMobileSDK-Android?sort=semver) -->


You have arrived at the source repository for the Salesforce Security Mobile SDK for Android, a clone for Salesforce Mobile SDK for Android with adjusts to close security vunerabilities. Welcome! 

Installation (do this first - really)
==

After cloning the SalesforceMobileSDK-Android project from github, run the install script from the command line:

`./install.sh`

This pulls submodule dependencies from github.

(Windows users: run `cscript install.vbs` from the command line instead.)

Introduction
==

### What's New in 10.2.0
See [release notes](https://github.com/frangoncalez75/SalesforceMobileSDK-Android/releases).

### Native Applications
The Salesforce Mobile SDK provides essential libraries for quickly building native mobile apps that seamlessly integrate with the Salesforce cloud architecture.  Out of the box, we provide an implementation of OAuth2, abstracting away the complexity of securely storing refresh tokens or fetching a new session ID when a session expires. The SDK also provides Java wrappers for the Salesforce REST API, making it easy to retrieve, store, and manipulate data.

### Hybrid Applications
HTML5 is quickly emerging as dominant technology for developing cross-platform mobile applications. While developers can create sophisticated apps with HTML5 and JavaScript, some limitations remain, specifically: session management, access to the camera and address book, and the inability to distribute apps inside public App Stores. The Salesforce Mobile Container makes possible to combine the ease of web app development with power of the Android platform by wrapping a web app inside a thin native container, producing a hybrid application.

Setting up your Development Environment
==

The following steps will help you get started with your development environment, whether you choose to develop native apps or hybrid apps. See the `README` files in the `native/` and `hybrid/` folders for additional notes pertaining to development in those environments.

1. Install the Android SDK and Android Studio: http://developer.android.com/sdk/index.html
2. Get setup on github: http://help.github.com/

Downloading the Salesforce SDK
==

To pull down the SDK from github, create a new directory and git clone the salesforce SDK repo.
<pre>
git clone https://github.com/frangoncalez75/SalesforceSecurityMobileSDK-Android.git
</pre>

