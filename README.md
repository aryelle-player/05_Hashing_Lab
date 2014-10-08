05_Hashing_Lab
==============

Implement a hash table in C++

Requirements
------------

1. `keyExists`, `find`, `remove`, and `size` should all be O(1)
2. `add` should be reasonably fast. Use linear probing to find an open slot in the hash table. This will be O(1), on average, except when `grow` is called.
3. `grow` should be O(n)
4. Do not leak memory


Reading
=======
"Open Data Structures," Chapter 5, except for 5.2.3. http://opendatastructures.org/ods-cpp/5_Hash_Tables.html

Questions
=========

#### 1. Which of the above requirements work, and which do not? For each requirement, write a brief response.

1. TODO
2. TODO
3. TODO
4. TODO

#### 2. I decided to use two function (`keyExists` and `find`) to enable lookup of keys. Another option would have been to have `find` return a `T*`, which would be `NULL` if an item with matching key is not found. Which design do you think would be better? Explain your reasoning. You may notice that the designers of C++ made the same decision I did when they designed http://www.cplusplus.com/reference/unordered_map/unordered_map/

Having the two funtions 'keyExists' and 'find' would be better because with one returning a template and one returning a boolean, you can write a funtion easier given the option to search for keys and return different things depending on what is needed for that function. Having 'find' return a template rather than a pointer to that template would be better just so that its easier to access whats associated with that key.

#### 3. What is one question that confused you about this exercise, or one piece of advice you would share with students next semester?

TODO