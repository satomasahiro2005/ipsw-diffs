## CoreRoutine

> `/System/Library/PrivateFrameworks/CoreRoutine.framework/CoreRoutine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6dfac` | `0x70c9c` | **`+0x2cf0`** |
| `__TEXT.__unwind_info` | `0x2070` | `0x2140` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x1508` | `0x1558` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x6560` | `0x6580` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x374` | `0x38c` | **`+0x18`** |
| `__TEXT.__cstring` | `0x773b` | `0x7748` | **`+0xd`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c08` | `0x2c10` | **`+0x8`** |

### Other Changes

```diff

-1117.0.0.0.0
+1119.0.0.0.0

-  Functions: 3113
-  Symbols:   5498
-  CStrings:  1218
+  Functions: 3114
+  Symbols:   5503
+  CStrings:  1219
Symbols:
+ GCC_except_table583
+ GCC_except_table587
+ ___58-[RTRoutineManager _enumerateElevationsWithOptions:reply:]_block_invoke_2
+ ___58-[RTRoutineManager _enumerateElevationsWithOptions:reply:]_block_invoke_3
+ ___block_descriptor_104_e8_32s40s48bs56r64r72r80r88r96r_e5_v8?0lr56l8s32l8r64l8s40l8s48l8r72l8r80l8r88l8r96l8
+ ___block_descriptor_56_e8_32bs40r48r_e17_v16?0"NSError"8lr40l8r48l8s32l8
+ ___block_descriptor_56_e8_32s40bs48r_e29_v24?0"NSArray"8"NSError"16lr48l8s32l8s40l8
+ ___block_descriptor_72_e8_32s40s48bs56r64r_e26_v24?08"RTTransaction"16lr56l8s32l8r64l8s40l8s48l8
+ ___block_descriptor_96_e8_32s40bs48r56r64r72r80r88r_e29_v24?0"NSArray"8"NSError"16ls32l8r48l8r56l8s40l8r64l8r72l8r80l8r88l8
- GCC_except_table585
- ___block_descriptor_56_e8_32s40bs48r_e29_v24?0"NSArray"8"NSError"16ls32l8r48l8s40l8
- ___block_descriptor_64_e8_32s40s48bs56r_e5_v8?0lr56l8s48l8s32l8s40l8
- ___block_descriptor_88_e8_32s40bs48r56r64r72r80r_e29_v24?0"NSArray"8"NSError"16lr48l8r56l8s40l8r64l8r72l8r80l8s32l8
CStrings:
+ ".queueHopGap"
```
