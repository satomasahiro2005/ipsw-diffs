## CoreAccessories

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/CoreAccessories`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27350` | `0x274b0` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x41b3` | `0x4235` | **`+0x82`** |
| `__AUTH_CONST.__const` | `0xb40` | `0xb60` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2038` | `0x2058` | **`+0x20`** |
| `__DATA.__bss` | `0x148` | `0x158` | **`+0x10`** |
| `__TEXT.__const` | `0x150` | `0x160` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa70` | `0xa78` | **`+0x8`** |

### Other Changes

```diff

-1219.40.5.0.0
+1219.40.7.0.0

-  Functions: 836
-  Symbols:   1900
-  CStrings:  881
+  Functions: 842
+  Symbols:   1906
+  CStrings:  883
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
