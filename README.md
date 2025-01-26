# Unexpected Instance Variable Modification in Ruby

This repository demonstrates a common pitfall in Ruby related to modifying instance variables.  When you don't define explicit setter methods, Ruby's implicit behavior might not be what you expect.

The `bug.rb` file shows how attempting to assign a value to an instance variable using the `=` operator will not correctly modify the underlying instance variable. The `bugSolution.rb` demonstrates the proper use of `instance_variable_set` to correctly change the value.