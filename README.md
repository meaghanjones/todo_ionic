# A basic ionic to do app to learn functionality
### Meaghan Jones October 26th, 2016 

# Ionic-Cli

The Ionic Framework command line utility makes it easy to start, build, run, and emulate [Ionic](http://ionicframework.com/) apps. In addition, it comes with (optional!) integration with the [Ionic Cloud](http://ionic.io/), a set of mobile backend services perfect for Ionic apps.

Use the `ionic --help` command for more detailed task information.

## Installing

```bash
$ npm install -g ionic
```

*Note: For a global install of `-g ionic`, OSX/Linux users may need to prefix the command with `sudo` or can setup [proper file permissions on OSX for npm](http://www.johnpapa.net/how-to-use-npm-global-without-sudo-on-osx/) to install without `sudo`.*


Minimal node requirements:

- NodeLTS or greater
- NPM 3x



## Starting this Ionic App

To start a Ionic 1x app, run:

```bash
$ ionic start myapp [template]
```

To start a Ionic 2 app, run:

```bash
$ ionic start myapp [template] --v2
```

## Testing this app in a Browser

Clone this repo to your desktop and then use `ionic serve` to start a local development server for app dev and testing. Additionally, this command starts LiveReload which is used to monitor changes in the file system. As soon as you save a file the browser is refreshed automatically. View [Using Sass](https://github.com/driftyco/ionic-cli/blob/master/README.md#using-sass) if you would also like to have `ionic serve` watch the project's Sass files.

```bash
$ ionic serve [options]
```

## Building the to do app

```bash
$ ionic build ios
```

## Emulating the to do app

Deploys the Ionic app on specified platform emulator. This is simply an alias for `run --emulator`.

```bash
$ ionic emulate ios [options]
```

## Running the to do app

Deploys the Ionic app on specified platform devices. If a device is not found it'll then deploy to an emulator/simulator.

```bash
$ ionic run ios [options]
```

## Share the application with another user

Use the `ionic share <email>` command to have an email sent to another person to have them view the Ionic application you are using. Note: You must have an [Ionic Cloud](http://ionic.io/) account as well as the user you are sharing with.


