## HomeKitMatter

> `/System/Library/PrivateFrameworks/HomeKitMatter.framework/HomeKitMatter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1815cc` | `0x1813a8` | **`-0x224`** |
| `__TEXT.__oslogstring` | `0x4f5a5` | `0x4f542` | **`-0x63`** |
| `__AUTH_CONST.__cfstring` | `0x6ce0` | `0x6d20` | **`+0x40`** |
| `__TEXT.__cstring` | `0x6e9e` | `0x6ed0` | **`+0x32`** |
| `__DATA_DIRTY.__bss` | `0xd8` | `0xc0` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x7098` | `0x7090` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x3140` | `0x3148` | **`+0x8`** |

### Other Changes

```diff

-1484.2.0.0.0
+1490.2.0.1.1

-  Symbols:   7341
+  Symbols:   7338
Symbols:
+ -[HMMTRProtocolMap getCHIPAttributesForCharacteristic:endpointID:clusterIDCharacteristicMap:]
+ _OBJC_CLASS_$_CoreHAPHKDF
+ _logCategory._hmf_once_t208
+ _logCategory._hmf_once_v209
- -[HMMTRProtocolMap getCHIPAttributesForCharacteristic:]
- _OBJC_CLASS_$_HAPECDSAKeyPairVerifySession
- __windowBeginSeconds
- __windowBoundariesInitialized
- __windowEndSeconds
- _logCategory._hmf_once_t210
- _logCategory._hmf_once_v211
Functions:
~ +[HMMTRBeaconProtectionKey bpkFromMatterFabricRawIPK:compressedFabricId:error:] : 588 -> 708
~ -[HMMTRDescriptorClusterManager _verifyHAPOptionalCharacteristicSupportAtCHIPEndpoint:device:endpointDeviceTypes:callbackQueue:clusterClassToQueryForAttributes:hapServicesToCheckForOptionalMatterAttribute:clusterAttributesSupported:hapServicesInUse:deviceTopology:bridgeAggregateNodeEndpoint:server:lastError:completionHandler:] : 2828 -> 2824
~ -[HMMTRAnnounceOtaScheduler init:] : 1044 -> 928
~ -[HMMTRAnnounceOtaScheduler _isWithinUpdateTimeWindowForComponents:windowBegin:windowEnd:] : 1216 -> 1088
~ -[HMMTRAnnounceOtaScheduler isWithinUpdateTimeWindow] : 84 -> 168
~ -[HMMTRProtocolMap getCHIPAttributesForCharacteristic:] -> -[HMMTRProtocolMap getCHIPAttributesForCharacteristic:endpointID:clusterIDCharacteristicMap:] : 696 -> 192
CStrings:
+ "HK Matter Privacy v1 BPK"
+ "HK Matter Privacy v1 TLK"
- "Window boundaries not initialized properly"
- "[%{public}@] Window boundaries not initialized properly"
```
