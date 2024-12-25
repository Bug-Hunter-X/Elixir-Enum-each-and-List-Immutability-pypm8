# Elixir Enum.each and List Immutability Bug

This example demonstrates a common misconception in Elixir: lists are immutable.  Attempting to modify a list inside an `Enum.each` loop does not change the original list.  The code in `bug.ex` shows this issue. The solution in `bugSolution.ex` provides the correct way to achieve the desired modification.

**To run the code:**

1. Ensure you have Elixir installed.
2. Save the code from `bug.ex` and `bugSolution.ex` into separate files.
3. Run `elixir bug.ex` and `elixir bugSolution.ex` from your terminal.