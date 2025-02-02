# Unexpected undefined variable in ActionScript
This repository demonstrates a common error in ActionScript 3.0: unexpected undefined variable behavior.

The issue arises when accessing a variable declared outside the scope of a function. While seemingly correctly defined and assigned, the variable might show as undefined, leading to unexpected outcomes.  This issue is often subtle and can be difficult to debug.

## How to Reproduce
1. Clone this repository.
2. Open `bug.as` in an ActionScript editor (like FlashDevelop).
3. Run the file. You will observe unexpected output.
4. Examine `bugSolution.as` to see how the problem is resolved. 

## Solution
The solution typically involves a proper understanding of variable scopes and the appropriate use of `public`, `private`, or `internal` access modifiers. In this case, the variable's scope needs to be appropriately defined to be accessible by the function.