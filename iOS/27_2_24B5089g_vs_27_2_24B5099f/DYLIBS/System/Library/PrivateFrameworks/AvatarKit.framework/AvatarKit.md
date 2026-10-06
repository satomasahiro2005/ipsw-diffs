## AvatarKit

> `/System/Library/PrivateFrameworks/AvatarKit.framework/AvatarKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x777e4` | `0x77530` | **`-0x2b4`** |
| `__AUTH.__objc_data` | `0x1888` | `0x1860` | **`-0x28`** |
| `__DATA_CONST.__const` | `0x27f0` | `0x2818` | **`+0x28`** |
| `__DATA_DIRTY.__objc_data` | `0x1b8` | `0x1e0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x249a0` | `0x249c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1df4c` | `0x1df61` | **`+0x15`** |
| `__TEXT.__objc_methlist` | `0x54c4` | `0x54cc` | **`+0x8`** |
| `__DATA.__data` | `0x788` | `0x784` | **`-0x4`** |

### Other Changes

```diff

-368.100.0.0.0
+368.101.0.0.0

-  Symbols:   4666
-  CStrings:  5159
+  Symbols:   4667
+  CStrings:  5160
Symbols:
+ -[AVTComponentInstance description]
+ GCC_except_table103
+ GCC_except_table117
+ GCC_except_table128
+ GCC_except_table168
+ ___55-[AVTMemoji addComponentAssetNode:toNode:forBodyParts:]_block_invoke
+ ___block_descriptor_48_e8_32s40r_e21_v24?0"VFXNode"8^B16lr40l8s32l8
- GCC_except_table102
- GCC_except_table116
- GCC_except_table129
- GCC_except_table169
- ___32-[AVTMemoji _updateWithOptions:]_block_invoke
- ___32-[AVTMemoji _updateWithOptions:]_block_invoke_2
CStrings:
+ "<%@ %p | assets: %@>"
```
