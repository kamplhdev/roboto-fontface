# Roboto font

A package providing the [Roboto](http://www.google.com/fonts/specimen/Roboto) font. The font was created by Christian Robertson.

## Installing

### Prerequisites

In order to install Roboto font you need to have installed following:
* [NodeJS](http://nodejs.org/)
* [NPM](https://www.npmjs.com/)

### Installation
If you have it already installed, open up a terminal, navigate to your projects root directory and then execute

```
# install via NPM
$ npm install roboto-fontface --save
```

## Usage

Import files in your project to have access to "Roboto" font face:
* `scss/roboto/roboto-fontface.scss` - whole font family in SCSS

Importing whole family may lead to huge build, so you can import only individual weights by importing for example:
* `scss/roboto/roboto-fontface-black.scss`
* `scss/roboto/roboto-fontface-black-italic.scss`