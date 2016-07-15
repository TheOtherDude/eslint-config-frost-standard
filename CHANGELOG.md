# 3.0.0
## Breaking changes
 * **Switched** to `eslint@3.x`

## New Rules

 * **Added** rule to error on a `describe.only` or `describeComponent.only` in tests
 * **Added** rule to warn on a `describe.skip` or `it.skip` (with `--fix` option 😄 )
 * **Added** rule to error on an `it('pending test')` with no test
 * **Added** rule to error on a global `it()`(not within a test suite)
 * **Added** rule to error if the `done` callback isn't called when it's defined.

# 2.1.0
* Added camelcase property for variables
* Added max-len property of 120 chars per line
