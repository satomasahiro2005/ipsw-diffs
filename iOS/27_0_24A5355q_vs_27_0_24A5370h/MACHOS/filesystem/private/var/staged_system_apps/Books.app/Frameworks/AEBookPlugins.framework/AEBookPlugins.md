## AEBookPlugins

> `/private/var/staged_system_apps/Books.app/Frameworks/AEBookPlugins.framework/AEBookPlugins`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x133de4` | `0x13349c` | **`-0x948`** |
| `__DATA.__objc_const` | `0x20608` | `0x204c8` | **`-0x140`** |
| `__TEXT.__objc_stubs` | `0x29440` | `0x29560` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x37f49` | `0x37fe9` | **`+0xa0`** |
| `__DATA.__objc_data` | `0x5d30` | `0x5ce0` | **`-0x50`** |
| `__TEXT.__objc_methlist` | `0x1831c` | `0x182cc` | **`-0x50`** |
| `__DATA.__objc_selrefs` | `0xd6a0` | `0xd6e0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x4318` | `0x4340` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x2c2d` | `0x2c0d` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0xa2cd` | `0xa2ad` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x53c8` | `0x53b0` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x1458` | `0x1448` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x15c0` | `0x15d0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2680` | `0x2690` | **`+0x10`** |
| `__TEXT.__const` | `0x17e8` | `0x17d8` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1358` | `0x1360` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x810` | `0x808` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x528` | `0x520` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6629.0.0.0.0
+6636.0.0.0.0

-  Functions: 8432
-  Symbols:   2312
-  CStrings:  12175
+  Functions: 8419
+  Symbols:   2309
+  CStrings:  12177
Symbols:
+ _OBJC_CLASS_$_UIBackgroundConfiguration
+ _OBJC_CLASS_$_UIContentUnavailableConfiguration
+ _swift_retain_x22
- OBJC_IVAR_$_BKBookmarkThumbnailDirectory._noBookmarksView
- OBJC_IVAR_$_BKTOCBookmarksDescription._descriptionLabel
- OBJC_IVAR_$_BKTOCBookmarksDescription._titleLabel
- _BKTOCBookmarkDescriptionTag
- _OBJC_CLASS_$_BKTOCBookmarksDescription
- _OBJC_METACLASS_$_BKTOCBookmarksDescription
CStrings:
+ "@\"UIImage\"24@0:8q16"
+ "T@\"UIBarButtonItem\",R,W,V_shareItem"
+ "_applyPageImageToView:pageNumber:size:isRight:addGutterAfter:completion:"
+ "_createContentUnavailableConfiguration"
+ "_decryptedSMILDataForPath:book:"
+ "_shareItem"
+ "assetViewControllerLockContentLayoutAtSize:"
+ "assetViewControllerUnlockContentLayout"
+ "clearConfiguration"
+ "contentUnavailableConfiguration"
+ "emptyConfiguration"
+ "pageNavigationSnapshotForPageNumber:"
+ "secondaryTextProperties"
+ "setContentUnavailableConfiguration:"
+ "setNeedsUpdateContentUnavailableConfiguration"
+ "setSecondaryText:"
+ "shareItem"
+ "textProperties"
+ "updateContentUnavailableConfigurationUsingState:"
+ "v64@0:8@16q24{CGSize=dd}32B48B52@?56"
- "@\"BKTOCBookmarksDescription\""
- "@40@0:8@16@24^B32"
- "BKTOCBookmarksDescription"
- "T@\"BKTOCBookmarksDescription\",&,N,V_descriptionView"
- "T@\"BKTOCBookmarksDescription\",&,N,V_noBookmarksView"
- "T@\"UILabel\",R,N,V_descriptionLabel"
- "T@\"UILabel\",R,N,V_titleLabel"
- "_decryptedSMILDataForPath:book:wasEncrypted:"
- "_descriptionLabel"
- "_descriptionView"
- "_noBookmarksView"
- "descriptionLabel"
- "descriptionView"
- "noBookmarksView"
- "pageNavigationSnapshotForPageNumber:completion:"
- "setDescriptionView:"
- "setNoBookmarksView:"
- "v32@0:8q16@?<v@?@\"UIImage\">24"
```
