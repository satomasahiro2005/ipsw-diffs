## Symbolication

> `/System/Library/PrivateFrameworks/Symbolication.framework/Symbolication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x608` | `0x1238` | **`+0xc30`** |
| `__DATA_DIRTY.__objc_data` | `0x1838` | `0xc08` | **`-0xc30`** |
| `__TEXT.__text` | `0xbb7a8` | `0xbb97c` | **`+0x1d4`** |
| `__DATA_CONST.__const` | `0x3e98` | `0x3ee8` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0xcb60` | `0xcb80` | **`+0x20`** |
| `__TEXT.__cstring` | `0x11268` | `0x11288` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x586c` | `0x5884` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x69d8` | `0x69f0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x39e8` | `0x39f8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x498` | `0x4a0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2d98` | `0x2da0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xd98` | `0xd9c` | **`+0x4`** |

### Other Changes

```diff

-64578.89.1.0.0
+64578.92.1.0.0

-  Functions: 3372
-  Symbols:   6127
-  CStrings:  2898
+  Functions: 3375
+  Symbols:   6134
+  CStrings:  2899
Symbols:
+ -[VMUObjectIdentifier buildOriginalMetaclassMap]
+ -[VMUObjectIdentifier originalMetaclassForObjCClassWithIsa:]
+ GCC_except_table137
+ GCC_except_table146
+ GCC_except_table148
+ GCC_except_table160
+ GCC_except_table166
+ GCC_except_table94
+ _OBJC_IVAR_$_VMUObjectIdentifier._classToOriginalMetaclassMap
+ ___48-[VMUObjectIdentifier buildOriginalMetaclassMap]_block_invoke
+ ___block_descriptor_100_e8_32s40s48bs56r64r_e10_v16?0r^v8ls32l8r56l8s40l8r64l8s48l8
+ ___block_descriptor_64_e8_32s_e22_v24?0r^v8"NSError"16ls32l8
- GCC_except_table143
- GCC_except_table145
- GCC_except_table154
- GCC_except_table163
- GCC_except_table82
CStrings:
+ "_objc_debug_original_metaclass_map"
```
