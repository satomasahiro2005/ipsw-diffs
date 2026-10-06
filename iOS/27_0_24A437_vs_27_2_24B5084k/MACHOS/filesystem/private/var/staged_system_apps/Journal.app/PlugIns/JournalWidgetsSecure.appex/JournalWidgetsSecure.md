## JournalWidgetsSecure

> `/private/var/staged_system_apps/Journal.app/PlugIns/JournalWidgetsSecure.appex/JournalWidgetsSecure`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb8e4c` | `0xb97bc` | **`+0x970`** |
| `__DATA.__data` | `0x6b10` | `0x69d0` | **`-0x140`** |
| `__DATA.__objc_data` | `0x6820` | `0x6760` | **`-0xc0`** |
| `__TEXT.__objc_methname` | `0x23bd` | `0x247d` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x2d9c` | `0x2e3c` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x3c78` | `0x3bf0` | **`-0x88`** |
| `__TEXT.__swift5_typeref` | `0x6c2a` | `0x6ba6` | **`-0x84`** |
| `__TEXT.__objc_stubs` | `0x2280` | `0x22e0` | **`+0x60`** |
| `__DATA.__objc_const` | `0x3328` | `0x32d8` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0x42c0` | `0x4300` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x3950` | `0x3980` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x14f8` | `0x1528` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2789` | `0x27b9` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0xfb4` | `0xf84` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x113a` | `0x116a` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x918` | `0x8e8` | **`-0x30`** |
| `__DATA_CONST.__auth_got` | `0x2168` | `0x2188` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xa38` | `0xa50` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x15b0` | `0x15c8` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x231c` | `0x2330` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x4f0` | `0x500` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2130` | `0x2140` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x200` | `0x1f8` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x494` | `0x48c` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2b8` | `0x2b4` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0xb8` | `0xbc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-99.2.2.0.0
+109.0.0.0.0

-  Functions: 2890
+  Functions: 2876

-  CStrings:  896
+  CStrings:  901
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
- "_TtC20JournalWidgetsSecure17CanvasGridManager"
- "fileExistsAtPath:"
```
