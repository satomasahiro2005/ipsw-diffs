## ServiceDiscovery

> `/System/Library/PrivateFrameworks/ServiceDiscovery.framework/ServiceDiscovery`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14d7b8` | `0x159a1c` | **`+0xc264`** |
| `__TEXT.__const` | `0x922c` | `0x94bc` | **`+0x290`** |
| `__DATA.__bss` | `0xbab0` | `0xbd30` | **`+0x280`** |
| `__AUTH_CONST.__const` | `0x4e50` | `0x5078` | **`+0x228`** |
| `__AUTH_CONST.__objc_const` | `0x2e08` | `0x2ff8` | **`+0x1f0`** |
| `__AUTH.__data` | `0x1dc8` | `0x1fb0` | **`+0x1e8`** |
| `__TEXT.__oslogstring` | `0x56c6` | `0x5896` | **`+0x1d0`** |
| `__TEXT.__eh_frame` | `0xa690` | `0xa840` | **`+0x1b0`** |
| `__TEXT.__swift5_typeref` | `0x2ce5` | `0x2e85` | **`+0x1a0`** |
| `__TEXT.__unwind_info` | `0x3ab8` | `0x3c40` | **`+0x188`** |
| `__DATA.__data` | `0x23f8` | `0x2530` | **`+0x138`** |
| `__TEXT.__constg_swiftt` | `0x1ec4` | `0x1fc8` | **`+0x104`** |
| `__TEXT.__swift5_fieldmd` | `0x1aa8` | `0x1b6c` | **`+0xc4`** |
| `__TEXT.__swift5_reflstr` | `0x1439` | `0x14b9` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x1038` | `0x10b4` | **`+0x7c`** |
| `__AUTH.__objc_data` | `0xca8` | `0xd18` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x13a0` | `0x1400` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2795` | `0x27e5` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xcdc` | `0xd2c` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x830` | `0x858` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x700` | `0x718` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x614` | `0x628` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x130` | `0x140` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x8c8` | `0x8d8` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x428` | `0x438` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x49c` | `0x4a8` | **`+0xc`** |

### Other Changes

```diff

-740.100.2.0.0
+743.100.4.0.0

-  Functions: 4147
-  Symbols:   1592
-  CStrings:  779
+  Functions: 4280
+  Symbols:   1635
+  CStrings:  789
Symbols:
+ _IsAppleInternalBuild
+ _OBJC_CLASS_$_SDServiceDatabase
+ _OBJC_METACLASS_$_SDServiceDatabase
+ __CLASS_METHODS_SDServiceDatabase
+ __DATA_SDServiceDatabase
+ __DATA__TtC16ServiceDiscovery11RateLimiter
+ __INSTANCE_METHODS_SDServiceDatabase
+ __IVARS__TtC16ServiceDiscovery11RateLimiter
+ __METACLASS_DATA_SDServiceDatabase
+ __METACLASS_DATA__TtC16ServiceDiscovery11RateLimiter
+ _associated conformance 16ServiceDiscovery14DiscoveredPeerV5EntryVSHAASQ
+ _associated conformance 16ServiceDiscovery18RedactedPersonaMapVSHAASQ
+ _swift_release_x11
+ _swift_release_x13
+ _swift_retain_x12
+ _swift_stdlib_random
+ _symbolic SDySS_____G s6UInt16V
+ _symbolic SDy__________G 16ServiceDiscovery0A9DirectoryV0aC3KeyV AA14DiscoveredPeerV5EntryV
+ _symbolic SS_ShySSGt
+ _symbolic Say_____G s15ContinuousClockV7InstantV
+ _symbolic _____ 16ServiceDiscovery0A8DatabaseV
+ _symbolic _____ 16ServiceDiscovery11RateLimiterC
+ _symbolic _____ 16ServiceDiscovery14DiscoveredPeerV5EntryV
+ _symbolic _____ 16ServiceDiscovery18RedactedPersonaMapV
+ _symbolic _____ s8DurationV
+ _symbolic _____3key______5valuet 16ServiceDiscovery0A9DirectoryV0aC3KeyV AA14DiscoveredPeerV5EntryV
+ _symbolic _____3key______5valuet 16ServiceDiscovery0A9DirectoryV0aC3KeyV AC
+ _symbolic _____Sg 16ServiceDiscovery11RateLimiterC
+ _symbolic _____Sg s15ContinuousClockV7InstantV
+ _symbolic _____SgXw 16ServiceDiscovery11RateLimiterC
+ _symbolic _____SgXw 16ServiceDiscovery17CloudKitSDManagerC
+ _symbolic _____SgXwz_Xx 16ServiceDiscovery11RateLimiterC
+ _symbolic _____Sg_ABt 16ServiceDiscovery0A11QueryResultV
+ _symbolic _____Sg_ABt s15ContinuousClockV7InstantV
+ _symbolic ___________t 16ServiceDiscovery0A9DirectoryV0aC3KeyV AA14DiscoveredPeerV5EntryV
+ _symbolic ___________t 16ServiceDiscovery0A9DirectoryV0aC3KeyV AC
+ _symbolic _____ySSG s11_SetStorageC
+ _symbolic _____ySSShySSGG s18_DictionaryStorageC
+ _symbolic _____ySS_ShySSGtG s23_ContiguousArrayStorageC
+ _symbolic _____ySS_____G s18_DictionaryStorageC s6UInt16V
+ _symbolic _____ySiSaySDySiSDySiShy_____GGGGG s18_DictionaryStorageC 16ServiceDiscovery0C10DefinitionV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s15ContinuousClockV7InstantV
+ _symbolic _____y_____SaySDySiSDySiShy_____GGGGG s18_DictionaryStorageC 16ServiceDiscovery0C9DirectoryV0cE3KeyV AC0C10DefinitionV
+ _symbolic _____y__________G s18_DictionaryStorageC 16ServiceDiscovery0C9DirectoryV0cE3KeyV AC14DiscoveredPeerV5EntryV
+ _symbolic _____y__________G s18_DictionaryStorageC 16ServiceDiscovery0C9DirectoryV0cE3KeyV AE
+ _symbolic yyYaYbYCc
+ _type_layout_string 16ServiceDiscovery18RedactedPersonaMapV
- _swift_release_x15
- _symbolic _____Sg 16ServiceDiscovery0A9DirectoryV
- _symbolic _____Sg_ABt 16ServiceDiscovery0A9DirectoryV
- _symbolic _____y_____G s15CollectionOfOneV s5UInt8V
CStrings:
+ "Advertisement %s has empty personaUniqueID"
+ "Failed to decode remote payload from %s for %s: %@"
+ "Inconsistent ServiceDirectory: %s doesn't have a redacted value"
+ "Inserted mapping %s -> %hu"
+ "LECAHap"
+ "LECAHapLow"
+ "LECATmap"
+ "LECATmapLow"
+ "Remote payload from %s for %s has no partitions, ignoring"
+ "Removed mapping %s -> %hu"
+ "[%s] Cannot update effective BC for partition %s (to %s from %s), stale payload"
+ "[%s] Cannot update effective BC to %s, no partitions"
+ "[%s] Expired %ld partition(s)"
+ "[%s] Expired peer"
+ "[%s] Ignoring Remote Payload partition %s - equal to cache"
+ "[%s] Ignoring Remote Payload partition %s - not newer than cache"
+ "[%s] Insufficient Service Directory for partition %s (have %s, need %s, using %s), need payload"
+ "[%s] Merge skipping other partition %s - not newer than existing"
+ "[%s] Merge using other partition %s - newer than existing"
+ "[%s] Merge using other partition %s - no existing"
+ "[%s] No partitions for peer, need payload"
+ "[%s] Peer updating effective BC for partition %s (to %s from %s)"
+ "[%s] Query %s found %ld results across %ld partitions"
+ "[%s] Skipping query %s for %s without effective broadcast state"
+ "[%s] Skipping query %s without partitions"
+ "[%s] Storing Remote Payload partition %s - empty cache"
+ "[%s] Storing Remote Payload partition %s - newer than cache"
+ "[%s] Storing Remote Payload partition %s - reached stale retry limit"
+ "[%{public}s] Deferring action for %llds"
+ "[%{public}s] Previous action is pending, dropping trigger"
+ "com.apple.anqe.test.service"
+ "com.apple.siri.companionlink"
- "LECA1"
- "LECA2"
- "LECA3"
- "LECA4"
- "[%s] Cannot update effective BC (to %s from %s), no payload"
- "[%s] Cannot update effective BC (to %s from %s), stale payload"
- "[%s] Ignoring Remote Payload - equal to cache"
- "[%s] Ignoring Remote Payload - not newer than cache"
- "[%s] Insufficient Service Directory for peer (have %s, need %s, using %s, need payload"
- "[%s] Merge skipping other Service Directory - does not exist"
- "[%s] Merge skipping other Service Directory - not newer than existing"
- "[%s] Merge using other Service Directory - newer than existing"
- "[%s] Merge using other Service Directory - no existing"
- "[%s] No Service Directory for peer, need payload"
- "[%s] Peer updating effective Broadcast State (to %s from %s)"
- "[%s] Query %s with %s found %ld results"
- "[%s] Remote service directory has effective broadcast state %s"
- "[%s] Skipping query %s without Service Directory"
- "[%s] Skipping query %s without effective broadcast state"
- "[%s] Storing Remote Payload - empty cache"
- "[%s] Storing Remote Payload - newer than cache"
- "[%s] Storing Remote Payload - reached stale retry limit"
```
