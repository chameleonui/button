
# button

Highly customisable buttons

## Installation

Install with [component](http://component.io):

    $ component install chameleonui/button

## API

### Use flags

```
use-button-style = 'flat'; // only flat style implemented
```

### Variables

```
button-class = 'button';

// Style -- common for all
button-default-padding ?= (1/8) (1/2);
button-default-font-size ?= 16px;
button-default-font-weight ?= 400;
button-default-line-height ?= 1.5;
button-default-border-width ?= 1px;
button-default-border-radius ?= 0;
button-default-disabled-opacity = .65;

// Sizes -- list
button-sizes-list ?= small, large;

// Sizes -- config for listed sizes above
button-small-padding ?= 2px 8px;
button-small-font-size ?= 14px;
button-small-line-height ?= 18px;
button-small-border-radius ?= 0;

button-large-padding ?= 12px 24px;
button-large-font-size ?= 18px;
button-large-line-height ?= 24px;
button-large-border-radius ?= 0;


// Type - Unnamed & default config
button-default-bg-color ?= #666;
button-default-color ?= #fff;
button-default-border-color ?= button-default-bg-color;

button-default-hover-bg-color ?= darken(button-default-bg-color, 25%);
button-default-hover-color ?= button-default-color;
button-default-hover-border-color ?= button-default-hover-bg-color;

button-default-active-bg-color ?= darken(button-default-bg-color, 50%);
button-default-active-color ?= button-default-color;
button-default-active-border-color ?= button-default-active-bg-color;

// Type - list of others
button-types-list ?= primary, danger;

// Type - config for listed types above
// -- Primary
button-primary-color ?= #fff;
button-primary-bg-color ?= #3338ff;
button-primary-border-color ?= button-primary-bg-color;

button-primary-hover-bg-color ?= darken(button-primary-bg-color, 25%);
button-primary-hover-color ?= button-primary-color;
button-primary-hover-border-color ?= button-primary-hover-bg-color;

button-primary-active-bg-color ?= darken(button-primary-bg-color, 50%);
button-primary-active-color ?= button-primary-color;
button-primary-active-border-color ?= button-primary-active-bg-color;

// -- Danger
button-danger-color ?= #fff;
button-danger-bg-color ?= #f5372b;
button-danger-border-color ?= button-danger-bg-color;

button-danger-hover-bg-color ?= darken(button-danger-bg-color, 25%);
button-danger-hover-color ?= button-danger-color;
button-danger-hover-border-color ?= button-danger-hover-bg-color;

button-danger-active-bg-color ?= darken(button-danger-bg-color, 50%);
button-danger-active-color ?= button-danger-color;
button-danger-active-border-color ?= button-danger-active-bg-color;
```

### Init

```
button();
```

## License

  MIT
