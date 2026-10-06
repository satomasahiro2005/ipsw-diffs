## JournalShareExtension

> `/private/var/staged_system_apps/Journal.app/PlugIns/JournalShareExtension.appex/JournalShareExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf9638` | `0xfd410` | **`+0x3dd8`** |
| `__TEXT.__eh_frame` | `0x4ca8` | `0x50c8` | **`+0x420`** |
| `__DATA_CONST.__const` | `0x4f80` | `0x5358` | **`+0x3d8`** |
| `__TEXT.__const` | `0x6474` | `0x65e4` | **`+0x170`** |
| `__TEXT.__objc_stubs` | `0x4ee0` | `0x5020` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x6b8d` | `0x6cad` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x2808` | `0x2900` | **`+0xf8`** |
| `__TEXT.__swift5_capture` | `0xf7c` | `0x1068` | **`+0xec`** |
| `__DATA.__bss` | `0x6810` | `0x68f0` | **`+0xe0`** |
| `__TEXT.__auth_stubs` | `0x40e0` | `0x41b0` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x1e8c` | `0x1f4c` | **`+0xc0`** |
| `__DATA.__objc_data` | `0x7c88` | `0x7bd8` | **`-0xb0`** |
| `__DATA.__objc_const` | `0x47c8` | `0x4838` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x2078` | `0x20e0` | **`+0x68`** |
| `__DATA_CONST.__got` | `0x1310` | `0x1360` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x19f1` | `0x1a41` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x2d34` | `0x2d84` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x374` | `0x3c0` | **`+0x4c`** |
| `__DATA.__objc_selrefs` | `0x1b18` | `0x1b58` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x3d68` | `0x3da4` | **`+0x3c`** |
| `__DATA_CONST.__auth_ptr` | `0xe18` | `0xe48` | **`+0x30`** |
| `__TEXT.__cstring` | `0x24b4` | `0x24e4` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x233d` | `0x236d` | **`+0x30`** |
| `__DATA.__data` | `0x5de8` | `0x5e10` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x1c97` | `0x1cb7` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x1f8` | `0x214` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x14d4` | `0x14ec` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x3c8` | `0x3e0` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x178` | `0x190` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x294` | `0x2a8` | **`+0x14`** |
| `__DATA.__common` | `0x650` | `0x648` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x260` | `0x268` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x40` | `0x44` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-99.2.2.0.0
+109.0.0.0.0

-  Functions: 3195
-  Symbols:   506
-  CStrings:  1724
+  Functions: 3251
+  Symbols:   508
+  CStrings:  1737
Symbols:
+ _CGRectIsEmpty
+ _OBJC_CLASS_$_AVAssetTrack
+ _UIViewNoIntrinsicMetric
+ _kCGImageSourceSkipMetadata
- _CGImageSourceCreateWithData
- _OBJC_CLASS_$_UIPasteboard
CStrings:
+ "Couldn't generate a thumbnail for %{public}s asset. Attachments count: %{public}ld [%{public}s]"
+ "MultiPinMapAnnotationRenderer: missing glyph for Maps-style single pin; rendering generic marker fallback"
+ "T@\"NSAttributedString\",N,&"
+ "Thumbnail created for %{public}s asset from file [%{public}s]"
+ "Thumbnail created from legacy field [%{public}s]"
+ "assetMediaResolutionChangeObserver"
+ "collectionViewLayout"
+ "com.apple.journal.PersistentCache"
+ "imageQueue"
+ "imageWithTintColor:"
+ "insertSubview:aboveSubview:"
+ "loadItemForTypeIdentifier:options:completionHandler:"
+ "loadTracksWithMediaType:completionHandler:"
+ "preferredMaxLayoutWidth"
+ "resolvedColorWithTraitCollection:"
+ "setAttributedString:"
+ "setAttributedText:"
+ "setPrefetchingEnabled:"
+ "setTextContainer:"
+ "tertiarySystemBackgroundColor"
+ "textInputView"
+ "userInterfaceStyle"
+ "v24@?0@\"<NSSecureCoding>\"8@\"NSError\"16"
- "Image created from file [%{public}s]"
- "Image was not found in cache or in an attachment file. Asset type: %{public}s, Attachments count: %{public}ld [%{public}s]"
- "Legacy support - data attachment [0] is nil"
- "Legacy support - will try to get image from Core Data"
- "_isExpanded"
- "frameLayoutGuide"
- "generalPasteboard"
- "hasStrings"
- "integerValue"
- "paste:"
```
