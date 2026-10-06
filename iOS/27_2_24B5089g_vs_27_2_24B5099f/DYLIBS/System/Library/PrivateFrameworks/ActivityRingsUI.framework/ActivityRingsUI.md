## ActivityRingsUI

> `/System/Library/PrivateFrameworks/ActivityRingsUI.framework/ActivityRingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22670` | `0x228f4` | **`+0x284`** |
| `__AUTH_CONST.__objc_const` | `0x98d8` | `0x9938` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x31fc` | `0x3234` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x768` | `0x788` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1878` | `0x1890` | **`+0x18`** |
| `__TEXT.__const` | `0x1144` | `0x1154` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x688` | `0x690` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3d8` | `0x3e0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc80` | `0xc88` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2027.1.1.0.0
+2027.1.2.0.0

-  Functions: 1308
-  Symbols:   2439
+  Functions: 1315
+  Symbols:   2450
Symbols:
+ -[ARUIRing setUseLightMode:]
+ -[ARUIRing useLightMode]
+ -[ARUIRingGroup setUseLightMode:]
+ -[ARUIRingGroup setUseLightMode:ofRingAtIndex:]
+ -[ARUIRingGroup useLightMode]
+ GCC_except_table28
+ GCC_except_table31
+ GCC_except_table34
+ GCC_except_table38
+ GCC_except_table49
+ GCC_except_table55
+ GCC_except_table63
+ GCC_except_table67
+ _OBJC_IVAR_$_ARUIRing._useLightMode
+ _OBJC_IVAR_$_ARUIRingGroup._useLightMode
+ ___20-[ARUIRing isEqual:]_block_invoke_14
+ ___33-[ARUIRingGroup setUseLightMode:]_block_invoke
+ ___block_descriptor_33_e25_v32?0"ARUIRing"8Q16^B24l
+ _arc4random_uniform
- GCC_except_table26
- GCC_except_table29
- GCC_except_table32
- GCC_except_table36
- GCC_except_table39
- GCC_except_table52
- GCC_except_table57
- GCC_except_table64
```
