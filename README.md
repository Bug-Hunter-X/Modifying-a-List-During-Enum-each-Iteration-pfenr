# Modifying a List During Enum.each Iteration in Elixir

This example demonstrates a common error in Elixir when attempting to modify a list while iterating over it using `Enum.each`.  The code intends to remove the element `3` from the list, but due to Elixir's immutability, this does not work as expected.