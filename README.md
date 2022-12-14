# Foundation for Emails Template

[![devDependency Status](https://david-dm.org/zurb/foundation-emails-template/dev-status.svg)](https://david-dm.org/zurb/foundation-emails-template#info=devDependencies)

**Please open all issues with this template on the main [Foundation for Emails](http://github.com/zurb/foundation-emails/issues) repo.**

This is the official starter project for [Foundation for Emails](http://foundation.zurb.com/emails), a framework for creating responsive HTML devices that work in any email client. It has a Gulp-powered build system with these features:

- Handlebars HTML templates with [Panini](http://github.com/zurb/panini)
- Simplified HTML email syntax with [Inky](http://github.com/zurb/inky)
- Sass compilation
- Image compression
- Built-in BrowserSync server
- Full email inlining process

## Installation

To use this template, your computer needs [Node.js](https://nodejs.org/en/) 0.12 or greater. The template can be installed with the Foundation CLI, or downloaded and set up manually.

```

### Setup

Open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm i
```

## Build Commands

Run `npm start` to kick off the build process. A new browser tab will open with a server pointing to your project files. (with serve mode)

Run `npm run build` to inline your CSS into your HTML along with the rest of the build process. (with serve mode)

Run `npm run buildhard` to inline your CSS into your HTML, delete all classes and create two folders with emails (minEmail 'compressed html', unMinEmail 'uncompressed html') along with the rest of the build process (no serve mode).


