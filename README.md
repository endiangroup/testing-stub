# Let's build a tester!

## Requirements

- It gathers test functions ready to execute
	- hint: `require(process.argv[2])`
- It reports test failures 
	- with a stack trace
	- with the test name
	- hint: create an interface around `console.log` and `console.error`
- It reports test passes
	- with the test name
- It reports a summary of passes and failures for a test run
- It logs a continuously inreasing count of passes and failures to disk

## Get started

- Run `yarn watch` to start the test watcher
- There are stub tester and tester tests in the `./src` directory
