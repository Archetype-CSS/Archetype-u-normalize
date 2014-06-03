# Archetype-u-normalize [![Build Status](https://secure.travis-ci.org/Archetype-CSS/Archetype-u-normalize.png?branch=master)](http://travis-ci.org/Archetype-CSS/Archetype-u-normalize) [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

Archetype utility for [normalize.css](http://necolas.github.io/normalize.css/)

## Installation
  * [Bower](http://bower.io): `bower install Archetype-u-normalize`
  * Git: `git clone https://github.com/Archetype-CSS/Archetype-u-normalize.git`

  Then, import the partial in your main project Sass file `@import 'Archetype-u-normalize';`

## Use

  * `@include normalize-display;` - normalize HTML5 display definitions
  * `@include normalize-page;` - normalize <code>html</code> and <code>body</code>
    element styles
  * `@include normalize-links;` - normalize hyperlinks
  * `@include normalize-typography;` - normalize typography
  * `@include normalize-embeds;` - normalize embeded content
  * `@include normalize-figures;` - normailze figures
  * `@include normalize-forms;` - normalize forms
  * `@include normalize-tables;` - normalize tables

## Run the Test Locally

```bash
git clone https://github.com/Archetype-CSS/Archetype-u-normalize.git
cd Archetype-u-normalize
npm install
grunt
```

### Browser Suport
  * Chrome (latest)
  * Firefox (4+)
  * Opera (latest)
  * Safari (5+)
  * Internet Explorer (8+)

#### License
[MIT](/LICENSE.md)

