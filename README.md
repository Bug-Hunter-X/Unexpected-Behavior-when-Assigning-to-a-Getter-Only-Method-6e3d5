# Unexpected Behavior when Assigning to a Getter-Only Method in Ruby

This repository demonstrates a common pitfall in Ruby: attempting to modify the state of an object through a getter-only method.  The code in `bug.rb` shows how assigning a new value to a getter method will not update the object's internal state, leading to unexpected results. The solution demonstrates proper ways to achieve this.

## How to Reproduce

1. Clone the repository.
2. Run `ruby bug.rb`.
3. Observe that the output is unexpected: the value remains unchanged.