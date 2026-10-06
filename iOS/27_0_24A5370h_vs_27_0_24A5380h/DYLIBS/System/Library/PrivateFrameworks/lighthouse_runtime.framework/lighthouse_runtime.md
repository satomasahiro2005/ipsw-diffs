## lighthouse_runtime

> `/System/Library/PrivateFrameworks/lighthouse_runtime.framework/lighthouse_runtime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf4c0` | `0xf420` | **`-0xa0`** |
| `__DATA.__bss` | `0x880` | `0x800` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x400` | `0x480` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1f9` | `0x1c9` | **`-0x30`** |
| `__TEXT.__eh_frame` | `0xe10` | `0xdf0` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x5d8` | `0x5e0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xb0` | `0xa8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x620` | `0x618` | **`-0x8`** |

### Other Changes

```diff

-6.0.1.0.0
+6.0.3.0.0

-  Functions: 409
-  Symbols:   298
-  CStrings:  29
+  Functions: 407
+  Symbols:   300
+  CStrings:  28
Symbols:
+ _swift_task_localValuePop
+ _swift_task_localValuePush
CStrings:
- "lighthouse_runtime/LighthouseRuntime.swift"
```
