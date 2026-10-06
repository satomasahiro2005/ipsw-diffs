## AppleIDSetupDaemon

> `/System/Library/PrivateFrameworks/AppleIDSetupDaemon.framework/AppleIDSetupDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b52c0` | `0x1b62d4` | **`+0x1014`** |
| `__TEXT.__eh_frame` | `0x16cd8` | `0x16dc8` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0x9a4f` | `0x9b0f` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x5d8` | `0x558` | **`-0x80`** |
| `__DATA_DIRTY.__objc_data` | `0x210` | `0x290` | **`+0x80`** |
| `__AUTH.__data` | `0xf10` | `0xee0` | **`-0x30`** |
| `__DATA.__data` | `0x1b00` | `0x1b30` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x878` | `0x8a8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x6450` | `0x6468` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x1514` | `0x1520` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0xa9c` | `0xaa8` | **`+0xc`** |
| `__TEXT.__constg_swiftt` | `0x1e28` | `0x1e30` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x56c` | `0x570` | **`+0x4`** |

### Other Changes

```diff

-124.0.0.0.0
+125.0.0.0.0

-  Functions: 4017
+  Functions: 4025

-  CStrings:  752
+  CStrings:  755
Symbols:
+ ___swift_closure_destructor.72Tm
- ___swift_closure_destructor.71Tm
CStrings:
+ "Failed to surface store account for sign-in progress UI: %@"
+ "No store account available in sign-in model to surface for progress UI"
+ "Surfaced store account for sign-in progress UI"
```
