## MobileSlideShowSettings

> `/System/Library/PreferenceBundles/MobileSlideShowSettings.bundle/MobileSlideShowSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c484` | `0x1c81c` | **`+0x398`** |
| `__TEXT.__objc_methname` | `0x488c` | `0x495c` | **`+0xd0`** |
| `__DATA_CONST.__cfstring` | `0x2ca0` | `0x2d40` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x2168` | `0x21e8` | **`+0x80`** |
| `__TEXT.__cstring` | `0x33c8` | `0x343c` | **`+0x74`** |
| `__TEXT.__objc_methlist` | `0x13d0` | `0x1438` | **`+0x68`** |
| `__DATA.__data` | `0x6d8` | `0x738` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x4140` | `0x4180` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x7b3` | `0x7ec` | **`+0x39`** |
| `__DATA.__objc_selrefs` | `0x1468` | `0x1498` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0xdd0` | `0xe00` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x4c0` | `0x4e0` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x506` | `0x523` | **`+0x1d`** |
| `__TEXT.__oslogstring` | `0x13da` | `0x13bd` | **`-0x1d`** |
| `__DATA_CONST.__auth_got` | `0x6f8` | `0x710` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x738` | `0x748` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xf0` | `0xf8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x68` | `0x70` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-910.21.101.0.0
+910.27.103.0.0

-  Functions: 498
-  Symbols:   442
-  CStrings:  1345
+  Functions: 505
+  Symbols:   446
+  CStrings:  1360
Symbols:
+ _OBJC_CLASS_$_CPLTurboSyncObserver
+ _PXIsStarRatingFeatureIsSupported
+ _PXPreferencesIsStarRatingAllowed
+ _PXPreferencesSetStarRatingAllowed
+ _PXPreferencesSetStarRatingBadgingEnabled
- _CPLSetTurboModeExpirationDate
CStrings:
+ "@\"CPLTurboSyncObserver\""
+ "CPLTurboSyncObserverDelegate"
+ "STAR_RATING_SECTION_FOOTER"
+ "STAR_RATING_SECTION_TITLE"
+ "STAR_RATING_SWITCH"
+ "StarRatingSwitch"
+ "Turbo sync changed to Off"
+ "ViewOptionsStarRatingGroup"
+ "_setStarRatingAllowed:specifier:"
+ "_setUpTurboSyncObserver"
+ "_starRatingAllowed:"
+ "_turboSyncObserver"
+ "setExpirationDate:"
+ "turboSyncObserverAvailabilityDidChange:"
+ "turboSyncObserverExpirationDateDidChange:"
+ "v24@0:8@\"CPLTurboSyncObserver\"16"
- "Turbo sync changed to Off — expires %@, 0s remaining"
```
