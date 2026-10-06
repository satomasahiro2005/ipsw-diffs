## Home

> `/System/Library/PrivateFrameworks/Home.framework/Home`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c4508` | `0x3cace4` | **`+0x67dc`** |
| `__DATA.__data` | `0x7778` | `0x79f8` | **`+0x280`** |
| `__TEXT.__cstring` | `0x34c7a` | `0x34e1f` | **`+0x1a5`** |
| `__AUTH.__data` | `0x1480` | `0x1580` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0xeb40` | `0xebe0` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x1d895` | `0x1d91d` | **`+0x88`** |
| `__TEXT.__swift5_typeref` | `0x2c8d` | `0x2d03` | **`+0x76`** |
| `__TEXT.__swift5_fieldmd` | `0x11c4` | `0x1238` | **`+0x74`** |
| `__DATA_CONST.__got` | `0x3258` | `0x32c8` | **`+0x70`** |
| `__TEXT.__const` | `0x5970` | `0x59e0` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x222c` | `0x227c` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x75a8` | `0x7558` | **`-0x50`** |
| `__TEXT.__swift5_reflstr` | `0xe90` | `0xee0` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x4c5b0` | `0x4c570` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x13070` | `0x13098` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x4cc8` | `0x4cf0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x27420` | `0x27440` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2ca1c` | `0x2ca3c` | **`+0x20`** |
| `__DATA.__common` | `0x178` | `0x168` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0xf10` | `0xf20` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2240` | `0x2238` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x194` | `0x19c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x270` | `0x268` | **`-0x8`** |

### Other Changes

```diff

-1238.0.0.0.0
+1241.1.7.1.2

+  - /System/Library/PrivateFrameworks/OSEligibility.framework/OSEligibility

-  Functions: 21285
-  Symbols:   30308
-  CStrings:  8542
+  Functions: 21339
+  Symbols:   30322
+  CStrings:  8555
Symbols:
+ +[HFUtilities supportsOnDeviceCaptionPlayback]
+ -[UIImage(HFAdditions) hf_imageForUserInterfaceStyle:]
+ -[UIImage(HFAdditions) hf_registerDarkModeImage:]
+ GCC_except_table95
+ _HFTopicMatchesCameraProfileCategory
+ _OBJC_CLASS_$_OSEligibilityQuery
+ ___swift_closure_destructor.105Tm
+ ___swift_closure_destructor.96Tm
+ ___swift_get_extra_inhabitant_index.19Tm
+ ___swift_store_extra_inhabitant_index.20Tm
+ _symbolic SDySS_____G 4Home8EVDeviceV
+ _symbolic SDySS_____G 4Home8EVDeviceV7SessionV
+ _symbolic SS______t 4Home8EVDeviceV
+ _symbolic SS______t 4Home8EVDeviceV7SessionV
+ _symbolic _____ 4Home8EVDeviceV
+ _symbolic _____ 4Home8EVDeviceV7SessionV
+ _symbolic _____5state______5eventt 4Home7EVStateO AA7HFEventV
+ _symbolic _____5state______5eventtSg 4Home7EVStateO AA7HFEventV
+ _symbolic _____6create_AA6updatet 4Home7HFEventV
+ _symbolic _____Sg 13HomeKitEvents17EVConnectionEventV17NotChargingReasonO
+ _symbolic _____Sg 13HomeKitEvents24SomeElectricVehicleEventO
+ _symbolic _____Sg 4Home8EVDeviceV
+ _symbolic _____Sg 4Home8EVDeviceV7SessionV
+ _symbolic _____Sg_ABt 13HomeKitEvents17EVConnectionEventV17NotChargingReasonO
+ _symbolic ______AA4witht 4Home7HFEventV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 4Home8EVDeviceV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 4Home8EVDeviceV7SessionV
+ _symbolic _____y_____G s15CollectionOfOneV 4Home7HFEventV
- ___swift_closure_destructor.107Tm
- ___swift_closure_destructor.98Tm
- ___swift_get_extra_inhabitant_indexTm
- ___swift_store_extra_inhabitant_indexTm
- _symbolic SDySS_____G 4Home17DeviceStateWindowV
- _symbolic SDySS_____G 4Home18SessionRangeWindowV
- _symbolic SDySS_____G 4Home26SessionReconstructionStateO
- _symbolic SS______t 4Home17DeviceStateWindowV
- _symbolic SS______t 4Home18SessionRangeWindowV
- _symbolic SS______t 4Home26SessionReconstructionStateO
- _symbolic _____Sg 4Home26SessionReconstructionStateO
- _symbolic _____ySS_____G s18_DictionaryStorageC 4Home17DeviceStateWindowV
- _symbolic _____ySS_____G s18_DictionaryStorageC 4Home18SessionRangeWindowV
- _symbolic _____ySS_____G s18_DictionaryStorageC 4Home26SessionReconstructionStateO
CStrings:
+ " with "
+ "Battery management"
+ "Connected to power"
+ "Demand response event"
+ "Disconnected from power"
+ "Finished charging"
+ "HFError_HFErrorCodeAppleIntelligenceReportDeviceNotNearby_description"
+ "Insufficient power"
+ "Less clean energy"
+ "NotChargingCombinedReason_description"
+ "NotChargingReason_description"
+ "Started charging"
+ "Stopped charging"
+ "Waited for lower rates"
+ "Waited to charge"
+ "Waiting for cleaner energy"
+ "Waiting for lower rates"
+ "Waiting to charge"
+ "[HFUtilities] Failed to read the eligibility for on device caption playback: %{public}@"
+ "create update "
+ "https://support.apple.com/127902?cid=mc-ols-apple_intelligence-article_127902-ui-62020270"
+ "replaceRow: waiting row not found for %s"
- " charging complete"
- " charging completed"
- " charging is paused"
- " charging paused"
- " waited to charge"
- " waiting to charge"
- "Charging complete"
- "Generic name for an EV"
- "appleIntelligenceSplash://"
```
