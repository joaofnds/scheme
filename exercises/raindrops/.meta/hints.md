## Track Specific Notes

## Running and testing your solutions

### Overview


* Start a REPL either in your favorite editor or from
the command line\.
* Type `(load "raindrops.scm")` at the prompt\.
* Test your code by calling `(test)` from the REPL\.
* Develop the solution in `raindrops.scm` and reload as you go\.

### Testing options

You can see more or less information about
failing test cases an by passing additional arguments to the
procedure `test`\.
To see the failing input call `(test 'input)` and to see the input and output together call `(test 'input 'output)`\.