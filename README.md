# Ruby Lookup Chain Exercise

## Activity 1

Examine the code in this repository and diagram the Object Model for a `Chair` instance.

## Activity 2

The `Chair` class has several superclasses and modules where Ruby can look for methods. At the bottom of the `chair.rb` file, a new instance of chair is created and the `chair_type` method is called on that instance. Your job is to comment out sections of the code in order to get `chair_type` to print each of the following:

1. "method"
1. "class"
1. "module"
1. "superclass"
1. "superclass's module"
1. "superclass's superclass"

## Wrap Up

* How does Ruby’s look up chain work? What is the order it checks things?
* What are three methods you can use to learn about where a built in Ruby method gets its components?
* Draw a diagram of where Ruby would look for the method ::new
