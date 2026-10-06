## VoiceOver

> `/System/Library/AccessibilityBundles/VoiceOver.axuiservice/VoiceOver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25d60` | `0x24fa4` | **`-0xdbc`** |
| `__TEXT.__objc_methname` | `0x70e6` | `0x6e56` | **`-0x290`** |
| `__TEXT.__objc_stubs` | `0x4d60` | `0x4b60` | **`-0x200`** |
| `__DATA.__objc_const` | `0x3918` | `0x3878` | **`-0xa0`** |
| `__DATA.__objc_selrefs` | `0x1aa0` | `0x1a20` | **`-0x80`** |
| `__DATA_CONST.__cfstring` | `0xd20` | `0xcc0` | **`-0x60`** |
| `__TEXT.__gcc_except_tab` | `0x28c` | `0x244` | **`-0x48`** |
| `__TEXT.__objc_methlist` | `0x1e44` | `0x1dfc` | **`-0x48`** |
| `__TEXT.__cstring` | `0x13b5` | `0x137a` | **`-0x3b`** |
| `__TEXT.__unwind_info` | `0xa10` | `0x9e0` | **`-0x30`** |
| `__DATA.__objc_ivar` | `0x20c` | `0x1fc` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x4b8` | `0x4b0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2470.0.0.0.0
+2472.1.0.0.0

-  Functions: 844
-  Symbols:   416
-  CStrings:  1516
+  Functions: 833
+  Symbols:   413
+  CStrings:  1491
Symbols:
- _OBJC_CLASS_$_NSAttributedString
- _UIEdgeInsetsZero
- _UIFontWeightMedium
CStrings:
+ "TB,N,V_captionTextEnabled"
+ "_captionTextEnabled"
+ "_captionsEnabledChanged"
+ "_reconfigureCaptionLayout"
+ "captionTextEnabled"
+ "isViewLoaded"
+ "setCaptionTextEnabled:"
- "\n%@"
- "T@\"UIScrollView\",&,N,V_sealedChamberScrollView"
- "T@\"UITextView\",&,N,V_sealedChamberText"
- "TB,N,V_showingSealedChamber"
- "VoiceOverSealedChamberKey"
- "VoiceOverSealedChamberSecret"
- "_animateScretChamberTextBack:"
- "_reconfigureLayoutForSealedChamberMode"
- "_sealedChamberHeight"
- "_sealedChamberScrollView"
- "_sealedChamberScrollingAnimator"
- "_sealedChamberScrollingStartTimer"
- "_sealedChamberText"
- "_showingSealedChamber"
- "_updateSecretChamberWithMessage:"
- "appendAttributedString:"
- "constraints"
- "deactivateConstraints:"
- "initWithString:attributes:"
- "monospacedSystemFontOfSize:weight:"
- "sealedChamberScrollView"
- "sealedChamberText"
- "setEditable:"
- "setScrollEnabled:"
- "setSealedChamberScrollView:"
- "setSealedChamberText:"
- "setShowingSealedChamber:"
- "setShowsHorizontalScrollIndicator:"
- "setShowsVerticalScrollIndicator:"
- "setTextContainerInset:"
- "showingSealedChamber"
- "systemYellowColor"
```
