# Tailwind CSS Bug: Unexpected Behavior with `@apply` and Custom Directives

This repository demonstrates an uncommon bug encountered when using Tailwind CSS's `@apply` directive in conjunction with custom directives within a nested component structure. The issue manifests as unexpected styling inconsistencies or complete failure of the `@apply` directive to function as expected.

## Bug Description

The bug primarily involves the unpredictable behavior of `@apply` when dealing with complex component nesting and custom directives.  The expected behavior is that the styles defined within the custom directives are applied correctly via the `@apply` directive. However, in certain scenarios, the styles are either not applied, partially applied, or applied inconsistently leading to unpredictable visual results.

## Reproduction Steps

1. Clone this repository.
2. Install the project dependencies using `npm install`.
3. Run the development server (command may vary based on your setup).
4. Observe the unexpected styling within the application.

## Solution

A possible solution and workaround can be found in the `bugSolution.js` file.