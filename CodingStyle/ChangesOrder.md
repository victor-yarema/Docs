# Commits order
This document describes recommended code changes order.
- Refactoring
  - Redundant content (delete)
    - Files
    - Code in files
    - Comments
      - Language specific documentation
      - Comments that state something that is well known (documented)
  - Ws (whitespace)
    - Trailing
    - Indentation
    - Multi ws blocks inside each line
  - Invert conditional statements to achieve *early exit* and decrease indentation
  - Spread code to multiple separate files (*single responsibility*)
- Implementation
