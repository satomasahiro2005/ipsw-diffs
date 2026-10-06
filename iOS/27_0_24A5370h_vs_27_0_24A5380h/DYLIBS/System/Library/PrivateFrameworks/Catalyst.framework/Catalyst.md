## Catalyst

> `/System/Library/PrivateFrameworks/Catalyst.framework/Catalyst`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `—` | `0x6e0` | **`+0x6e0`** |
| `__TEXT.__text` | `0x5f238` | `0x5f8d0` | **`+0x698`** |
| `__AUTH.__data` | `0x5a0` | `—` | **`-0x5a0`** |
| `__DATA.__data` | `0x1868` | `0x1728` | **`-0x140`** |
| `__AUTH.__objc_data` | `0xf0` | `—` | **`-0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0x2440` | `0x2530` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0xa51` | `0xac3` | **`+0x72`** |
| `__TEXT.__eh_frame` | `0x1720` | `0x1768` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x2088` | `0x20b8` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x1288` | `0x12a8` | **`+0x20`** |
| `__DATA.__bss` | `0x950` | `0x960` | **`+0x10`** |
| `__TEXT.__const` | `0xe28` | `0xe38` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xac` | `0xb4` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xb8` | `0xc0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x10c` | `0x108` | **`-0x4`** |

### Other Changes

```diff

-21.0.0.0.0
+23.0.0.0.0

-  Functions: 2590
+  Functions: 2601

-  CStrings:  524
+  CStrings:  526
CStrings:
+ "%{public}@ is unable to archive closeError: %{public}@."
+ "%{public}@ is unable to unarchive closeError: %{public}@."
```
