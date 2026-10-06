## libCommCenterBase.dylib

> `/System/Library/Frameworks/CoreTelephony.framework/Support/libCommCenterBase.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd2180` | `0xd228c` | **`+0x10c`** |
| `__TEXT.__cstring` | `0x14a0a` | `0x14a9d` | **`+0x93`** |
| `__AUTH_CONST.__cfstring` | `0x2c40` | `0x2cc0` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x7680` | `0x76d0` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x13b08` | `0x13b38` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x25d1` | `0x25ef` | **`+0x1e`** |
| `__TEXT.__const` | `0xd2d0` | `0xd2e0` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x14478` | `0x14470` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x4e40` | `0x4e48` | **`+0x8`** |

### Other Changes

```diff

-13478.3.1.3.0
+13482.1.0.0.0

-  Functions: 5759
-  Symbols:   9453
-  CStrings:  4479
+  Functions: 5760
+  Symbols:   9458
+  CStrings:  4486
Symbols:
+ __Z8asString15BootstrapStatus
+ _kTARFeatureDisabledBody
+ _kTARFeatureDisabledTitle
+ _kTARFeatureRestoredBody
+ _kTARFeatureRestoredTitle
CStrings:
+ "DisplayStatus [isOn=%{bool}d, isLocked=%{bool}d, isCoversheetActive=%{bool}d, isPasscodeSet=%{bool}d, isEffectivelyLocked=%{bool}d]"
+ "TAR_FEATURE_DISABLED_BODY"
+ "TAR_FEATURE_DISABLED_TITLE"
+ "TAR_FEATURE_RESTORED_BODY"
+ "TAR_FEATURE_RESTORED_TITLE"
+ "is_effectively_locked"
+ "kFour"
+ "kRecommended"
- "DisplayStatus [isOn=%{bool}d, isLocked=%{bool}d, isCoversheetActive=%{bool}d, isPasscodeSet=%{bool}d]"
```
