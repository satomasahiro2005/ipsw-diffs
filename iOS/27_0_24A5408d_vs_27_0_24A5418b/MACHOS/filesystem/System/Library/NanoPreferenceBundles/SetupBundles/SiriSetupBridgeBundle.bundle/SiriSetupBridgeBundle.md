## SiriSetupBridgeBundle

> `/System/Library/NanoPreferenceBundles/SetupBundles/SiriSetupBridgeBundle.bundle/SiriSetupBridgeBundle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4018` | `0x91ac` | **`+0x5194`** |
| `__TEXT.__cstring` | `0x1b7` | `0x541` | **`+0x38a`** |
| `__TEXT.__auth_stubs` | `0x5e0` | `0x930` | **`+0x350`** |
| `__TEXT.__objc_methname` | `0x6e7` | `0xa1b` | **`+0x334`** |
| `__TEXT.__objc_stubs` | `0x3c0` | `0x5a0` | **`+0x1e0`** |
| `__TEXT.__objc_methlist` | `0x24c` | `0x424` | **`+0x1d8`** |
| `__DATA_CONST.__const` | `0x260` | `0x430` | **`+0x1d0`** |
| `__DATA.__objc_data` | `0x258` | `0x410` | **`+0x1b8`** |
| `__DATA_CONST.__auth_got` | `0x2f8` | `0x4a0` | **`+0x1a8`** |
| `__TEXT.__oslogstring` | `0x41d` | `0x5c3` | **`+0x1a6`** |
| `__DATA.__objc_const` | `0x340` | `0x488` | **`+0x148`** |
| `__DATA.__bss` | `0x190` | `0x68` | **`-0x128`** |
| `__TEXT.__unwind_info` | `0x168` | `0x290` | **`+0x128`** |
| `__TEXT.__constg_swiftt` | `0x120` | `0x244` | **`+0x124`** |
| `__DATA.__objc_selrefs` | `0x200` | `0x310` | **`+0x110`** |
| `__DATA.__data` | `0x1c0` | `0x288` | **`+0xc8`** |
| `__TEXT.__swift5_capture` | `0x10` | `0xc0` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x108` | `0x199` | **`+0x91`** |
| `__DATA_CONST.__got` | `0xa8` | `0x120` | **`+0x78`** |
| `__TEXT.__objc_methtype` | `0x1ea` | `0x24c` | **`+0x62`** |
| `__TEXT.__objc_classname` | `0xd8` | `0x12c` | **`+0x54`** |
| `__TEXT.__swift5_reflstr` | `0x72` | `0xa7` | **`+0x35`** |
| `__TEXT.__swift5_fieldmd` | `0x6c` | `0xa0` | **`+0x34`** |
| `__DATA_CONST.__auth_ptr` | `0x80` | `0x60` | **`-0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x30` | `0x40` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xc` | `—` | **`-0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xc` | `0x10` | **`+0x4`** |
| `__TEXT.__const` | `0x17a` | `0x178` | **`-0x2`** |

### Other Changes

```diff

-1359.7.0.0.0
+1359.9.0.0.0

-  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 87
-  Symbols:   118
-  CStrings:  133
+  Functions: 190
+  Symbols:   151
+  CStrings:  202
Symbols:
+ _BPSPairingFlowIsTinkerPairing
+ _OBJC_CLASS_$_AFSettingsConnection
+ _OBJC_CLASS_$_BPSVideoControllingBuilder
+ _OBJC_CLASS_$_BPSWelcomeOptinViewController
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _OBJC_CLASS_$_SiriSetupWatchIntroViewController
+ _OBJC_METACLASS_$_BPSWelcomeOptinViewController
+ _OBJC_METACLASS_$_SiriSetupWatchIntroViewController
+ _objc_release_x26
+ _objc_release_x27
+ _objc_release_x28
+ _objc_retain_x22
+ _objc_retain_x23
+ _objc_retain_x24
+ _objc_retain_x27
+ _objc_retain_x4
+ _objc_retain_x8
+ _swift_endAccess
+ _swift_getObjCClassFromMetadata
+ _swift_getObjCClassMetadata
+ _swift_getSingletonMetadata
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_release_n
+ _swift_release_x21
+ _swift_release_x22
+ _swift_release_x26
+ _swift_release_x8
+ _swift_retain
+ _swift_retain_x19
+ _swift_retain_x21
+ _swift_retain_x22
+ _swift_retain_x23
+ _swift_retain_x25
+ _swift_retain_x26
+ _swift_retain_x27
+ _swift_retain_x28
+ _swift_updateClassMetadata2
- _objc_retain_x21
- _objc_retain_x26
- _swift_release_x24
- _swift_retain_x24
CStrings:
+ "@48@0:8@16@24@32q40"
+ "AFSettingsConnection unavailable; SiriSetup will resolve siriSharedUserId async"
+ "Ask about the world, find info from your apps, get answers on the go, and pick up where you left off in the new Siri app."
+ "BPSBuddyControllerHolding"
+ "Building AssistantConfiguration: siriEnabled=%{bool}d, language=%s"
+ "DeviceAssets/Screen-Siri-v3"
+ "DeviceAssets/Screen-Video-Siri"
+ "Don’t Use Siri"
+ "Learn More About Siri"
+ "More conversational, more capable, and deeply personal."
+ "Owner siriSharedUserId lookup failed: %s; SiriSetup will resolve it async"
+ "Owner siriSharedUserId lookup timed out; SiriSetup will resolve it async"
+ "SIRI_WATCH_INTRO_BETA_BADGE"
+ "SIRI_WATCH_INTRO_CONTINUE"
+ "SIRI_WATCH_INTRO_DETAIL"
+ "SIRI_WATCH_INTRO_DETAIL_AI"
+ "SIRI_WATCH_INTRO_DETAIL_AI_BODY"
+ "SIRI_WATCH_INTRO_DONT_USE_SIRI"
+ "SIRI_WATCH_INTRO_LEARN_MORE"
+ "SIRI_WATCH_INTRO_SET_UP_LATER"
+ "SIRI_WATCH_INTRO_TITLE"
+ "SIRI_WATCH_INTRO_TITLE_AI"
+ "SIRI_WATCH_INTRO_USE_SIRI"
+ "SIRI_WATCH_INTRO_USE_SIRI_AI"
+ "Setup already completed; ignoring duplicate completion"
+ "Siri helps you get things done just by asking. Send a message, start a workout, get directions, set a timer, and more."
+ "Siri with Apple Intelligence"
+ "SiriSetupBridgeBundle.SiriSetupWatchIntroViewController"
+ "SiriSetupBridgeBundle/SiriSetupWatchIntroViewController.swift"
+ "SiriSetupWatchIntroViewController"
+ "Skipping SiriSetup - Tinker/Family Setup pairing (legacy VTUI handles it)"
+ "Skipping watch Siri intro - Tinker/Family Setup pairing"
+ "TQ,N,R"
+ "alternateButtonPressed:"
+ "alternateButtonTitle"
+ "assistantIsEnabled"
+ "blackColor"
+ "buddyControllerReleaseHold:"
+ "buddyControllerReleaseHoldAndSkip:"
+ "com.apple.onboarding.siri"
+ "contentLayout"
+ "d16@0:8"
+ "detailString"
+ "didEstablishHold"
+ "didPushWaitScreen"
+ "getSharedUserID:"
+ "headerView"
+ "holdBeforeDisplaying"
+ "holdWithWaitScreen"
+ "imageResource"
+ "init(title:detailText:icon:contentLayout:)"
+ "init(title:detailText:symbolName:contentLayout:)"
+ "initWithTitle:detailText:icon:contentLayout:"
+ "initWithTitle:detailText:symbolName:contentLayout:"
+ "isViewLoaded"
+ "learnMoreButtonTitle"
+ "localizedWaitScreenDescription"
+ "miniFlowStepComplete (Not Now / skip); completing with committed Siri state"
+ "okayButtonPressed:"
+ "okayButtonTitle"
+ "plan"
+ "preStageSiriEnabled"
+ "preparedConfiguration"
+ "preparedPlan"
+ "privacyBundles"
+ "setBackgroundColor:"
+ "setBadgeText:"
+ "setStyle:"
+ "siri_funnel event=stage_completed status=%s siriEnabled=%{bool}d voiceTrainingEligible=%{bool}d"
+ "siri_funnel event=stage_shown voiceTrainingEligible=%{bool}d siriSharedUserIdResolved=%{bool}d"
+ "siri_funnel event=stage_skipped_empty siriEnabled=%{bool}d voiceTrainingEligible=%{bool}d"
+ "suggestedButtonPressed:"
+ "suggestedButtonTitle"
+ "synchronize"
+ "titleString"
+ "v32@?0@\"NSString\"8@\"NSString\"16@\"NSError\"24"
+ "v8@?0"
+ "videoController"
+ "videoControllerWithFileName:fileExtension:bundle:autoPlay:startDelay:shouldLoop:volume:"
+ "waitScreenPushGracePeriod"
+ "watch Siri intro controllerNeedsToRun: %{bool}d (disposition raw=%ld)"
+ "watch Siri intro: Continue (inherit)"
+ "watch Siri intro: Don’t Use Siri"
+ "watch Siri intro: Use Siri"
+ "watch Siri intro: skipped (inherit, no panes follow) — pass through"
+ "watchSupportsAlwaysListeningHeySiri"
- "Bridge"
- "Creating AssistantConfiguration with siriEnabled: %{bool}d, siriLanguage: %s"
- "Creating SiriSetupStageViewController with enrollmentMode: .watchApp, ignoreFiltering: true"
- "Enabled voice trigger upon profile sync for language: %s"
- "Flow already finished; ignoring duplicate buddyControllerDone"
- "Setting AFPreferences.assistantIsEnabled = true for SiriSetup"
- "SiriSetup completed with status: %s"
- "SiriSetupBridgeBundle.SiriSetupWrapper"
- "SiriSetupBridgeBundle/SiriSetupBridgeBuddyController.swift"
- "SiriVoiceTraining"
- "SiriVoiceTraining feature is disabled via feature flag"
- "Skip voice training"
- "Skipping SiriSetup - no iCloud account available for voice profile sync"
- "Skipping SiriSetup - user did not opt in to Siri during pairing"
- "Voice-training step complete (Not Now); advancing to next setup topic"
- "init(nibName:bundle:)"
- "setupFlowUserInfo[SiriOptedIn] = %{bool}d"
```
