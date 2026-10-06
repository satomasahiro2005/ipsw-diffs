## STSXPCHelper

> `/System/Library/PrivateFrameworks/STSXPCHelperClient.framework/XPCServices/STSXPCHelper.xpc/STSXPCHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a334` | `0x3a650` | **`+0x31c`** |
| `__TEXT.__objc_methname` | `0x6263` | `0x62b7` | **`+0x54`** |
| `__DATA.__objc_const` | `0x61e8` | `0x6228` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x4680` | `0x46c0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x28d0` | `0x28e8` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x1eed` | `0x1f01` | **`+0x14`** |
| `__TEXT.__cstring` | `0x95a4` | `0x95b7` | **`+0x13`** |
| `__DATA.__objc_selrefs` | `0x17e0` | `0x17f0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xaf0` | `0xb00` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4dc` | `0x4e4` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2e8` | `0x2f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-6.0.13.0.0
+6.0.15.0.0

-  Functions: 958
-  Symbols:   291
-  CStrings:  2530
+  Functions: 962
+  Symbols:   292
+  CStrings:  2533
Symbols:
+ ___NSDictionary0__struct
CStrings:
+ "-[STSXPCHelper startConnectionHandoverWithConfiguration:type:credentialType:deviceCAParameters:callback:]"
+ "Vv52@0:8Q16Q24C32@\"NSDictionary\"36@?<v@?@\"NSError\">44"
+ "Vv52@0:8Q16Q24C32@36@?44"
+ "_deviceCAParams"
+ "dictionaryWithDictionary:"
+ "setDeviceCAParameters:"
+ "startConnectionHandoverWithConfiguration:type:credentialType:deviceCAParameters:callback:"
- "-[STSXPCHelper startConnectionHandoverWithConfiguration:type:credentialType:callback:]"
- "Vv44@0:8Q16Q24C32@?36"
- "Vv44@0:8Q16Q24C32@?<v@?@\"NSError\">36"
- "startConnectionHandoverWithConfiguration:type:credentialType:callback:"
```
