[![Build Status](https://travis-ci.org/ng-wei/tiny-scheme.svg?branch=master)](https://travis-ci.org/ng-wei/tiny-scheme)
# tiny-scheme

no description    

## Design:

![design](doc/tiny-scheme.png)

## Installation


    $ lein uberjar

## Usage


    $ java -jar target/uberjar/tiny-scheme-0.1.0-standalone.jar

## Examples

    ;; numeric operation
    tiny-scheme.core >> (+ 1 2)
    3
    tiny-scheme.core >> (- 2 2)
    0
    tiny-scheme.core >> (* 2 3 4)
    24
    tiny-scheme.core >> (mod 3 4)
    3

    ;; variable definition
    tiny-scheme.core >> (define x 5)
    ok
    tiny-scheme.core >> x
    5

    ;; function 
    tiny-scheme.core >> (define (f x y) (+ x y))
    ok
    tiny-scheme.core >> (f 1 2)
    3

    ;; pair

    ;; list

    ;; if

    ;; lambda

    ;; bool

### Bugs

...

## License

Copyright © 2016 

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
