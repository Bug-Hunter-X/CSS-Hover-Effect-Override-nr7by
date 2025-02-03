# CSS Hover Effect Override Bug

This repository demonstrates a common CSS issue where a hover effect is unintentionally overridden by a more specific selector. The `bug.css` file contains the buggy code, while `bugSolution.css` provides the corrected version.  The problem arises from an incorrectly placed style that overrides the intended hover effect.

## Bug Description

A simple hover effect on an element is expected to change its background color. However, due to a more specific class selector being applied, the hover effect is never seen.