# Type 'string[]' is not assignable to type 'string'
This repo demonstrates a common TypeScript error: assigning an array of strings to a variable expecting a single string.  The `greeter` function expects a single string, but it receives an array.  The solution involves adjusting the function or input to handle the array correctly.

## How to reproduce
1. Clone this repository.
2. Run `tsc bug.ts` to see the TypeScript compiler error.
3. Run `node bug.js` (after compilation) to see the runtime error (if the compiler error is ignored).