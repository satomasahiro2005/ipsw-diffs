## FindMyLocate

> `/System/Library/PrivateFrameworks/FindMyLocate.framework/FindMyLocate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15ad68` | `0x15eab4` | **`+0x3d4c`** |
| `__TEXT.__cstring` | `0x2c28` | `0x3183` | **`+0x55b`** |
| `__AUTH.__data` | `0x678` | `0xb40` | **`+0x4c8`** |
| `__DATA_DIRTY.__data` | `0x2d60` | `0x2898` | **`-0x4c8`** |
| `__DATA.__bss` | `0x17300` | `0x17700` | **`+0x400`** |
| `__TEXT.__unwind_info` | `0x6348` | `0x6020` | **`-0x328`** |
| `__TEXT.__swift5_reflstr` | `0x22da` | `0x258a` | **`+0x2b0`** |
| `__TEXT.__const` | `0x116dc` | `0x11950` | **`+0x274`** |
| `__TEXT.__eh_frame` | `0xee48` | `0xf090` | **`+0x248`** |
| `__AUTH_CONST.__const` | `0xb890` | `0xbac0` | **`+0x230`** |
| `__TEXT.__swift5_fieldmd` | `0x38b8` | `0x3ad0` | **`+0x218`** |
| `__AUTH.__objc_data` | `0xe0` | `0x180` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x388` | `0x2e8` | **`-0xa0`** |
| `__TEXT.__swift5_typeref` | `0x3a6b` | `0x3ad3` | **`+0x68`** |
| `__TEXT.__swift5_capture` | `0x1b68` | `0x1bb4` | **`+0x4c`** |
| `__TEXT.__constg_swiftt` | `0x3114` | `0x315c` | **`+0x48`** |
| `__DATA.__data` | `0x22b8` | `0x22f0` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0xf40` | `0xf60` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x11a0` | `0x11c0` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x8e0` | `0x8f4` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x744` | `0x754` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xe60` | `0xe68` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x2de0` | `0x2de8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xc50` | `0xc58` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1194` | `0x119c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x438` | `0x440` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x2845` | `0x2846` | **`+0x1`** |

### Other Changes

```diff

-140.30.6.7.1
+141.30.6.14.2

-  Functions: 7037
-  Symbols:   1834
-  CStrings:  515
+  Functions: 7112
+  Symbols:   1842
+  CStrings:  553
Symbols:
+ ___swift_closure_destructor.208Tm
+ _associated conformance 12FindMyLocate19ClientConfigurationV10CodingKeys33_21BA88E05CE88FA03561EF74E7304CC7LLOSHAASQ
+ _associated conformance 12FindMyLocate19ClientConfigurationV10CodingKeys33_21BA88E05CE88FA03561EF74E7304CC7LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 12FindMyLocate19ClientConfigurationV10CodingKeys33_21BA88E05CE88FA03561EF74E7304CC7LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _symbolic ScCy___________pG 12FindMyLocate19ClientConfigurationV s5ErrorP
+ _symbolic _____ 12FindMyLocate19ClientConfigurationV
+ _symbolic _____ 12FindMyLocate19ClientConfigurationV10CodingKeys33_21BA88E05CE88FA03561EF74E7304CC7LLO
+ _symbolic _____ s5Int64V
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12FindMyLocate19ClientConfigurationV10CodingKeys33_21BA88E05CE88FA03561EF74E7304CC7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12FindMyLocate19ClientConfigurationV10CodingKeys33_21BA88E05CE88FA03561EF74E7304CC7LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12FindMyLocate18AutoMeCapableWatchV
+ _symbolic _____y_____yx_GG 15Synchronization5MutexVAARi_zrlE 12FindMyLocate17StreamBroadcasterC5State33_4088EFAD3DECC97480CD7DCBFBBB83E5LLV
+ _type_layout_string 12FindMyLocate19ClientConfigurationV
- ___swift_closure_destructor.206Tm
- _get_type_metadata 15Synchronization5MutexVyScTyyts5Error_pGSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVyScTyyts5NeverOGSgG noncopyable
- _get_type_metadata s8SendableRzl15Synchronization5MutexVy12FindMyLocate17StreamBroadcasterC5State33_4088EFAD3DECC97480CD7DCBFBBB83E5LLVyx_GG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "\nappBackgroundSubscriptionsTimeout: "
+ "\ncallbackTimeoutIntervalInMS: "
+ "\nfallbackToLegacyIntervalInSec: "
+ "\nfenceSetupLink: "
+ "\nheartbeatIntervalInSec: "
+ "\ninaccuracyRadiusThreshold: "
+ "\niterationNumber: "
+ "\nliveAnimationInterval: "
+ "\nliveTimeoutThreshold: "
+ "\nmaxCallbackIntervalInMS: "
+ "\nmaxOfferLocationDurationInSec: "
+ "\nminOfferLocationDurationInSec: "
+ "\npendingRemoveGracePeriod: "
+ "\npeopleFindingBackgroundedTimeout: "
+ "\npeopleFindingConnectingTime: "
+ "\npeopleFindingNearbyDistance: "
+ "\nprecisionFindingSessionTimeout: "
+ "\nreverseGeocodingThrottle: "
+ "\nreverseGeocodingThrottleDistance: "
+ "appBackgroundSubscriptionsTimeout"
+ "callbackTimeoutIntervalInMS"
+ "fallbackToLegacyIntervalInSec"
+ "heartbeatIntervalInSec"
+ "inaccuracyRadiusThreshold"
+ "liveAnimationInterval"
+ "liveTimeoutThreshold"
+ "maxCallbackIntervalInMS"
+ "maxOfferLocationDurationInSec"
+ "minCallbackIntervalInMS"
+ "minCallbackIntervalInMS: "
+ "minOfferLocationDurationInSec"
+ "pendingRemoveGracePeriod"
+ "peopleFindingBackgroundedTimeout"
+ "peopleFindingConnectingTime"
+ "peopleFindingNearbyDistance"
+ "precisionFindingSessionTimeout"
+ "reverseGeocodingThrottle"
+ "reverseGeocodingThrottleDistance"
```
