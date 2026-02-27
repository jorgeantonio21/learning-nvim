# Drills for c{motion}

## Setup (4 min)
1. Paste a block with mixed identifiers, quoted strings, and parentheses/braces.
2. Add at least 15 lines so you can repeat the same structure multiple times.
3. Place the cursor at 5 different starting points before beginning.

## Accuracy Drill (10 min)
1. Apply 'c{motion}' to 25 targets where the changed region is different each time.
2. After each change, verify exactly what text was replaced (no extra deletions).
3. Use `.` to repeat when possible and note where repeat is not appropriate.

## Boundary Drill (10 min)
1. Intentionally run 'c{motion}' at start, middle, and end of line contexts.
2. Test counts when supported (for example `2c{motion}`) and compare boundaries.
3. Run one pass where you cannot use backspace in Insert mode.

## Mastery Drill (6 min)
1. Refactor a small snippet using only 'c{motion}' plus motions and `.`.
2. Goal: complete in 3 passes with decreasing keystrokes.
3. Final pass must have zero undo operations.
