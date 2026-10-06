## ControlCenterUIServices

> `/System/Library/PrivateFrameworks/ControlCenterUIServices.framework/ControlCenterUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19ba8` | `0x19d64` | **`+0x1bc`** |
| `__TEXT.__oslogstring` | `—` | `0x58` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0x698` | `0x6b8` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0xb10` | `0xb30` | **`+0x20`** |
| `__DATA.__bss` | `0xc88` | `0xc98` | **`+0x10`** |
| `__TEXT.__const` | `0xe50` | `0xe60` | **`+0x10`** |
| `__TEXT.__cstring` | `0x2e54` | `0x2e64` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x10e8` | `0x10f0` | **`+0x8`** |

### Other Changes

```diff

-704.0.2.0.0
+704.2.2.0.0

-  Functions: 685
-  Symbols:   623
-  CStrings:  250
+  Functions: 688
+  Symbols:   630
+  CStrings:  252
Symbols:
+ _CCUIControlServicesLog.controlServicesLog
+ _CCUIControlServicesLog.onceToken
+ _NSStringFromCCUIGridSizeClass
+ ___CCUIControlServicesLog_block_invoke
+ ___block_descriptor_56_e8_32s40s_e8_v16?0q8ls32l8s40l8
+ __os_log_error_impl
+ _os_log_create
+ _os_log_type_enabled
- ___block_descriptor_48_e8_32s_e8_v16?0q8ls32l8
CStrings:
+ "ControlServices"
+ "Ignoring view-only grid size class %{public}@, declare its portrait counterpart instead"
```
