## NanoSleepBridgeSetup

> `/System/Library/NanoPreferenceBundles/SetupBundles/NanoSleepBridgeSetup.bundle/NanoSleepBridgeSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x267` | `0x287` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xe0` | `0x100` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x5a0` | `0x5b0` | **`+0x10`** |
| `__TEXT.__text` | `0x2ab4` | `0x2ac0` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2d8` | `0x2e0` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x98` | `0xa0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/SleepHealth.framework/SleepHealth

+  - /usr/lib/swift/libswiftMLCompute.dylib

-  Symbols:   95
-  CStrings:  40
+  Symbols:   98
+  CStrings:  41
Symbols:
+ _OBJC_CLASS_$_HKSleepHealthStore
+ __swift_FORCE_LOAD_$_swiftMLCompute
+ _objc_release_x22
Functions:
~ sub_16f8 -> sub_17a0 : 192 -> 204
CStrings:
+ "initWithHealthStore:"
+ "initWithIdentifier:scheduleHistoryWriter:"
- "initWithIdentifier:healthStore:"
```
