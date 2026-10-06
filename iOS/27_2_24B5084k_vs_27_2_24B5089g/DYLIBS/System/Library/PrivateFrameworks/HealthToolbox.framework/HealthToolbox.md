## HealthToolbox

> `/System/Library/PrivateFrameworks/HealthToolbox.framework/HealthToolbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x64da0` | `0x65ae4` | **`+0xd44`** |
| `__AUTH_CONST.__auth_got` | `0x708` | `0x808` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x55a0` | `0x5500` | **`-0xa0`** |
| `__AUTH.__objc_data` | `0x23a0` | `0x2400` | **`+0x60`** |
| `__TEXT.__const` | `0x1a6` | `0x1f4` | **`+0x4e`** |
| `__TEXT.__cstring` | `0x7a21` | `0x7a69` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0xb2b8` | `0xb280` | **`-0x38`** |
| `__TEXT.__constg_swiftt` | `0x8c` | `0xb8` | **`+0x2c`** |
| `__AUTH.__data` | `0x130` | `0x158` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1a08` | `0x1a30` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0xc` | `0x30` | **`+0x24`** |
| `__DATA_CONST.__got` | `0xc68` | `0xc88` | **`+0x20`** |
| `__DATA.__data` | `0x1050` | `0x1068` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x6fe8` | `0x6ff8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x20` | `0x30` | **`+0x10`** |
| `__DATA.__bss` | `0x68` | `0x60` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4868` | `0x4870` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x290` | `0x288` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x8` | `0xc` | **`+0x4`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 2380
-  Symbols:   4547
-  CStrings:  1095
+  Functions: 2393
+  Symbols:   4558
+  CStrings:  1096
Symbols:
+ _OBJC_CLASS_$_HKBilateralQuantitySample
+ _OBJC_CLASS_$_HKStaticDecimalPrecisionRule
+ __DATA_WDBilateralQuantityListDataProvider
+ __INSTANCE_METHODS_WDBilateralQuantityListDataProvider
+ __METACLASS_DATA_WDBilateralQuantityListDataProvider
+ ___swift_destroy_boxed_opaque_existential_0
+ __swift_stdlib_reportUnimplementedInitializer
+ _objc_allocWithZone
+ _swift_dynamicCastObjCClass
+ _swift_getObjectType
+ _swift_release_x19
+ _swift_release_x21
+ _swift_release_x8
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
+ _swift_unknownObjectRetain
+ _symbolic So24WDSampleListDataProviderC
+ _symbolic _____ 13HealthToolbox35WDBilateralQuantityListDataProviderC
- -[WDBilateralQuantityListDataProvider initWithDisplayType:profile:]
- -[WDBilateralQuantityListDataProvider sampleTypes]
- -[WDBilateralQuantityListDataProvider textForObject:]
- -[WDBilateralQuantityListDataProvider titleForSection:]
- __OBJC_$_INSTANCE_METHODS_WDBilateralQuantityListDataProvider
- __OBJC_CLASS_RO_$_WDBilateralQuantityListDataProvider
- __OBJC_METACLASS_RO_$_WDBilateralQuantityListDataProvider
CStrings:
+ "BILATERAL_RIGHT_"
+ "HealthToolbox.WDBilateralQuantityListDataProvider"
+ "HealthToolbox/WDBilateralQuantityListDataProvider.swift"
+ "HealthUI-Localizable-Assessments"
+ "init()"
- "Attempt to create a bilateral quantity list provider with a non-bilateral quantity data group"
- "BILATERAL_LEFT_FORMAT_%@"
- "BILATERAL_RIGHT_FORMAT_%@"
- "HealthUI-Localizable-Mulberry"
```
