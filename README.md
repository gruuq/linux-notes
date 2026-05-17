# Vim Notes

## Vim Modes

Vim is a mode-based editor. You always work in different modes:

| Mode | What it does | How to enter |
|---|---|---|
| NORMAL | navigate, delete, copy, commands | `Esc` |
| INSERT | write text | `i`, `a`, `I`, `A` |
| VISUAL | select text | `v`, `V` |
| COMMAND | run commands (:w, :q, etc) | `:` |

---

## How Vim works

- You start in NORMAL mode
- Press `i` → go to INSERT mode (write text)
- Press `Esc` → go back to NORMAL mode
- Use `:` for commands like save/exit

---

## Movement

| Key | Action |
|---|---|
| `h` | move left |
| `j` | move down |
| `k` | move up |
| `l` | move right |

---

## Word Navigation

| Key | Action |
|---|---|
| `w` | next word start |
| `b` | previous word start |
| `e` | end of word |

---

## Insert Mode

| Key | Action |
|---|---|
| `i` | insert before cursor |
| `a` | insert after cursor |
| `I` | insert at start of line |
| `A` | insert at end of line |

---

## Copy / Paste

| Key | Action |
|---|---|
| `y` | copy (yank) |
| `p` | paste |

---

## Visual Mode

| Key | Action |
|---|---|
| `v` | visual select |
| `V` | select whole line |

---

## Delete

| Key | Action |
|---|---|
| `d` | delete |
| `dd` | delete line |
| `dw` | delete word |

---

## Undo / Redo

| Key | Action |
|---|---|
| `u` | undo |
| `Ctrl + r` | redo |

---

## Search

| Key | Action |
|---|---|
| `/test` | search for "test" |

---

## Save / Exit

| Command | Action |
|---|---|
| `:w` | save |
| `:q` | quit |
| `:wq` | save and quit |
| `:q!` | quit without saving |

---

## Mode Switching Summary

| Key | Action |
|---|---|
| `Esc` | NORMAL mode |
| `i` | insert before cursor |
| `a` | insert after cursor |
| `I` | insert at start of line |
| `A` | insert at end of line |
| `v` | visual mode |
| `V` | visual line mode |
| `:` | command mode |

---

## Notes

- Vim is fully mode-based
- Most actions happen in NORMAL mode
- `Esc` always returns you to NORMAL mode
- Practice is more important than memorizing
