## SafariShared

> `/System/Library/PrivateFrameworks/SafariShared.framework/SafariShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b6720` | `0x2b76b0` | **`+0xf90`** |
| `__TEXT.__const` | `0xa3854` | `0xa3a94` | **`+0x240`** |
| `__DATA.__data` | `0x57c8` | `0x5848` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x36ca` | `0x374a` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x1ebe0` | `0x1ec3c` | **`+0x5c`** |
| `__TEXT.__eh_frame` | `0x5580` | `0x55d8` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x285f8` | `0x28638` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x1b0c0` | `0x1b0e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x23827` | `0x23847` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1668` | `0x1648` | **`-0x20`** |
| `__AUTH.__data` | `0x1798` | `0x17b0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xc188` | `0xc1a0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xefe0` | `0xeff8` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x15cc2` | `0x15cb2` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2d70` | `0x2d78` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x21c0` | `0x21c8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1617c` | `0x16184` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1940` | `0x1944` | **`+0x4`** |

### Other Changes

```diff

-625.2.5.10.1
+625.2.7.1.0

-  Functions: 14790
-  Symbols:   19354
-  CStrings:  6158
+  Functions: 14802
+  Symbols:   19359
+  CStrings:  6159
Symbols:
+ +[WBSTrialManager prepareLogDictionary:withExperimentId:withTreatmentId:withRolloutId:isCounterFactualSearch:withFactorData:]
+ -[WBSTabOrderManager _nextNonClosedTabAdjacentToIndex:inAscendingOrder:foundIndex:]
+ -[WBSTabOrderManager _nextTabSkippingCollapsedClustersFromIndex:inAscendingOrder:]
+ -[WBSTrialManager inExperimentOrRollout]
+ _OBJC_IVAR_$_WBSTrialManager._rolloutId
+ ___swift_closure_destructor.179Tm
+ _symbolic Say_____yxGG 12SafariShared25WBSBookmarksFolderClusterV
+ _symbolic _____7cluster_SDySSSiG13itemPositionst 12SafariShared17WBSClusterManagerC7ClusterV
+ _symbolic ___________7cluster_SDySSSiG13itemPositionstt 10Foundation4UUIDV 12SafariShared17WBSClusterManagerC7ClusterV
+ _symbolic _____y__________7cluster_SDySSSiG13itemPositionstG s18_DictionaryStorageC 10Foundation4UUIDV 12SafariShared17WBSClusterManagerC7ClusterV
- +[WBSTrialManager prepareLogDictionary:withExperimentId:withTreatmentId:isCounterFactualSearch:withFactorData:]
- -[WBSTabOrderManager _nextNonClosedTabAdjacentToIndex:inAscendingOrder:]
- -[WBSTabOrderManager _nextTabSkippingCollapsedClustersFromTab:inAscendingOrder:]
- ___swift_closure_destructor.178Tm
- _symbolic Say_____yxGGSg 12SafariShared25WBSBookmarksFolderClusterV
CStrings:
+ "8625.2.7.1"
+ "Factor \"%@\" has value of %@ from Trial"
+ "Not enrolled in a rollout"
+ "Not enrolled in an experiment or rollout"
+ "Rollout ID"
- "8625.2.5.10.1"
- "Factor \"%@\" has value of %@ from the experiment"
- "Unknown Experiment ID"
- "Unknown Treatment ID"
```
