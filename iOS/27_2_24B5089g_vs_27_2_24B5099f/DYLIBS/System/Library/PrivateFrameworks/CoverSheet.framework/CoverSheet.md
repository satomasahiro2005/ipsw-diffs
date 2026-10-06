## CoverSheet

> `/System/Library/PrivateFrameworks/CoverSheet.framework/CoverSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18d344` | `0x18d5b8` | **`+0x274`** |
| `__AUTH_CONST.__objc_const` | `0x3c7f0` | `0x3c920` | **`+0x130`** |
| `__TEXT.__objc_methlist` | `0x1650c` | `0x1658c` | **`+0x80`** |
| `__TEXT.__cstring` | `0xcb2d` | `0xcaef` | **`-0x3e`** |
| `__AUTH_CONST.__const` | `0xd10` | `0xcf0` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x40d0` | `0x40b0` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xc6e0` | `0xc6f8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1bb4` | `0x1bc4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4868` | `0x4870` | **`+0x8`** |

### Other Changes

```diff

-159.2.1.0.0
+159.2.4.0.0

-  Functions: 7949
-  Symbols:   14099
-  CStrings:  2665
+  Functions: 7957
+  Symbols:   14111
+  CStrings:  2664
Symbols:
+ -[CSBatteryChargingRingView _updateForInternalBattery]
+ -[CSBatteryChargingRingView setPresumeCharging:]
+ -[CSQuickActionControlGlyphView contentInterfaceStyle]
+ -[CSQuickActionControlGlyphView setContentInterfaceStyle:]
+ -[CSQuickActionImageGlyphView contentInterfaceStyle]
+ -[CSQuickActionImageGlyphView setContentInterfaceStyle:]
+ -[CSQuickActionsButton contentInterfaceStyle]
+ -[CSQuickActionsButton setContentInterfaceStyle:]
+ -[CSQuickActionsView contentInterfaceStyle]
+ -[CSQuickActionsView setContentInterfaceStyle:]
+ _CSCoverSheetActiveComponentIdentifier
+ _OBJC_IVAR_$_CSQuickActionImageGlyphView._contentInterfaceStyle
+ _OBJC_IVAR_$_CSQuickActionImageGlyphView._offColor
+ _OBJC_IVAR_$_CSQuickActionsButton._contentInterfaceStyle
+ _OBJC_IVAR_$_CSQuickActionsView._contentInterfaceStyle
+ ___58-[CSQuickActionControlGlyphView setContentInterfaceStyle:]_block_invoke
+ ___block_descriptor_40_e50_v16?0"CHUISMutableControlInstanceConfiguration"8l
- -[CSQuickActionControlGlyphView _updateControlConfigurationColorSchemeWithTraitCollection:previousTraitCollection:]
- ___115-[CSQuickActionControlGlyphView _updateControlConfigurationColorSchemeWithTraitCollection:previousTraitCollection:]_block_invoke
- ___74-[CSQuickActionControlGlyphView initWithControlInstance:symbolScaleValue:]_block_invoke
- ___block_descriptor_32_e61_v24?0"CSQuickActionControlGlyphView"8"UITraitCollection"16l
- ___block_descriptor_40_e8_32s_e50_v16?0"CHUISMutableControlInstanceConfiguration"8ls32l8
CStrings:
+ "\xb1"
- "v24@?0@\"CSQuickActionControlGlyphView\"8@\"UITraitCollection\"16"
- "\xa1"
```
