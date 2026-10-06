## TVRemoteUI

> `/System/Library/PrivateFrameworks/TVRemoteUI.framework/TVRemoteUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd413c` | `0xd4628` | **`+0x4ec`** |
| `__TEXT.__oslogstring` | `0x5b56` | `0x5c26` | **`+0xd0`** |
| `__AUTH_CONST.__objc_const` | `0x156c0` | `0x15710` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xbc24` | `0xbc6c` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x3900` | `0x38c0` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x6bf0` | `0x6c20` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1908` | `0x1930` | **`+0x28`** |
| `__TEXT.__cstring` | `0x4df1` | `0x4de1` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1d54` | `0x1d64` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xbbc` | `0xbc4` | **`+0x8`** |

### Other Changes

```diff

-627.0.19.0.0
+627.0.28.0.0

-  Functions: 4931
-  Symbols:   7095
-  CStrings:  1247
+  Functions: 4938
+  Symbols:   7105
+  CStrings:  1248
Symbols:
+ -[TVRUIDirectionalControlView didMoveToSuperview]
+ -[TVRUIHintsViewController _hasUserIntentButtonInfo]
+ -[TVRUIHintsViewController _hasVolumeButtonInfo]
+ -[TVRUIResizabilityLayoutManager _occlusionRegionFrame]
+ -[TVRUIResizabilityLayoutManager setShouldAnimateRenderFormatChange:]
+ -[TVRUIResizabilityLayoutManager shouldAnimateRenderFormatChange]
+ GCC_except_table120
+ GCC_except_table188
+ GCC_except_table60
+ GCC_except_table83
+ _OBJC_IVAR_$_TVRUIResizabilityLayoutManager._hasComputedFormat
+ _OBJC_IVAR_$_TVRUIResizabilityLayoutManager._shouldAnimateRenderFormatChange
+ ___51-[TVRUIRemoteViewController viewWillLayoutSubviews]_block_invoke
+ ___block_descriptor_209_e8_32s_e5_v8?0ls32l8
- GCC_except_table187
- GCC_except_table59
- GCC_except_table66
- GCC_except_table82
CStrings:
+ "#directional - toggleControlState mediaControlsAreVisible:%{bool}d landscape:%{bool}d compactWindow:%{bool}d"
+ "No user-intent button geometry for this device, suppressing Siri hint"
+ "No volume-button geometry for this device, suppressing volume hint"
+ "Not starting deviceQueryThresholdTimer - already have an active device"
- "#directional - toggleControlState mediaControlsAreVisible:%{bool}d small:%{bool}d landscape:%{bool}d"
- "alwaysOnCaptions"
- "captions"
```
