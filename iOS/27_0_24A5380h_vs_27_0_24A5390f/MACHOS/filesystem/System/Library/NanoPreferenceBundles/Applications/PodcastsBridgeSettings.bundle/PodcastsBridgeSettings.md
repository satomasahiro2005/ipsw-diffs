## PodcastsBridgeSettings

> `/System/Library/NanoPreferenceBundles/Applications/PodcastsBridgeSettings.bundle/PodcastsBridgeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xff40` | `0xfff8` | **`+0xb8`** |
| `__TEXT.__ustring` | `0x8de` | `0x984` | **`+0xa6`** |
| `__DATA_CONST.__cfstring` | `0xfe0` | `0x1000` | **`+0x20`** |
| `__TEXT.__cstring` | `0xb66` | `0xb4a` | **`-0x1c`** |
| `__TEXT.__unwind_info` | `0x408` | `0x400` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4027.100.75.0.0
+4027.100.80.0.0

-  CStrings:  852
+  CStrings:  853
Functions:
~ sub_2678 : 12 -> 104
~ sub_2684 -> sub_26e0 : 12 -> 104
CStrings:
+ "OPEN_PODCASTS"
+ "OPEN_PODCASTS_FOOTER_STRING"
+ "To download podcasts on Apple\u00a0Watch, open the Podcasts app to update your library."
- "Launch Podcasts [Eng UI]"
- "Launch Podcasts to migrate database [Eng UI]"
```
