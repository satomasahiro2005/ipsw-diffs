## MediaControls

> `/System/Library/PrivateFrameworks/MediaControls.framework/MediaControls`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20a0d4` | `0x21fbec` | **`+0x15b18`** |
| `__AUTH_CONST.__objc_const` | `0x42de0` | `0x439e0` | **`+0xc00`** |
| `__AUTH_CONST.__const` | `0x9f00` | `0xa7f0` | **`+0x8f0`** |
| `__AUTH.__objc_data` | `0x30c0` | `0x3828` | **`+0x768`** |
| `__DATA.__bss` | `0x8348` | `0x8898` | **`+0x550`** |
| `__TEXT.__constg_swiftt` | `0x722c` | `0x7740` | **`+0x514`** |
| `__TEXT.__unwind_info` | `0x8408` | `0x88c8` | **`+0x4c0`** |
| `__TEXT.__const` | `0xb414` | `0xb844` | **`+0x430`** |
| `__TEXT.__objc_methlist` | `0x15784` | `0x15b94` | **`+0x410`** |
| `__TEXT.__cstring` | `0x6be4` | `0x6f44` | **`+0x360`** |
| `__TEXT.__swift5_fieldmd` | `0x47dc` | `0x4b08` | **`+0x32c`** |
| `__TEXT.__swift5_reflstr` | `0x4783` | `0x4a03` | **`+0x280`** |
| `__DATA.__common` | `0x4d8` | `0x720` | **`+0x248`** |
| `__TEXT.__swift5_capture` | `0x11c0` | `0x13d8` | **`+0x218`** |
| `__DATA_CONST.__objc_selrefs` | `0xa518` | `0xa6d8` | **`+0x1c0`** |
| `__DATA.__data` | `0x3f88` | `0x4128` | **`+0x1a0`** |
| `__TEXT.__swift5_typeref` | `0x3280` | `0x3398` | **`+0x118`** |
| `__AUTH.__data` | `0x1158` | `0x1238` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x86b9` | `0x8799` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x3000` | `0x30a8` | **`+0xa8`** |
| `__AUTH_CONST.__auth_got` | `0x1f88` | `0x2010` | **`+0x88`** |
| `__TEXT.__gcc_except_tab` | `0x1518` | `0x1598` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x18a8` | `0x1900` | **`+0x58`** |
| `__TEXT.__swift5_builtin` | `0x2e4` | `0x334` | **`+0x50`** |
| `__TEXT.__swift5_types` | `0x5c8` | `0x604` | **`+0x3c`** |
| `__DATA_CONST.__got` | `0x1860` | `0x1898` | **`+0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x990` | `0x9b8` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x5c0` | `0x5e8` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x18b0` | `0x18d0` | **`+0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x7250` | `0x7270` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x330` | `0x348` | **`+0x18`** |
| `__TEXT.__swift5_mpenum` | `0x48` | `0x50` | **`+0x8`** |

### Other Changes

```diff

-4026.110.75.1.0
+4026.100.79.0.0

+  - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth

+  - /System/Library/PrivateFrameworks/AudioAccessoryServices.framework/AudioAccessoryServices

-  Functions: 13879
-  Symbols:   13725
-  CStrings:  1590
+  Functions: 14347
+  Symbols:   13835
+  CStrings:  1625
Symbols:
+ +[MRUStringsProvider accessibilityCollapseOptionsHint]
+ +[MRUStringsProvider accessibilityExpandOptionsHint]
+ +[MRUStringsProvider listeningModeANCErrorMessageB494B]
+ +[MRUStringsProvider listeningModeANCErrorMessageB494]
+ +[MRUStringsProvider listeningModeANCErrorMessageB498]
+ +[MRUStringsProvider listeningModeANCErrorMessageB507]
+ +[MRUStringsProvider listeningModeANCErrorMessageB515]
+ +[MRUStringsProvider listeningModeANCErrorMessageB607]
+ +[MRUStringsProvider listeningModeANCErrorMessage]
+ +[MRUStringsProvider listeningModeAdaptiveErrorMessageB494B]
+ +[MRUStringsProvider listeningModeAdaptiveErrorMessageB494]
+ +[MRUStringsProvider listeningModeAdaptiveErrorMessageB498]
+ +[MRUStringsProvider listeningModeAdaptiveErrorMessageB507]
+ +[MRUStringsProvider listeningModeAdaptiveErrorMessageB515]
+ +[MRUStringsProvider listeningModeAdaptiveErrorMessageB607]
+ +[MRUStringsProvider listeningModeAdaptiveErrorMessage]
+ -[MRUAudioModuleController listeningModeController:didChangePrimaryListeningModeConfigs:listeningMode:autoANCCapability:autoANCStrength:]
+ -[MRUAudioModuleController listeningModeController:didChangeSecondaryListeningModeConfigs:listeningMode:autoANCCapability:autoANCStrength:]
+ -[MRUAudioModuleController updateActiveState]
+ -[MRUHearingServiceController monitoring]
+ -[MRUHearingServiceController setMonitoring:]
+ -[MRUHearingServiceController startMonitoring]
+ -[MRUHearingServiceController stopMonitoring]
+ -[MRUListeningModeController adaptiveMessageErrorForOutputDevice:]
+ -[MRUListeningModeController audioAccessoryDeviceForRoute:]
+ -[MRUListeningModeController createDeviceManager]
+ -[MRUListeningModeController deviceManager]
+ -[MRUListeningModeController listeningModeConfigsForAudioAccessoryDevice:]
+ -[MRUListeningModeController listeningModeConfigsForOutputDevice:allowOffMode:]
+ -[MRUListeningModeController listeningModeForOutputDeviceBluetoothListeningMode:]
+ -[MRUListeningModeController noiseCancellationErrorMessageForOutputDevice:]
+ -[MRUListeningModeController outputDeviceBluetoothListeningModeForListeningMode:]
+ -[MRUListeningModeController primaryAutoANCCapability]
+ -[MRUListeningModeController primaryAutoANCStrength]
+ -[MRUListeningModeController primaryListeningModeConfigs]
+ -[MRUListeningModeController reset]
+ -[MRUListeningModeController secondaryAutoANCCapability]
+ -[MRUListeningModeController secondaryAutoANCStrength]
+ -[MRUListeningModeController secondaryListeningModeConfigs]
+ -[MRUListeningModeController setDeviceManager:]
+ -[MRUListeningModeController setListeningMode:autoANCStrength:forRoute:completion:]
+ -[MRUListeningModeController setPrimaryListeningMode:autoANCStrength:completion:]
+ -[MRUListeningModeController setSecondaryListeningMode:autoANCStrength:completion:]
+ -[MRUListeningModeController startMonitoring]
+ -[MRUListeningModeController stopMonitoring]
+ -[MRUVolumeBackgroundView multiOptionButtons]
+ -[MRUVolumeBackgroundViewController audioModuleController:listeningModeController:didChangePrimaryListeningModeConfigs:listeningMode:autoANCCapability:autoANCStrength:]
+ -[MRUVolumeBackgroundViewController audioModuleController:listeningModeController:didChangeSecondaryListeningModeConfigs:listeningMode:autoANCCapability:autoANCStrength:]
+ -[MRUVolumeBackgroundViewController collapseButton:]
+ -[MRUVolumeBackgroundViewController expandButton:]
+ -[MRUVolumeViewController audioModuleControllerShouldBeActive:]
+ -[MRUVolumeViewController setUserVisibilityStatus:]
+ -[MRUVolumeViewController userVisibilityStatus]
+ _MRUAmbientNowPlayingHorizontalAltLayoutContainerToScrubberSpacing
+ _MRUAmbientNowPlayingHorizontalAltLayoutTransportControlBottomInset
+ _MRUAmbientNowPlayingHorizontalLayoutIntercomponentSpacing
+ _MRUAmbientNowPlayingIntercomponentSpacingForLayoutAxis
+ _MRUAmbientNowPlayingVerticalLayoutIntercomponentSpacing
+ _MRUAmbientNowPlayingViewSizeClassForLayoutAxis
+ _MRUNowPlayingSwipeRestrictInset
+ _OBJC_CLASS_$_AADeviceConfig
+ _OBJC_CLASS_$_AADeviceManager
+ _OBJC_CLASS_$_CBProductInfo
+ _OBJC_CLASS_$_MRUMultiOptionButton
+ _OBJC_CLASS_$_MRUMultiOptionButtonConfiguration
+ _OBJC_CLASS_$__TtCC13MediaControls17MultiOptionButton10OptionView
+ _OBJC_CLASS_$__TtCC13MediaControls17MultiOptionButton13SelectionView
+ _OBJC_CLASS_$__TtCC13MediaControls17MultiOptionButton9RangeView
+ _OBJC_IVAR_$_MRUHearingServiceController._monitoring
+ _OBJC_IVAR_$_MRUListeningModeController._deviceManager
+ _OBJC_IVAR_$_MRUListeningModeController._primaryAutoANCCapability
+ _OBJC_IVAR_$_MRUListeningModeController._primaryAutoANCStrength
+ _OBJC_IVAR_$_MRUListeningModeController._primaryListeningModeConfigs
+ _OBJC_IVAR_$_MRUListeningModeController._secondaryAutoANCCapability
+ _OBJC_IVAR_$_MRUListeningModeController._secondaryAutoANCStrength
+ _OBJC_IVAR_$_MRUListeningModeController._secondaryListeningModeConfigs
+ _OBJC_IVAR_$_MRUVolumeBackgroundView._multiOptionButtons
+ _OBJC_IVAR_$_MRUVolumeViewController._userVisibilityStatus
+ _OBJC_METACLASS_$_MRUMultiOptionButton
+ _OBJC_METACLASS_$_MRUMultiOptionButtonConfiguration
+ _OBJC_METACLASS_$__TtCC13MediaControls17MultiOptionButton10OptionView
+ _OBJC_METACLASS_$__TtCC13MediaControls17MultiOptionButton13SelectionView
+ _OBJC_METACLASS_$__TtCC13MediaControls17MultiOptionButton9RangeView
+ _UIAccessibilityConvertFrameToScreenCoordinates
+ _UIAccessibilityTraitAdjustable
+ _UIAccessibilityTraitToggleButton
+ __CLASS_METHODS_MRUMultiOptionButtonConfiguration
+ __DATA_MRUMultiOptionButton
+ __DATA_MRUMultiOptionButtonConfiguration
+ __DATA__TtCC13MediaControls17MultiOptionButton10OptionView
+ __DATA__TtCC13MediaControls17MultiOptionButton13SelectionView
+ __DATA__TtCC13MediaControls17MultiOptionButton9RangeView
+ __INSTANCE_METHODS_MRUMultiOptionButtonConfiguration
+ __INSTANCE_METHODS__TtCC13MediaControls17MultiOptionButton10OptionView
+ __INSTANCE_METHODS__TtCC13MediaControls17MultiOptionButton13SelectionView
+ __INSTANCE_METHODS__TtCC13MediaControls17MultiOptionButton9RangeView
+ __IVARS_MRUMultiOptionButton
+ __IVARS__TtCC13MediaControls17MultiOptionButton10OptionView
+ __IVARS__TtCC13MediaControls17MultiOptionButton13SelectionView
+ __IVARS__TtCC13MediaControls17MultiOptionButton9RangeView
+ __METACLASS_DATA_MRUMultiOptionButton
+ __METACLASS_DATA_MRUMultiOptionButtonConfiguration
+ __METACLASS_DATA__TtCC13MediaControls17MultiOptionButton10OptionView
+ __METACLASS_DATA__TtCC13MediaControls17MultiOptionButton13SelectionView
+ __METACLASS_DATA__TtCC13MediaControls17MultiOptionButton9RangeView
+ __OBJC_$_INSTANCE_METHODS_MRUMultiOptionButton(MediaControls|MediaControls1|MediaControls2)
+ __OBJC_CLASS_PROTOCOLS_$_MRUMultiOptionButton(MediaControls|MediaControls1|MediaControls2)
+ ___168-[MRUVolumeBackgroundViewController audioModuleController:listeningModeController:didChangePrimaryListeningModeConfigs:listeningMode:autoANCCapability:autoANCStrength:]_block_invoke
+ ___170-[MRUVolumeBackgroundViewController audioModuleController:listeningModeController:didChangeSecondaryListeningModeConfigs:listeningMode:autoANCCapability:autoANCStrength:]_block_invoke
+ ___45-[MRUSpatialAudioController setSelectedMode:]_block_invoke
+ ___49-[MRUListeningModeController createDeviceManager]_block_invoke
+ ___49-[MRUListeningModeController createDeviceManager]_block_invoke_2
+ ___49-[MRUListeningModeController createDeviceManager]_block_invoke_3
+ ___49-[MRUListeningModeController createDeviceManager]_block_invoke_4
+ ___50-[MRUVolumeBackgroundViewController expandButton:]_block_invoke
+ ___59-[MRUListeningModeController audioAccessoryDeviceForRoute:]_block_invoke
+ ___83-[MRUListeningModeController setListeningMode:autoANCStrength:forRoute:completion:]_block_invoke
+ ___block_descriptor_40_e8_32s_e30_B16?0"AudioAccessoryDevice"8ls32l8
+ ___block_descriptor_40_e8_32w_e30_v16?0"AudioAccessoryDevice"8lw32l8
+ ___block_descriptor_80_e8_32s40s48bs56w_e17_v16?0"NSError"8lw56l8s32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56s64bs72w_e17_v16?0"NSError"8ls32l8w72l8s40l8s48l8s56l8s64l8
+ ___swift_closure_destructor.13Tm
+ ___swift_closure_destructor.54Tm
+ ___swift_closure_destructor.61Tm
+ ___swift_memcpy4_1
+ _associated conformance 13MediaControls17MultiOptionButtonC6LayoutV4AxisOSHAASQ
+ _associated conformance 13MediaControls17MultiOptionButtonC9RangeViewC5StateOSHAASQ
+ _symbolic SNy_____G 12CoreGraphics7CGFloatV
+ _symbolic Say_____G 13MediaControls17MultiOptionButtonC0D0V
+ _symbolic Say_____G 13MediaControls17MultiOptionButtonC0D4ViewC
+ _symbolic Si5count_Si13selectedIndext
+ _symbolic So22UITapGestureRecognizerC
+ _symbolic _____ 13MediaControls17MultiOptionButtonC
+ _symbolic _____ 13MediaControls17MultiOptionButtonC0D0V
+ _symbolic _____ 13MediaControls17MultiOptionButtonC0D0V15HapticIntensityO
+ _symbolic _____ 13MediaControls17MultiOptionButtonC0D0V5ValueO
+ _symbolic _____ 13MediaControls17MultiOptionButtonC0D4ViewC
+ _symbolic _____ 13MediaControls17MultiOptionButtonC13SelectionViewC
+ _symbolic _____ 13MediaControls17MultiOptionButtonC6LayoutV
+ _symbolic _____ 13MediaControls17MultiOptionButtonC6LayoutV4AxisO
+ _symbolic _____ 13MediaControls17MultiOptionButtonC9RangeViewC
+ _symbolic _____ 13MediaControls17MultiOptionButtonC9RangeViewC5StateO
+ _symbolic _____ 13MediaControls30MultiOptionButtonConfigurationC
+ _symbolic _____ So15AAListeningModeV
+ _symbolic _____ So17AAAutoANCStrengthV
+ _symbolic _____ So19AAAutoANCCapabilityV
+ _symbolic _____Sg 13MediaControls17MultiOptionButtonC0D0V
+ _symbolic _____Sg So7CGPointV
+ _symbolic _____SgXw 13MediaControls17MultiOptionButtonC
+ _symbolic _____Sg_ABt 13MediaControls17MultiOptionButtonC0D0V
+ _symbolic ___________t 13MediaControls17MultiOptionButtonC0D4ViewC AC0D0V
+ _symbolic _____y_____G s11_SetStorageC 13MediaControls17MultiOptionButtonC0F4ViewC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 13MediaControls17MultiOptionButtonC0G0V
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So15AAListeningModeV
+ _type_layout_string 13MediaControls17MultiOptionButtonC0D0V
+ _type_layout_string 13MediaControls17MultiOptionButtonC6LayoutV
- +[MRUStringsProvider listeningModeErrorMessageB494B]
- +[MRUStringsProvider listeningModeErrorMessageB494]
- +[MRUStringsProvider listeningModeErrorMessageB498]
- +[MRUStringsProvider listeningModeErrorMessageB507]
- +[MRUStringsProvider listeningModeErrorMessageB515]
- +[MRUStringsProvider listeningModeErrorMessageB607]
- +[MRUStringsProvider listeningModeErrorMessage]
- -[MRUAudioModuleController listeningModeController:didChangeAvailablePrimaryListeningMode:]
- -[MRUAudioModuleController listeningModeController:didChangeAvailableSecondaryListeningModes:]
- -[MRUAudioModuleController listeningModeController:didChangePrimaryListeningMode:]
- -[MRUAudioModuleController listeningModeController:didChangeSecondaryListeningMode:]
- -[MRUListeningModeController availablePrimaryListeningModes]
- -[MRUListeningModeController availableSecondaryListeningModes]
- -[MRUListeningModeController listeningModeErrorMessageForOutputDevice:]
- -[MRUListeningModeController setPrimaryListeningMode:completion:]
- -[MRUListeningModeController setSecondaryListeningMode:completion:]
- -[MRUListeningModeController sortedListeningModes:excludeModes:]
- -[MRUVolumeBackgroundViewController audioModuleController:listeningModeController:didChangeAvailablePrimaryListeningMode:]
- -[MRUVolumeBackgroundViewController audioModuleController:listeningModeController:didChangeAvailableSecondaryListeningModes:]
- -[MRUVolumeBackgroundViewController audioModuleController:listeningModeController:didChangePrimaryListeningMode:]
- -[MRUVolumeBackgroundViewController audioModuleController:listeningModeController:didChangeSecondaryListeningMode:]
- -[MRUVolumeBackgroundViewController didTapPrimaryListeningModeButton:]
- -[MRUVolumeBackgroundViewController didTapSecondaryListeningModeButton:]
- -[MRUVolumeBackgroundViewController didTapSpatialAudioModeButton:]
- _MRUAmbientNowPlayingIntercomponentSpacing
- _MRUEdgeInsetsForAxis
- _MRUUserInterfaceSizeClasseForAxis
- _OBJC_IVAR_$_MRUListeningModeController._availablePrimaryListeningModes
- _OBJC_IVAR_$_MRUListeningModeController._availableSecondaryListeningModes
- ___113-[MRUVolumeBackgroundViewController audioModuleController:listeningModeController:didChangePrimaryListeningMode:]_block_invoke
- ___115-[MRUVolumeBackgroundViewController audioModuleController:listeningModeController:didChangeSecondaryListeningMode:]_block_invoke
- ___122-[MRUVolumeBackgroundViewController audioModuleController:listeningModeController:didChangeAvailablePrimaryListeningMode:]_block_invoke
- ___125-[MRUVolumeBackgroundViewController audioModuleController:listeningModeController:didChangeAvailableSecondaryListeningModes:]_block_invoke
- ___65-[MRUListeningModeController setPrimaryListeningMode:completion:]_block_invoke
- ___66-[MRUVolumeBackgroundViewController didTapSpatialAudioModeButton:]_block_invoke
- ___67-[MRUListeningModeController setSecondaryListeningMode:completion:]_block_invoke
- ___70-[MRUVolumeBackgroundViewController didTapPrimaryListeningModeButton:]_block_invoke
- ___72-[MRUVolumeBackgroundViewController didTapSecondaryListeningModeButton:]_block_invoke
- ___74-[MRUVolumeBackgroundViewController spatialAudioModeButtonDidChangeValue:]_block_invoke
- ___78-[MRUVolumeBackgroundViewController primaryListeningModeButtonDidChangeValue:]_block_invoke
- ___79-[MRUVolumeBackgroundViewController conversationAwarenessButtonDidChangeValue:]_block_invoke
- ___80-[MRUVolumeBackgroundViewController secondaryListeningModeButtonDidChangeValue:]_block_invoke
- ___block_descriptor_40_e8_32bs_e21_v20?0B8"NSString"12ls32l8
- ___block_descriptor_40_e8_32s_e18_v16?0"NSString"8ls32l8
- ___block_descriptor_48_e8_32s40s_e21_v20?0B8"NSString"12ls32l8s40l8
- ___block_descriptor_80_e8_32s40s48s56s64s72bs_e17_v16?0"NSError"8ls32l8s40l8s48l8s56l8s64l8s72l8
CStrings:
+ "%{public}@ Device manager activated"
+ "%{public}@ Failed to activate device manager: %{public}@"
+ "%{public}@ set bluetooth listening mode, completed: %{public}@ | previous: %{public}@ | device: %{public}@ | error: %@"
+ "%{public}@ set bluetooth listening mode: %{public}@ | previous: %{public}@ | device: %{public}@"
+ "%{public}@ set listening mode failed: %{public}@ | output device: %{public}@"
+ "%{public}@ set listening mode: %{public}s | previous: %{public}s | strength: %{public}s | previous: %{public}s | error: %{public}@ | device: %{public}@"
+ "%{public}@ update primary listening mode cofigs: %@ | selected: %{public}s | capability: %{public}s | strength: %{public}s | device: %{public}@"
+ "%{public}@ update secondary listening mode cofigs: %@ | selected: %{public}s | capability: %{public}s | strength: %{public}s | off allowed: %{BOOL}u | device: %{public}@"
+ "A!"
+ "ACCESSIBILITY_COLLAPSE_OPTIONS_HINT"
+ "ACCESSIBILITY_EXPAND_OPTIONS_HINT"
+ "ANC"
+ "AutoANC"
+ "B16@?0@\"AudioAccessoryDevice\"8"
+ "Disabled"
+ "High"
+ "LISTENING_MODE_ADAPTIVE_REQUIRES_BOTH_BUDS_IN_EAR"
+ "LISTENING_MODE_ADAPTIVE_REQUIRES_BOTH_BUDS_IN_EAR_B494"
+ "LISTENING_MODE_ADAPTIVE_REQUIRES_BOTH_BUDS_IN_EAR_B494b"
+ "LISTENING_MODE_ADAPTIVE_REQUIRES_BOTH_BUDS_IN_EAR_B498"
+ "LISTENING_MODE_ADAPTIVE_REQUIRES_BOTH_BUDS_IN_EAR_B507"
+ "LISTENING_MODE_ADAPTIVE_REQUIRES_BOTH_BUDS_IN_EAR_B607"
+ "LISTENING_MODE_ADAPTIVE_REQUIRES_ON_HEAD_B515"
+ "LISTENING_MODE_ANC_REQUIRES_BOTH_BUDS_IN_EAR"
+ "LISTENING_MODE_ANC_REQUIRES_BOTH_BUDS_IN_EAR_B494"
+ "LISTENING_MODE_ANC_REQUIRES_BOTH_BUDS_IN_EAR_B494b"
+ "LISTENING_MODE_ANC_REQUIRES_BOTH_BUDS_IN_EAR_B498"
+ "LISTENING_MODE_ANC_REQUIRES_BOTH_BUDS_IN_EAR_B507"
+ "LISTENING_MODE_ANC_REQUIRES_BOTH_BUDS_IN_EAR_B607"
+ "LISTENING_MODE_ANC_REQUIRES_ON_HEAD_B515"
+ "LISTENING_MODE_AUTOMATIC_TITLE"
+ "LISTENING_MODE_NOISE_CANCELLATION_TITLE"
+ "LISTENING_MODE_NOISE_CONTROL_TITLE"
+ "LISTENING_MODE_OFF_TITLE"
+ "LISTENING_MODE_TRANSPARENCY_TITLE"
+ "Low"
+ "MediaControls/MultiOptionButton+OptionView.swift"
+ "MediaControls/MultiOptionButton+RangeView.swift"
+ "MediaControls/MultiOptionButton+SelectionView.swift"
+ "MediaControls/MultiOptionButton.swift"
+ "Normal"
+ "R"
+ "Step1"
+ "Step2"
+ "Step3"
+ "Step4"
+ "Step6"
+ "Step7"
+ "Step8"
+ "Step9"
+ "Transparency"
+ "Version1"
+ "Version2"
+ "Version3"
+ "a"
+ "conversationAwareness.off"
+ "conversationAwareness.on"
+ "person.and.sparkles.fill"
+ "person.closed.fill"
+ "person.open.fill"
+ "person.spatialaudio.fill"
+ "person.spatialaudio.stereo.fill"
+ "spatialAudio.headTracked"
+ "spatialAudio.off"
+ "v16@?0@\"AudioAccessoryDevice\"8"
+ "\xa1"
- "%{public}@ set bluetooth to listening mode completed: %{public}@ | %{public}@ | device: %{public}@ | error: %@"
- "%{public}@ set bluetooth to listening mode: %{public}@ | %{public}@ | device: %{public}@"
- "%{public}@ update available primary bluetooth to listening mode: %{public}@ | %{public}@ | device: %{public}@"
- "%{public}@ update available secondary bluetooth to listening mode: %{public}@ | %{public}@ | device: %{public}@"
- "%{public}@ update primary bluetooth to listening mode: %{public}@ | %{public}@ | device: %{public}@"
- "%{public}@ update secondary bluetooth to listening mode: %{public}@ | %{public}@ | device: %{public}@"
- "1!"
- "B"
- "BLUETOOTH_LISTENING_MODE_AUTOMATIC_TITLE"
- "BLUETOOTH_LISTENING_MODE_NOISE_CANCELLATION_TITLE"
- "BLUETOOTH_LISTENING_MODE_NOISE_CONTROL_TITLE"
- "BLUETOOTH_LISTENING_MODE_OFF_TITLE"
- "BLUETOOTH_LISTENING_MODE_REQUIRES_BOTH_BUDS_IN_EAR"
- "BLUETOOTH_LISTENING_MODE_REQUIRES_BOTH_BUDS_IN_EAR_B494"
- "BLUETOOTH_LISTENING_MODE_REQUIRES_BOTH_BUDS_IN_EAR_B494b"
- "BLUETOOTH_LISTENING_MODE_REQUIRES_BOTH_BUDS_IN_EAR_B498"
- "BLUETOOTH_LISTENING_MODE_REQUIRES_BOTH_BUDS_IN_EAR_B507"
- "BLUETOOTH_LISTENING_MODE_REQUIRES_BOTH_BUDS_IN_EAR_B607"
- "BLUETOOTH_LISTENING_MODE_REQUIRES_ON_HEAD_B515"
- "BLUETOOTH_LISTENING_MODE_TRANSPARENCY_TITLE"
- "SpatialMultichannelHeadTracked"
- "SpatialMultichannelOff"
- "SpatialMultichannelOn"
- "SpatialStereoHeadTracked"
- "SpatialStereoOff"
- "SpatialStereoOn"
- "animating"
- "head-tracked"
- "v16@?0@\"NSString\"8"
- "v20@?0B8@\"NSString\"12"
- "\x91"
```
