## VideoConferenceControlCenterModule

> `/System/Library/ControlCenter/Bundles/VideoConferenceControlCenterModule.bundle/VideoConferenceControlCenterModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x277c8` | `0x2891c` | **`+0x1154`** |
| `__TEXT.__objc_stubs` | `0x1d20` | `0x1ee0` | **`+0x1c0`** |
| `__TEXT.__objc_methname` | `0x2d18` | `0x2ea8` | **`+0x190`** |
| `__DATA_CONST.__const` | `0x11e0` | `0x12d0` | **`+0xf0`** |
| `__DATA.__objc_data` | `0xae8` | `0xbd0` | **`+0xe8`** |
| `__TEXT.__const` | `0x10e8` | `0x11b8` | **`+0xd0`** |
| `__DATA.__objc_const` | `0x2650` | `0x2710` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x10e0` | `0x1190` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x870` | `0x8ec` | **`+0x7c`** |
| `__DATA.__objc_selrefs` | `0xae0` | `0xb50` | **`+0x70`** |
| `__DATA.__data` | `0x9c0` | `0xa20` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0x351` | `0x3b1` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0xe31` | `0xe91` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x880` | `0x8d8` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0xb14` | `0xb64` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x970` | `0x9c0` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x870` | `0x8a4` | **`+0x34`** |
| `__TEXT.__cstring` | `0x18c4` | `0x18e4` | **`+0x20`** |
| `__DATA.__bss` | `0xdf0` | `0xde0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x2a8` | `0x2b8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x5f0` | `0x600` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x60` | `0x68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-765.11.1.0.0
+765.14.1.0.0

+  - /System/Library/Frameworks/QuartzCore.framework/QuartzCore

-  Functions: 950
-  Symbols:   283
-  CStrings:  818
+  Functions: 982
+  Symbols:   295
+  CStrings:  838
Symbols:
+ _CGColorCreate
+ _CGColorSpaceCreateDeviceRGB
+ _CGColorSpaceCreateWithName
+ _CGRectGetMaxX
+ _CGRectGetMidY
+ _CGRectGetMinX
+ _OBJC_CLASS_$_CAGradientLayer
+ _kCGColorSpaceLinearSRGB
+ _objc_destroyWeak
+ _objc_loadWeakRetained
+ _objc_storeWeak
+ _swift_arrayInitWithCopy
CStrings:
+ "1"
+ "CGColor"
+ "CONTROL_CENTER_EDGE_LIGHT_INTENSITY_LABEL_ALL_CAPS"
+ "T#,N,R"
+ "T@\"<VideoEffectsManagerDelegate>\",W,N,V_delegate"
+ "_TtCC34VideoConferenceControlCenterModule13EffectControl23ColorSliderGradientView"
+ "blackColor"
+ "colorSliderGradientView"
+ "colorSliderIndicatorView"
+ "colorSliderValueChangedForIndicator"
+ "containerViewHeightConstraint"
+ "edgeLightDevOverrideActive"
+ "removeTarget:action:forControlEvents:"
+ "setColors:"
+ "setCornerRadius:"
+ "setEndPoint:"
+ "setFrame:"
+ "setLocations:"
+ "setShadowColor:"
+ "setShadowOffset:"
+ "setStartPoint:"
+ "setUserInteractionEnabled:"
+ "tertiaryLabelColor"
- "CONTROL_CENTER_LINE_WIDTH"
- "T@\"<VideoEffectsManagerDelegate>\",&,N,V_delegate"
- "quaternaryLabelColor"
```
