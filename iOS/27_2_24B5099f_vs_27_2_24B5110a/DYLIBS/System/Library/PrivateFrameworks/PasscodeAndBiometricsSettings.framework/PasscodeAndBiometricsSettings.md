## PasscodeAndBiometricsSettings

> `/System/Library/PrivateFrameworks/PasscodeAndBiometricsSettings.framework/PasscodeAndBiometricsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c29c` | `0x3c7bc` | **`+0x520`** |
| `__TEXT.__oslogstring` | `0x50f5` | `0x51f5` | **`+0x100`** |
| `__TEXT.__cstring` | `0x36a8` | `0x3718` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x2f00` | `0x2f40` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x2184` | `0x21c4` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x2188` | `0x21c0` | **`+0x38`** |
| `__DATA.__data` | `0x694` | `0x6c4` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x10a0` | `0x10d0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x720` | `0x740` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e48` | `0x1e68` | **`+0x20`** |
| `__TEXT.__const` | `0xc74` | `0xc84` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x648` | `0x650` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xe0` | `0xe4` | **`+0x4`** |

### Other Changes

```diff

-40.2.1.0.0
+40.2.3.100.0

-  Functions: 1324
-  Symbols:   1851
-  CStrings:  884
+  Functions: 1335
+  Symbols:   1857
+  CStrings:  889
Symbols:
+ -[PABSPasscodeLockController viewDidLayoutSubviews]
+ -[PABSTouchIDPasscodeController enrollFlowTornDownByResult]
+ -[PABSTouchIDPasscodeController enrollmentNavigationControllerDidDismiss:]
+ -[PABSTouchIDPasscodeController enrollmentNavigationControllerWillDismiss:]
+ -[PABSTouchIDPasscodeController setEnrollFlowTornDownByResult:]
+ GCC_except_table117
+ GCC_except_table119
+ GCC_except_table121
+ GCC_except_table130
+ GCC_except_table151
+ GCC_except_table27
+ GCC_except_table30
+ GCC_except_table38
+ GCC_except_table47
+ GCC_except_table53
+ GCC_except_table55
+ GCC_except_table72
+ GCC_except_table86
+ _OBJC_IVAR_$_PABSTouchIDPasscodeController._enrollFlowTornDownByResult
- GCC_except_table116
- GCC_except_table118
- GCC_except_table120
- GCC_except_table129
- GCC_except_table150
- GCC_except_table31
- GCC_except_table44
- GCC_except_table46
- GCC_except_table51
- GCC_except_table52
- GCC_except_table67
- GCC_except_table74
- GCC_except_table85
CStrings:
+ "DTO_SECURITY_DELAY_OPTIONS_GROUP_FOOTER_DESCRIPTION_ALWAYS_FACE_ID"
+ "DTO_SECURITY_DELAY_OPTIONS_GROUP_FOOTER_DESCRIPTION_ALWAYS_TOUCH_ID"
+ "DTO_SECURITY_DELAY_OPTIONS_GROUP_HEADER_DESCRIPTION_FACE_ID"
+ "DTO_SECURITY_DELAY_OPTIONS_GROUP_HEADER_DESCRIPTION_TOUCH_ID"
+ "PHONE_NEARBY_DEVICE_AUTO_UNLOCK_FOOTER"
+ "PHONE_VISION_PRO_AUTO_UNLOCK_ALERT_BODY_DEFAULT"
+ "Touch ID: No enrollment controller from BiometricKitUI, not starting enrollment"
+ "Touch ID: enrollment navigation controller dismissed without an enroll result"
+ "Touch ID: enrollment navigation controller dismissed, already handled by enroll result"
- "DTO_SECURITY_DELAY_OPTIONS_GROUP_FOOTER_DESCRIPTION_ALWAYS"
- "DTO_SECURITY_DELAY_OPTIONS_GROUP_HEADER_DESCRIPTION"
- "PHONE_NEARBY_DEVICE_AUTO_UNLOCK_FOOTER_ASSISTANT_DISABLED"
- "PHONE_NEARBY_DEVICE_AUTO_UNLOCK_FOOTER_ASSISTANT_ENABLED"
```
