## Day 2 Questions

1. Create an array containing the following strings: `"zebra", "giraffe", "elephant"`.
    - ["zebra", "giraffe", "elephant"]

1. Save the array you created above to a variable `animals`.
    - animals = ["zebra", "giraffe", "elephant"]

1. Using the array `animals`, how would you access `"giraffe"`?
    - animals[1]

1. How would you add `"lion"` to the `animals` array?
    - animals << "lion"

1. Name and describe two additional array methods:
    - `.take` will return the first *n* elements in the array.  
        - arr = [1, 2, 3, 4, 5]
        - arr.take(2)  # => [1, 2]
    - `.at(index)` will return element at specified index
        - arr.at(3) # => 4    

1. What are the boolean values in Ruby?
    - a boolean will return a true or false value for a logical statement 

1. In Ruby, how would you evaluate if `2` is equal to `25`? What is the result of this evaluation?
    - 2 == 25
    - false

1. In Ruby, how would you evaluate if `25` is greater than `2`? What is the result of this evaluation?
    - 25 > 2
    - true