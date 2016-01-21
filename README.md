# JavaScript-TDD-Creating--own--plugin

JavaScript Test Driven Development approach:
--Utility Library--

Plugin to be used in JavaScript. Provides the following functionalities:

Array methods:

    first, return the first element in an array.
    last, return the last element in an array.
    without, return a new array that does not contain the value passed to it.
    range, return an array of values starting at 0 when a single number is supplied. If two arguments are supplied, returns an array of values that start with the first argument and ends with the second value.
    lastIndexOf, return the last index of the supplied value.
    sample, return a single value from an array when no argument is supplied. Return an array of multiple, non-repeated elements when a quantity is supplied.

Object and object collection methods:

    findWhere, return the first object with properties that match the supplied object. If no objects match all the supplied properties, undefined is returned.
    where, return an array of all objects with properties that match the supplied object.
    pluck, return an array of the values that match the supplied key from a collection of objects.
    keys, return an array of the keys from an object.
    values, return an array of the values from an object.
    extend, takes two or more objects, taking the properties and values from the last argument and adding them to the argument before it. Object extensions occur recursively from last argument to first. The first argument ends up being modified to include all properties and values from the other objects passed in.
    pick, return a new object with the passed in properties taken from the old object. Accepts one or more arguments.
    omit, return a new object with any passed in properties omitted.
    has, return true when the property passed in exists, false if it doesn't.


