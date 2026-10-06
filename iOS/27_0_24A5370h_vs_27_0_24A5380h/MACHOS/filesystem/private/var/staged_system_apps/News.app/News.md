## News

> `/private/var/staged_system_apps/News.app/News`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6171c` | `0x61308` | **`-0x414`** |
| `__DATA.__objc_const` | `0xd500` | `0xd408` | **`-0xf8`** |
| `__TEXT.__cstring` | `0x8a74` | `0x8994` | **`-0xe0`** |
| `__DATA.__objc_data` | `0x1e98` | `0x1e48` | **`-0x50`** |
| `__TEXT.__objc_methtype` | `0x4fc7` | `0x5017` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x77c4` | `0x7784` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x1787e` | `0x1784e` | **`-0x30`** |
| `__TEXT.__objc_stubs` | `0xe2a0` | `0xe280` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xd08` | `0xd18` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1600` | `0x15f0` | **`-0x10`** |
| `__TEXT.__objc_classname` | `0x1713` | `0x1703` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1a98` | `0x1a88` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xb10` | `0xb08` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x320` | `0x318` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x220` | `0x218` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x5d0` | `0x5cc` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5920.0.0.0.0
+5923.0.0.0.0

-  - /System/Library/PrivateFrameworks/NewsUserEvents.framework/NewsUserEvents

-  Functions: 2710
-  Symbols:   900
-  CStrings:  5423
+  Functions: 2702
+  Symbols:   897
+  CStrings:  5419
Symbols:
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_willThrowTypedImpl
CStrings:
+ "@\"NSArray\"32@0:8@\"NSArray\"16@?<@\"FCFeedPersonalizedItemScoreProfile\"@?@\"<FCFeedPersonalizingItem>\">24"
+ "@\"NSURL\"32@0:8@\"NSString\"16^@24"
+ "@32@0:8@16^@24"
+ "baseFileURL"
+ "limitItemsByMinimumItemQuality:scoreProvider:"
+ "scoreTagsIDs:"
+ "sortTagIDsDescending:"
+ "zipForExportWithFilename:error:"
- "-[FRSubscribedTagRanker initWithTagRanker:]"
- "-[FRSubscribedTagRanker init]"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Feldspar/feldspar/Classes/FRSubscribedTagRanker.m"
- "@\"NSArray\"32@0:8@\"NSArray\"16@\"FCMapTable\"24"
- "FRSubscribedTagRanker"
- "T@\"<FCTagRanking>\",R,N,V_tagRanker"
- "initWithTagRanker:"
- "limitItemsByMinimumItemQuality:scoreProfiles:"
- "rankTagIDsDescending:"
- "readBaseDirectoryWithAccessor:"
- "scoresForTagIDs:"
- "v24@0:8@?<v@?@\"NSURL\">16"
```
