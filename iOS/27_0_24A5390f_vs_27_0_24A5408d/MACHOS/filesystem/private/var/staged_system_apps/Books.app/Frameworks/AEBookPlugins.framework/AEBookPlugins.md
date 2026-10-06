## AEBookPlugins

> `/private/var/staged_system_apps/Books.app/Frameworks/AEBookPlugins.framework/AEBookPlugins`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x57e7` | `0x5b77` | **`+0x390`** |
| `__TEXT.__text` | `0x133630` | `0x1332e0` | **`-0x350`** |
| `__TEXT.__objc_stubs` | `0x29560` | `0x29440` | **`-0x120`** |
| `__TEXT.__objc_methname` | `0x38009` | `0x37ef9` | **`-0x110`** |
| `__DATA.__data` | `0x4268` | `0x41a8` | **`-0xc0`** |
| `__DATA.__objc_const` | `0x204d0` | `0x20420` | **`-0xb0`** |
| `__TEXT.__gcc_except_tab` | `0x3ea8` | `0x3f2c` | **`+0x84`** |
| `__DATA.__objc_selrefs` | `0xd6e8` | `0xd6a0` | **`-0x48`** |
| `__TEXT.__const` | `0x17d8` | `0x17f8` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x2c0d` | `0x2bed` | **`-0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x520` | `0x510` | **`-0x10`** |
| `__TEXT.__cstring` | `0x92b7` | `0x92a7` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x1448` | `0x143c` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x16c0` | `0x16b8` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x182ec` | `0x182f4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x53b8` | `0x53b0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6647.0.0.0.0
+6655.0.0.0.0

-  Functions: 8422
-  Symbols:   2311
-  CStrings:  12179
+  Functions: 8423
+  Symbols:   2308
+  CStrings:  12174
Symbols:
+ _OBJC_CLASS_$_BKSafeAreaInsetRemovingView
+ _OBJC_METACLASS_$_BKSafeAreaInsetRemovingView
- OBJC_IVAR_$_BKThumbnailBookViewController._bookmarkButton
- OBJC_IVAR_$_BKThumbnailBookViewController._topToolbar
- _OBJC_CLASS_$_BCUIFullHeightNavWrapper
- _OBJC_CLASS_$_BKBottomSafeAreaInsetRemovingView
- _OBJC_METACLASS_$_BKBottomSafeAreaInsetRemovingView
CStrings:
+ "BKSafeAreaInsetRemovingView"
+ "T@\"UINavigationBar\",R,N"
+ "[DRMTrace][open] -> silent keybag refetch dsid=%{private}@ logID:%{public}@"
+ "[DRMTrace][open] Auth needed due to non-existing account for asset at url, username: %@ -- %@, logID:%{public}@"
+ "[DRMTrace][open] DRM/Keybag failure for book at URL: %@ -- %@ logID:%{public}@"
+ "[DRMTrace][open] Error authenticating account: %@ -- %@, logID:%{public}@"
+ "[DRMTrace][open] Error refetching bag for dsid: %@ -- %@, logID:%{public}@"
+ "[DRMTrace][open] confirmBagContents ENTER sinfCount=%lu"
+ "[DRMTrace][open] confirmBagContents keybag-refetch-required; underlying=%{public}@ familyRemoval=%{BOOL}d"
+ "[DRMTrace][open] gate(AE): accountNil=%{BOOL}d credentialEmpty=%{BOOL}d credential=%{private}@ logID:%{public}@"
+ "[DRMTrace][open] identity: usernamePresent=%{BOOL}d dsid=%{private}@ logID:%{public}@"
+ "[DRMTrace][open] interactive auth result ok=%{BOOL}d err=%{public}@ logID:%{public}@"
+ "[DRMTrace][open] open failed err=%{public}@ underlying=%{public}@ refetchRequired=%{BOOL}d canRefetch=%{BOOL}d logID:%{public}@"
+ "[DRMTrace][open] parse decrypt keybag-refetch-required; underlying FairPlay status=%d"
+ "[DRMTrace][open] vcWithOptions ENTER url=%@ canRefetch=%{BOOL}d logID:%{public}@"
+ "[DRMTrace][read] SMIL FairPlay decrypt failed: %{public}@ Path: %{public}@ refetch:%d"
+ "_configuredBuyButtonItem"
+ "_setNavigationBarHidden:edge:duration:"
+ "isNavigationBarHidden"
+ "setAttributedTitle:"
+ "setLeftBarButtonItems:"
+ "setTrailingItemGroups:"
+ "shouldHideSearchItem"
+ "supportsAlernativeBarLayout"
+ "updateBookmarkItem:"
+ "wantsBottomScrubber"
- "Auth needed due to non-existing account for asset at url, username: %@ -- %@, logID:%{public}@"
- "BCToolbarDelegate"
- "BKBottomSafeAreaInsetRemovingView"
- "DRM/Keybag failure for book at URL: %@ -- %@ logID:%{public}@"
- "Error authenticating account: %@ -- %@, logID:%{public}@"
- "Error refetching bag for dsid: %@ -- %@, logID:%{public}@"
- "SMIL FairPlay decrypt failed: %{public}@ Path: %{public}@ refetch:%d"
- "T@\"BCNavigationBar\",R,N,V_topToolbar"
- "T@\"NSLayoutConstraint\",&,N,V_pageNumberHUDTopConstraint"
- "UIToolbarDelegate"
- "_bookmarkButton"
- "_pageNumberHUDTopConstraint"
- "_topToolbar"
- "arrayWithArray:"
- "assetViewControllerMinifiedBarButtonItem:"
- "barButtonItems"
- "invalidateIntrinsicContentSize"
- "pageNumberHUDTopConstraint"
- "setAccessibilityElementsHidden:"
- "setAdditionalSafeAreaInsets:"
- "setCursorInsets:"
- "setLeftItems:"
- "setLeftItems:rightItems:titleView:animated:"
- "setPageNumberHUDTopConstraint:"
- "setRightItemGroups:"
- "setSpecifiedWidth:"
- "specifiedWidth"
- "stylizeBCNavigationBarTranslucent:"
- "toolbarItems"
- "updateBookmarkButton"
- "updateBookmarkButton:"
```
