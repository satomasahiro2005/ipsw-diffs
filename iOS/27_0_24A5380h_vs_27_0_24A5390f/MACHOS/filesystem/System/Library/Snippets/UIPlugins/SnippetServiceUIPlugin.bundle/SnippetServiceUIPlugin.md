## SnippetServiceUIPlugin

> `/System/Library/Snippets/UIPlugins/SnippetServiceUIPlugin.bundle/SnippetServiceUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b27c` | `0x9f288` | **`+0x1400c`** |
| `__TEXT.__swift5_typeref` | `0xb613` | `0xd099` | **`+0x1a86`** |
| `__TEXT.__eh_frame` | `0x1e20` | `0x27d0` | **`+0x9b0`** |
| `__TEXT.__const` | `0x64d0` | `0x6cf0` | **`+0x820`** |
| `__DATA.__data` | `0x43f0` | `0x4bd8` | **`+0x7e8`** |
| `__DATA.__bss` | `0x4898` | `0x4d78` | **`+0x4e0`** |
| `__TEXT.__unwind_info` | `0x20d8` | `0x2580` | **`+0x4a8`** |
| `__TEXT.__oslogstring` | `0x1f50` | `0x23e0` | **`+0x490`** |
| `__DATA_CONST.__const` | `0x4060` | `0x4470` | **`+0x410`** |
| `__TEXT.__auth_stubs` | `0x3eb0` | `0x42a0` | **`+0x3f0`** |
| `__TEXT.__constg_swiftt` | `0x1ca8` | `0x2028` | **`+0x380`** |
| `__TEXT.__swift5_fieldmd` | `0x14c0` | `0x16bc` | **`+0x1fc`** |
| `__DATA_CONST.__auth_got` | `0x1f60` | `0x2158` | **`+0x1f8`** |
| `__DATA_CONST.__auth_ptr` | `0x1b80` | `0x1d20` | **`+0x1a0`** |
| `__TEXT.__swift5_capture` | `0x11b0` | `0x1334` | **`+0x184`** |
| `__DATA.__objc_const` | `0xc18` | `0xd48` | **`+0x130`** |
| `__DATA_CONST.__got` | `0xcb8` | `0xdc8` | **`+0x110`** |
| `__TEXT.__cstring` | `0x15f3` | `0x16f3` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0x1223` | `0x12e3` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x20bd` | `0x2174` | **`+0xb7`** |
| `__TEXT.__objc_classname` | `0x355` | `0x3d5` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x11c0` | `0x1240` | **`+0x80`** |
| `__TEXT.__swift5_assocty` | `0x690` | `0x708` | **`+0x78`** |
| `__TEXT.__swift_as_cont` | `0xe0` | `0x134` | **`+0x54`** |
| `__TEXT.__swift_as_ret` | `0x90` | `0xd8` | **`+0x48`** |
| `__TEXT.__swift_as_entry` | `0x98` | `0xd4` | **`+0x3c`** |
| `__TEXT.__objc_methtype` | `0xff1` | `0x102c` | **`+0x3b`** |
| `__DATA.__common` | `0x78` | `0xb0` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x8a8` | `0x8d0` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x234` | `0x25c` | **`+0x28`** |
| `__DATA.__objc_data` | `0x6a0` | `0x6c0` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x20c` | `0x22c` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x898` | `0x8b0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_builtin`

### Other Changes

```diff

-3600.65.18.1.1
+3600.65.26.1.1

-  Functions: 3859
-  Symbols:   308
-  CStrings:  686
+  Functions: 4264
+  Symbols:   312
+  CStrings:  721
Symbols:
+ _OBJC_CLASS_$_NSLock
+ _OBJC_CLASS_$_QLItem
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_getTupleTypeMetadata3
- _OBJC_CLASS_$_PHCloudIdentifier
- __swift_stdlib_bridgeErrorToNSError
CStrings:
+ "#ActionableRow: dispatch via entityOpen"
+ "#ActionableRow: entityOpen resolved no open tool or launchable app; no-op"
+ "#AlbumPickerView deferring picker presentation for island transition"
+ "#AlbumPickerView dismiss notification received, dismissing picker"
+ "#AlbumPickerView island transition complete, showing album picker"
+ "#AlbumPickerView showing album picker"
+ "#AppLauncher: launching bundleId=%s"
+ "#AppLauncher: no launchable bundle id"
+ "#AppLauncher: openApplication failed bundleId=%s domain=%s code=%ld"
+ "#EntityOpenExecutor: ApplicationEntity → launch bundleId=%s"
+ "#EntityOpenExecutor: Tier 1 (system OpenIntent) resolved tool=%s"
+ "#EntityOpenExecutor: Tier 2 (%s) resolved tool=%s"
+ "#EntityOpenExecutor: Tier 3 (.openEntity) resolved tool=%s"
+ "#EntityOpenExecutor: executed tool=%s"
+ "#EntityOpenExecutor: execution failed tool=%s domain=%s code=%ld"
+ "#EntityOpenExecutor: no open tool for type; Tier 4 launch"
+ "#EntityOpenExecutor: no open tool resolved for type=%s"
+ "#EntityOpenExecutor: no tier resolved and no launchable bundle; no-op"
+ "#PhotoPickerView dismiss notification received, dismissing picker"
+ "#PhotosUIGridView QuickLook tap ignored after retry, identifier still unresolved cloudId=%s"
+ "#PhotosUIGridView QuickLook tap not ready, re-resolving before retry"
+ "#PhotosUIGridView dismiss notification received, dismissing Show All grid + QuickLook"
+ "#PhotosUIGridView no identifier conversion needed"
+ "#PhotosUIGridView resolved identifiers success=%ld failed=%ld total=%ld"
+ "#PhotosUIGridView resolved privateFileURLs resolved=%ld requested=%ld"
+ "#PhotosUIGridView starting identifier resolution for %ld identifiers"
+ "@\"<SFCardResourceLoader>\"16@0:8"
+ "ApplicationEntity"
+ "NavigateToDeviceIntent"
+ "NavigateToHomeIntent"
+ "NavigateToRoomIntent"
+ "OpenMediaAlbumIntent"
+ "OpenReadingListItemIntent"
+ "SFCardView Coordinator: in-process open resolved no open tool or launchable app; no-op"
+ "View.task @ SnippetServiceUIPlugin/ItemView.swift:"
+ "_TtCO22SnippetServiceUIPlugin18EntityOpenExecutor20DatabaseToolResolver"
+ "_TtCV22SnippetServiceUIPluginP33_A55D1686EB50A90C63EC2EF22A9A716139QuickLookPreviewControllerRepresentable11Coordinator"
+ "_selection"
+ "cardLoader"
+ "cloudIdentifier"
+ "com.apple.intelligenceflow"
+ "currentPreviewItemIndex"
+ "database"
+ "entityIdentifier entityType bundleId "
+ "indexObserver"
+ "initWithURL:previewTitle:editingMode:"
+ "items"
+ "lock"
+ "reloadData"
+ "setDisablesZoomTransition:"
+ "unlock"
- "#ItemView: failed to build prescribed action for simpleItem openAction errorDomain=%s errorCode=%ld"
- "#PhotosUIGridView Pre-resolved %ld/%ld QuickLook URLs"
- "#PhotosUIGridView QuickLook tap ignored, data source not ready or preview index not found cloudIdIndex=%ld"
- "#PhotosUIGridView cloud identifier not found in mappings index=%ld"
- "#PhotosUIGridView failed to resolve cloud identifier index=%ld errorDomain=%s errorCode=%ld"
- "#PhotosUIGridView no cloud identifier conversion needed"
- "#PhotosUIGridView resolved identifiers success=%ld failed=%ld"
- "#PhotosUIGridView starting cloud identifier resolution identifierCount=%ld"
- "#PhotosUIGridView using fallback local identifier index=%ld"
- "%s Failed to build prescribed action: %@"
- "SnippetServiceUIPlugin.PhotosQuickLookCoordinator"
- "_TtC22SnippetServiceUIPlugin26PhotosQuickLookCoordinator"
- "_isPresented"
- "initWithStringValue:"
- "performCardOpenAction(_:)"
- "stringValue"
```
