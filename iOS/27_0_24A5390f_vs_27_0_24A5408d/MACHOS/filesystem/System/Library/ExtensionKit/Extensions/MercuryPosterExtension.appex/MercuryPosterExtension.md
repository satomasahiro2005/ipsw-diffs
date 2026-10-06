## MercuryPosterExtension

> `/System/Library/ExtensionKit/Extensions/MercuryPosterExtension.appex/MercuryPosterExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfd1e4` | `0xfd5e4` | **`+0x400`** |
| `__DATA.__common` | `0x3ac0` | `0x38b0` | **`-0x210`** |
| `__TEXT.__objc_methname` | `0x81e8` | `0x82f8` | **`+0x110`** |
| `__TEXT.__swift5_typeref` | `0x22bf` | `0x2357` | **`+0x98`** |
| `__TEXT.__objc_stubs` | `0x2de0` | `0x2e40` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x2815` | `0x2875` | **`+0x60`** |
| `__DATA.__objc_const` | `0x6758` | `0x6718` | **`-0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x4368` | `0x432c` | **`-0x3c`** |
| `__DATA.__data` | `0x5638` | `0x5608` | **`-0x30`** |
| `__DATA.__objc_data` | `0x820` | `0x850` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x42be` | `0x428e` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x3690` | `0x36b8` | **`+0x28`** |
| `__TEXT.__const` | `0xb2d8` | `0xb2b8` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x1910` | `0x1928` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xf0e8` | `0xf0d8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x6d8` | `0x6e8` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x1ff8` | `0x2000` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1bc8` | `0x1bd0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-84.0.0.0.0
+88.0.1.0.0

-  Functions: 2740
-  Symbols:   394
-  CStrings:  2137
+  Functions: 2735
+  Symbols:   396
+  CStrings:  2140
Symbols:
+ _OBJC_CLASS_$_PRPosterDescriptorGalleryTitleStyle
+ _PRDisplayTypeEmbedded
CStrings:
+ "Celosia unable to create MTLBinaryArchive. Error: %s"
+ "currentRunLoop"
+ "currentScreen"
+ "galleryOptionsWithAssetLookupInfo:galleryPresentationStyle:galleryDisplayStyle:preferredTitleStyles:snapshotPreferences:"
+ "initWithPreferredTimeMaxYPortrait:preferredTimeMaxYLandscape:"
+ "vertConstants"
+ "🖥️ screen changed"
- "normX"
- "normY"
- "normZ"
- "petalUniforms"
```
