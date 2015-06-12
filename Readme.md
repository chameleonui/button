
# button

Highly customisable buttons

## Requirements

| Prerequisite | Version | How to check | How to install |
| --- | --- | --- | --- |
| Node | v0.12.2 | `node -v`| [nodejs.org](https://nodejs.org/) |
| component | ~v0.19 | `component -V` | [component](https://github.com/componentjs/component) |
| stylus | v0.33 | `stylus -V` | [stylus](https://learnboost.github.io/stylus/) |

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
button-default-padding = (1/8) (1/2);
button-default-font-size = 16px;
button-default-font-weight = 400;
button-default-line-height = 1.5;
button-default-border-width = 1px;
button-default-border-radius = 0;
button-default-disabled-opacity = .65;

// Sizes -- list
button-sizes-list = small, large;

// Sizes -- config for listed sizes above
button-small-padding = 2px 8px;
button-small-font-size = 14px;
button-small-line-height = 18px;
button-small-border-radius = 0;

button-large-padding = 12px 24px;
button-large-font-size = 18px;
button-large-line-height = 24px;
button-large-border-radius = 0;


// Type - Unnamed & default config
button-default-bg-color = #666;
button-default-color = #fff;
button-default-border-color = button-default-bg-color;

button-default-hover-bg-color = darken(button-default-bg-color, 25%);
button-default-hover-color = button-default-color;
button-default-hover-border-color = button-default-hover-bg-color;

button-default-active-bg-color = darken(button-default-bg-color, 50%);
button-default-active-color = button-default-color;
button-default-active-border-color = button-default-active-bg-color;

// Type - list of others
button-types-list = primary, danger;

// Type - config for listed types above
// -- Primary
button-primary-color = #fff;
button-primary-bg-color = #3338ff;
button-primary-border-color = button-primary-bg-color;

button-primary-hover-bg-color = darken(button-primary-bg-color, 25%);
button-primary-hover-color = button-primary-color;
button-primary-hover-border-color = button-primary-hover-bg-color;

button-primary-active-bg-color = darken(button-primary-bg-color, 50%);
button-primary-active-color = button-primary-color;
button-primary-active-border-color = button-primary-active-bg-color;

// -- Danger
button-danger-color = #fff;
button-danger-bg-color = #f5372b;
button-danger-border-color = button-danger-bg-color;

button-danger-hover-bg-color = darken(button-danger-bg-color, 25%);
button-danger-hover-color = button-danger-color;
button-danger-hover-border-color = button-danger-hover-bg-color;

button-danger-active-bg-color = darken(button-danger-bg-color, 50%);
button-danger-active-color = button-danger-color;
button-danger-active-border-color = button-danger-active-bg-color;
```

### Defining new button types

Append another button type to `button-types-list` list. In this case, will create Legendary button type.

```
// Type - list of others
button-types-list = primary, danger, legendary;
```
And add new set of variables with same type keyword.

```
// -- Legendary button type
button-legendary-color = #fff;
button-legendary-bg-color = #14B694;
button-legendary-border-color = button-legendary-bg-color;

button-legendary-hover-bg-color = darken(button-legendary-bg-color, 25%);
button-legendary-hover-color = button-legendary-color;
button-legendary-hover-border-color = button-legendary-hover-bg-color;

button-legendary-active-bg-color = darken(button-legendary-bg-color, 50%);
button-legendary-active-color = button-legendary-color;
button-legendary-active-border-color = button-legendary-active-bg-color;
```


### Init

```
button();
```

## Author(s)

Edgedesign s.r.o. – Tomas Kuba

## License

The MIT License (MIT)

Copyright © 2013 Edgedesign s.r.o.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
