## MobileSafariUI

> `/System/Library/PrivateFrameworks/MobileSafariUI.framework/MobileSafariUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f1504` | `0x2f1f7c` | **`+0xa78`** |
| `__TEXT.__objc_methlist` | `0x24e9c` | `0x24f2c` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x6607` | `0x6691` | **`+0x8a`** |
| `__TEXT.__unwind_info` | `0x10338` | `0x10368` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x33808` | `0x33830` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x9938` | `0x9960` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x3834` | `0x385c` | **`+0x28`** |
| `__DATA.__data` | `0x9c28` | `0x9c48` | **`+0x20`** |
| `__TEXT.__const` | `0x5010` | `0x5030` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1f6d0` | `0x1f6b4` | **`-0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x2e10` | `0x2e28` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x18830` | `0x18840` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x15d8` | `0x15c8` | **`-0x10`** |

### Other Changes

```diff

-625.2.5.10.1
+625.2.7.1.0

-  Functions: 16332
-  Symbols:   23092
+  Functions: 16349
+  Symbols:   23107
Symbols:
+ -[StartPageController _createRecentSearchesStartPageControllerIfNeeded]
+ -[TabController indexOfTabWithIdentifier:inClusterWithID:]
+ -[TabController sizeOfClusterWithID:]
+ -[TabGroupTabOrderProvider clusterIDForTab:]
+ -[TabGroupTabOrderProvider firstTabInClusterWithID:]
+ -[TabGroupTabOrderProvider indexOfTabWithIdentifier:inClusterWithID:]
+ -[TabGroupTabOrderProvider isClusterExpanded:]
+ -[TabGroupTabOrderProvider isClusteringEnabled]
+ -[TabGroupTabOrderProvider lastTabInClusterWithID:]
+ -[TabGroupTabOrderProvider sizeOfClusterWithID:]
+ -[TabSwitcherViewController beginSizeTransitionAnimated:]
+ -[TabSwitcherViewController endSizeTransitionAnimated:]
+ GCC_except_table141
+ GCC_except_table368
+ GCC_except_table479
+ _WBSTimeUntilNextTwiceDailyAnalyticsReportForKey
+ ___71-[StartPageController _createRecentSearchesStartPageControllerIfNeeded]_block_invoke
+ ___block_descriptor_49_e8_32s40s_e8_v12?0B8ls32l8s40l8
+ _symbolic _____7cluster_SDySSSiG13itemPositionst 12SafariShared17WBSClusterManagerC7ClusterV
+ _symbolic ___________7cluster_SDySSSiG13itemPositionstt 10Foundation4UUIDV 12SafariShared17WBSClusterManagerC7ClusterV
+ _symbolic _____y__________7cluster_SDySSSiG13itemPositionstG s18_DictionaryStorageC 10Foundation4UUIDV 12SafariShared17WBSClusterManagerC7ClusterV
- -[TabSwitcherViewController beginAnimatedSizeTransition]
- -[TabSwitcherViewController endAnimatedSizeTransition]
- GCC_except_table274
- GCC_except_table428
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_WBSTabOrderProvider
- ___51-[StartPageController initWithVisualStyleProvider:]_block_invoke_4
```
