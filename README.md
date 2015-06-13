# Sassy-border

Sassy-border is Sass shorthand mixin for border property. 

Have you ever caught yourself thinking about declaring border property in one shorthand, like we do with `margin` and `padding`? I did :trollface:

## Documentation

Sassy-border [Official Documentation](http://skoks.github.io/sassy-border/)

## Usage

```
@include border(1px, solid, red); // Apply to all four borders
@include border(5px 0, solid, green); // vertical | horizontal
@include border(2px 3px 5px, solid, blue);  // border-top | horizontal | border-bottom
@include border(2px 1em 0 25px, dotted, pink); // border-top | border-right | border-bottom | border-left
```

## Installation

_Git_:

```
git clone git@github.com:skoks/sassy-border.git ./
```

_Bower_:

```
bower install sassy-border --save-dev
```
