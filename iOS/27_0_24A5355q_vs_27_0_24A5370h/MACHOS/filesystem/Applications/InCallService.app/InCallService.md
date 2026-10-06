## InCallService

> `/Applications/InCallService.app/InCallService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x297084` | `0x298434` | **`+0x13b0`** |
| `__TEXT.__oslogstring` | `0x22dcd` | `0x230dd` | **`+0x310`** |
| `__TEXT.__objc_methname` | `0x47e61` | `0x47f41` | **`+0xe0`** |
| `__TEXT.__auth_stubs` | `0x71b0` | `0x7240` | **`+0x90`** |
| `__DATA.__objc_const` | `0x249f8` | `0x24a78` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x2d940` | `0x2d9c0` | **`+0x80`** |
| `__TEXT.__cstring` | `0xaec0` | `0xaf10` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x38e8` | `0x3930` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x22c0` | `0x2300` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x90a4` | `0x90dc` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x19620` | `0x19658` | **`+0x38`** |
| `__DATA.__objc_data` | `0xace8` | `0xad10` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0xe5a0` | `0xe5c8` | **`+0x28`** |
| `__TEXT.__const` | `0xa3d4` | `0xa3f4` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x5c5c` | `0x5c7c` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xa148` | `0xa168` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x43bc` | `0x43a8` | **`-0x14`** |
| `__DATA.__data` | `0x9b48` | `0x9b58` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x3f49` | `0x3f59` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x36c8` | `0x36d4` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x5d4` | `0x5dc` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x254` | `0x25c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa4b0` | `0xa4a8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x12e0` | `0x12e4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-3060.100.14.2.1
+143.100.11.2.1

+  - /System/Library/PrivateFrameworks/CallIntelligence.framework/CallIntelligence

+  - /System/Library/PrivateFrameworks/CallsUtilities.framework/CallsUtilities

-  Functions: 16817
-  Symbols:   3471
-  CStrings:  14727
+  Functions: 16830
+  Symbols:   3488
+  CStrings:  14747
Symbols:
+ _$s14CallsUtilities11ABCReporterC6domain4typeACSS_SStcfc
+ _$s14CallsUtilities11ABCReporterC6report4with8durationSDys11AnyHashableVypGAI_SdtYaF
+ _$s14CallsUtilities11ABCReporterC6report4with8durationSDys11AnyHashableVypGAI_SdtYaFTu
+ _$s14CallsUtilities11ABCReporterC9signature7subType7context7processSDys11AnyHashableVypGSgSS_S2StF
+ _$s14CallsUtilities11ABCReporterCMa
+ _$s16CallIntelligence0A23ContextCardsBiomeStreamC14EngagementTypeO02noG0yA2EmFWC
+ _$s16CallIntelligence0A23ContextCardsBiomeStreamC14EngagementTypeO10viewSourceyA2EmFWC
+ _$s16CallIntelligence0A23ContextCardsBiomeStreamC14EngagementTypeO15readAloudPausedyA2EmFWC
+ _$s16CallIntelligence0A23ContextCardsBiomeStreamC14EngagementTypeO16readAloudStartedyA2EmFWC
+ _$s16CallIntelligence0A23ContextCardsBiomeStreamC14EngagementTypeO28viewSourceAndReadAloudPausedyA2EmFWC
+ _$s16CallIntelligence0A23ContextCardsBiomeStreamC14EngagementTypeO29viewSourceAndReadAloudStartedyA2EmFWC
+ _$s16CallIntelligence0A23ContextCardsBiomeStreamC14EngagementTypeOMa
+ _$s16CallIntelligence0A23ContextCardsBiomeStreamC16submitShownEvent9cardTitle14engagementTypeySSSg_AC010EngagementM0OtFTj
+ _$s16CallIntelligence0A23ContextCardsBiomeStreamC6sharedACvgZ
+ _$s16CallIntelligence0A23ContextCardsBiomeStreamCMa
+ _$s16CommunicationsUI15ContextCardViewV8cardData18confirmationLayout12readProvider02onE18ConfirmationNumberAC18TelephonyUtilities06TUCallcD0V_AC0mnI0OyycSS_ySayAC14ReadTimingInfoVGcyycys5Error_pSg_SdSgtctcSgyycSgtcfC
+ _$s20CommunicationsUICore11TTSSpellOutC34spellConfirmationNumberAloudOnCall_6locale22didGenerateWordTimings0L13StartSpeaking0l4StopQ0ySS_10Foundation6LocaleVySayAC05SpelldN10TimingInfoVGcyycys5Error_pSg_SdSgtctFTj
+ _$s20CommunicationsUICore18FTMenuItemRegistryC8register4with8micModes16punchOutProvider13callRecording8deskView6routes12liveCaptions0R11Translation11screenShare9sharePlay10splitCalls22conferenceParticipantsySS_AA0cdL0_pSgA9RSayAaQ_pGSgtF
+ _TUBundleIdentifierContactsApplication
+ _TUCanShowContextCards
- _$s16CommunicationsUI15ContextCardViewV8cardData18confirmationLayout12readProvider02onE18ConfirmationNumberAC18TelephonyUtilities06TUCallcD0V_AC0mnI0OyycSS_ySayAC14ReadTimingInfoVGcySicys5Error_pSgctcSgyycSgtcfC
- _$s20CommunicationsUICore11TTSSpellOutC34spellConfirmationNumberAloudOnCall_6locale22didGenerateWordTimings0L13StartSpeaking0l4StopQ0ySS_10Foundation6LocaleVySayAC05SpelldN10TimingInfoVGcySicys5Error_pSgctFTj
- _$s20CommunicationsUICore18FTMenuItemRegistryC8register4with16punchOutProvider13callRecording8deskView6routes12liveCaptions0P11Translation11screenShare9sharePlay10splitCalls22conferenceParticipantsySS_AA0cdJ0_pSgA8QSayAaP_pGSgtF
CStrings:
+ "%{public}@: pictureInPictureProxyViewFrameForTransitionAnimation returning (%f, %f, %f, %f), sourceProvider=%p"
+ "%{public}@: wrapperViewControllerPreferredContentSize from provider: (%f, %f)"
+ "%{public}@: wrapperViewControllerPreferredContentSize: sourceProvider is nil, using fallback"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/PhoneFaceTime_InCallService/MobilePhone/InCallService/ScreenSharingButtonViewModel.swift"
+ "ReadAloud Failure: "
+ "Source Clicked Failure: "
+ "T@\"UIStackView\",&,V_statusLineStack"
+ "Td,R,N"
+ "_shouldTrustDialRequestOrigin:"
+ "_statusLineStack"
+ "didSubmitBiomeEvent"
+ "dismissFailureAlertIfNeeded: No longer need to show failure alert(s) since we have an active call"
+ "dismissFailureAlertIfNeeded: activeCall=%@, hasFailureAlert=%d, hasCallFailure=%d, failureAlertController=%@"
+ "frameForTransitionAnimation: provider returned zero frame, using cached frame (%f, %f, %f, %f)"
+ "frameForTransitionAnimation: returning cached frame"
+ "frameForTransitionAnimation: returning fallback wrapper view frame"
+ "frameForTransitionAnimation: returning zero frame"
+ "frameForTransitionAnimation: sourceProvider is nil, using cached frame (%f, %f, %f, %f)"
+ "pipContentCornerRadius"
+ "setModalInPresentation:"
+ "setPipContentCornerRadius:"
+ "setStatusLineStack:"
+ "statusLineStack"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobilePhone/InCallService/ScreenSharingButtonViewModel.swift"
- "No longer need to show failure alert since we have an active call"
- "_shouldTrustDialRequestFromDialer:"
```
