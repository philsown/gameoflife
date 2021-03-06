# Game of Life OOP PHP

An implementation of [Conway's Game of Life](http://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) in OOP PHP.

With help from Laracast's [Code Katas](http://laracasts.com/series/code-katas-in-php) and [Gulp File](https://laracasts.com/lessons/how-to-trigger-tests-on-save).

## Requirements

1. PHP 5.4+
2. [Node & NPM](http://nodejs.org)
3. [Composer](https://getcomposer.org)

## Installation

```bash
$ git clone https://github.com/philsown/gameoflife.git
$ cd GameOfLife
$ npm install
$ composer install
```

## Tests

```bash
$ vendor/bin/phpspec run
```

### Automating Tests

```bash
$ gulp
```

I like to run it silently so I only see the test output.

```bash
$ gulp --silent
```

## Feedback

I did this as an exercise in OOP, phpspec, and programming in general. Feedback is invited. Send any to philsown at gmail or create an issue. Feel free to fork. Thanks.
