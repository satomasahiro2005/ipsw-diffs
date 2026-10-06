## HealthRecordsAssembler

> `/System/Library/PrivateFrameworks/HealthRecordsAssembler.framework/HealthRecordsAssembler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2888` | `0x28ec` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0xb0` | `0xd0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x238` | `0x250` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0xa1` | `0xb5` | **`+0x14`** |
| `__TEXT.__swift5_fieldmd` | `0x34` | `0x40` | **`+0xc`** |
| `__TEXT.__swift5_reflstr` | `0x49` | `0x55` | **`+0xc`** |
| `__AUTH.__data` | `0xc0` | `0xc8` | **`+0x8`** |
| `__DATA.__data` | `0x90` | `0x98` | **`+0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Symbols:   111
+  Symbols:   115
Symbols:
+ _objc_release_x23
+ _objc_release_x8
+ _objc_retain_x9
+ _swift_release_x24
+ _swift_retain_x24
+ _symbolic So13HKHealthStoreC
- _swift_release_x22
- _swift_retain_x22
Functions:
~ sub_2ce28c704 -> sub_2cdf93704 : 64 -> 80
~ sub_2ce28c744 -> sub_2cdf93754 : 476 -> 508
~ sub_2ce28d918 -> sub_2cdf94948 : 212 -> 228
~ sub_2ce28d9ec -> sub_2cdf94a2c : 304 -> 324
~ sub_2ce28ebc0 -> sub_2cdf95c14 : 168 -> 184
```
