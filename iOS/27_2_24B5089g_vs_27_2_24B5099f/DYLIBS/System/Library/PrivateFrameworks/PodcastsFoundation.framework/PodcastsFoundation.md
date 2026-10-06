## PodcastsFoundation

> `/System/Library/PrivateFrameworks/PodcastsFoundation.framework/PodcastsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e038c` | `0x4e2b04` | **`+0x2778`** |
| `__TEXT.__oslogstring` | `0x11aa0` | `0x11c40` | **`+0x1a0`** |
| `__DATA_DIRTY.__data` | `0x11140` | `0x11090` | **`-0xb0`** |
| `__TEXT.__swift5_reflstr` | `0xc90b` | `0xc9ab` | **`+0xa0`** |
| `__AUTH.__data` | `0x3110` | `0x31a0` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x1901e` | `0x190ae` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x1be08` | `0x1be88` | **`+0x80`** |
| `__TEXT.__const` | `0x3cca0` | `0x3cd20` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0xfb28` | `0xfb94` | **`+0x6c`** |
| `__AUTH_CONST.__const` | `0x2f480` | `0x2f4d0` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x1004c` | `0x1009c` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x12460` | `0x124b0` | **`+0x50`** |
| `__DATA.__data` | `0x6bf8` | `0x6c28` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x6934` | `0x6964` | **`+0x30`** |
| `__TEXT.__cstring` | `0x109dd` | `0x109fd` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2bc8` | `0x2be0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x16e8` | `0x16d8` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x69b0` | `0x69c0` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x14f04` | `0x14f14` | **`+0x10`** |
| `__DATA.__common` | `0x70` | `0x68` | **`-0x8`** |

### Other Changes

```diff

-4027.200.26.0.0
+4027.200.32.0.0

-  Functions: 27868
-  Symbols:   12526
-  CStrings:  3722
+  Functions: 27897
+  Symbols:   12534
+  CStrings:  3726
Symbols:
+ _CFRunLoopSourceInvalidate
+ _generic environment 5StateQy_Rsz18PodcastsFoundation07EpisodeA4RuleR_r0_l
+ _kMTPodcastDefaultUpdateInterval
+ _symbolic SDy__________G s5Int64V 18PodcastsFoundation16StoreFeedUpdaterC5Retry33_BBE9105918B104270B8AD7D17C924A48LLV
+ _symbolic SaySo17NSManagedObjectIDC_ABSgtG
+ _symbolic So17NSManagedObjectIDC07podcastC0_ABSg07episodeC0t
+ _symbolic So17NSManagedObjectIDC_ABSgt
+ _symbolic Sv
+ _symbolic _____ 18PodcastsFoundation16StoreFeedUpdaterC5Retry33_BBE9105918B104270B8AD7D17C924A48LLV
+ _symbolic _____Iegg_ 18PodcastsFoundation19PodcastStateMachineC
+ _symbolic _____Sg 18PodcastsFoundation16StoreFeedUpdaterC5Retry33_BBE9105918B104270B8AD7D17C924A48LLV
+ _symbolic _____ySo17NSManagedObjectIDC07podcastC0_ACSg07episodeC0tG s23_ContiguousArrayStorageC
+ _symbolic _____ySo17NSManagedObjectIDC_ACSgtG s23_ContiguousArrayStorageC
+ _symbolic _____y__________G s18_DictionaryStorageC s5Int64V 18PodcastsFoundation16StoreFeedUpdaterC5Retry33_BBE9105918B104270B8AD7D17C924A48LLV
+ _symbolic _____yxq_G 18PodcastsFoundation32StateMachineChangeObserverAction33_41103DDF35D7302800FCEE22DF941C95LLV
+ _symbolic _____yxq_GIegg_ 18PodcastsFoundation19EpisodeStateMachineC
+ _symbolic _____yy_____cG s23_ContiguousArrayStorageC 18PodcastsFoundation19PodcastStateMachineC
- _symbolic SDy__________G s5Int64V 18PodcastsFoundation16StoreFeedUpdaterC5RetryV
- _symbolic SaySo17NSManagedObjectIDC_ABtG
- _symbolic So17NSManagedObjectIDC07podcastC0_AB07episodeC0t
- _symbolic So17NSManagedObjectIDC_ABt
- _symbolic _____ 18PodcastsFoundation16StoreFeedUpdaterC5RetryV
- _symbolic _____Sg 18PodcastsFoundation16StoreFeedUpdaterC5RetryV
- _symbolic _____ySo17NSManagedObjectIDC07podcastC0_AC07episodeC0tG s23_ContiguousArrayStorageC
- _symbolic _____ySo17NSManagedObjectIDC_ACtG s23_ContiguousArrayStorageC
- _symbolic _____y__________G s18_DictionaryStorageC s5Int64V 18PodcastsFoundation16StoreFeedUpdaterC5RetryV
CStrings:
+ "ForceiPhoneSoloLandscapeSupport"
+ "Not proceeding with eviction of implicitly followed shows -- Count of implicitly followed shows: %ld is not over the limit: %ld"
+ "There is a running update for %{private,mask.hash}s. This is a follow, holding until the running update is done."
+ "[UpNextSplit] Couldn't find any unplayed episodes for episodic (old-to-new) show %s - \"%{private}s\""
+ "[UpNextSplit] Marking oldest unplayed episode as Current New Episode for episodic (old-to-new) show %s - \"%{private}s\". Episode \"%{private}s\""
+ "[UpNextSplit] Oldest unplayed episode is partially played for episodic (old-to-new) show %s - \"%{private}s\". Episode \"%{private}s\""
- "Not proceeding with eviction of implicitly followed shows -- Count of implicitly followed shows: %lu is not over the limit: %ld"
- "[UpNextSplit] Oldest unplayed episode for episodic (old-to-new) show %s - \"%{private}s\". Episode with ID %@"
```
