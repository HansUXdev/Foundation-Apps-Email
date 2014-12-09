# About this template
This template is more or less the same as the [email template](http://foundation.zurb.com/apps/app-templates/email/) found on zurbs offical website. All I'm doing is adding icons and some basic angular magic to make it more functional and less boilerplate. It's also good practices for learning how to work with Foundation for Apps.

# Changes
	* Added foundation-icons
	* Working search bar 
	* Repeated message in inbox


* TODO
	* Add more VIEWS for inbox, sent, favorite, and trash.



http://foundation.zurb.com/apps/app-templates/email/


# Foundation for Apps Template

This is the default template project for Foundation for Apps. It's powered by Node, Gulp, Angular, and libsass. It provides you with a basic template to get started with Angular and Foundation for Apps. If you're already an Angular developer, you may instead want to install the components into your own stack using Bower: `bower install foundation-apps`

## Requirements

You'll need the following software installed to get started.

  * [Node.js](http://nodejs.org): Use the installer provided on the NodeJS website.
  * [Git](http://git-scm.com/downloads): Use the installer for your OS.
    * Windows users can also try [Git for Windows](http://git-for-windows.github.io/).
  * [Ruby](https://www.ruby-lang.org/en/): Use the installer for your OS. For Windows users, [JRuby](http://jruby.org/) is a popular alternative.
    * With Ruby installed, run `gem install bundler sass`.
  * [Gulp](http://gulpjs.com/) and [Bower](http://bower.io): Run `[sudo] npm install -g gulp bower`

## Get Started

Clone this repository, where `app` is the name of your app.

```bash
git clone https://github.com/zurb/foundation-apps-template.git app
```

Change into the directory.

```bash
cd app
```

Install the dependencies. Running `npm install` will also automatically run `bower install` after. If you're running Mac OS or Linux, you may need to run `sudo npm install` instead, depending on how your machine is configured. Running `bundle` will install the correct version of Sass for the template.

```bash
npm install
bundle
```

While you're working on your project, run:

```bash
npm start
```

This will compile the Sass and assemble your Angular app. **Now go to `localhost:8080` in your browser to see it in action.**

To run the compiling process once, without watching any files:

```bash
npm start build
```