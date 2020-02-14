# Phonegap CLI

Phonegap is used to make mobile apps with HTML, CSS and JS.

## Requirments

There are a few simple requirements you'll need prior to installing the PhoneGap CLI:

[node.js](https://nodejs.org/) - a JavaScript runtime to build your JavaScript code
[git](http://git-scm.com/) - used in the background by the CLI to download assets. It comes pre-installed on some operating systems.

To see if you already have it installed, type `git` from the command line.

## Step 1: Install Phonegap

1. Install the PhoneGap CLI via  npm with the following command from the Terminal app (Mac) or Caommand Prompt (Win).

```bash
$ npm install -g phonegap@latest
```

> [!TIP]
> 1) The `$` sysmbol is used throughout the guide to indicate the command prompt. it should not be typed.
> 
> 2) `npm` is the node package manager and installed with node.js. The `npm` command fetches the necessary dependencies for the PhoneGap CLI to run on your local machine. It creates a **node_modules** folder with the necessary code needed to run the CLI. The `-g` flag specifies that folder to be installed at the global location so it can be accessed from anywhere on your machine (defaults to **usr/local/lib/node_modules/phonegap** on your Mac).

> [!WARNING]
> **OS X Users:** You may need to prefix this command with `sudo` to allow installation to restricted directories and type the following instead `$ sudo npm install -g phonegap@latest`
> 
> **Windows 8 Users:** if you just inatlled Node.js, be sure to start the **Node.js Command Prompt** application specifically.

2. Test to ensure the PhoneGap CLI is properly insatlled by typing `phonegap` on command line. You should see the following `help` text output displayed.

```bash
$ phonegap
Usage: phonegap [options] [commands]
Description:
PhoneGap command-line tool.
Commands:
   help [command]       output usage information
   create <path>        create a phonegap project
   ...
```

> [!TIP]
> You can access the PhoneGap CLI usage text at any time by adding the keyword `help`, or the `-h` or `--h` attribute with any phonegap command i.e: `$ phonegap create help`, `$ phonegap server -h`.

## Step 2: Install Mobile App

The PhoneGap Developer App is a mobile app that runs on devices and allows you to preview and test the PhoneGap mobile apps you build across platforms without any additional setup. It's meant to provide an easy way for developers to get started creating and testing their PhoneGap applications quickly with minimal setup.

### Install PhoneGap Developer

1. Locate the free PhoneGap Developer app from one of the following supported app market places and install it to your mobile device:
  - [Google Play](https://play.google.com/store/apps/details?id=com.adobe.phonegap.app)
  - [Windows Phone Store](https://www.microsof.com/en-us/store/p/phonegap-developer/9wzdncrdfsj0)
  - [~Itunes~ Not available but you can build it yourself!](https://blog.phonegap.com/update-on-the-phonegap-developer-app-ios-99e07e3309dd)
  
 2. Once installed tap the PhoneGap Developer app icon from your home screen to open it.
 
 3. Once installed, move on to the next step where you will create your PhoneGap app.
 
 ## Step 3: Create Your App
 
 ### Create Default PhoneGap Project
 
 The PhoneGap 
