## SpriteKit

> `/System/Library/Frameworks/SpriteKit.framework/SpriteKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcb9a8` | `0xcbad4` | **`+0x12c`** |
| `__DATA_CONST.__const` | `0xa20` | `0xa48` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x4230` | `0x4240` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x13d24` | `0x13d34` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x58d8` | `0x58e8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x668` | `0x670` | **`+0x8`** |

### Other Changes

```diff

-53.0.2.0.0
+53.1.1.0.0

-  Functions: 4220
-  Symbols:   7082
+  Functions: 4221
+  Symbols:   7087
Symbols:
+ GCC_except_table202
+ GCC_except_table204
+ GCC_except_table209
+ GCC_except_table212
+ GCC_except_table216
+ GCC_except_table218
+ GCC_except_table224
+ GCC_except_table229
+ _OBJC_CLASS_$_NSThread
+ ____ZL12_removeChildP6SKNodeS0_P7SKScene_block_invoke
+ ___block_descriptor_48_ea8_32s40s_e5_v8?0ls32l8s40l8
- GCC_except_table203
- GCC_except_table211
- GCC_except_table215
- GCC_except_table217
- GCC_except_table223
- GCC_except_table228
Functions:
~ -[SKTileMapNode initWithCoder:] : 1188 -> 1208
~ -[SKTileMapNode initWithTileSet:columns:rows:tileSize:tileGroupLayout:] : 540 -> 560
~ -[SKTileMapNode setColumns:andRows:] : 448 -> 508
~ __ZL12_removeChildP6SKNodeS0_P7SKScene : 368 -> 448
+ ____ZL12_removeChildP6SKNodeS0_P7SKScene_block_invoke
~ _SKGetVersionString : 164 -> 168
```
