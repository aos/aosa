# A Continuous Integration System

# Notes

- Automated
- Pulls source code from `git`
- Looks for tests in specified directories

# Structure of a CI system

Three components:
1. Observer - watches repo and notifies job dispatcher
2. Test job dispatcher - finds a test runner and gives it commit to test
3. Test runner - runs test
