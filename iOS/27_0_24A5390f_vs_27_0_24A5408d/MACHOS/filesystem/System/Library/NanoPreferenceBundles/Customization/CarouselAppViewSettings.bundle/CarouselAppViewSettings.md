## CarouselAppViewSettings

> `/System/Library/NanoPreferenceBundles/Customization/CarouselAppViewSettings.bundle/CarouselAppViewSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22d08` | `0x22ca0` | **`-0x68`** |
| `__DATA_CONST.__got` | `0x4a0` | `0x498` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1115.0.101.0.0
+1115.0.105.0.0

-  Symbols:   353
+  Symbols:   352
Symbols:
+ _kFindMyBundleIdentifier
+ _kIntelligentCanvasTrampolineBundleIdentifier
+ _kReadinessBundleIdentifier
- _kFindMyDevicesBundleIdentifier
- _kFindMyItemsBundleIdentifier
- _kFindMyPeopleBundleIdentifier
- _kTinCanBundleIdentifier
Functions:
~ sub_aff8 : 6956 -> 6860
~ sub_cb24 -> sub_cac4 : 320 -> 312
```
