# Drills for :%s

## Setup (4 min)
1. Create a 60-line file with repeated tokens and close variants.
2. Include punctuation-heavy and camelCase examples.
3. Keep one untouched copy block at file bottom for comparison.

## Pattern Drill (10 min)
1. Run ':%s' for 20 substitutions with increasing specificity.
2. Start broad, then tighten patterns to avoid false matches.
3. Verify changed line counts after each substitution.

## Confirmation Drill (9 min)
1. Practice both global replacement and selective confirmation flows.
2. Reject at least 5 matches deliberately to train judgment.
3. Undo entire substitution once, then redo with corrected pattern.

## Mastery Drill (7 min)
1. Refactor naming across the file with minimal collateral changes.
2. Constraint: no manual per-line edits for target token changes.
3. Final check: diff against untouched copy block.
