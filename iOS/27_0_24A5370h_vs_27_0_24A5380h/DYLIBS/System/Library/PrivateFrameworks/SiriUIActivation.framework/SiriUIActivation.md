## SiriUIActivation

> `/System/Library/PrivateFrameworks/SiriUIActivation.framework/SiriUIActivation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f2e4` | `0x2f288` | **`-0x5c`** |
| `__AUTH.__objc_data` | `0x2b8` | `0x268` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x6a8` | `0x6f8` | **`+0x50`** |
| `__DATA.__data` | `0xa20` | `0xa10` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x4d7b` | `0x4d6b` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x5d8` | `0x5d0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fe0` | `0x1fd8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xde8` | `0xde0` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x524` | `0x51e` | **`-0x6`** |

### Other Changes

```diff

-3600.55.10.0.0
+3600.55.26.0.0

-  Functions: 1074
-  Symbols:   1660
+  Functions: 1073
+  Symbols:   1658
Symbols:
- _get_type_metadata 15Synchronization6AtomicVySiG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
Functions:
- sub_21eca007c
~ -[SiriPresentationViewController siriViewController].cold.1 : 120 -> 76
CStrings:
+ "%s #activation Attempting to use siriViewController, but one does not exist"
- "%s #activation Attempting to use siriViewController, but one does not exist. Backtrace: %@"
```
