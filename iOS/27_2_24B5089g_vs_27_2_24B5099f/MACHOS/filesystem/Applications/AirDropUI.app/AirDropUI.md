## AirDropUI

> `/Applications/AirDropUI.app/AirDropUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13df0c` | `0x13f628` | **`+0x171c`** |
| `__TEXT.__swift5_typeref` | `0x2576c` | `0x25a62` | **`+0x2f6`** |
| `__TEXT.__const` | `0xcfc4` | `0xd0c4` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x6a38` | `0x6ae8` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0x7ba0` | `0x7c10` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x2ae0` | `0x2b40` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x44a0` | `0x44f0` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x289a` | `0x28da` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x231c` | `0x235c` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x29cd` | `0x2a0d` | **`+0x40`** |
| `__DATA.__data` | `0x8040` | `0x8070` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x1558` | `0x1580` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x2258` | `0x2280` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x4c60` | `0x4c88` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x31a0` | `0x31c0` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x4078` | `0x4094` | **`+0x1c`** |
| `__DATA.__objc_data` | `0x2290` | `0x22a8` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x15d8` | `0x15ec` | **`+0x14`** |
| `__TEXT.__swift5_mpenum` | `0x30` | `0x44` | **`+0x14`** |
| `__DATA.__bss` | `0x7ed8` | `0x7ee8` | **`+0x10`** |
| `__DATA.__objc_const` | `0xa770` | `0xa778` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1448` | `0x1450` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1cac` | `0x1cb4` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2c8` | `0x2cc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2131.20.71.0.0
+2131.21.21.0.0

+  - /System/Library/Frameworks/CoreText.framework/CoreText

-  Functions: 4521
-  Symbols:   2075
-  CStrings:  1760
+  Functions: 4531
+  Symbols:   2082
+  CStrings:  1766
Symbols:
+ _$s10Foundation16AttributedStringV8CoreTextE10LineHeightV5tightAFvgZ
+ _$s10Foundation16AttributedStringV8CoreTextE10LineHeightV8variableAFvgZ
+ _$s10Foundation16AttributedStringV8CoreTextE10LineHeightVMa
+ _$s10Foundation16AttributedStringV8CoreTextE10LineHeightVMn
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s7SwiftUI4FontV4boldACyF
+ _$s7SwiftUI4TextV14TruncationModeO6middleyA2EmFWC
+ _$s7SwiftUI4ViewPAAE10lineHeightyQr10Foundation16AttributedStringV8CoreTextE04LineE0VSgF
+ _$s7SwiftUI4ViewPAAE10lineHeightyQr10Foundation16AttributedStringV8CoreTextE04LineE0VSgFQOMQ
+ _$sSiSZsMc
+ _$sSiSxsWP
+ _$sSnyxGSksSxRzSZ6StrideRpzrlMc
+ _$sSy10FoundationE10components11separatedBySaySSGqd___tSyRd__lF
- _$s10Foundation4DateVSLAAMc
- _$s7SwiftUI17EnvironmentValuesV11lineSpacing12CoreGraphics7CGFloatVvg
- _$s7SwiftUI17EnvironmentValuesV11lineSpacing12CoreGraphics7CGFloatVvpMV
- _$s7SwiftUI17EnvironmentValuesV11lineSpacing12CoreGraphics7CGFloatVvs
- _$sSL2geoiySbx_xtFZTj
- _$ss8DurationV7secondsyABSdFZ
CStrings:
+ "conversationManager:debugSendInterpreterLink:toHandle:"
+ "horizontalSizeClass"
+ "setNeedsUpdateOfSupportedInterfaceOrientations"
+ "traitCollectionDidChange:"
+ "v40@0:8@\"TUConversationManager\"16@\"NSString\"24@\"NSString\"32"
+ "verticalSizeClass"
```
