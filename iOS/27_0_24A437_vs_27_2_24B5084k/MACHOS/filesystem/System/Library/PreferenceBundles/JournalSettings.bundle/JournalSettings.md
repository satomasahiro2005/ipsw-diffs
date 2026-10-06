## JournalSettings

> `/System/Library/PreferenceBundles/JournalSettings.bundle/JournalSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76b3c` | `0x7b3fc` | **`+0x48c0`** |
| `__DATA.__objc_data` | `0x6a28` | `0x6968` | **`-0xc0`** |
| `__TEXT.__auth_stubs` | `0x3330` | `0x33f0` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x2f24` | `0x2e6c` | **`-0xb8`** |
| `__TEXT.__objc_methname` | `0x2c36` | `0x2ce6` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x1c40` | `0x1ce8` | **`+0xa8`** |
| `__DATA_CONST.__got` | `0xf00` | `0xf90` | **`+0x90`** |
| `__DATA.__data` | `0x4788` | `0x4718` | **`-0x70`** |
| `__TEXT.__oslogstring` | `0x1165` | `0x11d5` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x19a0` | `0x1a00` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x2480` | `0x24e0` | **`+0x60`** |
| `__DATA.__objc_const` | `0x3110` | `0x30c0` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x15b0` | `0x15e8` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x1e46` | `0x1e14` | **`-0x32`** |
| `__DATA_CONST.__const` | `0x2cb0` | `0x2ce0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2984` | `0x29b4` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0xe6f` | `0xe3f` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `0x5d8` | `0x5a8` | **`-0x30`** |
| `__DATA_CONST.__auth_ptr` | `0xbd8` | `0xc00` | **`+0x28`** |
| `__DATA.__common` | `0x478` | `0x460` | **`-0x18`** |
| `__DATA.__objc_selrefs` | `0xbe8` | `0xc00` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x1858` | `0x186c` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x4f0` | `0x500` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x14fa` | `0x150a` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1e8` | `0x1e0` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x300` | `0x2f8` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0xd0` | `0xd8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1dc` | `0x1d8` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x98` | `0x9c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-99.2.2.0.0
+109.0.0.0.0

-  Functions: 1836
-  Symbols:   347
-  CStrings:  971
+  Functions: 1843
+  Symbols:   348
+  CStrings:  977
Symbols:
+ _swift_initStaticObject
+ _swift_release_x12
- _swift_retain_x24
CStrings:
+ "Couldn't generate a thumbnail for %{public}s asset. Attachments count: %{public}ld [%{public}s]"
+ "FUP-AVAIL Apple Intelligence restricted: %{public}s"
+ "FUP-AVAIL Apple Intelligence unavailable: %{public}s"
+ "FUP-AVAIL model restricted: %{public}s"
+ "FUP-AVAIL model unavailable: %{public}s"
+ "MultiPinMapAnnotationRenderer: missing glyph for Maps-style single pin; rendering generic marker fallback"
+ "Thumbnail created for %{public}s asset from file [%{public}s]"
+ "Thumbnail created from legacy field [%{public}s]"
+ "assetMediaResolutionChangeObserver"
+ "com.apple.journal.PersistentCache"
+ "imageQueue"
+ "imageWithTintColor:"
+ "resolvedColorWithTraitCollection:"
+ "tertiarySystemBackgroundColor"
+ "userInterfaceStyle"
- "FUP-AVAIL journaling.FollowUpPrompts availability=%{public}s"
- "FUP-AVAIL restricted reasons=[%{public}s]"
- "FUP-AVAIL unavailable reasons=[%{public}s]"
- "Image created from file [%{public}s]"
- "Image was not found in cache or in an attachment file. Asset type: %{public}s, Attachments count: %{public}ld [%{public}s]"
- "Legacy support - data attachment [0] is nil"
- "Legacy support - will try to get image from Core Data"
- "_TtC15JournalSettings17CanvasGridManager"
- "fileExistsAtPath:"
```
