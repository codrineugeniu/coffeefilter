## CoffeeFilter

Have you or someone on your team ever accidently installed a module without knowing it was *"Generated by CoffeeScript"*? I know the feeling and its horrible! Well have no fear, CoffeeFilter is here to save your day!

Just simple install and soon as your app attempts to use a module generated CoffeeScript, your application will segfault for you!

## Install

```shell
npm install coffeefilter
```

## Usage

Just require it before everything else:

```javascript

require('coffeefilter');
var obj = require('bastard-who-might-ruin-your-day');

