
## Py-1

- Boolean and Logical Operations
- List
    - append(), insert(), extend()
    - pop(), count(), index()
- Set
    - Unordered, Mutable, Iterable, but no Duplicate items.
    - Set does not support Indexing & Subscripting
- Dictionary
    - Unordered, Mutable, Indexed
    - Access value based on key (not based on index)
    - Looping through dictionary_keys, dictionary_values, both.
    - Adding and Updating data in dictionary
- Nested Dictionary
- Tuple
    - once created, it is Immutable.

## Py-2

- simple Function
- print() vs return
- function with Arguments
- function with Positional args and Keyword args
- for loop inside a function
- Lambda function
- Map function
    - syntax == map(function, iterables)
- Filter function
    - syntax == filter(function, iterables)
- Filter + Lambda
- Map + Lambda
- List Comprehension
    - List comprehension provides an easy way to display output in Lists.
    - It consists of Brackets[ ] containing an Expression(i*i), followed by a for loop (for i in lis). And then zero or more for/if clauses (if i%2==0).

## Py-3

- List Iterables vs Iterators:
    - Iterables: capable of accessing a sequence of items.
    - Iterator: iter() ...(it is an in-built function)
    - to retrive the items, next() function is used
    - using for_loop to retrive remaining_items or range_of_items
    - exception handling for Stop_Iteration_Error
- Generator:
    - "yield" keyword retrives all the items from the generator
    - "next()" function can be used to iter through the generator
- Iterator and Generator application:
    - Generator: helps to write Fast and Compact code
    - Iterator: is memory efficient
    - Generator is also an Iterator. Generator inherits from the iterator.
- String Formatting
- Exception Handling:
    - try & except
    - try & else
    - try else & finally

