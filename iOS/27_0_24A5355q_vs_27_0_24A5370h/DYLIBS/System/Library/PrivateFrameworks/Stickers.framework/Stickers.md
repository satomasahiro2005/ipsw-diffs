## Stickers

> `/System/Library/PrivateFrameworks/Stickers.framework/Stickers`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91bc8` | `0x92324` | **`+0x75c`** |
| `__TEXT.__oslogstring` | `0x1fa9` | `0x2009` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x4e70` | `0x4e38` | **`-0x38`** |
| `__AUTH_CONST.__const` | `0x2f90` | `0x2fb8` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x804` | `0x814` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2308` | `0x2300` | **`-0x8`** |

### Other Changes

```diff

-84.0.0.0.0
+85.0.0.0.0

-  Functions: 2837
+  Functions: 2838

-  CStrings:  306
+  CStrings:  307
CStrings:
+ "Representation %s has stale byteCount cache (recorded=%ld, actual=%ld)"
+ "Skipped %ld of %ld stickers that failed to decode"
- "Could not convert fetched stickers: %@"
```
