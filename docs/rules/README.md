# Rules

|recommended (level*)|fixable|rule|description|
|-|-|-|-|
|:heavy_check_mark: (error)|| [handle-done-callback](handle-done-callback.md) | enforces handling of callbacks for async tests
|:heavy_check_mark: (error)|| [max-top-level-suites](max-top-level-suites.md) | limit the number of top-level suites in a single file
|:heavy_check_mark: (error)|:wrench:| [no-async-describe](no-async-describe.md) | disallow async functions passed to describe
|:heavy_check_mark: (warn)|| [no-exclusive-tests](no-exclusive-tests.md) | disallow exclusive mocha tests
|:heavy_check_mark: (error)|| [no-exports](no-exports.md) | disallow exports from test files
|:heavy_check_mark: (error)|| [no-global-tests](no-global-tests.md) | disallow global tests
||| [no-hooks](no-hooks.md) | disallow hooks
||| [no-hooks-for-single-case](no-hooks-for-single-case.md) | disallow hooks for a single test or test suite
|:heavy_check_mark: (error)|| [no-identical-title](no-identical-title.md) | disallow identical titles
|:heavy_check_mark: (error)|:wrench:| [no-mocha-arrows](no-mocha-arrows.md) | disallow arrow functions as arguments to mocha globals
|:heavy_check_mark: (error)|| [no-nested-tests](no-nested-tests.md) | disallow tests to be nested within other tests
|:heavy_check_mark: (warn)|| [no-pending-tests](no-pending-tests.md) | disallow pending/unimplemented mocha tests
|:heavy_check_mark: (error)|| [no-return-and-callback](no-return-and-callback.md) | disallow returning in a test or hook function that uses a callback
||| [no-return-from-async](no-return-from-async.md) | disallow returning from an async test or hook
|:heavy_check_mark: (error)|| [no-setup-in-describe](no-setup-in-describe.md) | disallow calling functions and dot operators directly in describe blocks
|:heavy_check_mark: (error) || [no-sibling-hooks](no-sibling-hooks.md) | disallow duplicate uses of a hook at the same level inside a describe
|:heavy_check_mark: (warn)|| [no-skipped-tests](no-skipped-tests.md) | disallow skipped mocha tests
||| [no-synchronous-tests](no-synchronous-tests.md) | disallow synchronous tests
|:heavy_check_mark:(warn)|| [no-top-level-hooks](no-top-level-hooks.md) | disallow top-level hooks
||:wrench:| [prefer-arrow-callback](prefer-arrow-callback.md) | prefer arrow function callbacks (mocha-aware)
||| [valid-suite-description](valid-suite-description.md) | match suite descriptions against a pre-configured regular expression
||| [valid-test-description](valid-test-description.md) | match test descriptions against a pre-configured regular expression
|:heavy_check_mark: (error)|| [no-empty-description](no-empty-description.md) | Disallow empty test descriptions

*: level is defined in [index](../../index.js) file, `configs.recommended.rules` key
