## Pegasus

> `/System/Library/PrivateFrameworks/Pegasus.framework/Pegasus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42fd8` | `0x43c38` | **`+0xc60`** |
| `__AUTH_CONST.__objc_const` | `0xac18` | `0xada0` | **`+0x188`** |
| `__TEXT.__objc_methlist` | `0x45ac` | `0x4654` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0xc80` | `0xcd0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x1c10` | `0x1c60` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x450` | `0x488` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x2cd0` | `0x2d08` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1438` | `0x1470` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x2f20` | `0x2f40` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x5cc` | `0x5e4` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4ec` | `0x500` | **`+0x14`** |
| `__TEXT.__cstring` | `0x47ce` | `0x47de` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x198` | `0x1a0` | **`+0x8`** |

### Other Changes

```diff

-305.0.0.0.0
+307.0.0.0.0

-  Functions: 1744
-  Symbols:   3135
-  CStrings:  665
+  Functions: 1761
+  Symbols:   3165
+  CStrings:  666
Symbols:
+ -[PGButtonGroupView .cxx_destruct]
+ -[PGButtonGroupView _configureButton:forGlass:]
+ -[PGButtonGroupView _layoutVisibleButtons]
+ -[PGButtonGroupView _resizeAroundCurrentVisibility]
+ -[PGButtonGroupView groupSize]
+ -[PGButtonGroupView initWithFrame:wantsGlassBackground:buttons:]
+ -[PGButtonGroupView layoutSubviews]
+ -[PGButtonGroupView setButton:hidden:]
+ -[PGControlsViewModel isInProminentMode]
+ -[PGControlsViewModel setInProminentMode:]
+ -[PGControlsViewModelValues isInProminentMode]
+ -[PGPictureInPictureViewController isInProminentMode]
+ -[PGPictureInPictureViewController setInProminentMode:]
+ GCC_except_table3
+ _OBJC_CLASS_$_PGButtonGroupView
+ _OBJC_IVAR_$_PGButtonGroupView._allButtons
+ _OBJC_IVAR_$_PGButtonGroupView._animator
+ _OBJC_IVAR_$_PGButtonGroupView._collapsedButtons
+ _OBJC_IVAR_$_PGButtonGroupView._wantsGlassBackground
+ _OBJC_IVAR_$_PGControlsView._allSingleButtons
+ _OBJC_IVAR_$_PGControlsView._topRightGroup
+ _OBJC_IVAR_$_PGControlsViewModel._inProminentMode
+ _OBJC_METACLASS_$_PGButtonGroupView
+ __OBJC_$_INSTANCE_METHODS_PGButtonGroupView
+ __OBJC_$_INSTANCE_VARIABLES_PGButtonGroupView
+ __OBJC_CLASS_RO_$_PGButtonGroupView
+ __OBJC_METACLASS_RO_$_PGButtonGroupView
+ ___38-[PGButtonGroupView setButton:hidden:]_block_invoke
+ ___38-[PGButtonGroupView setButton:hidden:]_block_invoke_2
+ ___block_descriptor_49_e8_32s40r_e8_v16?0q8ls32l8r40l8
+ ___block_descriptor_97_e8_32s40s_e5_v8?0ls32l8s40l8
- _OBJC_IVAR_$_PGControlsView._allButtons
CStrings:
+ "isInProminentMode"
```
