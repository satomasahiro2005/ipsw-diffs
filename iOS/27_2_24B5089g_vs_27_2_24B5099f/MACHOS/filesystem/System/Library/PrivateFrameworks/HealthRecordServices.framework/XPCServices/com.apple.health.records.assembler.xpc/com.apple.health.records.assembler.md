## com.apple.health.records.assembler

> `/System/Library/PrivateFrameworks/HealthRecordServices.framework/XPCServices/com.apple.health.records.assembler.xpc/com.apple.health.records.assembler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__text` | `0x1148` | `0x1164` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0x198` | `0x1a8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x330` | `0x340` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x68` | `0x70` | **`+0x8`** |
| `__TEXT.__objc_methname` | `—` | `0x5` | **`+0x5`** |

### Same-size Content Changes

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

+  - /System/Library/Frameworks/HealthKit.framework/HealthKit

-  Symbols:   54
-  CStrings:  1
+  Symbols:   57
+  CStrings:  2
Symbols:
+ _OBJC_CLASS_$_HKHealthStore
+ _objc_allocWithZone
+ _objc_msgSend
Functions:
~ sub_100001060 -> sub_1000011a8 : 904 -> 932
CStrings:
+ "init"
```
