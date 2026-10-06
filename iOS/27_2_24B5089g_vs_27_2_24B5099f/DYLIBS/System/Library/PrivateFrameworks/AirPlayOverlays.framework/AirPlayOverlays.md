## AirPlayOverlays

> `/System/Library/PrivateFrameworks/AirPlayOverlays.framework/AirPlayOverlays`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8710` | `0x8944` | **`+0x234`** |
| `__TEXT.__cstring` | `0x271` | `0x2b1` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x1308` | `0x1338` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x210` | `0x230` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x51c` | `0x534` | **`+0x18`** |
| `__AUTH.__data` | `0x328` | `0x338` | **`+0x10`** |
| `__DATA.__data` | `0x358` | `0x368` | **`+0x10`** |
| `__TEXT.__const` | `0x32c` | `0x33c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x308` | `0x318` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-807.2.0.0.0
+807.4.0.0.0

-  Functions: 264
+  Functions: 269

-  CStrings:  33
+  CStrings:  35
CStrings:
+ ", should-borrow: "
+ "Remote airplay overlay is tapped on notification identifier %@"
+ "interactionShouldBorrow"
- "Remote airplay overlay is tapped on notification identifier %s"
```
