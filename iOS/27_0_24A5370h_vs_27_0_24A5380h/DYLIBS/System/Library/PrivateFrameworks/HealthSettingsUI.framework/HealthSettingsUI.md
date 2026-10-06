## HealthSettingsUI

> `/System/Library/PrivateFrameworks/HealthSettingsUI.framework/HealthSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0xe70` | `0xbe0` | **`-0x290`** |
| `__DATA_DIRTY.__bss` | `—` | `0x290` | **`+0x290`** |
| `__DATA_DIRTY.__data` | `—` | `0x198` | **`+0x198`** |
| `__AUTH.__objc_data` | `0x330` | `0x1a0` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x190` | **`+0x190`** |
| `__AUTH.__data` | `0x200` | `0xb0` | **`-0x150`** |
| `__DATA.__data` | `0x6d8` | `0x688` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0x320` | `0x340` | **`+0x20`** |
| `__TEXT.__cstring` | `0x671` | `0x691` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x480` | `0x468` | **`-0x18`** |
| `__TEXT.__text` | `0x11e50` | `0x11e64` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x708` | `0x710` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x974` | `0x97c` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x367` | `0x36f` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5d0` | `0x5c8` | **`-0x8`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  CStrings:  70
+  CStrings:  71
Symbols:
+ -[HKHealthSettingsController configurePersonalizedSuggestionsItemInSpecifiers:]
+ GCC_except_table19
+ GCC_except_table22
+ GCC_except_table29
+ ___swift_closure_destructor.22Tm
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE s5Int32V
- GCC_except_table18
- GCC_except_table21
- GCC_except_table28
- ___swift_closure_destructor.23Tm
- _get_type_metadata 15Synchronization5MutexVys5Int32VG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "PERSONALIZED_SUGGESTIONS_ITEM"
```
