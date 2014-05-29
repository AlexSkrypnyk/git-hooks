Useful git hooks
================

commit-msg
----------
Allows to reject incorrectly formatted commit messages. 

Shipped with self testing functionality to ease custom rules development.

Possible commits formats:
* [PRJ-123] Verb in past ending with a dot at the end.
* [PRJ, PRJ-123] Verb in past ending with a dot at the end.
* [PRJ-321, PRJ-123] Verb in past ending with a dot at the end.
* [PRJ] Verb in past ending with a dot at the end.
* Verb in past ending with a dot at the end.
* Verb in past ending with a dot at the end. Another sentence with dot.