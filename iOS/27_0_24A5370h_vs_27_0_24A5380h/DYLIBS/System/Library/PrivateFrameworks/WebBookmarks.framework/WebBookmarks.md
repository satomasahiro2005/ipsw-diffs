## WebBookmarks

> `/System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa637c` | `0xa726c` | **`+0xef0`** |
| `__TEXT.__gcc_except_tab` | `0xc004` | `0xc1e4` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x9d80` | `0x9f00` | **`+0x180`** |
| `__DATA_DIRTY.__objc_data` | `0x1450` | `0x1590` | **`+0x140`** |
| `__AUTH.__objc_data` | `0x140` | `0x50` | **`-0xf0`** |
| `__TEXT.__oslogstring` | `0x9d87` | `0x9e5d` | **`+0xd6`** |
| `__AUTH.__data` | `0xb8` | `—` | **`-0xb8`** |
| `__DATA_DIRTY.__data` | `0x10` | `0xc8` | **`+0xb8`** |
| `__TEXT.__objc_methlist` | `0x8884` | `0x893c` | **`+0xb8`** |
| `__TEXT.__cstring` | `0xfbf1` | `0xfc87` | **`+0x96`** |
| `__TEXT.__unwind_info` | `0x4690` | `0x46f8` | **`+0x68`** |
| `__DATA.__data` | `0x1070` | `0x10d0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x3008` | `0x3060` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x5060` | `0x50a8` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x7f8` | `0x818` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x61c` | `0x624` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x230` | `0x238` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x108` | `0x110` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1e0` | `0x1e8` | **`+0x8`** |

### Other Changes

```diff

-625.1.20.10.3
+625.1.22.10.3

-  Functions: 3692
-  Symbols:   6041
-  CStrings:  2078
+  Functions: 3706
+  Symbols:   6071
+  CStrings:  2083
Symbols:
+ +[WBProfile profileTitleWithTitle:forProfileIdentifier:]
+ -[WBTab clusterID]
+ -[WebBookmark(ReadingList) featureTextFetchError]
+ -[WebBookmark(ReadingList) setFeatureTextFetchError:]
+ -[WebBookmarkTabCollection _resolveLastSelectedChildOfTabGroup:toInsertedTabWithUUID:]
+ -[WebBookmarkTabCollection _saveTabGroup:childTabs:selectedTabUUID:]
+ -[WebBookmarkTabCollection _saveWindowState:localTabs:localSelectedTabUUID:privateTabs:privateSelectedTabUUID:]
+ -[WebBookmarkTabCollection _saveWindowState:localTabs:localSelectedTabUUID:privateTabs:privateSelectedTabUUID:forApplyingInMemoryChanges:]
+ -[WebBookmarkTabCollection indexableProfiles]
+ -[WebBookmarkTabCollection saveWindowState:localTabs:localSelectedTabUUID:privateTabs:privateSelectedTabUUID:]
+ -[_WBIndexableProfile .cxx_destruct]
+ -[_WBIndexableProfile displayTitle]
+ -[_WBIndexableProfile identifier]
+ -[_WBIndexableProfile initWithIdentifier:displayTitle:]
+ GCC_except_table135
+ _OBJC_CLASS_$__WBIndexableProfile
+ _OBJC_IVAR_$_WebBookmark._featureTextFetchError
+ _OBJC_IVAR_$__WBIndexableProfile._displayTitle
+ _OBJC_IVAR_$__WBIndexableProfile._identifier
+ _OBJC_METACLASS_$__WBIndexableProfile
+ __OBJC_$_INSTANCE_METHODS__WBIndexableProfile
+ __OBJC_$_INSTANCE_VARIABLES__WBIndexableProfile
+ __OBJC_$_PROP_LIST_WBSIndexableProfile
+ __OBJC_$_PROP_LIST__WBIndexableProfile
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_WBSIndexableProfile
+ __OBJC_$_PROTOCOL_METHOD_TYPES_WBSIndexableProfile
+ __OBJC_CLASS_PROTOCOLS_$__WBIndexableProfile
+ __OBJC_CLASS_RO_$__WBIndexableProfile
+ __OBJC_LABEL_PROTOCOL_$_WBSIndexableProfile
+ __OBJC_METACLASS_RO_$__WBIndexableProfile
+ __OBJC_PROTOCOL_$_WBSIndexableProfile
+ ___111-[WebBookmarkTabCollection _saveWindowState:localTabs:localSelectedTabUUID:privateTabs:privateSelectedTabUUID:]_block_invoke
+ ___138-[WebBookmarkTabCollection _saveWindowState:localTabs:localSelectedTabUUID:privateTabs:privateSelectedTabUUID:forApplyingInMemoryChanges:]_block_invoke
+ ___68-[WebBookmarkTabCollection _saveTabGroup:childTabs:selectedTabUUID:]_block_invoke
+ ___block_descriptor_80_ea8_32s40s48s56s64s72s_e5_B8?0ls32l8s40l8s48l8s56l8s64l8s72l8
+ ___block_descriptor_88_ea8_32s40s48s56s64s72s80r_e5_v8?0lr80l8s32l8s40l8s48l8s56l8s64l8s72l8
+ ___block_descriptor_96_ea8_32s40s48s56s64s72s80bs88r_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8r88l8s80l8
+ _sqlite3_changes
- -[WebBookmarkTabCollection _saveWindowState:forApplyingInMemoryChanges:]
- -[WebBookmarkTabCollection saveWindowState:]
- GCC_except_table136
- OBJC_IVAR_$_WBProfile._titleProvider
- ___35-[WBProfile initWithBookmark:kind:]_block_invoke
- ___45-[WebBookmarkTabCollection _saveWindowState:]_block_invoke
- ___72-[WebBookmarkTabCollection _saveWindowState:forApplyingInMemoryChanges:]_block_invoke
- ___block_descriptor_32_e15_"NSString"8?0l
CStrings:
+ "Failed to persist %{public}lu tab(s) for tab group %{public}@"
+ "Failed to save localTabGroup %{public}@ for windowState: %{public}@"
+ "Failed to save privateTabGroup %{public}@ for windowState: %{public}@"
+ "Failed to save tab group %{public}@"
+ "Failed to update last selected tab for tab group %{public}@"
+ "SELECT external_uuid, title FROM bookmarks WHERE parent = 0 AND syncable = 1 AND type = 1 AND subtype = 2 AND special_id = 0 ORDER BY order_index ASC"
+ "Tried to update bookmark %{public}@ marked inserted (id=%d) but no row matched — row is missing from the database"
- "Failed to save local tab group %{public}@ while trying to save window state with UUID: %{public}@"
- "Failed to save private tab group %{public}@ while trying to save window state with UUID: %{public}@"
```
