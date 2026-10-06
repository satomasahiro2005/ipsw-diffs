## BiometricKit

> `/System/Library/PrivateFrameworks/BiometricKit.framework/BiometricKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c59c` | `0x3cbc4` | **`+0x628`** |
| `__TEXT.__oslogstring` | `0x4f8a` | `0x4fea` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0xb58` | `0xba0` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x17c0` | `0x1800` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x2cf4` | `0x2d24` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2818` | `0x2841` | **`+0x29`** |
| `__AUTH_CONST.__objc_const` | `0x5258` | `0x5280` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x10d0` | `0x10f0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1768` | `0x1780` | **`+0x18`** |
| `__DATA.__bss` | `0x28` | `0x38` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2ec` | `0x2f0` | **`+0x4`** |

### Other Changes

```diff

-577.0.0.0.0
+578.40.6.0.0

-  Functions: 1548
-  Symbols:   2086
-  CStrings:  741
+  Functions: 1555
+  Symbols:   2095
+  CStrings:  745
Symbols:
+ -[BKDevice valueForDeviceProperty:error:]
+ -[BiometricKitXPCClient getDeviceProperties:]
+ GCC_except_table126
+ GCC_except_table172
+ GCC_except_table196
+ GCC_except_table241
+ GCC_except_table249
+ GCC_except_table281
+ GCC_except_table72
+ _OBJC_IVAR_$_BKDevice._deviceProperties
+ _OSLogHandle
+ _OSLogTraceHandle
+ ___45-[BiometricKitXPCClient getDeviceProperties:]_block_invoke
+ ___45-[BiometricKitXPCClient getDeviceProperties:]_block_invoke_2
- GCC_except_table136
- GCC_except_table175
- GCC_except_table199
- GCC_except_table246
- GCC_except_table251
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-578.40.6~29, %s file: %s, line: %d\n\n"
+ "BKDPHasFaceIDInExclave"
+ "BKDPRequiresFaceIDLatencyMitigation"
+ "BKDevicePearl::valueForDeviceProperty: %lu (_cid:%lu)\n"
+ "BKDevicePearl::valueForDeviceProperty: -> %@, error:%@\n"
+ "Couldn't create OS Log for 'com.apple.BiometricKit.Framework'!\n"
+ "Couldn't create OS Log for 'com.apple.BiometricKit.Framework-Legacy'!\n"
+ "Framework"
+ "Framework-Legacy"
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-577~3088, %s file: %s, line: %d\n\n"
- "Couldn't create OS Log for 'com.apple.BiometricKit.Framework-Internal'!\n"
- "Couldn't create OS Log for 'com.apple.BiometricKit.Framework-Internal-Legacy'!\n"
- "Framework-Internal"
- "Framework-Internal-Legacy"
```
