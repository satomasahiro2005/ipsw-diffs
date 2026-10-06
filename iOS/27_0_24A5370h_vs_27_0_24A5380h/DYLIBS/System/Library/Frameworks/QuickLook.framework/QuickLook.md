## QuickLook

> `/System/Library/Frameworks/QuickLook.framework/QuickLook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdd16c` | `0xddf48` | **`+0xddc`** |
| `__AUTH_CONST.__objc_const` | `0x11988` | `0x11b90` | **`+0x208`** |
| `__TEXT.__objc_methlist` | `0xb744` | `0xb864` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x2bb8` | `0x2c68` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x917` | `0x9a7` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x7430` | `0x74a0` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x1800` | `0x1854` | **`+0x54`** |
| `__DATA_DIRTY.__objc_data` | `0x460` | `0x4b0` | **`+0x50`** |
| `__TEXT.__const` | `0x3ad4` | `0x3b24` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0xb0c` | `0xb58` | **`+0x4c`** |
| `__DATA.__data` | `0x3420` | `0x3460` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x46f0` | `0x4730` | **`+0x40`** |
| `__AUTH.__data` | `0x1648` | `0x1680` | **`+0x38`** |
| `__DATA_CONST.__got` | `0xfa8` | `0xfe0` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x14e0` | `0x1500` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0x3340` | `0x3360` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2698` | `0x26b0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xc0c` | `0xc20` | **`+0x14`** |
| `__TEXT.__swift5_typeref` | `0x1cf4` | `0x1d08` | **`+0x14`** |
| `__TEXT.__cstring` | `0x54a4` | `0x54b4` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x470` | `0x478` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x11c` | `0x120` | **`+0x4`** |

### Other Changes

```diff

-1029.0.0.0.0
+1032.0.0.0.0

-  Functions: 5702
-  Symbols:   7513
-  CStrings:  913
+  Functions: 5735
+  Symbols:   7540
+  CStrings:  915
Symbols:
+ -[QLAudioItemViewController prefersArrangedAccessoryView]
+ -[QLAudioItemViewController shouldDisplayPlayButtonInNavigationBar]
+ -[QLAudioItemViewController timeLabelHostView]
+ -[QLItemAggregatedViewController prefersArrangedAccessoryView]
+ -[QLMediaItemViewController timeLabelHostView]
+ -[QLOverlayPlayButton setPlaying:]
+ -[QLPageViewController scrollEdgeEffectsHidden]
+ -[QLPageViewController setScrollEdgeEffectsHidden:]
+ -[QLPreviewCollection prefersArrangedAccessoryView]
+ -[QLPreviewController accessoryArrangementView]
+ -[QLPreviewController prefersArrangedAccessoryView]
+ -[QLPreviewController setAccessoryArrangementView:]
+ -[QLPreviewController setPrefersArrangedAccessoryView:]
+ GCC_except_table158
+ GCC_except_table183
+ GCC_except_table184
+ GCC_except_table202
+ GCC_except_table206
+ GCC_except_table91
+ _OBJC_CLASS_$_QLAudioArrangementViewWrapper
+ _OBJC_IVAR_$_QLAudioItemViewController._arrangementViewWrapper
+ _OBJC_IVAR_$_QLOverlayPlayButton._pauseImage
+ _OBJC_IVAR_$_QLOverlayPlayButton._playImage
+ _OBJC_IVAR_$_QLPageViewController._scrollEdgeEffectsHidden
+ _OBJC_IVAR_$_QLPreviewController._accessoryArrangementView
+ _OBJC_METACLASS_$_QLAudioArrangementViewWrapper
+ __DATA_QLAudioArrangementViewWrapper
+ __INSTANCE_METHODS_QLAudioArrangementViewWrapper
+ __IVARS_QLAudioArrangementViewWrapper
+ __METACLASS_DATA_QLAudioArrangementViewWrapper
+ __PROPERTIES_QLAudioArrangementViewWrapper
+ ___55-[QLPreviewController setPrefersArrangedAccessoryView:]_block_invoke
+ ___swift_closure_destructor.164Tm
+ ___swift_closure_destructor.208Tm
+ ___swift_closure_destructor.353Tm
+ _symbolic _____ 9QuickLook29QLAudioArrangementViewWrapperC
+ _symbolic _____y_____G 5UIKit21_UIArrangementView_v0C AA08_UIStackc12Arrangement_D0V
- GCC_except_table119
- GCC_except_table155
- GCC_except_table177
- GCC_except_table181
- GCC_except_table199
- GCC_except_table203
- GCC_except_table89
- ___swift_closure_destructor.161Tm
- ___swift_closure_destructor.205Tm
- ___swift_closure_destructor.350Tm
CStrings:
+ "A"
+ "pause.fill"
```
