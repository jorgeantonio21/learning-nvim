# NVim Command Lessons (NVChad-Friendly)

This repository is a command-by-command Neovim practice workbook.
Each lesson focuses on one Vim command and follows a beginner-to-expert progression.

## Structure

Each command folder contains:

- `goals.md` - what to learn and success criteria
- `drills.md` - warm-up, constraint, and speed drills
- `applied.md` - realistic editing tasks
- `evaluation.md` - self-check and scorecard
- `nvchad.md` - NVChad-specific guidance

## How To Use

1. Pick one command folder.
2. Read `goals.md` first.
3. Run drills in `drills.md`.
4. Do the scenario in `applied.md`.
5. Grade yourself in `evaluation.md`.
6. Review `nvchad.md` and repeat once with NVChad tooling if useful.

Recommended pace: 1-3 command lessons per day.

## Naming Notes

Most folders are literal command names.
Some commands use aliases due to filesystem constraints:

- Uppercase/lowercase collisions:
  - `A` -> `A_upper`
  - `E` -> `E_upper`
  - `F{char}` -> `F{char}_upper`
  - `T{char}` -> `T{char}_upper`
  - `gu` -> `gu_lower`
  - `I` -> `I_upper`
  - `N` -> `N_upper`
  - `O` -> `O_upper`
  - `P` -> `P_upper`
  - `R` -> `R_upper`
  - `V` -> `V_upper`
  - `X` -> `X_upper`
  - `ZZ` -> `ZZ_write_quit`
- Slash-based names:
  - `/` -> `SEARCH_SLASH`
  - `?` -> `SEARCH_QUESTION`
  - `:%s///g` -> `:%s-slash-slash-slash-g`

See `INDEX.md` for the full mapping summary.
