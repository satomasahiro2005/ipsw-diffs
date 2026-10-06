## JetFoundation

> `/System/Library/PrivateFrameworks/JetFoundation.framework/JetFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa654` | `0xa498` | **`-0x1bc`** |
| `__TEXT.__cstring` | `0x175` | `0x145` | **`-0x30`** |
| `__TEXT.__eh_frame` | `0x3f0` | `0x3c0` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x348` | `0x318` | **`-0x30`** |
| `__TEXT.__const` | `0xc18` | `0xbf8` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x498` | `0x480` | **`-0x18`** |
| `__TEXT.__swift_as_cont` | `0x18` | `—` | **`-0x18`** |
| `__DATA.__data` | `0x110` | `0x108` | **`-0x8`** |
| `__DATA_DIRTY.__data` | `0x170` | `0x178` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x18` | `0x14` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x1c` | `0x18` | **`-0x4`** |

### Other Changes

```diff

-10.0.38.0.0
+10.0.42.0.0

-  Functions: 288
-  Symbols:   217
-  CStrings:  12
+  Functions: 275
+  Symbols:   214
+  CStrings:  11
Symbols:
+ _swift_retain_x24
- ___swift_async_cont_functlets
- __swift_implicitisolationactor_to_executor_cast
- _swift_task_switch
- _swift_willThrowTypedImpl
CStrings:
- "JetFoundation/Requirements.swift"
```
