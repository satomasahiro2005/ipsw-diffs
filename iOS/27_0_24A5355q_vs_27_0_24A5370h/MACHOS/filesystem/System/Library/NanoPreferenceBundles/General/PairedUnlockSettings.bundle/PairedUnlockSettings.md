## PairedUnlockSettings

> `/System/Library/NanoPreferenceBundles/General/PairedUnlockSettings.bundle/PairedUnlockSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xbcf` | `0xc29` | **`+0x5a`** |
| `__DATA_CONST.__cfstring` | `0xbe0` | `0xc20` | **`+0x40`** |
| `__TEXT.__text` | `0x6244` | `0x627c` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x460` | `0x470` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x240` | `0x248` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-184.4.2.0.0
+184.4.3.0.0

-  Symbols:   144
-  CStrings:  482
+  Symbols:   145
+  CStrings:  486
Symbols:
+ __os_feature_enabled_impl
Functions:
~ sub_1f74 : 468 -> 464
~ sub_57f8 -> sub_57f4 : 1756 -> 1816
CStrings:
+ "Elton"
+ "PasscodeSettings_EltonTap"
+ "WRIST_DETECTION_DISABLE_WARNING_MSG_TAP_GESTURES"
+ "elton_st"
```
