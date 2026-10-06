## MediaRemoteUI

> `/Applications/MediaRemoteUI.app/MediaRemoteUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d628` | `0x3d96c` | **`+0x344`** |
| `__DATA_CONST.__const` | `0x1f58` | `0x1fe0` | **`+0x88`** |
| `__TEXT.__objc_methname` | `0x5bed` | `0x5c6d` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x11c1` | `0x1231` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x18c3` | `0x1923` | **`+0x60`** |
| `__TEXT.__const` | `0x1fc4` | `0x1ff4` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x10f8` | `0x1120` | **`+0x28`** |
| `__DATA.__objc_const` | `0xada8` | `0xad88` | **`-0x20`** |
| `__DATA.__objc_data` | `0x3b40` | `0x3b20` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x2b60` | `0x2b80` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0xf0` | `0x104` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x18e0` | `0x18f0` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x7b8` | `0x7a8` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x11f8` | `0x1200` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xc80` | `0xc88` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x6b0` | `0x6b8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x508` | `0x500` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x23d4` | `0x23dc` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x12ae` | `0x12b6` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1008` | `0x1010` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x108` | `0x10c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.100.60.1.0
+4026.100.68.0.0

-  Functions: 1459
+  Functions: 1467
Symbols:
+ _CGRectGetMaxX
+ _CGRectGetMinX
- _OBJC_CLASS_$_UIScreen
- _UIRectInset
CStrings:
+ "LockScreenCoordinator: layoutMetrics is nil. normalizedExtendedContentCutoutBounds: %s, normalizedWidgetsContentCutoutBounds: %s, contentCutoutBounds: %s, platterContentSize: %s, platterViewWidth: %s, backdropSceneScreenSize: %s."
+ "configurationWithPointSize:weight:"
+ "contentCutoutBounds"
+ "contentInsets"
+ "normalizedExtendedContentCutoutBounds"
+ "normalizedWidgetsContentCutoutBounds"
+ "setPreferredSymbolConfiguration:"
- "LockScreenCoordinator: layoutMetrics is nil. topBounds: %s, widgetsTopBounds: %s, platterContentSize: %s, platterViewWidth: %s."
- "bottomBounds"
- "bottomGap"
- "mainScreen"
- "topBounds"
- "topGap"
- "widgetsTopBounds"
```
