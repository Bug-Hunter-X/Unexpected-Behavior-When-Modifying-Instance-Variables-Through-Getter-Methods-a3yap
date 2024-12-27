# Ruby: Unexpected Instance Variable Modification

This example demonstrates a subtle issue in Ruby regarding instance variables and getter methods.  Attempting to modify an instance variable through its getter method will not change the internal state of the object. This is a common pitfall for developers unfamiliar with Ruby's behavior. The code demonstrates this issue and shows a proper way to modify the instance variable.

The `bug.rb` file shows the problem, and `bugSolution.rb` shows the corrected version.