## Assignables

> `/System/Library/Frameworks/Assignables.framework/Assignables`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b228c` | `0x1b27f8` | **`+0x56c`** |
| `__TEXT.__eh_frame` | `0x927c` | `0x9344` | **`+0xc8`** |
| `__TEXT.__const` | `0xc7b0` | `0xc7c0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x43e0` | `0x43f0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x258` | `0x250` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x2a0` | `0x2a8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x51c` | `0x518` | **`-0x4`** |

### Other Changes

```diff

-3.0.1.0.0
+3.0.2.0.0

-  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 5195
+  Functions: 5198
Symbols:
+ _swift_task_localValuePop
+ _swift_task_localValuePush
- __swift_FORCE_LOAD_$_swiftIntents
- _swift_willThrowTypedImpl
```
