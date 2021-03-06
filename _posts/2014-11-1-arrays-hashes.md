---
layout: post
title: Ruby Arrays and Hashes
---

Ruby is an object-oriented language, which means that it is composed of objects that interact with each other. Ruby objects can be anything from integers to characters, or hashes and arrays containing multiple other objects. In this post, I will be focusing on hashes and arrays, otherwise known as 'container objects' due to the fact that  both of these objects act as collections of objects, sort of like storage units for other objects.

Arrays are a type of Ruby container object which inherently include a consecutive numerical index. Any object can be stored in an array - even other arrays! The array's index is used to reference and access certain elements in the array, without having to rename the referenced variable directly. This index starts at array[0] (the syntax for array indices being array[int_position)]) - representing the first object in the array - and the last object in the array can be found using array[-1]. The array's position index can be changed by adding or removing an object from the array, but the array's index is only as long as the length of the current array.

Hashes are very similar to arrays in the sense that they are also container objects which are used to store and access other objects; however, hashes store pairs of objects in the format of a declared key and a value. In other words, the numbered index in arrays are replaced by specifically named keys in a hash - which refer to other declared values. Values can be received in a program by referencing the value's specific key.

Arrays and hashes are comparable in the sense that they both use keys to access specific variables: the only difference being that array keys are inherently set to consecutive integers, whereas hash values are specifically assigned keys. Arrays are better suited for use as strictly storage units for related information, or information that you wish to access or iterate through all together. Hashes are great for more relational purposes, or when you have a certain value , or list of values, that you want specifically to refer to other values.

Finally, hashes and arrays have use Ruby syntax:


        Array = [int, [other_array], "string"]


        Hash = {"key" => "value", "other_key" => "other_value"}


Good luck with this topic! Hashes are still one of the more confusing topics I have come across in Ruby so far.
