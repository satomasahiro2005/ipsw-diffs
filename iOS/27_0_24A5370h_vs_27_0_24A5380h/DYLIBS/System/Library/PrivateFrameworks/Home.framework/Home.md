## Home

> `/System/Library/PrivateFrameworks/Home.framework/Home`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bf4ec` | `0x3c268c` | **`+0x31a0`** |
| `__TEXT.__oslogstring` | `0x1d704` | `0x1d855` | **`+0x151`** |
| `__AUTH_CONST.__const` | `0xf368` | `0xf4a0` | **`+0x138`** |
| `__TEXT.__cstring` | `0x34abd` | `0x34be3` | **`+0x126`** |
| `__AUTH_CONST.__cfstring` | `0x272e0` | `0x273e0` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0x73e0` | `0x74d8` | **`+0xf8`** |
| `__TEXT.__swift5_typeref` | `0x2bd7` | `0x2c53` | **`+0x7c`** |
| `__TEXT.__unwind_info` | `0xea50` | `0xeac0` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x2c974` | `0x2c9d4` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x11230` | `0x11288` | **`+0x58`** |
| `__DATA_DIRTY.__data` | `0xea0` | `0xef0` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x1074` | `0x10b0` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x2208` | `0x2240` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x4c420` | `0x4c458` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x12ff8` | `0x13030` | **`+0x38`** |
| `__DATA.__data` | `0x76a8` | `0x76c8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x3228` | `0x3248` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x2370` | `0x2358` | **`-0x18`** |
| `__DATA.__bss` | `0x3c50` | `0x3c60` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1120` | `0x112c` | **`+0xc`** |
| `__AUTH.__objc_data` | `0xa4b8` | `0xa4c0` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-1227.0.0.0.1
+1232.3.0.0.0

-  Functions: 21213
-  Symbols:   30271
-  CStrings:  8525
+  Functions: 21250
+  Symbols:   30296
+  CStrings:  8539
Symbols:
+ +[HFSetupPairingControllerUtilities didSkipDetectedForRecentNFC]
+ +[HFSetupPairingControllerUtilities recordSkippedDetectedForRecentNFC]
+ -[HFAccessoryItem _isMultiOutletAccessory]
+ -[HFAccessoryItem _multiOutletAccessoryTileDescription]
+ -[HMAccessory(HFAdditions) hf_isAwaitingPostPairingSetup]
+ GCC_except_table157
+ GCC_except_table158
+ _HFAccessorySetupOnboardingAccessoryIdentifierKey
+ _HFAccessorySetupOnboardingDidCompleteNotification
+ _HFAccessorySetupOnboardingHomeIdentifierKey
+ _HFForceNativeMatter
+ ___42-[HFAccessoryItem _isMultiOutletAccessory]_block_invoke
+ ___42-[HFAccessoryLikeItemProvider reloadItems]_block_invoke_6
+ ___42-[HFAccessoryLikeItemProvider reloadItems]_block_invoke_7
+ ___45+[HFUserNotificationServiceTopic na_identity]_block_invoke_6
+ ___55-[HFUnreachableStatusItem _subclass_updateWithOptions:]_block_invoke_10
+ ___58-[HFFirmwareUpdateStatusItem _subclass_updateWithOptions:]_block_invoke_2
+ ___block_descriptor_32_e36_B16?0"<HFAccessoryRepresentable>"8l
+ ___block_descriptor_32_e50_"NSString"16?0"HFUserNotificationServiceTopic"8l
+ ___swift_closure_destructor.18Tm
+ _detectedCardSkippedForRecentNFC
+ _swift_retain_x13
+ _symbolic Say_____G So17OS_dispatch_queueC8DispatchE10AttributesV
+ _symbolic Say_____G s6UInt16V
+ _symbolic So14CHHapticEngineCSgXw
+ _symbolic So14CHHapticEngineCSgXwz_Xx
+ _symbolic So17OS_dispatch_queueC
+ _symbolic _____ 8Dispatch0A4TimeV
+ _symbolic _____y_____G s11_SetStorageC 13HomeDataModel14StaticEndpointV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s6UInt16V
- GCC_except_table145
- GCC_except_table146
- _get_type_metadata 15Synchronization5MutexVySDy10Foundation4UUIDVSo22HFCameraRecordingEvent_pGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "@\"NSString\"16@?0@\"HFUserNotificationServiceTopic\"8"
+ "Failed to pre-warm haptic engine: %@"
+ "HFAccessorySetupOnboardingAccessoryIdentifierKey"
+ "HFAccessorySetupOnboardingDidCompleteNotification"
+ "HFAccessorySetupOnboardingHomeIdentifierKey"
+ "Haptic engine stopped (reason %ld); will restart on next play"
+ "Haptic pattern '%s' playback started, %llums after request"
+ "MatterAccessoryLikeItemProvider: Failed to get static accessory for tilePath %{public}s"
+ "NSDoubleLocalizedStrings"
+ "NSForceRightToLeftLocalizedStrings"
+ "Pre-warming haptic engine"
+ "ResumeWelcome"
+ "Room Selection"
+ "SelectRoom"
+ "Suppressing NFCPairingTapDetected scan haptic (skip-Detected path; launch tap already played it)"
+ "com.apple.Home.HapticFeedbackProvider"
- "%s Failed to get static accessory for tilePath %{public}s"
- "Home/MatterAccessoryLikeItemProvider.swift"
```
