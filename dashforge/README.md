# DashForge

## Installation

### Node JS

Before installing gulp and sass first you must have NodeJs installed, NodeJS will have npm (node packaged modules).

Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient. Node.js' package ecosystem, npm, is the largest ecosystem of open source libraries in the world.

Online Reference: <https://nodejs.org/en/>

#### Installing in Mac

Simply download the Macintosh Installer direct from the nodejs.org web site.

If you want to download the package with bash:

```bash
curl "https://nodejs.org/dist/latest/node-${VERSION:-$(wget -qO- https://nodejs.org/dist/latest/ | sed -nE 's|.*>node-(.*)\.pkg.*|\1|p')}.pkg" > "$HOME/Downloads/node-latest.pkg" && sudo installer -store -pkg "$HOME/Downloads/node-latest.pkg"
-target "/"
```

Using Homebrew:

```bash
brew install node
```

#### Installing in Windows

Simply download the Windows Installer direct from the nodejs.org web site.

### Gulp JS

Before installing gulp first you must have NodeJs installed, NodeJS will have npm (node packaged modules).

Gulp is a toolkit for automating painful or time-consuming tasks in your development workflow, so you can stop messing around and build something.

Online Reference: <https://gruntjs.com/>

#### Installing the CLI

If you have previously installed a version of gulp globally, please run `npm rm --global gulp` to make sure your old version doesn't collide with gulp-cli

```bash
npm install -g gulp-cli
```

verify that gulp is successfully installed, and version of installed gulp will appear

```bash
gulp --version
```

### SASS

Before running grunt first you must check if you have sass installed in your machine. You can verify that sass is already installed by running the command.

```bash
sass --version
```

If version appear, it means sass already installed in your machine and proceed to the next topic, otherwise follow the instructions below on installing sass.

#### Installing in Windows

Before you start using Sass you will need to install Ruby. The fastest way to get Ruby on your Windows computer is to use Ruby Installer. It's a single-click installer that will get everything set up for you super fast.

#### Installing in Mac

If you prefer the command line over an application then getting Sass set up is a fairly quick process. Sass has a Ruby dependency but if you're using a Mac, congratulations, Ruby comes pre-installed.

#### Install SASS

Ruby uses Gems to manage its various packages of code like Sass. In your open terminal or cmd window:

```bash
gem install sass
```

You should now have Sass installed, but it never hurts to double-check.

```bash
sass --version
```

## Running local

You're moments away to see the dashboard template up and running in your local machine. First, go to the root folder where the package.json located. In your download package it should be in the root folder. Please run the following command below.

Note: Running this template to you local machine is not a requirements for you to see the template. You can directly browse to the template folder and choose any html file you want to open by opening it directly to the browser.

```bash
npm install
```

This will download all dependencies defined in package.json file. Once it finished running the command, it will generate a folder name `node_modules/` where you see downloaded files.Next, run another command below.

### Running in Browser

Now you're good to go in running the template and preview it in browser by running the command below

```bash
gulp serve
```

The template is now up and running in your browser. Feel free to visit each page and familiarize the flow of it.
