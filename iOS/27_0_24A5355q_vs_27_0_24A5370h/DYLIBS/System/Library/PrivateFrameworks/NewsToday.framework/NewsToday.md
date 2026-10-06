## NewsToday

> `/System/Library/PrivateFrameworks/NewsToday.framework/NewsToday`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x451c8` | `0x45904` | **`+0x73c`** |
| `__AUTH_CONST.__objc_const` | `0xddc0` | `0xdf20` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x15f0` | `0x16f0` | **`+0x100`** |
| `__TEXT.__gcc_except_tab` | `0x9cc` | `0xa6c` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x647c` | `0x6504` | **`+0x88`** |
| `__AUTH.__objc_data` | `0x490` | `0x4e0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d50` | `0x3d98` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x1de0` | `0x1e20` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x17c8` | `0x17f0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xa58` | `0xa80` | **`+0x28`** |
| `__TEXT.__cstring` | `0x8f75` | `0x8f85` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x5bc` | `0x5c4` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xea0` | `0xea8` | **`+0x8`** |

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

-  Functions: 2002
-  Symbols:   3232
-  CStrings:  815
+  Functions: 2009
+  Symbols:   3255
+  CStrings:  820
Symbols:
+ +[NTForYouRequestManifest supportsSecureCoding]
+ -[NTForYouRequestManifest .cxx_destruct]
+ -[NTForYouRequestManifest encodeWithCoder:]
+ -[NTForYouRequestManifest fetchDate]
+ -[NTForYouRequestManifest initWithCoder:]
+ -[NTForYouRequestManifest initWithFetchDate:tagIDs:]
+ -[NTForYouRequestManifest tagIDs]
+ _FCCKWidgetSectionConfigSectionFilterBriefingArticlesKey
+ _FCCKWidgetSectionConfigSectionFilterExpiredArticlesKey
+ _FCCKWidgetSectionConfigSectionFilterRecipeArticlesKey
+ _FCCKWidgetSectionConfigSectionFilterReduceVisibilityForNonFollowersKey
+ _OBJC_CLASS_$_NTForYouRequestManifest
+ _OBJC_IVAR_$_NTForYouRequestManifest._fetchDate
+ _OBJC_IVAR_$_NTForYouRequestManifest._tagIDs
+ _OBJC_METACLASS_$_NTForYouRequestManifest
+ __OBJC_$_CLASS_METHODS_NTForYouRequestManifest
+ __OBJC_$_CLASS_PROP_LIST_NTForYouRequestManifest
+ __OBJC_$_INSTANCE_METHODS_NTForYouRequestManifest
+ __OBJC_$_INSTANCE_VARIABLES_NTForYouRequestManifest
+ __OBJC_$_PROP_LIST_NTForYouRequestManifest
+ __OBJC_CLASS_PROTOCOLS_$_NTForYouRequestManifest
+ __OBJC_CLASS_RO_$_NTForYouRequestManifest
+ __OBJC_METACLASS_RO_$_NTForYouRequestManifest
+ ___block_descriptor_105_e8_32s40s48s56s64s72s80s88s96bs_e29_v24?0"NSArray"8"NSError"16ls96l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8
+ ___block_descriptor_64_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_89_e8_32s40s48s56s64s72s80bs_e54_v40?0"NSArray"8"NSArray"16"NSObject"24"NSError"32ls80l8s32l8s40l8s48l8s56l8s64l8s72l8
- ___210-[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:completion:]_block_invoke_5
- ___block_descriptor_73_e8_32s40s48s56s64bs_e54_v40?0"NSArray"8"NSArray"16"NSObject"24"NSError"32ls64l8s32l8s40l8s48l8s56l8
- ___block_descriptor_97_e8_32s40s48s56s64s72s80s88bs_e29_v24?0"NSArray"8"NSError"16ls88l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8
CStrings:
+ "Failed to decode For You manifest at %{public}@, error=%{public}@"
+ "Failed to encode For You manifest for %{public}@, error=%{public}@"
+ "fetchDate"
+ "fy-manifest-"
+ "pruning section from queue, identifier=%{public}@, favoritesOnly=%d, watchEligible=%d, mutingTag=%d, mutingTagID=%{public}@"
+ "tagIDs"
- "fy-fetchdate-"
```
