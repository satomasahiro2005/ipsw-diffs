## CarouselLayoutSettings

> `/System/Library/NanoPreferenceBundles/Customization/CarouselLayoutSettings.bundle/CarouselLayoutSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x218c8` | `0x21860` | **`-0x68`** |
| `__DATA_CONST.__got` | `0x458` | `0x450` | **`-0x8`** |

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

-  Symbols:   328
+  Symbols:   327
Symbols:
+ _kFindMyBundleIdentifier
+ _kIntelligentCanvasTrampolineBundleIdentifier
+ _kReadinessBundleIdentifier
- _kFindMyDevicesBundleIdentifier
- _kFindMyItemsBundleIdentifier
- _kFindMyPeopleBundleIdentifier
- _kTinCanBundleIdentifier
Functions:
~ sub_153f4 : 6956 -> 6860
~ sub_16f20 -> sub_16ec0 : 320 -> 312
```
