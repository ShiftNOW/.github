## Available Workflows

### Test Node

Clone Repo, Install NPM dependencies, build, lint, and run CI tests, according to ShiftNOW conventions.

Requirements:

- Must be Node `>=17`
- Must have a `build` `npm` script, that asserts the build can be performed successfully.
- Must have a `check` `npm` script, that will run all linting and styling checks
- Must have a `test:ci` `npm` script, that will run all tests that are desired to be run, as part of CI.
