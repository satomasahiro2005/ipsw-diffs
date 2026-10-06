## TVRemoteUI

> `/System/Library/PrivateFrameworks/TVRemoteUI.framework/TVRemoteUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3584` | `0xd3ad0` | **`+0x54c`** |
| `__TEXT.__gcc_except_tab` | `0x1ccc` | `0x1d48` | **`+0x7c`** |
| `__DATA_CONST.__got` | `0xd98` | `0xe10` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x5b36` | `0x5ba6` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x6970` | `0x6920` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x7d0` | `0x820` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xb854` | `0xb89c` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x2fb0` | `0x2fd0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b78` | `0x6b90` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x151f0` | `0x15200` | **`+0x10`** |
| `__DATA.__bss` | `0x2770` | `0x2780` | **`+0x10`** |
| `__TEXT.__cstring` | `0x4d31` | `0x4d41` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2cd8` | `0x2ce8` | **`+0x10`** |

### Other Changes

```diff

-627.0.9.0.0
+627.0.14.0.0

-  Functions: 4854
-  Symbols:   6987
-  CStrings:  1233
+  Functions: 4861
+  Symbols:   6991
+  CStrings:  1236
Symbols:
+ +[TVRUIFeatures isLandscapeModeEnabled]
+ -[TVRUICoreDevice device:updatedPairedRemoteInfo:]
+ -[TVRUIRemoteViewController device:updatedPairedRemoteInfo:]
+ GCC_except_table122
+ GCC_except_table190
+ GCC_except_table62
+ GCC_except_table69
+ GCC_except_table85
+ GCC_except_table99
+ _OBJC_CLASS_$_UITraitActiveAppearance
+ __TVRUISceneLog
+ ____TVRUISceneLog_block_invoke
- GCC_except_table121
- GCC_except_table188
- GCC_except_table23
- GCC_except_table39
- GCC_except_table61
- GCC_except_table68
- GCC_except_table84
- GCC_except_table98
CStrings:
+ "ActiveAppearanceTrait changed:%ld, scene activation state:%ld, supportsSiri:%{bool}d"
+ "Deactivating Siri events"
+ "Paired remote info updated: %@"
+ "Scene"
+ "device: '%{public}@' updated paired remote info: %@"
- "%s - %{public}@"
- "Deactivating connection - notification scene object: %@ current scene: %@"
```
