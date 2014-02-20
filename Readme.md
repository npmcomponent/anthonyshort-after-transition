*This repository is a mirror of the [component](http://component.io) module [anthonyshort/after-transition](http://github.com/anthonyshort/after-transition). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/anthonyshort-after-transition`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# after-transition

  Fire a callback after a transition or immediately if the browser does not support transitions.
  If the element does not have a transition property it will also fire immediately.

## Installation

    $ component install anthonyshort/after-transition

or via npm for use with Browserify

    $ npm install after-transition

## API

    var afterTransition = require('after-transition');

    afterTransition(el, function(){
      // Do things when the transition has finished
      // This will fire immediately for IE
    });

    afterTransition.once(el, function(){
      // Same as above but will only fire once
    });

## License

  MIT
