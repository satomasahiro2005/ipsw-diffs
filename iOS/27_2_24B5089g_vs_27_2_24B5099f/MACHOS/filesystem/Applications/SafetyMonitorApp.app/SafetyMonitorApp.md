## SafetyMonitorApp

> `/Applications/SafetyMonitorApp.app/SafetyMonitorApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xce60` | `0xc57c` | **`-0x8e4`** |
| `__DATA.__bss` | `0x410` | `0x310` | **`-0x100`** |
| `__TEXT.__swift5_reflstr` | `0x2b4` | `0x1f4` | **`-0xc0`** |
| `__DATA.__objc_data` | `0x610` | `0x560` | **`-0xb0`** |
| `__TEXT.__constg_swiftt` | `0x560` | `0x4bc` | **`-0xa4`** |
| `__DATA.__objc_const` | `0xbd8` | `0xb38` | **`-0xa0`** |
| `__DATA_CONST.__const` | `0x518` | `0x488` | **`-0x90`** |
| `__TEXT.__objc_methname` | `0x1607` | `0x1577` | **`-0x90`** |
| `__TEXT.__const` | `0x5f4` | `0x574` | **`-0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x1fc` | `0x18c` | **`-0x70`** |
| `__TEXT.__cstring` | `0x2c5` | `0x275` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x5cc` | `0x57c` | **`-0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x2b8` | `0x280` | **`-0x38`** |
| `__DATA.__data` | `0x870` | `0x840` | **`-0x30`** |
| `__TEXT.__auth_stubs` | `0xe80` | `0xe50` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x44a` | `0x41e` | **`-0x2c`** |
| `__DATA_CONST.__auth_got` | `0x748` | `0x730` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x2d8` | `0x2c0` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x20` | `0x18` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x34` | `0x30` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1123.0.0.0.0
+1123.0.3.0.0

-  Functions: 233
-  Symbols:   408
-  CStrings:  336
+  Functions: 217
+  Symbols:   398
+  CStrings:  328
Symbols:
+ _swift_retain_x21
- _$s15SafetyMonitorUI0aB11UIConstantsO41liveActivityDynamicIslandInnerEdgePadding12CoreGraphics7CGFloatVvgZ
- _$s15SafetyMonitorUI0aB11UIConstantsO41liveActivityDynamicIslandOuterEdgePadding12CoreGraphics7CGFloatVvgZ
- _$sSH13_rawHashValue4seedS2i_tFTq
- _$sSH4hash4intoys6HasherVz_tFTq
- _$sSH9hashValueSivgTq
- _$sSHMp
- _$sSHSQTb
- _$sSQ2eeoiySbx_xtFZTq
- _$sSQMp
- _$ss6HasherV8_combineyySuF
- _objc_retain_x26
CStrings:
+ "SBUISA_systemApertureLeadingConcentricContentLayoutGuide"
+ "SBUISA_systemApertureTrailingConcentricContentLayoutGuide"
+ "diameter"
+ "setPriority:"
- "%s: isDisplayedWithLimitedSize, %{bool}d"
- "%s: isLimitedSize, %{bool}d"
- "avatarTrailingConstraint"
- "invalidateIntrinsicContentSize"
- "isDisplayedWithLimitedSize"
- "leadingViewWidthConstraint"
- "setConstant:"
- "trailingGlyphLeadingConstraint"
- "trailingViewWidthConstraint"
- "updateConstraintsForLimitedSize()"
- "updateLimitedSizeState(_:)"
- "viewType"
```
