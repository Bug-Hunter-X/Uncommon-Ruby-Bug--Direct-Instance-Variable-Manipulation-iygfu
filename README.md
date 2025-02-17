# Uncommon Ruby Bug: Direct Instance Variable Manipulation

This repository demonstrates a subtle bug in Ruby related to directly manipulating instance variables using `instance_variable_set`.

## The Bug
The `bug.rb` file shows how directly modifying instance variables outside the defined methods can bypass the class's intended behavior and lead to unexpected results.

## The Solution
The `bugSolution.rb` file provides a solution using accessor methods to interact with instance variables, which improves code maintainability and prevents unintended side effects.