## ShelfKit

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/ShelfKit.framework/ShelfKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3de87c` | `0x3e0b18` | **`+0x229c`** |
| `__TEXT.__oslogstring` | `0x3aaf` | `0x3c1f` | **`+0x170`** |
| `__DATA.__data` | `0x1e900` | `0x1e9c0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x9907` | `0x99b7` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x1cb70` | `0x1cc10` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0xf178` | `0xf1e0` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0xd19c` | `0xd1f4` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0xd1c8` | `0xd220` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0xaa90` | `0xaae0` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x1717b` | `0x171c1` | **`+0x46`** |
| `__TEXT.__swift5_reflstr` | `0xc742` | `0xc782` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x4520` | `0x4554` | **`+0x34`** |
| `__TEXT.__constg_swiftt` | `0xc9e8` | `0xca18` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x5558` | `0x5580` | **`+0x28`** |
| `__DATA.__objc_const` | `0x106a0` | `0x106c0` | **`+0x20`** |
| `__TEXT.__const` | `0x2c5e8` | `0x2c608` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x9fb5` | `0x9fc5` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xcc0` | `0xcc4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4027.200.26.0.0
+4027.200.32.0.0

-  Functions: 18944
-  Symbols:   7343
-  CStrings:  3368
+  Functions: 18972
+  Symbols:   7347
+  CStrings:  3379
Symbols:
+ _symbolic _____ 8ShelfKit27LibraryMediaArtworkProtocolV10ShowLookup33_A0EFE9A5F50BA812268A598984663E49LLO
+ _symbolic _____Sg5model______6adamIDSSSg5titlet 18PodcastsFoundation12ArtworkModelV s5Int64V
+ _symbolic _____SgXwz_Xx 8ShelfKit20NewEpisodesPresenterC
+ _symbolic _____XDXMT 8ShelfKit20NewEpisodesPresenterC
CStrings:
+ "Library show artwork failed to load. uuid: %{public}s, adamID: %{public}lld, template: %{public}s, size: %{public}s, error: %@"
+ "Library show artwork unavailable, no managed object context: %@"
+ "Library show artwork: no show for uuid %{public}s"
+ "Library show artwork: show has no artwork model. uuid: %{public}s, adamID: %{public}lld, title: %s"
+ "MARK_SEASON_AS_PLAYED"
+ "MARK_SEASON_AS_UNPLAYED"
+ "Mark All As Played"
+ "Mark All As Unplayed"
+ "accessibilityTitle"
+ "manuallyDeselectAll"
+ "model adamID title "
```
