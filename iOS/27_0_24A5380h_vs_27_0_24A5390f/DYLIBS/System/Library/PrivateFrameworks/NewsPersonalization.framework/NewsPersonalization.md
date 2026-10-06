## NewsPersonalization

> `/System/Library/PrivateFrameworks/NewsPersonalization.framework/NewsPersonalization`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23b944` | `0x24a040` | **`+0xe6fc`** |
| `__TEXT.__cstring` | `0x106a1` | `0x10ea1` | **`+0x800`** |
| `__TEXT.__eh_frame` | `0xeac0` | `0xeddc` | **`+0x31c`** |
| `__AUTH_CONST.__objc_const` | `0xbd40` | `0xc008` | **`+0x2c8`** |
| `__AUTH.__data` | `0xe58` | `0x10f0` | **`+0x298`** |
| `__TEXT.__const` | `0x19ad0` | `0x19d50` | **`+0x280`** |
| `__AUTH_CONST.__const` | `0xb998` | `0xbb88` | **`+0x1f0`** |
| `__TEXT.__swift5_reflstr` | `0x4e65` | `0x5015` | **`+0x1b0`** |
| `__TEXT.__unwind_info` | `0x8430` | `0x85e0` | **`+0x1b0`** |
| `__TEXT.__swift5_fieldmd` | `0x5e40` | `0x5fbc` | **`+0x17c`** |
| `__TEXT.__constg_swiftt` | `0x534c` | `0x54ac` | **`+0x160`** |
| `__AUTH_CONST.__auth_got` | `0x2d20` | `0x2e68` | **`+0x148`** |
| `__DATA.__data` | `0x4b88` | `0x4c98` | **`+0x110`** |
| `__DATA.__bss` | `0x21510` | `0x21610` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0x4497` | `0x4585` | **`+0xee`** |
| `__TEXT.__swift5_capture` | `0xea0` | `0xf08` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x36f8` | `0x3740` | **`+0x48`** |
| `__DATA.__common` | `0x130` | `0x158` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0xa028` | `0xa048` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x698` | `0x6b4` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x2d0` | `0x2e8` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x148c` | `0x1498` | **`+0xc`** |
| `__TEXT.__swift5_protos` | `0xe0` | `0xe4` | **`+0x4`** |

### Other Changes

```diff

-5923.0.0.0.0
+5926.0.0.0.0

-  Functions: 11417
-  Symbols:   2682
-  CStrings:  1136
+  Functions: 11564
+  Symbols:   2714
+  CStrings:  1173
Symbols:
+ _OBJC_CLASS_$_NSLock
+ __DATA__TtC19NewsPersonalization28GroupFormationBestOfProvider
+ __DATA__TtC19NewsPersonalization28GroupFormationCandidateStore
+ __DATA__TtC19NewsPersonalization46ComputeServiceGroupFormationCapabilityProvider
+ __IVARS__TtC19NewsPersonalization28GroupFormationBestOfProvider
+ __IVARS__TtC19NewsPersonalization28GroupFormationCandidateStore
+ __IVARS__TtC19NewsPersonalization46ComputeServiceGroupFormationCapabilityProvider
+ __METACLASS_DATA__TtC19NewsPersonalization28GroupFormationBestOfProvider
+ __METACLASS_DATA__TtC19NewsPersonalization28GroupFormationCandidateStore
+ __METACLASS_DATA__TtC19NewsPersonalization46ComputeServiceGroupFormationCapabilityProvider
+ ___swift_closure_destructor.10Tm
+ __os_signpost_emit_with_name_impl
+ _get_enum_tag_for_layout_string 19NewsPersonalization30XavierFormGroupFunctionHandlerV6ErrorsO
+ _swift_release_x10
+ _symbolic $s19NewsPersonalization32GroupFormationCapabilityProviderP
+ _symbolic SDySS_____G 10XavierNews17GroupableHeadlineV
+ _symbolic SDySS_____G 19NewsPersonalization21GroupFormationContextV
+ _symbolic SNySiG
+ _symbolic SS5token_t
+ _symbolic Say_____G 10XavierNews7ClassicV22HeadlineClusteringRuleO
+ _symbolic So6NSLockC
+ _symbolic _____ 10XavierNews7ClassicV13ConfigurationV010ClusteringD0V6QuotasV
+ _symbolic _____ 11TeaSettings0B0C19NewsPersonalizationE14GroupFormationV
+ _symbolic _____ 19NewsPersonalization21GroupFormationContextV
+ _symbolic _____ 19NewsPersonalization28GroupFormationBestOfProviderC
+ _symbolic _____ 19NewsPersonalization28GroupFormationCandidateStoreC
+ _symbolic _____ 19NewsPersonalization30XavierFormGroupFunctionHandlerV
+ _symbolic _____ 19NewsPersonalization30XavierFormGroupFunctionHandlerV6ErrorsO
+ _symbolic _____ 19NewsPersonalization46ComputeServiceGroupFormationCapabilityProviderC
+ _symbolic __________Sg______SbSay_____GSdSNySdGXESiSNySiGSay_____GtKcSgyc 10XavierNews7ClassicV17HeadlineClustererV14GroupingResultV AA12GroupableTagV AC13ConfigurationV010ClusteringJ0V6QuotasV AC0dK4RuleO AA0hD0V
+ _type_layout_string 19NewsPersonalization30XavierFormGroupFunctionHandlerV
+ _type_layout_string 19NewsPersonalization30XavierFormGroupFunctionHandlerV6ErrorsO
CStrings:
+ "Best Of: routing through ComputationalGraph (For You)"
+ "GroupFormation verify(forYou): path=%{public}@ kept=%ld"
+ "XavierFormGroupFunctionHandler.execute"
+ "bestOf: inventory prefix-limited %ld -> %ld (limit=%ld)"
+ "bestOf: tag=%{public}@ kind=%{public}@ candidates=%ld kept=%ld"
+ "capability: bestOfClustering=%ld runningVersion=%{public}@"
+ "capability: multiGroupClustering=%ld runningVersion=%{public}@"
+ "computational-graph"
+ "gate: %{public}@ internal=%ld serverFlag=%{public}d capability=%{public}d runningVersion=%{public}@ liveVersion=%{public}@"
+ "gate: closed reason=internal-disabled"
+ "groupFormation.adjustedScore"
+ "groupFormation.empiricalCompose"
+ "groupFormation.isChannelSubscribed"
+ "groupFormation.itemID"
+ "groupFormation.maxPublisherOccurrences"
+ "groupFormation.publisherContentRating"
+ "groupFormation.publisherID"
+ "groupFormation.publisherID.curated.clicks"
+ "groupFormation.publisherID.curated.impressions"
+ "groupFormation.publisherID.personalized.clicks"
+ "groupFormation.publisherID.personalized.impressions"
+ "groupFormation.publisherRelevanceRating"
+ "groupFormation.requestToken"
+ "groupFormation.score"
+ "groupFormation.selectedRank"
+ "groupFormation.topicContentRatings"
+ "groupFormation.topicRelevanceRatings"
+ "kept: tag=%{public}@ n=%ld slots=[%{public}@]"
+ "news.features.xavierGroupingDeprecation"
+ "newsGroupFormation"
+ "registry: registered group-formation handler=%{public}@"
+ "reorder: tag=%{public}@ n=%ld moved=%ld topByAdjusted=[%{public}@]"
+ "slot accepted "
+ "xavierHandler: WARNING count mismatch token=%{public}@ adjustedRank=%ld itemIDs=%ld"
+ "xavierHandler: accepts token=%{public}@ tag=%{public}@ kept=%ld organic=%ld promoNewsPlus=%ld promoAccessible=%ld slots=[%{public}@]"
+ "xavierHandler: enter token=%{public}@ candidates=%ld minSize=%ld maxSize=%ld rules=%ld"
+ "xavierHandler: exit token=%{public}@ kept=%ld rejected=%ld"
```
