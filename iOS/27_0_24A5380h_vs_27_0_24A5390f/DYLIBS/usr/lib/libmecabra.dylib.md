## libmecabra.dylib

> `/usr/lib/libmecabra.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26b9f4` | `0x26b520` | **`-0x4d4`** |
| `__TEXT.__cstring` | `0x16af0` | `0x16aab` | **`-0x45`** |
| `__DATA_CONST.__const` | `0x16898` | `0x16860` | **`-0x38`** |
| `__TEXT.__gcc_except_tab` | `0x1a7b0` | `0x1a790` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0xce80` | `0xce60` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x13e0` | `0x13f8` | **`+0x18`** |

### Other Changes

```diff

-1151.0.0.0.0
+1154.0.0.0.0

-  Functions: 11152
-  Symbols:   1094
-  CStrings:  4425
+  Functions: 11145
+  Symbols:   1095
+  CStrings:  4423
Symbols:
+ _dispatch_block_cancel
+ _dispatch_block_create
+ _dispatch_block_wait
- _MecabraContextAddStringContext
- _MecabraContextSetRightContextFromString
CStrings:
- "unique_lock::lock: already locked"
- "unique_lock::lock: references null mutex"
```
