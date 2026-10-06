## Microstackshot

> `/System/Library/Trace/PassiveDataSources/Microstackshot.bundle/Microstackshot`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x16f` | `0x2f3` | **`+0x184`** |
| `__DATA_CONST.__cfstring` | `0x120` | `0x160` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xb8` | `0xf0` | **`+0x38`** |
| `__TEXT.__objc_methname` | `0x2d7` | `0x302` | **`+0x2b`** |
| `__TEXT.__text` | `0x874` | `0x888` | **`+0x14`** |
| `__DATA.__objc_const` | `0x150` | `0x160` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xd0` | `0xe0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-188.0.0.0.0
+196.0.0.0.0

-  Functions: 10
+  Functions: 12

-  CStrings:  59
+  CStrings:  63
CStrings:
+ "Always-on and low cadence CPU samples."
+ "Every N CPU cycles executed, the backtrace for the current on-core thread is sampled.\nSince sampling is driven by CPU cycles, not timers, the time between samples varies as a function of total system activity.\nThese low-cadence samples are useful for identifying and diagnosing long term cpu use and are not intended for very granular CPU analysis."
+ "conciseDocumentation"
+ "detailedDocumentation"
```
