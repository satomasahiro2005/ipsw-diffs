## PasscodeAndBiometricsSettings

> `/System/Library/PrivateFrameworks/PasscodeAndBiometricsSettings.framework/PasscodeAndBiometricsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b8c0` | `0x3bd70` | **`+0x4b0`** |
| `__TEXT.__oslogstring` | `0x5115` | `0x5165` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x212c` | `0x2144` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e30` | `0x1e40` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa70` | `0xa68` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1090` | `0x1098` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x8c8` | `0x8c4` | **`-0x4`** |

### Other Changes

```diff

-34.0.0.0.0
+35.3.0.0.0

-  Functions: 1317
-  Symbols:   1837
-  CStrings:  884
+  Functions: 1320
+  Symbols:   1838
+  CStrings:  885
Symbols:
+ -[PABSBiometrics isEnrolledInAnyBiometric]
+ -[PABSBiometrics removeAllIdentities]
- _PSPointImageOfColor
CStrings:
+ "Biometrics enrolled with no passcode set — removing all identities"
```
