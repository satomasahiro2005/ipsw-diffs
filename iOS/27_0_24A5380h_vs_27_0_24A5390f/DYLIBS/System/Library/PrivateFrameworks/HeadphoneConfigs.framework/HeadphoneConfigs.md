## HeadphoneConfigs

> `/System/Library/PrivateFrameworks/HeadphoneConfigs.framework/HeadphoneConfigs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc92f0` | `0xc9614` | **`+0x324`** |
| `__AUTH_CONST.__cfstring` | `0x95a0` | `0x95e0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0xa3ab` | `0xa3db` | **`+0x30`** |
| `__TEXT.__cstring` | `0x9623` | `0x9643` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3668` | `0x3680` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x4f98` | `0x4fa8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2420` | `0x2428` | **`+0x8`** |

### Other Changes

```diff

-2700.15.0.0.0
+2700.16.0.0.0

-  Functions: 4193
-  Symbols:   3536
-  CStrings:  2245
+  Functions: 4195
+  Symbols:   3538
+  CStrings:  2248
Symbols:
+ -[BTSDeviceConfigController deviceAccessCompanionAppResolved:]
+ GCC_except_table131
+ GCC_except_table135
+ GCC_except_table165
+ GCC_except_table202
+ GCC_except_table203
+ GCC_except_table207
+ GCC_except_table208
+ GCC_except_table244
+ ___62-[BTSDeviceConfigController deviceAccessCompanionAppResolved:]_block_invoke
- GCC_except_table129
- GCC_except_table133
- GCC_except_table163
- GCC_except_table200
- GCC_except_table201
- GCC_except_table205
- GCC_except_table206
- GCC_except_table242
CStrings:
+ "ASAccessoryCompanionAppResolved"
+ "Headphone Configs: companion app resolved. %@"
+ "companionApp"
```
