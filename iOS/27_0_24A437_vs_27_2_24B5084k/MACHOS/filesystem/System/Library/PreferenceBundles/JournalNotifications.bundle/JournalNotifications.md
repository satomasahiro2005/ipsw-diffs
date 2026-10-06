## JournalNotifications

> `/System/Library/PreferenceBundles/JournalNotifications.bundle/JournalNotifications`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa6464` | `0xa6dcc` | **`+0x968`** |
| `__DATA.__data` | `0x58e0` | `0x57b0` | **`-0x130`** |
| `__DATA.__objc_data` | `0x6be0` | `0x6b20` | **`-0xc0`** |
| `__TEXT.__eh_frame` | `0x2a98` | `0x2b40` | **`+0xa8`** |
| `__TEXT.__objc_methname` | `0x3236` | `0x32d6` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x305c` | `0x2fce` | **`-0x8e`** |
| `__TEXT.__constg_swiftt` | `0x36e4` | `0x365c` | **`-0x88`** |
| `__TEXT.__objc_stubs` | `0x2d20` | `0x2d80` | **`+0x60`** |
| `__DATA.__objc_const` | `0x33b0` | `0x3360` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x3920` | `0x3950` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x13a0` | `0x13d0` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x3be0` | `0x3c10` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2104` | `0x2134` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0xef4` | `0xec4` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x1159` | `0x1189` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x7f0` | `0x7c0` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0xdf8` | `0xe10` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x1df8` | `0x1e10` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xf28` | `0xf40` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1f00` | `0x1f18` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x21e8` | `0x21fc` | **`+0x14`** |
| `__TEXT.__const` | `0x6bc4` | `0x6bb4` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x534` | `0x544` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1a4f` | `0x1a5f` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1e8` | `0x1e0` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x478` | `0x470` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x190` | `0x198` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x274` | `0x270` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0xb0` | `0xb4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-99.2.2.0.0
+109.0.0.0.0

-  Functions: 2654
-  Symbols:   462
-  CStrings:  1011
+  Functions: 2640
+  Symbols:   461
+  CStrings:  1016
Symbols:
- _swift_retain_x24
CStrings:
+ "Couldn't generate a thumbnail for %{public}s asset. Attachments count: %{public}ld [%{public}s]"
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
- "Image created from file [%{public}s]"
- "Image was not found in cache or in an attachment file. Asset type: %{public}s, Attachments count: %{public}ld [%{public}s]"
- "Legacy support - data attachment [0] is nil"
- "Legacy support - will try to get image from Core Data"
- "_TtC20JournalNotifications17CanvasGridManager"
- "fileExistsAtPath:"
```
