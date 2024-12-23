# Off-by-One Error in C While Loop

This repository demonstrates a common off-by-one error in C that can occur when using post-increment operators within loop conditions.  The `bug.c` file contains the erroneous code, and `bugSolution.c` provides the corrected version.

The error arises from a misunderstanding of how the post-increment operator (`i++`) works.  The value of `i` is used in the comparison *before* it's incremented. This subtle detail can lead to unexpected loop behavior.

The solution involves carefully considering the loop condition and ensuring it aligns with the intended number of iterations.