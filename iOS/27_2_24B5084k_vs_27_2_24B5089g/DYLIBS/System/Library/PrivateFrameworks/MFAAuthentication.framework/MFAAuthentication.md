## MFAAuthentication

> `/System/Library/PrivateFrameworks/MFAAuthentication.framework/MFAAuthentication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42b50` | `0x42d48` | **`+0x1f8`** |
| `__TEXT.__oslogstring` | `0x4e68` | `0x4eea` | **`+0x82`** |
| `__AUTH_CONST.__const` | `0x1c30` | `0x1c50` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x57a0` | `0x57c0` | **`+0x20`** |
| `__DATA.__bss` | `0xc0` | `0xd0` | **`+0x10`** |
| `__TEXT.__const` | `0x6de13` | `0x6de23` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7e0` | `0x7f0` | **`+0x10`** |

### Other Changes

```diff

-1219.40.5.0.0
+1219.40.7.0.0

-  Functions: 855
-  Symbols:   1885
-  CStrings:  733
+  Functions: 861
+  Symbols:   1891
+  CStrings:  735
Symbols:
+ ___acc_internalSettings_isInternalBuild_block_invoke
+ _acc_internalSettings_boolForKey
+ _acc_internalSettings_integerForKey
+ _acc_internalSettings_isInternalBuild
+ _acc_internalSettings_isInternalBuild.isInternalBuild
+ _acc_internalSettings_isInternalBuild.onceToken
CStrings:
+ "acc_internalSettings: internal-only setting %{public}@ active"
+ "acc_internalSettings: internal-only setting %{public}@ active (%ld)"
```
