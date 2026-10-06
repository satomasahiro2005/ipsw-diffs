## BiometricSupport

> `/System/Library/PrivateFrameworks/BiometricSupport.framework/BiometricSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ebc8` | `0x4ed98` | **`+0x1d0`** |
| `__DATA_CONST.__const` | `0x1ae8` | `0x1b10` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x1048` | `0x1060` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1058` | `0x1070` | **`+0x18`** |
| `__TEXT.__cstring` | `0x6fcf` | `0x6fdc` | **`+0xd`** |
| `__TEXT.__oslogstring` | `0x3734` | `0x3735` | **`+0x1`** |

### Other Changes

```diff

-576.0.0.0.0
+577.0.0.0.0

-  Functions: 2018
-  Symbols:   2756
-  CStrings:  1235
+  Functions: 2020
+  Symbols:   2759
+  CStrings:  1236
Symbols:
+ GCC_except_table114
+ ___72-[BiometricKitXPCExportedObject enableMatchAutoRetry:client:replyBlock:]_block_invoke
+ ___block_descriptor_49_e8_32s40r_e5_v8?0ls32l8r40l8
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-577~3006, %s file: %s, line: %d\n\n"
+ "tmpErr == 0 "
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-576~458, %s file: %s, line: %d\n\n"
```
