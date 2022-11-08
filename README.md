# Tips to Writing Safe Code

## General
* Use enums as error types (in zig, just use the `error` abstraction).
* Be pessimistic by default (i.e., expect functions to fail).
* Initialize variables before use
* Do not ignore compiler warnings
* Always check return values
* Check input values, (i.e., never trust a stranger)
* Always give variables descriptive names (no stupid i, j, k... Even for counters). Variable names must reflect the meaning associated with the type.
* Implement only what is needed. If it's not needed, don't implement it for "later".
* Don't start with optimization as the goal
* Make functions very simple and short
* Test every functionality of a module
* A file is a module
* Detect and remove dead code
* Do not store long-lived references to pointers to stack memory.
