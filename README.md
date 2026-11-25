# Vimium C Configuration

A streamlined, ergonomic **Vimium C** configuration built for fast keyboard-driven browsing with zero conflicts against native Chrome (`Ctrl`) or `whkdrc` / Komorebi (`Alt`) shortcuts.

## Design Philosophy
- **Zero `Ctrl` / `Alt` overrides:** Leaves all native browser (`Ctrl`) and window-manager (`Alt`) shortcuts untouched.
- **Ergonomic split layout:** Right hand handles scrolling and tab switching on the home row; left hand handles undo, close, copy, and paste (`z x c v`).
- **Home-row link hints:** `f` / `F` hints use only `asdfghjkl` so your fingers stay anchored on the home row.
- **Selective site pass-through:** Keeps browser navigation (`h`/`l`, `x`, `o`) active on web apps like YouTube and Gmail while passing through only the single-letter shortcuts those sites use natively.

---

## Key Mappings

### Right Hand — Home Row (Scroll & Tabs)
| Key | Action |
| :--- | :--- |
| `j` / `k` | Scroll down / up (`100px` @ `120ms`) |
| `J` / `K` | Scroll half-page down / up |
| `h` / `l` | Previous tab / Next tab |
| `H` / `L` | History back / forward |
| `gg` / `G` | Scroll to top / bottom |
| `,` | Jump to previously visited tab |

### Left Hand — `ZXCV` (Undo, Close, Copy, Paste)
| Key | Action |
| :--- | :--- |
| `z` | Restore closed tab |
| `x` | Close current tab (focuses previous/near tab) |
| `c` | Copy current URL |
| `v` / `V` | Open copied URL in current / new tab |

### Single-Key First-Letter Actions
| Key | Action |
| :--- | :--- |
| `f` / `F` | Open link hints in current / new tab |
| `r` / `R` | Reload / Hard reload |
| `o` / `O` | Open Vomnibar in current / new tab |
| `t` / `T` | Create new tab / Search open tabs |
| `b` / `B` | Search bookmarks in current / new tab |
| `/` | Enter find mode (`n` next, `N` previous) |

### `g` Prefix Jumps
| Key | Action |
| :--- | :--- |
| `gi` | Focus first text input |
| `g0` / `g$` | Go to first / last tab |
| `gf` / `gF` | Select next frame / main frame |

### `Space` Leader (Toggles & Modes)
| Key | Action |
| :--- | :--- |
| `<space>p` | Pin / unpin tab |
| `<space>m` | Mute / unmute tab |
| `<space>d` | Duplicate tab |
| `<space>x` | Close other tabs |
| `<space>v` | Enter visual mode |
| `<space>h` | Search browsing history in new tab |
| `<space>,` / `<space>.` | Scroll left / right |
| `i` / `<space>i` | Enter insert mode (`Esc` to exit) |
| `?` | Show help dialog |

---

## Custom Vomnibar Search Shortcuts
Press `o` (or `O`), type a prefix + space + query, and hit `Enter`:
- `g` — Google
- `y` / `yt` — YouTube
- `gh` — GitHub
- `w` — Wikipedia
- `d` — DuckDuckGo
- `r` — Reddit
- `gm` — Google Maps
- `tr` — Google Translate
- `mdn` — MDN Web Docs
- `math` — Built-in calculator (or type math directly)

---

## Installation
1. Open **Vimium C Options** in Chrome.
2. Scroll to the bottom and click **Import Settings**.
3. Select `vimium_c.json` from this repository.
