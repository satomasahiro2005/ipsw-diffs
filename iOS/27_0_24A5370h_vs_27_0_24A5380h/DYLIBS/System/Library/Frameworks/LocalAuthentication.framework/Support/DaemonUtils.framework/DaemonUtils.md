## DaemonUtils

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/DaemonUtils.framework/DaemonUtils`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8dbc` | `0x8aa8` | **`-0x314`** |
| `__TEXT.__oslogstring` | `0xa0b` | `0x997` | **`-0x74`** |
| `__AUTH_CONST.__const` | `0x240` | `0x1e0` | **`-0x60`** |
| `__TEXT.__cstring` | `0x595` | `0x553` | **`-0x42`** |
| `__AUTH_CONST.__cfstring` | `0x620` | `0x5e0` | **`-0x40`** |
| `__DATA.__bss` | `0x50` | `0x28` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0x1258` | `0x1230` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x210` | `0x228` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xaf0` | `0xad8` | **`-0x18`** |
| `__TEXT.__const` | `0x160` | `0x170` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3b0` | `0x3a0` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0xc4` | `0xd0` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2b8` | `0x2c0` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0xd0` | `0xc8` | **`-0x8`** |

### Other Changes

```diff

-2319.0.16.502.1
+2319.0.33.0.1

-  Functions: 347
-  Symbols:   750
-  CStrings:  119
+  Functions: 335
+  Symbols:   745
+  CStrings:  114
Symbols:
+ -[LAAnalyticsDTO _skipRetryInterval]
+ GCC_except_table11
+ GCC_except_table17
+ _LACErrorCodeInternal
+ _LACLogPushButton
+ _OBJC_CLASS_$_LACError
+ _OBJC_CLASS_$_LACMobileGestalt
- +[DaemonUtils deviceHasSecureDoublePressHW]
- +[DaemonUtils deviceHasSpecialTouchID]
- +[DaemonUtils deviceHasTouchIDAndSecureDoublePress]
- +[DaemonUtils deviceIsPoseidon]
- +[DaemonUtils deviceSupportsSecureDoubleClick]
- GCC_except_table12
- ___43+[DaemonUtils deviceHasSecureDoublePressHW]_block_invoke
- ___46+[DaemonUtils deviceSupportsSecureDoubleClick]_block_invoke
- _deviceHasSecureDoublePressHW.hasSecureDoublePressHW
- _deviceHasSecureDoublePressHW.onceToken
- _deviceSupportsSecureDoubleClick.onceToken
- _deviceSupportsSecureDoubleClick.supportsSecureDoubleClick
CStrings:
- "Can't query SecureDoubleClick."
- "DeviceSupportsSecureDoubleClick"
- "HardwareSupportsSecureDoubleClick"
- "deviceHasSecureDoublePressHW returned %d"
- "deviceSupportsSecureDoubleClick returned %d"
```
