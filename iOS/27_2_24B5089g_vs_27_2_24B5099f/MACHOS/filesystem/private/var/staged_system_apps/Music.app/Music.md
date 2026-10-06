## Music

> `/private/var/staged_system_apps/Music.app/Music`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x102c918` | `0x102f0a0` | **`+0x2788`** |
| `__DATA_CONST.__const` | `0x7c548` | `0x7c6d8` | **`+0x190`** |
| `__DATA.__bss` | `0x63a48` | `0x63b48` | **`+0x100`** |
| `__TEXT.__constg_swiftt` | `0x37044` | `0x37108` | **`+0xc4`** |
| `__DATA.__objc_data` | `0x31cf0` | `0x31d90` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x2c141` | `0x2c1e1` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x27abc` | `0x27b48` | **`+0x8c`** |
| `__DATA.__objc_const` | `0x403a0` | `0x40420` | **`+0x80`** |
| `__TEXT.__const` | `0x72b80` | `0x72c00` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x1e0bc` | `0x1e128` | **`+0x6c`** |
| `__TEXT.__auth_stubs` | `0x11a40` | `0x11aa0` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x40cd8` | `0x40d30` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x2d2d0` | `0x2d320` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x62a50` | `0x62a9e` | **`+0x4e`** |
| `__DATA.__data` | `0x4f050` | `0x4f010` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0x1c2c0` | `0x1c280` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0x8d30` | `0x8d60` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x3937a` | `0x393aa` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x9b58` | `0x9b48` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0xcc38` | `0xcc48` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x73a0` | `0x73b0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x5db78` | `0x5db68` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x3abc` | `0x3ac4` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x276c` | `0x2774` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1578` | `0x1574` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-4026.200.16.0.0
+4026.210.24.1.0

-  Functions: 64619
-  Symbols:   9398
-  CStrings:  15723
+  Functions: 64659
+  Symbols:   9407
+  CStrings:  15726
Symbols:
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s16MusicKitInternal0A21AlbumDetailDataSourceC4KindO7catalogyAE0aB00D0V_AG0A22CatalogResourceRequestVyAIGtcAEmFWC
+ _$s16MusicKitInternal0A21AlbumDetailDataSourceC4KindOMa
+ _$s16MusicKitInternal0A21AlbumDetailDataSourceC4kindA2C4KindO_tcfc
+ _$s16MusicKitInternal0A21AlbumDetailDataSourceC5album0aB00D0Vvg
+ _$s16MusicKitInternal0A21AlbumDetailDataSourceCMa
+ _$s16MusicKitInternal0A21AlbumDetailDataSourceCMn
+ _$s5UIKit35UICollectionLayoutListConfigurationV10AppearanceO12sidebarPlainyA2EmFWC
+ _$s8MusicKit07PartialA8PropertyC0aB8InternalAA5AlbumVRszlE25pushNotificationChannelIDAA0a17ExtendedAttributeD0CyAFSSGvgZ
+ _$s8MusicKit5AlbumV0aB8InternalE25pushNotificationChannelIDSSSgvg
- _$s5UIKit25UIBackgroundConfigurationV26listAccompaniedSidebarCellACyFZ
CStrings:
+ "autoupdatingCatalogResponse"
+ "axis"
+ "elapsedTrackHeightConstraint"
+ "jojo_unlocked"
+ "music-channel-subscriptions"
+ "startingLength"
+ "systemImageNamed:compatibleWithTraitCollection:"
+ "trackWidthConstraint"
- "Detail page badge for upcoming track with release year included"
- "_setAdditionalMinimumTopInset:"
- "_setMarginInCompactHeight:"
- "_setMarginInRegularWidthRegularHeight:"
- "startingWidth"
```
