# Daily Exercises for :%s///g

## Practice Buffer
```text
EX-01 color=blue
EX-02 color=blue
EX-03 color=red
EX-04 colour=blue
EX-05 user_name=john
EX-06 username=jane
EX-07 path=/tmp/app
EX-08 path=/tmp/log
EX-09 TODO fix color
EX-10 done
```

## Exercise List
1. Replace `color=blue` with `color=green` where intended.
2. Keep `colour=blue` unchanged.
3. Replace key `user_name` with `account_name` only once.
4. Update `/tmp` prefix to `/var/tmp` for both path lines.
5. Replace `TODO` with `DONE` only on EX-09.
6. Run one global substitution and verify total affected matches.
7. Run one confirmed substitution (accept some, reject some).
8. Undo the previous substitution and rerun with tighter pattern.
9. Normalize remaining `blue` to `green` without touching words like `blueprint`.
10. End with all desired replacements and zero collateral edits.
