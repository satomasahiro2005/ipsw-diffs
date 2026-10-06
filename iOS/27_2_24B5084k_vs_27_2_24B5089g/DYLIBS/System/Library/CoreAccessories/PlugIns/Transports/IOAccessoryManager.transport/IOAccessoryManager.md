## IOAccessoryManager

> `/System/Library/CoreAccessories/PlugIns/Transports/IOAccessoryManager.transport/IOAccessoryManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x611dc` | `0x6133c` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0xc94a` | `0xc9cc` | **`+0x82`** |
| `__AUTH_CONST.__const` | `0x4a0` | `0x4c0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1020` | `0x1040` | **`+0x20`** |
| `__DATA.__bss` | `0x128` | `0x138` | **`+0x10`** |
| `__TEXT.__const` | `0x360` | `0x368` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xf18` | `0xf20` | **`+0x8`** |

### Other Changes

```diff

-1219.40.5.0.0
+1219.40.7.0.0

-  Functions: 1992
-  Symbols:   2897
-  CStrings:  1773
+  Functions: 1998
+  Symbols:   2903
+  CStrings:  1775
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
