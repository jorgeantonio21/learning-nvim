# Daily Exercises for T{char}

## Practice Buffer
```text
EX-01 a,b,c,d,e,f,g
EX-02 key:value;next:value
EX-03 (one)(two)(three)
EX-04 id=abc-123-xyz
EX-05 x_y_z_q_r
EX-06 a1b2c3d4e5
EX-07 [red][green][blue]
EX-08 foo.bar.baz
EX-09 <h1>Title</h1>
EX-10 end-marker
```

## Exercise List
1. `/EX-01` use `T{char}` to land on `d` directly.
2. `/EX-02` land on the second `:` then delete to next `;`.
3. `/EX-03` jump to `(` before `three` and change inner word.
4. `/EX-04` jump to second `-` and replace suffix.
5. `/EX-05` hop separators and uppercase `z` token.
6. `/EX-06` land on `4` and change to `9`.
7. `/EX-07` jump to `[` before `blue` and delete bracket pair content.
8. `/EX-08` navigate by `.` and change `bar` to `core`.
9. `/EX-09` jump to `>` before `Title` and replace text.
10. `/EX-10` do one precise jump and return without search commands.
