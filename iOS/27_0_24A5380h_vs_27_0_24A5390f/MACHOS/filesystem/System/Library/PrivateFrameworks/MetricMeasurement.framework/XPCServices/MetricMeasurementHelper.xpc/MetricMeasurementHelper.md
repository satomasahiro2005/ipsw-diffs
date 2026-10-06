## MetricMeasurementHelper

> `/System/Library/PrivateFrameworks/MetricMeasurement.framework/XPCServices/MetricMeasurementHelper.xpc/MetricMeasurementHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55ac` | `0x58e8` | **`+0x33c`** |
| `__DATA_CONST.__cfstring` | `0x440` | `0x4e0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x658` | `0x6e1` | **`+0x89`** |
| `__DATA.__objc_const` | `0x1120` | `0x1190` | **`+0x70`** |
| `__DATA.__data` | `0x480` | `0x4e0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x10bd` | `0x111d` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0xe20` | `0xe60` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x5ad` | `0x5da` | **`+0x2d`** |
| `__TEXT.__objc_methlist` | `0x6a4` | `0x6cc` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x208` | `0x229` | **`+0x21`** |
| `__DATA.__objc_selrefs` | `0x550` | `0x568` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x138` | `0x148` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x60` | `0x68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-358.0.0.0.0
+361.0.0.0.0

-  Functions: 110
-  Symbols:   184
-  CStrings:  406
+  Functions: 111
+  Symbols:   186
+  CStrings:  416
Symbols:
+ _OBJC_CLASS_$_MXMOSSignpostProbe
+ _OBJC_CLASS_$_NSArray
Functions:
~ sub_100004568 : 8 -> 828
+ sub_1000048a4
CStrings:
+ "MXMSProxySignpostConfig_Internal"
+ "Signpost allowlist config is nil or not a dictionary."
+ "Signpost allowlist filterEntries is not an array."
+ "_syncSignpostAllowlistConfig:response:"
+ "category"
+ "filterEntries"
+ "registerSubsystem:category:"
+ "resetRegisteredFilterEntries"
+ "subsystem"
+ "v32@0:8@\"NSDictionary\"16@?<v@?B@\"NSError\">24"
```
