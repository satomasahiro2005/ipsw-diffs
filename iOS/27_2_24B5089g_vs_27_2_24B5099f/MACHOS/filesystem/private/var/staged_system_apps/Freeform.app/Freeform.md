## Freeform

> `/private/var/staged_system_apps/Freeform.app/Freeform`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1468a4c` | `0x1463980` | **`-0x50cc`** |
| `__TEXT.__eh_frame` | `0x5814c` | `0x57c44` | **`-0x508`** |
| `__TEXT.__cstring` | `0xc6b45` | `0xc6955` | **`-0x1f0`** |
| `__DATA_CONST.__const` | `0x819d0` | `0x818b8` | **`-0x118`** |
| `__TEXT.__swift5_capture` | `0x11dfc` | `0x11d28` | **`-0xd4`** |
| `__DATA.__data` | `0x50488` | `0x503e8` | **`-0xa0`** |
| `__TEXT.__const` | `0x79b74` | `0x79c14` | **`+0xa0`** |
| `__TEXT.__swift_as_cont` | `0x3f74` | `0x3ee0` | **`-0x94`** |
| `__TEXT.__unwind_info` | `0x43ea0` | `0x43e28` | **`-0x78`** |
| `__DATA.__objc_const` | `0x9c6a0` | `0x9c640` | **`-0x60`** |
| `__TEXT.__swift5_reflstr` | `0x24225` | `0x241c5` | **`-0x60`** |
| `__TEXT.__swift5_typeref` | `0x37be2` | `0x37ba2` | **`-0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x207a0` | `0x2077c` | **`-0x24`** |
| `__TEXT.__objc_methname` | `0xc9319` | `0xc92f9` | **`-0x20`** |
| `__TEXT.__swift_as_entry` | `0x1454` | `0x1464` | **`+0x10`** |
| `__DATA.__common` | `0x46e0` | `0x46e8` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x25488` | `0x25480` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x4cf8` | `0x4d00` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x570f0` | `0x570f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-656.40.6.0.0
+656.40.8.0.0

-  Functions: 91652
-  Symbols:   7834
-  CStrings:  48769
+  Functions: 91598
+  Symbols:   7836
+  CStrings:  48763
Symbols:
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _OBJC_CLASS_$_LPImage
+ _OBJC_CLASS_$_LPImageProperties
- _$ss27_diagnoseUnexpectedEnumCase4types5NeverOxm_tlF
CStrings:
+ "Failed to get ckShare thumbnail for board %{public}@ due to error %{public}@ %@"
+ "Setting parent folder hints because item for which MSUI is being displayed is a subshare inside a shared folder"
+ "cachedItemThumbnailData"
+ "ckShareThumbnail(for:) received unexpected item type"
+ "init(libraryProvider:presentingViewController:)"
+ "initWithPlatformImage:properties:"
+ "presentExportScenesAsPDFActivityViewController(boardActor:viewControllerToPresentFrom:sourceItem:scenesOnly:deviceWindowSize:withScenes:)"
+ "previewController:canEnterFullScreenForItem:"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Freeform/src/freeform/Source/CrossPlatformUI/Gelato/CRLGelatoShareSheetProvider.swift"
- "Attempting to createActivityViewControllerForSharing for board without thumbnailer set"
- "CRLGelatoShareSheetProvider: Could not create activity view controller. Thumbnail provider is expected."
- "Failed to load board thumbnail for header image: %@"
- "Setting folder hints for subshare manage UI"
- "boardThumbnailProvider"
- "init(libraryProvider:presentingViewController:boardThumbnailProvider:)"
- "makeManageShareController: inherited share has neither boardIdentifier nor folderIdentifier"
- "preferredInterfaceOrientationForPresentation"
- "presentActivityShareOptionsViewController(button:viewController:appearanceMode:existingShare:)"
- "presentExportScenesAsPDFActivityViewController(boardActor:viewControllerToPresentFrom:sourceView:sourceRect:scenesOnly:deviceWindowSize:withScenes:)"
- "setIconProvider:"
- "supportedInterfaceOrientations"
- "thumbnailProvider"
```
