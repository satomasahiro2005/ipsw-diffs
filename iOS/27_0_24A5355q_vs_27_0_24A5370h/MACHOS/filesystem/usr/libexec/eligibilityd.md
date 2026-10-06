## eligibilityd

> `/usr/libexec/eligibilityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42310` | `0x43924` | **`+0x1614`** |
| `__DATA_CONST.__objc_arraydata` | `0xbed0` | `0xc288` | **`+0x3b8`** |
| `__DATA_CONST.__objc_dictobj` | `0xacd0` | `0xafa0` | **`+0x2d0`** |
| `__TEXT.__cstring` | `0x6ef2` | `0x7063` | **`+0x171`** |
| `__DATA_CONST.__cfstring` | `0x5460` | `0x55c0` | **`+0x160`** |
| `__DATA_CONST.__const` | `0x28d8` | `0x29c8` | **`+0xf0`** |
| `__TEXT.__objc_methname` | `0x31ef` | `0x32bf` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x2980` | `0x2a40` | **`+0xc0`** |
| `__DATA_CONST.__objc_arrayobj` | `0x2e50` | `0x2ee0` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0xbd0` | `0xc00` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x7b9` | `0x78b` | **`-0x2e`** |
| `__TEXT.__oslogstring` | `0x273b` | `0x2768` | **`+0x2d`** |
| `__TEXT.__unwind_info` | `0x12a0` | `0x12c8` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x1a90` | `0x1a70` | **`-0x20`** |
| `__DATA.__data` | `0x12f0` | `0x1300` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xd58` | `0xd48` | **`-0x10`** |
| `__TEXT.__const` | `0x2710` | `0x2720` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x91a` | `0x928` | **`+0xe`** |
| `__DATA_CONST.__got` | `0x3b8` | `0x3b0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-417.0.0.502.1
+432.0.0.0.2

-  Functions: 1390
-  Symbols:   650
-  CStrings:  1997
+  Functions: 1401
+  Symbols:   647
+  CStrings:  2017
Symbols:
+ _$sSa10FoundationE34_conditionallyBridgeFromObjectiveC_6resultSbSo7NSArrayC_SayxGSgztFZ
+ _OBJC_CLASS_$_MAAutoAssetSet
+ _OBJC_CLASS_$_MAAutoAssetSetAtomicEntry
+ _OBJC_CLASS_$_MAAutoAssetSetEntry
- _$s8Dispatch0A3QoSV0B6SClassO7defaultyA2EmFWC
- _$s8Dispatch0A3QoSV0B6SClassOMa
- _$sSo17OS_dispatch_queueC8DispatchE6global3qosAbC0D3QoSV0G6SClassO_tFZ
- _OBJC_CLASS_$_MAAutoAsset
- _OBJC_CLASS_$_MAAutoAssetSelector
- _OBJC_CLASS_$_OS_dispatch_queue
- _objc_retain_x28
CStrings:
+ "%s: Answer plist %s unexpectedly returned a non-dictionary object"
+ "%s: Attempting to force domain %s to unknown answer value %llu"
+ "%s: Detected a China Location device incorrectly returning eligible. isGreymatter: %d, isDubnium: %d, isSiriMode: %d, isAmericium: %d, isMeitnerium %d, hasBillingAccount: %d, chinaBilling: %d, chinaLocation: %d"
+ "%s: Detected a ChinaSKU device incorrectly returning eligible. isGreymatter: %d, isStrontium: %d, isDubnium: %d, isSiriMode: %d, isAmericium: %d, isMeitnerium: %d"
+ "%s: Skipping domain %s because it doesn't have a plist specified"
+ "%s: Unable to load the current eligibility answers on disk, skipping file %s: %@"
+ "%s: Unknown domain %s read from file %s"
+ "%s: Unsupported answer source: %llu"
+ "%s: Unsupported eligibility input type %s"
+ "00:36:44"
+ "432.0.0.0.2"
+ "AgeAssuranceWaterfallAccountOptBR"
+ "AppleTV"
+ "AudioAccessory"
+ "Expected exactly 1 locked entry, got %ld"
+ "Failed to cast locked entries to [MAAutoAssetSetAtomicEntry]"
+ "Jun 12 2026"
+ "Locked content had nil entries"
+ "Locked entry had nil localContentURL"
+ "MeitneriumBlockChina"
+ "MeitneriumPolicy"
+ "OS_ELIGIBILITY_"
+ "OS_ELIGIBILITY_ANSWER_"
+ "OS_ELIGIBILITY_ANSWER_SOURCE_"
+ "OS_ELIGIBILITY_ANSWER_SOURCE_COMPUTED"
+ "OS_ELIGIBILITY_ANSWER_SOURCE_FORCED"
+ "OS_ELIGIBILITY_ANSWER_SOURCE_INVALID"
+ "OS_ELIGIBILITY_DOMAIN_"
+ "autoAssetSetWithClient:error:"
+ "eligibility_answer_source_to_str"
+ "endAtomicLock:ofAtomicInstance:completion:"
+ "endAtomicLockSync:ofAtomicInstance:"
+ "fetchAndIngestAssetSetAsync"
+ "fetchAndIngestAssetSetWithError:"
+ "fullAssetSelector"
+ "hasPrefix:"
+ "ingestAssetWithLocalContentURL:blockAssetSelector:error:"
+ "initUsingClientDomain:forClientName:forAssetSetIdentifier:comprisedOfEntries:error:"
+ "length"
+ "localContentURL"
+ "lockAtomic:forAtomicInstance:withTimeout:completion:"
+ "lockAtomicSync:forAtomicInstance:withNeedPolicy:withTimeout:lockedAtomicEntries:error:"
+ "lockedInstance was nil despite successful lock"
+ "markInterestInAssetSetAsync"
+ "needForAtomic:completion:"
+ "substringFromIndex:"
+ "unsignedLongLongValue"
+ "v24@?0@\"NSString\"8@\"NSError\"16"
+ "v32@?0@\"NSString\"8@\"NSArray\"16@\"NSError\"24"
+ "v32@?0@\"NSString\"8@\"NSNumber\"16^B24"
- "%s: Answer plist %llu unexpectedly returned a non-dictionary object"
- "%s: Attempting to force domain %llu to unknown answer value %llu"
- "%s: Detected a China Location device incorrectly returning eligible. isGreymatter: %d, isDubnium: %d, isSiriMode: %d, isAmericium: %d, hasBillingAccount: %d, chinaBilling: %d, chinaLocation: %d"
- "%s: Detected a ChinaSKU device incorrectly returning eligible. isGreymatter: %d, isStrontium: %d, isDubnium: %d, isSiriMode %d, isAmericium %d"
- "%s: Skipping domain %llu because it doesn't have a plist specified"
- "%s: Unable to load the current eligibility answers on disk, skipping file %llu: %@"
- "%s: Unknown domain %s read from file %llu"
- "%s: Unsupported eligibility input type %llu"
- "20:47:38"
- "417.0.0.502.1"
- "B48@0:8@16@24@32^@40"
- "Jun  3 2026"
- "MobileAsssetMarkInterest"
- "Newer version in progress %s"
- "No newer version currently being downloaded"
- "Succesfully locked content, but the URL given by MobileAsset was nil"
- "autoAssetWithClient:error:"
- "endLockUsage:completion:"
- "endLockUsageSync:"
- "fetchAndIngestAssetAsync"
- "fetchAndIngestAssetWithError:"
- "ingestAssetWithLocalContentURL:blockAssetSelector:newerInProgress:error:"
- "initForClientName:selectingAsset:completingFromQueue:error:"
- "interestInContent:completion:"
- "lockContent:withTimeout:completion:"
- "lockContentSync:withTimeout:lockedAssetSelector:newerInProgress:error:"
- "lockedAssetSelector was not set despite a successful return from lockContentSync"
- "markInterestInAssetAsync"
- "v24@?0@\"MAAutoAssetSelector\"8@\"NSError\"16"
- "v44@?0@\"MAAutoAssetSelector\"8B16@\"NSURL\"20@\"MAAutoAssetStatus\"28@\"NSError\"36"
```
