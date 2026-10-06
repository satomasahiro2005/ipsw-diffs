## findmylocated

> `/usr/libexec/findmylocated`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x15648` | `0x15da8` | **`+0x760`** |
| `__TEXT.__text` | `0x5853b4` | `0x585adc` | **`+0x728`** |
| `__TEXT.__cstring` | `0xb482` | `0xb842` | **`+0x3c0`** |
| `__TEXT.__swift5_reflstr` | `0x7cfd` | `0x7e1d` | **`+0x120`** |
| `__TEXT.__swift5_fieldmd` | `0x8eac` | `0x8f84` | **`+0xd8`** |
| `__TEXT.__eh_frame` | `0x48008` | `0x48098` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x5c90` | `0x5cc0` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x4e85` | `0x4eb5` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x432c` | `0x435c` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x72ca` | `0x729c` | **`-0x2e`** |
| `__DATA_CONST.__const` | `0x181a0` | `0x181c0` | **`+0x20`** |
| `__TEXT.__const` | `0x20738` | `0x20718` | **`-0x20`** |
| `__TEXT.__swift_as_ret` | `0x27d8` | `0x27f4` | **`+0x1c`** |
| `__DATA.__data` | `0xefb8` | `0xefa0` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x2e50` | `0x2e68` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xf1c` | `0xf34` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x1a48` | `0x1a58` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1d10` | `0x1d20` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x70bc` | `0x70cc` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x18f3c` | `0x18f2c` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x1694` | `0x16a4` | **`+0x10`** |
| `__DATA.__objc_const` | `0x6270` | `0x6278` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xd50` | `0xd58` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x4d28` | `0x4d2c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-140.30.6.7.1
+141.30.6.14.2

-  Functions: 17434
-  Symbols:   2864
-  CStrings:  3812
+  Functions: 17446
+  Symbols:   2870
+  CStrings:  3834
Symbols:
+ _$s12FindMyLocate16SettingsProtocolP19clientConfigurationAA06ClientG0VyYaKFTj
+ _$s12FindMyLocate16SettingsProtocolP19clientConfigurationAA06ClientG0VyYaKFTjTu
+ _$s12FindMyLocate16SettingsProtocolP19clientConfigurationAA06ClientG0VyYaKFTq
+ _$s12FindMyLocate19ClientConfigurationV23minCallbackIntervalInMS25inaccuracyRadiusThreshold03maxghiJ0016fallbackToLegacyhI3Sec32reverseGeocodingThrottleDistance015callbackTimeouthiJ05prsId09heartbeathiR004livexM0013liveAnimationH00stU015iterationNumber0f21OfferLocationDurationiR00n21OfferLocationDurationiR014fenceSetupLink023precisionFindingSessionX0019peopleFindingNearbyV027peopleFindingConnectingTime025peopleFindingBackgroundedX0026appBackgroundSubscriptionsX024pendingRemoveGracePeriodACSd_S5ds5Int64VS4dSiS2dSSS5dSitcfC
+ _$s12FindMyLocate19ClientConfigurationVMa
+ _$s12FindMyLocate19ClientConfigurationVMn
+ _$s12FindMyLocate19ClientConfigurationVSEAAMc
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ " appBackgroundSubscriptionsTimeout:"
+ " fenceSetupLink:"
+ " maxOfferLocationDurationInSec:"
+ " minOfferLocationDurationInSec:"
+ " pendingRemoveGracePeriod:"
+ " peopleFindingBackgroundedTimeout:"
+ " peopleFindingConnectingTime:"
+ " peopleFindingNearbyDistance:"
+ " precisionFindingSessionTimeout:"
+ "AutoMe is active - not accepting live location request."
+ "Fence %{public}s cannot be triggered because this device is not currently publishing locations"
+ "Scheduling void command to %{public}s on %{public}s WorkItem: %{public}s"
+ "appBackgroundSubscriptionsTimeout"
+ "clientConfiguration(completion:)"
+ "clientConfigurationWithCompletion:"
+ "https://support.apple.com/guide/findmy-mac/set-location-notifications-fmmeb70d2de0/mac"
+ "https://support.apple.com/guide/ipad/set-location-notifications-for-friends-ipad4c370380/ipados"
+ "https://support.apple.com/guide/iphone/set-location-notifications-for-friends-iph843dd79b6/ios"
+ "maxOfferLocationDurationInSec"
+ "minOfferLocationDurationInSec"
+ "pendingRemoveGracePeriod"
+ "peopleFindingBackgroundedTimeout"
+ "peopleFindingConnectingTime"
+ "peopleFindingNearbyDistance"
+ "precisionFindingSessionTimeout"
+ "sendVoidCommand(_:content:credential:)"
- "FenceService: dataManagerStateStream is nil — cannot monitor for friend removal"
- "FenceService: failed to set up .removedFriend monitor: %{public}@"
- "Scheduling AckAlert command to %{public}s on %{public}s WorkItem: %{public}s"
- "sendAckAlertCommand(_:content:credential:)"
```
