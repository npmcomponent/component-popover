*This repository is a mirror of the [component](http://component.io) module [component/popover](http://github.com/component/popover). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-popover`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# Popover

  Popover component built on top of [Tip](http://github.com/component/tip).

  ![js popover component](http://f.cl.ly/items/282X271J2Y1s1P342o02/Screen%20Shot%202012-08-02%20at%205.07.07%20PM.png)

## Installation

```
$ npm install popover-component
```

## Features

  - events for composition
  - "auto" positioning
  - fluent API
  - minimal base styling

## API

### new Popover(content, [title])

  Create a new popover with `content` being
  either a string, html, or element, and optional
  `title` which may contain html or be an element as well.

```js
var Popover = require('popover');
var popover = new Popover('You have mail!!!', 'Mail');
popover.show('#avatar');
```

 View [Tip](http://github.com/component/tip) for additional
 API documentation.

## Themes

  - [Aurora](https://github.com/component/aurora-popover)

## License

  MIT