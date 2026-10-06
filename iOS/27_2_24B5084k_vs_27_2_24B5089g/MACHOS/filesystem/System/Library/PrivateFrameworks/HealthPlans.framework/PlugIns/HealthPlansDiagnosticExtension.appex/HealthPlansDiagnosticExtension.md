## HealthPlansDiagnosticExtension

> `/System/Library/PrivateFrameworks/HealthPlans.framework/PlugIns/HealthPlansDiagnosticExtension.appex/HealthPlansDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x20` | `0x40` | **`+0x20`** |
| `__TEXT.__text` | `0x1654` | `0x166c` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x59` | `0x69` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x68` | `0x70` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

+  - /System/Library/Frameworks/HealthKit.framework/HealthKit

+  - /usr/lib/swift/libswiftCoreLocation.dylib

+  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib

-  Symbols:   49
+  Symbols:   52
Symbols:
+ _OBJC_CLASS_$_HKHealthStore
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
Functions:
~ sub_100001cd4 -> sub_100001dc4 : 1400 -> 1424
```
