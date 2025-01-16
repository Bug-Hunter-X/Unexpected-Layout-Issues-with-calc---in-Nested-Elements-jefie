# Unexpected Layout Issues with calc() in Nested Elements

This repository demonstrates a common CSS bug involving the `calc()` function and unexpected layout behavior in nested elements.

**Bug:** Incorrect usage of `calc()` within nested elements can lead to inaccurate width calculations if the parent element's width is not explicitly set.

**Solution:** Ensuring the parent element has an explicitly defined width resolves the issue. Alternatively, using viewport units (`vw`) or other appropriate units can prevent the problem.

The `bug.css` file contains the buggy code. The `solution.css` shows the corrected code.