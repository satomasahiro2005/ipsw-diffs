## NewsPersonalization

> `/System/Library/PrivateFrameworks/NewsPersonalization.framework/NewsPersonalization`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x245dc8` | `0x248a98` | **`+0x2cd0`** |
| `__TEXT.__cstring` | `0x104a1` | `0x106a1` | **`+0x200`** |
| `__TEXT.__const` | `0x19f60` | `0x19e80` | **`-0xe0`** |
| `__TEXT.__swift5_typeref` | `0x4c9b` | `0x4bd1` | **`-0xca`** |
| `__TEXT.__constg_swiftt` | `0x5688` | `0x55c4` | **`-0xc4`** |
| `__AUTH_CONST.__objc_const` | `0xbed0` | `0xbe20` | **`-0xb0`** |
| `__AUTH.__data` | `0xef8` | `0xe58` | **`-0xa0`** |
| `__DATA_DIRTY.__bss` | `0x5f90` | `0x5f10` | **`-0x80`** |
| `__DATA_DIRTY.__data` | `0xa518` | `0xa4a8` | **`-0x70`** |
| `__AUTH.__objc_data` | `0x4f8` | `0x4a8` | **`-0x50`** |
| `__DATA.__data` | `0x4c38` | `0x4c78` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x5fd8` | `0x5f98` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x8848` | `0x8808` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x3c2c` | `0x3c58` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0xc640` | `0xc618` | **`-0x28`** |
| `__TEXT.__swift5_reflstr` | `0x4f55` | `0x4f75` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x36d8` | `0x36f0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2dc8` | `0x2db8` | **`-0x10`** |
| `__DATA_CONST.__const` | `0xb38` | `0xb48` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2e0` | `0x2d0` | **`-0x10`** |
| `__TEXT.__eh_frame` | `0xf6a8` | `0xf6b8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x149c` | `0x1490` | **`-0xc`** |
| `__DATA.__common` | `0x120` | `0x118` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0xe8` | `0xe0` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x6c0` | `0x6b8` | **`-0x8`** |

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

-  Functions: 11721
-  Symbols:   2787
-  CStrings:  1139
+  Functions: 11735
+  Symbols:   2772
+  CStrings:  1144
Symbols:
+ ___swift_memcpy86_8
- _OBJC_CLASS_$_FCNewsArticleEmbeddingsConfiguration
- __DATA__TtC19NewsPersonalization33UserEmbeddingConfigurationService
- __DATA__TtC19NewsPersonalization36KnownAggregateStoreStateModeResolver
- __IVARS__TtC19NewsPersonalization33UserEmbeddingConfigurationService
- __IVARS__TtC19NewsPersonalization36KnownAggregateStoreStateModeResolver
- __METACLASS_DATA__TtC19NewsPersonalization33UserEmbeddingConfigurationService
- __METACLASS_DATA__TtC19NewsPersonalization36KnownAggregateStoreStateModeResolver
- ___swift_memcpy94_8
- _objc_retain_x2
- _symbolic $s19NewsPersonalization30AggregateStateModeResolverTypeP
- _symbolic $s19NewsPersonalization37UserEmbeddingConfigurationServiceTypeP
- _symbolic _____ 13NewsAnalytics18AggregateStateModeO
- _symbolic _____ 19NewsPersonalization33UserEmbeddingConfigurationServiceC
- _symbolic _____ 19NewsPersonalization36KnownAggregateStoreStateModeResolverC
- _symbolic ______p 13TeaFoundation12ResolverTypeP
- _symbolic _____ySo36FCNewsArticleEmbeddingsConfigurationCG 19NewsPersonalization12FeatureStateO
CStrings:
+ "NTPBArticleTopic with nil tagID encountered during tagMetadata; older clients crash on this shape (rdar://177742140). itemID=%{public}@"
+ "NTPBArticleTopic with nil tagID encountered while building NewsCoreArticleData topics; older clients crash on this shape (rdar://177742140). itemID=%{public}@"
+ "Publisher group engagement filtering: excludeInaccessible=true, filteredArticleCount=%{public}@"
+ "SESSION_MESSAGE_VERSION_SEVEN"
+ "is_inaccessible"
+ "news.news_personalization.excludeInaccessibleArticlesFromPublisherGroupEngagement"
- "articleEmbeddingsScoring"
```
