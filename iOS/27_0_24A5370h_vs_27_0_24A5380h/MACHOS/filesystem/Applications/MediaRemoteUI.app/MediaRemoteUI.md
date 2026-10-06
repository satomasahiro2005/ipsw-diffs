## MediaRemoteUI

> `/Applications/MediaRemoteUI.app/MediaRemoteUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d96c` | `0x3ee68` | **`+0x14fc`** |
| `__TEXT.__oslogstring` | `0x1231` | `0x13e1` | **`+0x1b0`** |
| `__TEXT.__objc_methname` | `0x5c6d` | `0x5d1d` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x2b80` | `0x2c20` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1448` | `0x13e8` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x1fe0` | `0x2030` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x1200` | `0x1238` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1010` | `0x1038` | **`+0x28`** |
| `__DATA.__common` | `0x170` | `0x190` | **`+0x20`** |
| `__DATA.__objc_data` | `0x3b20` | `0x3b40` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x23dc` | `0x23fc` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x6e4` | `0x704` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x12b6` | `0x12d6` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1c78` | `0x1c90` | **`+0x18`** |
| `__DATA.__data` | `0x29a0` | `0x29b0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x6b8` | `0x6c8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x18f0` | `0x1900` | **`+0x10`** |
| `__TEXT.__const` | `0x1ff4` | `0x2004` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xc88` | `0xc90` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.100.68.0.0
+4026.110.75.1.0

-  Functions: 1467
-  Symbols:   731
-  CStrings:  1272
+  Functions: 1479
+  Symbols:   732
+  CStrings:  1284
Symbols:
+ __UISheetContainerInsets
CStrings:
+ "BackdropScene effectiveGeometry updated to %@ from %@"
+ "LockScreenArtwork"
+ "LockScreenCoordinator updateAvailableArtworkBounds - no backdrop scene. Bailing."
+ "[CoverSheetBackgroundView] staticArtworkInsets base: %f contentInsets: %f/%f sheet: %f/%f sizeClass: %ld/%ld"
+ "contentCutoutBoundsForInterfaceOrientation:windowScene:"
+ "effectiveGeometry"
+ "geometry updated"
+ "interfaceOrientation"
+ "protocolName"
+ "protocolUID"
+ "routeRecommendationConnectedToProtocolName:protocolUID:"
+ "routeRecommendationTapToProtocolName:protocolUID:"
+ "safeAreaInsetsDidChange"
+ "updateBackdropSceneGeometry"
+ "verticalSizeClass"
- "contentCutoutBoundsForInterfaceOrientation:"
- "routeRecommendationAirPlayConnected"
- "routeRecommendationTapToAirPlay"
```
