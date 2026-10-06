## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b5dbc` | `0x8ba008` | **`+0x424c`** |
| `__AUTH.__objc_data` | `0xb9e8` | `0xb290` | **`-0x758`** |
| `__DATA_DIRTY.__objc_data` | `0x5660` | `0x5db8` | **`+0x758`** |
| `__DATA_DIRTY.__data` | `0x2c30` | `0x2fc8` | **`+0x398`** |
| `__DATA.__bss` | `0x26d60` | `0x270e0` | **`+0x380`** |
| `__AUTH.__data` | `0x3858` | `0x3530` | **`-0x328`** |
| `__TEXT.__cstring` | `0x30bd2` | `0x30e0c` | **`+0x23a`** |
| `__AUTH_CONST.__const` | `0x3c960` | `0x3cb80` | **`+0x220`** |
| `__TEXT.__oslogstring` | `0x38416` | `0x385a8` | **`+0x192`** |
| `__TEXT.__const` | `0x60350` | `0x604c0` | **`+0x170`** |
| `__TEXT.__eh_frame` | `0x1ffec` | `0x20134` | **`+0x148`** |
| `__AUTH_CONST.__objc_const` | `0x41f28` | `0x42050` | **`+0x128`** |
| `__TEXT.__swift5_fieldmd` | `0x7c44` | `0x7d60` | **`+0x11c`** |
| `__TEXT.__swift5_reflstr` | `0x671e` | `0x681e` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x25484` | `0x25544` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x10648` | `0x106d0` | **`+0x88`** |
| `__TEXT.__swift5_capture` | `0x779c` | `0x7810` | **`+0x74`** |
| `__TEXT.__gcc_except_tab` | `0x54ec` | `0x547c` | **`-0x70`** |
| `__TEXT.__unwind_info` | `0x16910` | `0x16980` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x7b08` | `0x7b68` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x24300` | `0x24340` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x907f` | `0x90bf` | **`+0x40`** |
| `__DATA_CONST.__const` | `0xd858` | `0xd888` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x1a5c` | `0x1a78` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0x17b4` | `0x17d0` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x27a8` | `0x27c0` | **`+0x18`** |
| `__DATA.__data` | `0x91e4` | `0x91d8` | **`-0xc`** |
| `__TEXT.__swift_as_cont` | `0x1a9c` | `0x1aa8` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0xda8` | `0xdb4` | **`+0xc`** |
| `__DATA.__common` | `0xb74` | `0xb6c` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1b38` | `0x1b40` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0xa0` | `0xa8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x8f4` | `0x8fc` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xafc` | `0xb00` | **`+0x4`** |

### Other Changes

```diff

-10.1.11.2.1
+10.1.13.2.1

-  Functions: 35702
-  Symbols:   27306
-  CStrings:  9825
+  Functions: 35826
+  Symbols:   27341
+  CStrings:  9845
Symbols:
+ +[AMSDefaults cardEnrollmentWarmWindowCount]
+ +[AMSDefaults cardEnrollmentWarmWindowStart]
+ +[AMSDefaults setCardEnrollmentWarmWindowCount:]
+ +[AMSDefaults setCardEnrollmentWarmWindowStart:]
+ +[AMSProcessInfo _bundleInfoStringForKey:bundleIdentifier:record:]
+ -[AMSProcessInfo _bundleFactsLocked]
+ -[AMSProcessInfo _resolveBundleURLLocked]
+ -[AMSProcessInfo _resolveBundleVersionLocked]
+ -[AMSProcessInfo _resolveClientVersionLocked]
+ -[AMSProcessInfo _resolveCodablePropertiesLocked]
+ -[AMSProcessInfo _resolveDescriptionPropertiesLocked]
+ -[AMSProcessInfo _resolveEqualityPropertiesLocked]
+ -[AMSProcessInfo _resolveExecutableNameLocked]
+ -[AMSProcessInfo _resolveLocalizedNameLocked]
+ -[AMSProcessInfoBundleFacts _resolvedStringValue:generator:]
+ -[AMSProcessInfoBundleFacts _resolvedURLValue:generator:]
+ -[AMSProcessInfoBundleFacts initWithBundleURLGenerator:executableNameGenerator:localizedNameGenerator:bundleVersionGenerator:clientVersionGenerator:]
+ _AKCredentialCollectionIsLoud
+ _OBJC_IVAR_$_AMSProcessInfo._bundleFacts
+ _OBJC_IVAR_$_AMSProcessInfo._resolvesFromBundleFacts
+ _OBJC_IVAR_$_AMSProcessInfoBundleFacts._bundleURLGenerator
+ _OBJC_IVAR_$_AMSProcessInfoBundleFacts._bundleVersionGenerator
+ _OBJC_IVAR_$_AMSProcessInfoBundleFacts._clientVersionGenerator
+ _OBJC_IVAR_$_AMSProcessInfoBundleFacts._executableNameGenerator
+ _OBJC_IVAR_$_AMSProcessInfoBundleFacts._localizedNameGenerator
+ _OBJC_IVAR_$_AMSProcessInfoBundleFacts._lock
+ ___58+[AMSProcessInfo _launchServicesBundleFactsForIdentifier:]_block_invoke_3
+ ___58+[AMSProcessInfo _launchServicesBundleFactsForIdentifier:]_block_invoke_4
+ ___58+[AMSProcessInfo _launchServicesBundleFactsForIdentifier:]_block_invoke_5
+ ___block_descriptor_40_e8_32s_e12_"NSURL"8?0ls32l8
+ ___block_descriptor_40_e8_32s_e15_"NSString"8?0ls32l8
+ ___block_descriptor_64_e8_32s40s48s_e53_v24?0"AMSMetricsFigaroBagConfguration"8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48bs_e5_v8?0ls32l8u56l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___swift_memcpy343_8
+ ___swift_memcpy695_8
+ _associated conformance 18AppleMediaServices19SelfieConfigurationV17FaceIDCalibrationV10CodingKeys33_5876F864F6DA530D109B30F5992255AFLLOSHAASQ
+ _associated conformance 18AppleMediaServices19SelfieConfigurationV17FaceIDCalibrationV10CodingKeys33_5876F864F6DA530D109B30F5992255AFLLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 18AppleMediaServices19SelfieConfigurationV17FaceIDCalibrationV10CodingKeys33_5876F864F6DA530D109B30F5992255AFLLOs0H3KeyAAs28CustomDebugStringConvertible
+ _symbolic _____ 18AppleMediaServices19SelfieConfigurationV17FaceIDCalibrationV
+ _symbolic _____ 18AppleMediaServices19SelfieConfigurationV17FaceIDCalibrationV10CodingKeys33_5876F864F6DA530D109B30F5992255AFLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 18AppleMediaServices19SelfieConfigurationV17FaceIDCalibrationV10CodingKeys33_5876F864F6DA530D109B30F5992255AFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 18AppleMediaServices19SelfieConfigurationV17FaceIDCalibrationV10CodingKeys33_5876F864F6DA530D109B30F5992255AFLLO
+ _type_layout_string 18AppleMediaServices19SelfieConfigurationV17FaceIDCalibrationV
- -[AMSProcessInfo _ensureAllPropertiesResolved]
- -[AMSProcessInfo _resolveRecordPropertiesIfNeededLocked]
- _OBJC_IVAR_$_AMSProcessInfo._recordPropertiesResolved
- ___block_descriptor_48_e8_32s40bs_e24_24?0^{__CFString=}8#16ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48r_e15_"NSBundle"8?0lr48l8s32l8s40l8
- ___block_descriptor_56_e8_32s40s_e53_v24?0"AMSMetricsFigaroBagConfguration"8"NSError"16ls32l8s40l8
- ___block_descriptor_64_e8_32s40bs_e5_v8?0ls32l8u48l8s40l8
- ___swift_memcpy295_8
- ___swift_memcpy599_8
CStrings:
+ " bytes); dropping"
+ "%{public}@: [%{public}@] Cannot schedule flush for container %{public}@ with style %{public}ld (no flush interval available)"
+ "%{public}@: [%{public}@] Cannot schedule flush for container %{public}@ with style %{public}ld because one is already scheduled and pending; it may be one deferred until the app becomes active."
+ "%{public}@: [%{public}@] Cannot schedule flush for container %{public}@ with style %{public}ld because the style is currently not allowed."
+ "%{public}@: [%{public}@] Flush scheduled for container %{public}@. (style: %{public}ld, time: %{public}.3f)"
+ "%{public}@: [%{public}@] Not scheduling flush for container %{public}@ because we failed to get Figaro bag configuration: %{public}@"
+ "%{public}@: [%{public}@] Replacing a deferred flush for container %{public}@ that has not run yet; the app has not become active since it was deferred."
+ "%{public}@: [%{public}@] Scheduled flush for container %{public}@ with flush style %{public}ld unable to run while app is inactive, it will be run when app becomes active again."
+ "%{public}@authResults credential source AKCredentialCollectionIsLoud = %{public}@"
+ "2`"
+ "@\"NSString\"8@?0"
+ "@\"NSURL\"8@?0"
+ "AMSCardEnrollmentWarmWindowCount"
+ "AMSCardEnrollmentWarmWindowStart"
+ "CardEnrollmentCacheWarming"
+ "Diagnostic attachment too large ("
+ "Failed to write diagnostic attachment. Error: "
+ "Passcode Engagement not available: Feature flag turned off"
+ "PasscodeEngagement"
+ "Rejected unsafe diagnostic filename: "
+ "centerBinPitchMaximum"
+ "centerBinPitchMinimum"
+ "correctionSeedFrameCount"
+ "faceIDCalibration"
+ "pitchCorrectionAlpha"
+ "pitchRangeComputeMax"
+ "pitchRangeComputeMin"
+ "pitchRangeForCorrectionMinimum"
- "%{public}@: [%{public}@] Cannot schedule flush with style %{public}ld (no flush interval available)"
- "%{public}@: [%{public}@] Cannot schedule flush with style %{public}ld because one has already been scheduled and is pending."
- "%{public}@: [%{public}@] Cannot schedule flush with style %{public}ld because the style is currently not allowed."
- "%{public}@: [%{public}@] Flush scheduled. (style: %{public}ld, time: %{public}.3f)"
- "%{public}@: [%{public}@] Not scheduling flush because we failed to get Figaro bag configuration: %{public}@"
- "%{public}@: [%{public}@] Scheduled flush for container %@{public}@ with flush style %{public}ld unable to run while app is inactive, it will be run when app becomes active again."
- "@\"NSBundle\"8@?0"
- "@24@?0^{__CFString=}8#16"
```
