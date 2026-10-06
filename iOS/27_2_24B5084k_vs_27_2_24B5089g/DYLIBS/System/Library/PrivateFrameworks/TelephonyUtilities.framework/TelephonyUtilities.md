## TelephonyUtilities

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b7280` | `0x1b7a9c` | **`+0x81c`** |
| `__AUTH.__objc_data` | `0x3228` | `0x2b70` | **`-0x6b8`** |
| `__DATA_DIRTY.__objc_data` | `0x26f0` | `0x2da8` | **`+0x6b8`** |
| `__TEXT.__cstring` | `0x14546` | `0x14616` | **`+0xd0`** |
| `__AUTH_CONST.__objc_const` | `0x2b598` | `0x2b648` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x127a0` | `0x12820` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x3898` | `0x3910` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x1ba28` | `0x1ba80` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0xb890` | `0xb8c0` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x58` | `0x78` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x14857` | `0x14877` | **`+0x20`** |
| `__DATA.__data` | `0x3f10` | `0x3f20` | **`+0x10`** |
| `__TEXT.__const` | `0x4acc` | `0x4adc` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7238` | `0x7248` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1940` | `0x194c` | **`+0xc`** |
| `__AUTH.__data` | `0xde8` | `0xde0` | **`-0x8`** |

### Other Changes

```diff

-1626.200.53.0.0
+1626.200.65.0.0

-  Functions: 11970
-  Symbols:   16237
-  CStrings:  4668
+  Functions: 11979
+  Symbols:   16252
+  CStrings:  4673
Symbols:
+ -[TUCall relayHostCallScreeningEligibility]
+ -[TUIDSLookupManager lastForcedQueryTimestamps]
+ -[TUSimulatedIDSIDQueryController _currentCachedRemoteDevicesForDestinations:service:preferredFromID:listenerID:]
+ -[TUSimulatedIDSIDQueryController currentRemoteDevicesForDestinations:service:preferredFromID:listenerID:queue:completionBlockWithError:]
+ -[TUSimulatedParticipantUpdate isVideoEnabled]
+ -[TUSimulatedParticipantUpdate setVideoEnabled:]
+ _OBJC_IVAR_$_TUCall._relayHostCallScreeningEligibility
+ _OBJC_IVAR_$_TUIDSLookupManager._lastForcedQueryTimestamps
+ _OBJC_IVAR_$_TUSimulatedParticipantUpdate._videoEnabled
+ ___58-[TUIDSLookupManager beginQueryWithDestination:onService:]_block_invoke_2
+ ___58-[TUIDSLookupManager beginQueryWithDestination:onService:]_block_invoke_3
+ ___block_descriptor_40_e8_32s_e33_B32?0"NSString"8"NSDate"16^B24ls32l8
+ ___block_descriptor_56_e8_32s40s48s_e22_v16?0"NSDictionary"8ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56s_e22_v16?0"NSDictionary"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8
+ __endpointsDictionaryForDestinations
- ___block_descriptor_56_e8_32s40s48bs_e22_v16?0"NSDictionary"8ls32l8s40l8s48l8
CStrings:
+ " rhse=%ld"
+ "B32@?0@\"NSString\"8@\"NSDate\"16^B24"
+ "Companion Software Not Compatible"
+ "The companion device could not complete the operation because it is on an incompatible software version."
+ "isEligibleForScreening: YES because the host device reported this relay call as eligible"
+ "relayHostCallScreeningEligibility"
+ "smartHoldingAvailability=%i, callSupportsScreening=%i validRemoteParticipantCount=%i validNotConferenced=%i, validSystemProvider=%i, validNotEmergencyCall=%i, validCallStatus=%i(%i), validEndpointOnCurrentDevice=%i, validIsNotVideo=%i, validLocale=%i(%@), validCaptioningAvailable=%i, isGASRAvailable=%i, validLockdownMode=%i, qfaLocaleExpansionEnabled=%i, qfaLocaleExpansionItPtEnabled=%i"
- "isEligibleForScreening: YES because it is a relay call that can screen"
- "smartHoldingAvailability=%i, validRemoteParticipantCount=%i validNotConferenced=%i, validSystemProvider=%i, validNotEmergencyCall=%i, validCallStatus=%i(%i), validEndpointOnCurrentDevice=%i, validIsNotVideo=%i, validLocale=%i(%@), validCaptioningAvailable=%i, isGASRAvailable=%i, validLockdownMode=%i, qfaLocaleExpansionEnabled=%i, qfaLocaleExpansionItPtEnabled=%i"
```
