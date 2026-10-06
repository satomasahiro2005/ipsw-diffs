## HeadphoneSettingsUI

> `/System/Library/PrivateFrameworks/HeadphoneSettingsUI.framework/HeadphoneSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22681c` | `0x23503c` | **`+0xe820`** |
| `__TEXT.__const` | `0xda94` | `0xe4e4` | **`+0xa50`** |
| `__DATA.__bss` | `0x101b8` | `0x10ae8` | **`+0x930`** |
| `__TEXT.__cstring` | `0xa7de` | `0xb03e` | **`+0x860`** |
| `__AUTH_CONST.__const` | `0x11fd0` | `0x127b0` | **`+0x7e0`** |
| `__TEXT.__oslogstring` | `0x6c5f` | `0x6e0f` | **`+0x1b0`** |
| `__TEXT.__swift5_proto` | `0xb34` | `0xcbc` | **`+0x188`** |
| `__TEXT.__unwind_info` | `0x40b8` | `0x41f8` | **`+0x140`** |
| `__AUTH_CONST.__cfstring` | `0x3200` | `0x32e0` | **`+0xe0`** |
| `__DATA.__data` | `0x3cb0` | `0x3d48` | **`+0x98`** |
| `__TEXT.__swift5_assocty` | `0xda8` | `0xe38` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x5798` | `0x5828` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x4ad8` | `0x4b40` | **`+0x68`** |
| `__TEXT.__swift5_reflstr` | `0x21ab` | `0x220b` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x28e0` | `0x2938` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x231c` | `0x2370` | **`+0x54`** |
| `__AUTH_CONST.__auth_got` | `0x23e8` | `0x2438` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xcf0` | `0xd40` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0xd40e` | `0xd45e` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x36fc` | `0x372c` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x398` | `0x3c0` | **`+0x28`** |
| `__DATA.__common` | `0x5a8` | `0x5c0` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x530` | `0x548` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1080` | `0x1090` | **`+0x10`** |

### Other Changes

```diff

-40.41.1.1.7
+40.41.1.1.10

-  Functions: 9673
-  Symbols:   4147
-  CStrings:  1731
+  Functions: 9902
+  Symbols:   4175
+  CStrings:  1811
Symbols:
+ +[HPSProductUtils isShortScreenDevice]
+ +[HPSProductUtils stringForUIInterfaceOrientation:]
+ -[HPSUISpatialProfileSingeStepEnrollmentController showNonLandscapeLeftAlert]
+ -[HPSUISpatialProfileSingeStepEnrollmentController viewWillTransitionToSize:withTransitionCoordinator:]
+ _MGGetProductType
+ _MGIsDeviceOfType
+ _OBJC_CLASS_$_CBControllerSettings
+ ___103-[HPSUISpatialProfileSingeStepEnrollmentController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
+ ___38+[HPSProductUtils isShortScreenDevice]_block_invoke
+ ___77-[HPSUISpatialProfileSingeStepEnrollmentController showNonLandscapeLeftAlert]_block_invoke
+ ___78-[HPSUISpatialProfileManagementController presentProfileEnrollmentController:]_block_invoke
+ ___block_descriptor_40_e8_32s_e56_v16?0"<UIViewControllerTransitionCoordinatorContext>"8ls32l8
+ _associated conformance 16HeadphoneManager29DefaultFeatureContentInternalC13HearingModeUI0gdE00a8SettingsI0s28CustomDebugStringConvertible
+ _associated conformance 19HeadphoneSettingsUI15InternalFeatureVSHAASQ
+ _associated conformance 19HeadphoneSettingsUI15InternalFeatureVs12IdentifiableAA2IDsADP_SH
+ _associated conformance So13CBDeviceFlagsVs10SetAlgebraSCSQ
+ _associated conformance So13CBDeviceFlagsVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So13CBDeviceFlagsVs9OptionSetSCSY
+ _associated conformance So13CBDeviceFlagsVs9OptionSetSCs0D7Algebra
+ _isShortScreenDevice.onceToken
+ _isShortScreenDevice.sIsShortScreenDevice
+ _os_variant_has_internal_ui
+ _symbolic _____ 19HeadphoneSettingsUI15InternalFeatureV
+ _symbolic _____ So13CBDeviceFlagsV
+ _symbolic _____ So13MGProductTypea
+ _symbolic _____ s6UInt64V
+ _type_layout_string 19HeadphoneSettingsUI15InternalFeatureV
+ _type_layout_string So13CBDeviceFlagsV
+ _type_layout_string So13MGProductTypea
- _type_layout_string So22UIViewAnimationOptionsV
CStrings:
+ "AIRPODS_5"
+ "AIRPODS_5_WIRELESS_CHARGING"
+ "B518"
+ "B518-"
+ "B518-Default"
+ "B518-iOS-Localizable"
+ "B868"
+ "B868-iOS-Localizable"
+ "B868_Left"
+ "B868_Right"
+ "B868_Translate"
+ "B868_case-closed-charged"
+ "Beats 360"
+ "Beats 360 (Testing)"
+ "Configure Livability"
+ "DarkBiasValue-1"
+ "DarkBiasValue-2"
+ "DarkBiasValue-3"
+ "DarkBiasValue-4"
+ "DarkMatrixValue-1"
+ "DarkMatrixValue-2"
+ "DarkMatrixValue-3"
+ "DarkMatrixValue-4"
+ "Development Device"
+ "Dynamic Audio Feedback"
+ "False"
+ "Force Show Fit Test"
+ "HPSProductUtils: isShortScreenDevice -> %s"
+ "HeadphoneSettingsUI/B868FeatureProviding.swift"
+ "HeadphoneSettingsUI/DevelopmentAccessoryFeatureProviding.swift"
+ "HeadphoneSettingsUI/InternalFeature.swift"
+ "HideInternalBTSettings"
+ "InDevelopmentDevice"
+ "Internal"
+ "Internal Feature"
+ "InternalspatialAudioGroupSpecifier"
+ "LISTENING_MODE_PLACE_%@_ADAPTIVE_AUDIO_FOOTER"
+ "LISTENING_MODE_PLACE_%@_NOISE_CANCELLATION_FOOTER"
+ "LandscapeLeft"
+ "LandscapeRight"
+ "LightBiasValue-1"
+ "LightBiasValue-2"
+ "LightBiasValue-3"
+ "LightBiasValue-4"
+ "LightMatrixValue-1"
+ "LightMatrixValue-2"
+ "LightMatrixValue-3"
+ "LightMatrixValue-4"
+ "More details available at "
+ "NON_LANDSCAPE_LEFT_MODE_ALERT_DETAIL"
+ "NON_LANDSCAPE_LEFT_MODE_ALERT_TITLE"
+ "Portrait"
+ "PortraitUpsideDown"
+ "Press And Hold "
+ "Recommended Builds"
+ "Show in Internal App"
+ "Spatial Profile: Enrollment not supported, Tall Screen: %u, Orientation: %@, Show pop up alert"
+ "Spatial Profile: Force hiding Prox Card"
+ "Spatial Profile: Interface Orientation Changed"
+ "Spatial Profile: Non Landscape Left Mode Detected, not supported, show pop up alert"
+ "Spatial Profile: Tall Screen: %u (%f), Orientation: %@"
+ "Spatial Profile: V68: localHardwareSupport was %s, forced to True for V68"
+ "True"
+ "Unrecognized (%ld)"
+ "Use Spatial Audio Profile"
+ "Video Capture Spatial Audio Profile"
+ "VideoCaptureEnabled"
+ "airpods.pro.eartips.sizes"
+ "airpods.pro.right.arrow.trianglehead.down.left"
+ "airpods.pro.right.arrow.trianglehead.up.right"
+ "airpodspro"
+ "beats.headphones"
+ "com.apple.Preferences"
+ "com.apple.bluetoothSettings"
+ "com.apple.hrtfEnrollment"
+ "headphoneInternalApp://headphoneDetail?btAddress="
+ "https://at.apple.com/SIZnRn"
+ "nosign"
+ "prefs:root=INTERNAL_SETTINGS&path=AccessoriesFirmwareUpdate/"
+ "v16@?0@\"<UIViewControllerTransitionCoordinatorContext>\"8"
```
