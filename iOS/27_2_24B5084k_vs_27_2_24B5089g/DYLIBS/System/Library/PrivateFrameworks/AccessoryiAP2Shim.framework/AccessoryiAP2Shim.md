## AccessoryiAP2Shim

> `/System/Library/PrivateFrameworks/AccessoryiAP2Shim.framework/AccessoryiAP2Shim`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc080` | `0xc1e0` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x22e4` | `0x2366` | **`+0x82`** |
| `__AUTH_CONST.__const` | `0x220` | `0x240` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x9c8` | `0x9e8` | **`+0x20`** |
| `__DATA.__bss` | `0xf0` | `0x100` | **`+0x10`** |
| `__TEXT.__const` | `0x541` | `0x551` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x308` | `0x310` | **`+0x8`** |

### Other Changes

```diff

-1219.40.5.0.0
+1219.40.7.0.0

-  Functions: 306
-  Symbols:   844
-  CStrings:  339
+  Functions: 312
+  Symbols:   850
+  CStrings:  341
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
