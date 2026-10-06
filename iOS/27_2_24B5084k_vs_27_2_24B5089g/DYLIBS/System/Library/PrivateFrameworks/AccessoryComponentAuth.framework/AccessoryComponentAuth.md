## AccessoryComponentAuth

> `/System/Library/PrivateFrameworks/AccessoryComponentAuth.framework/AccessoryComponentAuth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12a34` | `0x12bec` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0x1248` | `0x12ca` | **`+0x82`** |
| `__AUTH_CONST.__const` | `0xc68` | `0xc88` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1720` | `0x1740` | **`+0x20`** |
| `__DATA.__bss` | `0x118` | `0x128` | **`+0x10`** |
| `__TEXT.__const` | `0xd720` | `0xd730` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x440` | `0x448` | **`+0x8`** |

### Other Changes

```diff

-1219.40.5.0.0
+1219.40.7.0.0

-  Functions: 491
-  Symbols:   1508
-  CStrings:  351
+  Functions: 497
+  Symbols:   1514
+  CStrings:  353
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
