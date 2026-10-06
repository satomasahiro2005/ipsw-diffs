## ControlCenterUI

> `/System/Library/PrivateFrameworks/ControlCenterUI.framework/ControlCenterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbb590` | `0xbb550` | **`-0x40`** |
| `__DATA.__data` | `0x3a80` | `0x3a50` | **`-0x30`** |
| `__DATA_DIRTY.__data` | `0xe60` | `0xe80` | **`+0x20`** |
| `__DATA.__common` | `0x30` | `0x28` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x6958` | `0x6950` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2d68` | `0x2d70` | **`+0x8`** |

### Other Changes

```diff

-704.2.2.0.0
+704.2.3.0.0
Functions:
~ -[CCUIMainViewController dealloc] : 156 -> 92
```
