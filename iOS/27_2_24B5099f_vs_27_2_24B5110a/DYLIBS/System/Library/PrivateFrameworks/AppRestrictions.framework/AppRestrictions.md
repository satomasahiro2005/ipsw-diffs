## AppRestrictions

> `/System/Library/PrivateFrameworks/AppRestrictions.framework/AppRestrictions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10f20` | `0x11434` | **`+0x514`** |
| `__TEXT.__eh_frame` | `0x900` | `0x968` | **`+0x68`** |
| `__TEXT.__const` | `0x948` | `0x970` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x2b48` | `0x2b68` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x332` | `0x352` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x2d7` | `0x2f7` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x610` | `0x628` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x600` | `0x610` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2a8` | `0x2b4` | **`+0xc`** |
| `__DATA.__bss` | `0xd8` | `0xe0` | **`+0x8`** |
| `__DATA.__data` | `0x4c0` | `0x4c8` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x3b0` | `0x3b8` | **`+0x8`** |

### Other Changes

```diff

-22.2.2.0.0
+22.2.2.100.0

-  Functions: 421
+  Functions: 432
CStrings:
+ "%s: returning requiresPreflight FALSE as there's no highestPriorityPreflightSource"
+ "Updated highestPriorityPreflightSource source: %s"
- "%s: returning requiresPreflight FALSE as there's no activePreflightSource"
- "Updated activePreflightSource source: %s"
```
