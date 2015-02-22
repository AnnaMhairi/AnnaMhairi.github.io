---
layout: post
title: Enumerable#map
---
Enumerable is an extremely useful Ruby module, or library of methods, that can be used across multiple classes - such as the Array class or Hash class. The Enumerable module enables programmers to cycle through various elements in collection objects like arrays and hashes, and perform various actions to each object within the collection. These methods can produce much simpler versions of other looping options, and can also perform more specific repeated tasks in an elegant way.

The Enumerable method I would like to focus on in this post is Enumerable#map. To preface my explanation of this method, here is a simple example of how it works:

    arr = [1,3,5] </p><p>arr.map { |n| n * n }</p><p>
    returns the new array [1, 9, 25]

The enumerable map method, as seen above, enables the creation of a new array which has been modified in a way specified by the programmer. It can either be thought of as performing a certain action and collecting the results, as in the similar #collect method, or as "re-mapping" the original object (|n| in our example), and producing a new array of changed versions of the original object. The new array is filled with whatever is returned by the block each time it runs - for each object in the collection object.

This method and the concept of enumerators can be intimidating at first, but the methods in the Enumerable module are fairly intuitive and extremely useful once you realize that they are simply a form of going through each element in a collection object and performing a certain task to each object.

