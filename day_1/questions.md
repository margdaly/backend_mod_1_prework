## Day 1 Questions

1. How would you print the string `"Hello World!"` to the terminal?

    p '"Hello World!"'


1. What character is used to indicate comments in a ruby file?

    # comment

1. Explain the difference between an integer and a float?

    An integer is a whole number including zero and negatives, while a float is a number with decimals.

1. In the space below, create a variable `animal` that holds the string `"zebra"`

    animal = "zebra"

1. How would you print the string `"zebra"` using the variable that you created above?

    p animal

1. What is interpolation? Use interpolation to print a sentence using the variable `animal`.
    Interpolation lets you insert variable values into a string using placeholders #{} for the information. 
    p "A #{animal} is fast and striped."

1. What method is used to get input from a user?
    the 'gets' method

1. Name and describe two common string methods:
    -string#gsub! This will substitute one section or all of the string with your replacement string. The ! will permentaly change your string.  
    s = "margdaly"
    s.gsub!(/daly/, 'aret')
    p s   # => 'margaret'
    -string#capitalize This will capitalize the first character in a string and downcase all other characters.
    s = 'margaret'
    p s.capitalize   # => 'Margaret'

