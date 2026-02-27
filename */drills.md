# Daily Exercises for *

## Practice Buffer
```text
EX-01 bug_id=42 status=open
EX-02 bug_id=17 status=closed
EX-03 BUG_ID=42 status=stale
EX-04 bug_id=99 status=open
EX-05 bugfix_pending=true
EX-06 user_bug_count=3
EX-07 status=open bug_id=42
EX-08 bug-id=42
EX-09 debug_mode=false
EX-10 done
```

## Exercise List
1. `/EX-01` find `bug_id=42` with `*`.
2. Move to next match and change `open` to `triaged`.
3. Skip uppercase mismatch intentionally, then target exact pattern again.
4. Find `status=open` matches and edit only first two.
5. Find token `bug` occurrences and count true matches vs false positives.
6. Navigate result set forward/backward using `n`/`N`.
7. Replace `bugfix_pending` value after finding key.
8. Locate `bug-id=42` separately and normalize to `bug_id=42`.
9. Turn highlight off/on once (`:set hlsearch` context).
10. Finish by finding `done` in minimum keystrokes.
