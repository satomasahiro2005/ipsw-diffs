## CoreML

> `/System/Library/Frameworks/CoreML.framework/CoreML`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x703c8c` | `0x704550` | **`+0x8c4`** |
| `__AUTH.__objc_data` | `0x54b8` | `0x5698` | **`+0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0xd48` | `0xb68` | **`-0x1e0`** |
| `__TEXT.__eh_frame` | `0x53e4` | `0x54d4` | **`+0xf0`** |
| `__DATA_CONST.__got` | `0x1150` | `0x11a0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x10440` | `0x10470` | **`+0x30`** |
| `__DATA.__data` | `0x38f8` | `0x3918` | **`+0x20`** |
| `__DATA.__bss` | `0xb518` | `0xb508` | **`-0x10`** |
| `__TEXT.__const` | `0x51473` | `0x51483` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2bd0` | `0x2bc8` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0xc8` | `0xd0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x108` | `0x110` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x21f6` | `0x21f0` | **`-0x6`** |
| `__TEXT.__swift_as_cont` | `0x140` | `0x13c` | **`-0x4`** |

### Other Changes

```diff

-  Functions: 16995
-  Symbols:   24694
+  Functions: 16997
+  Symbols:   24692
Symbols:
+ _swift_task_localValuePop
+ _swift_task_localValuePush
- _get_type_metadata 15Synchronization5MutexVySay4ODIE8FunctionCGG noncopyable
- _swift_release_x9
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
```
