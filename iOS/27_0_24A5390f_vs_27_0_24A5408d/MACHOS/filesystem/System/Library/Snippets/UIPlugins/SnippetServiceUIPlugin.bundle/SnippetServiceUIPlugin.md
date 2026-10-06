## SnippetServiceUIPlugin

> `/System/Library/Snippets/UIPlugins/SnippetServiceUIPlugin.bundle/SnippetServiceUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9f288` | `0xa2fa8` | **`+0x3d20`** |
| `__TEXT.__swift5_typeref` | `0xd099` | `0xe526` | **`+0x148d`** |
| `__DATA_CONST.__const` | `0x4470` | `0x4850` | **`+0x3e0`** |
| `__TEXT.__const` | `0x6cf0` | `0x6fa4` | **`+0x2b4`** |
| `__DATA.__bss` | `0x4d78` | `0x4f60` | **`+0x1e8`** |
| `__TEXT.__swift5_capture` | `0x1334` | `0x14d4` | **`+0x1a0`** |
| `__TEXT.__auth_stubs` | `0x42a0` | `0x43f0` | **`+0x150`** |
| `__DATA_CONST.__auth_ptr` | `0x1d20` | `0x1e60` | **`+0x140`** |
| `__TEXT.__eh_frame` | `0x27d0` | `0x26dc` | **`-0xf4`** |
| `__TEXT.__objc_stubs` | `0x1240` | `0x1300` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x12e3` | `0x13a3` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x16f3` | `0x1637` | **`-0xbc`** |
| `__DATA_CONST.__auth_got` | `0x2158` | `0x2200` | **`+0xa8`** |
| `__TEXT.__objc_methname` | `0x2174` | `0x2215` | **`+0xa1`** |
| `__TEXT.__constg_swiftt` | `0x2028` | `0x20b4` | **`+0x8c`** |
| `__TEXT.__swift5_fieldmd` | `0x16bc` | `0x1740` | **`+0x84`** |
| `__DATA.__data` | `0x4bd8` | `0x4c58` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x23e0` | `0x2440` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x708` | `0x768` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x8d0` | `0x908` | **`+0x38`** |
| `__DATA.__objc_const` | `0xd48` | `0xd20` | **`-0x28`** |
| `__TEXT.__objc_methtype` | `0x102c` | `0x1044` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2580` | `0x2568` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x22c` | `0x240` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x25c` | `0x270` | **`+0x14`** |
| `__TEXT.__objc_classname` | `0x3d5` | `0x3e6` | **`+0x11`** |
| `__DATA.__common` | `0xb0` | `0xa0` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0xd4` | `0xe0` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xdc8` | `0xdc0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x8b0` | `0x8b8` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x4` | `—` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x134` | `0x130` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.65.26.1.1
+3600.65.34.0.0

-  Functions: 4264
-  Symbols:   312
-  CStrings:  721
+  Functions: 4397
+  Symbols:   313
+  CStrings:  727
Symbols:
+ _OBJC_CLASS_$_PHAssetChangeRequest
+ _OBJC_CLASS_$_SFOpenCoreSpotlightItemCommand
+ _OBJC_CLASS_$_UIPasteboard
+ _PHImageManagerMaximumSize
+ _objc_retain_x24
- _OBJC_CLASS_$_NSLock
- _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
- _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
- _swift_cvw_singlePayloadEnumGeneric_getEnumTag
CStrings:
+ "#PhotosImageActions asset not found for uuid=%{private}s"
+ "#PhotosImageActions copy found no image"
+ "#PhotosImageActions copy found no image for localId=%{private}s"
+ "#PhotosImageActions save found no image"
+ "#PhotosImageActions save to photos failed domain=%s code=%ld"
+ "#PhotosUIGridView 'Show More' button tapped, presenting tabbed grid"
+ "#PhotosUIGridView dismiss notification received, dismissing Show More grid + QuickLook"
+ "#PhotosUIGridView failed to load resolved image id=%s"
+ "#PhotosUIGridView loadAllResolvedImages no photo library available"
+ "#PhotosUIGridView prepareQuickLook no photo library available (container=%s)"
+ "Nil bundle id for app item, unable to build action"
+ "PlatformImage: asset not found in bundle, name=%s"
+ "SFCardView Coordinator: intercepting cross-platform command originalBundle=%s"
+ "SFCardView Coordinator: opening URL=%s"
+ "TQ,?,R"
+ "Unable to resolve action for simpleItem"
+ "_TtC22SnippetServiceUIPluginP33_206F3F04E213852AA189421E6B93424719ResourceBundleClass"
+ "bundleForClass:"
+ "creationRequestForAssetFromImage:"
+ "fetchAssetsWithUUIDs:options:"
+ "fetchImage(localId:fetchOptions:targetSize:)"
+ "generalPasteboard"
+ "imageNamed:inBundle:withConfiguration:"
+ "imageWithRenderingMode:"
+ "openActionableRowAction entityIdentifier=%s entityType=%s bundleId=%s"
+ "performChanges:completionHandler:"
+ "presentationSource"
+ "setApplicationBundleIdentifier:"
+ "setImage:"
+ "square.and.arrow.down"
+ "tmp_tryAskingSiri"
+ "uuid"
+ "v8@?0"
- "#EntityOpenExecutor: ApplicationEntity → launch bundleId=%s"
- "#EntityOpenExecutor: Tier 1 (system OpenIntent) resolved tool=%s"
- "#EntityOpenExecutor: Tier 2 (%s) resolved tool=%s"
- "#EntityOpenExecutor: Tier 3 (.openEntity) resolved tool=%s"
- "#EntityOpenExecutor: executed tool=%s"
- "#EntityOpenExecutor: execution failed tool=%s domain=%s code=%ld"
- "#EntityOpenExecutor: no open tool for type; Tier 4 launch"
- "#EntityOpenExecutor: no open tool resolved for type=%s"
- "#EntityOpenExecutor: no tier resolved and no launchable bundle; no-op"
- "#PhotoPickerView failed to decode photosQueryAttributedString"
- "#PhotosUIGridView 'Show All' button tapped, presenting tabbed grid"
- "#PhotosUIGridView asset not found for localId=%{private}s"
- "#PhotosUIGridView dismiss notification received, dismissing Show All grid + QuickLook"
- "#PhotosUIGridView failed to load a resolved image"
- "ApplicationEntity"
- "NavigateToDeviceIntent"
- "NavigateToHomeIntent"
- "NavigateToRoomIntent"
- "OpenMediaAlbumIntent"
- "OpenReadingListItemIntent"
- "_TtCO22SnippetServiceUIPlugin18EntityOpenExecutor20DatabaseToolResolver"
- "database"
- "fetchAssetsWithLocalIdentifiers:options:"
- "fetchImageFromAsset(localId:fetchOptions:targetSize:)"
- "lock"
- "simpleItem (action: "
- "unlock"
```
