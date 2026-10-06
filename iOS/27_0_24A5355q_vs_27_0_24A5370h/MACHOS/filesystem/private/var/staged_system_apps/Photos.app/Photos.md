## Photos

> `/private/var/staged_system_apps/Photos.app/Photos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x7000` | `0x6e40` | **`-0x1c0`** |
| `__TEXT.__objc_methname` | `0x92ff` | `0x9178` | **`-0x187`** |
| `__TEXT.__text` | `0x34e08` | `0x34ccc` | **`-0x13c`** |
| `__DATA.__objc_selrefs` | `0x24d0` | `0x2470` | **`-0x60`** |
| `__DATA_CONST.__cfstring` | `0x3440` | `0x34a0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x1a79` | `0x1a33` | **`-0x46`** |
| `__TEXT.__cstring` | `0x3143` | `0x317e` | **`+0x3b`** |
| `__DATA.__objc_const` | `0x19f8` | `0x19c8` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x2660` | `0x2688` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x1600` | `0x1620` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x180b` | `0x17f2` | **`-0x19`** |
| `__DATA_CONST.__got` | `0x9c0` | `0x9d8` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xb10` | `0xb20` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x688` | `0x694` | **`+0xc`** |
| `__TEXT.__const` | `0xc50` | `0xc48` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x1d14` | `0x1d0c` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xfb0` | `0xfb8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x98` | `0x94` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Symbols:   870
-  CStrings:  2140
+  Symbols:   875
+  CStrings:  2127
Symbols:
+ _OBJC_CLASS_$_PXManageKeywordsPresenter
+ _OBJC_CLASS_$_PXSharedCollectionJoiningProgressController
+ _OBJC_CLASS_$_UIDeferredMenuElementProvider
+ _PXAssetActionTypeStarRating
+ _PXImageMenuStarRatingDeferredElementIdentifier
+ _PXIsStarRatingFeatureEnabled
+ _swift_retain_x27
- _OBJC_CLASS_$_PUSidebarViewController
- _OBJC_CLASS_$_PXSplitViewController
CStrings:
+ "MANAGE_KEYWORDS_SHORTCUT"
+ "initWithPresentingViewController:"
+ "joinSharedAlbumWithShareURL:inPhotoLibrary:resultHandler:"
+ "k"
+ "manageKeywords:"
+ "menuElementForActionType:image:willStartActionHandler:didEndActionHandler:"
+ "presentManageKeywordsFromViewController:photoLibrary:"
+ "providerForDeferredMenuElement:"
+ "providerWithElementProvider:"
+ "tag"
+ "v16@?0@?<v@?@\"NSArray\">8"
+ "v28@?0@\"PHCollectionShare\"8@\"NSError\"16B24"
+ "\xd1"
- "@\"PXSplitViewController\""
- "CreateSidebarViewController"
- "T@\"PXSplitViewController\",&,N,V_splitViewController"
- "Will fetch shared collection from URL: %@"
- "_ensureSplitViewControllerExistsIfNeeded"
- "_splitViewController"
- "allAlbumsCollection"
- "fetchSharedCollectionWithShareURL:inPhotoLibrary:acceptIfPending:completionHandler:"
- "horizontalSizeClass"
- "initWithNavigationRoot:photoLibrary:libraryFilterState:"
- "initWithSidebarViewController:contentViewController:"
- "navigateToFallbackForDestination:"
- "navigationItem"
- "px_enableExtendedTraitCollection"
- "px_virtualCollections"
- "registerChangeObserver:"
- "setLargeTitleDisplayMode:"
- "setPreferredPrimaryColumnWidth:"
- "setSidebarViewController:"
- "setSplitViewController:"
- "setTabBarController:"
- "setViewController:forColumn:"
- "splitViewController"
- "v24@?0@\"PHCollectionShare\"8@\"NSError\"16"
- "wantsSplitViewController"
- "\xe1"
```
