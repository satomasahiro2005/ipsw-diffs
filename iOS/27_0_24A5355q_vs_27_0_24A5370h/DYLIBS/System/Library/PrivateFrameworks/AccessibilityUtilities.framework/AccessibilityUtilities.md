## AccessibilityUtilities

> `/System/Library/PrivateFrameworks/AccessibilityUtilities.framework/AccessibilityUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fabf4` | `0x1ff6ec` | **`+0x4af8`** |
| `__TEXT.__cstring` | `0x1cf0b` | `0x1d463` | **`+0x558`** |
| `__AUTH_CONST.__cfstring` | `0x12f60` | `0x133c0` | **`+0x460`** |
| `__TEXT.__oslogstring` | `0x6650` | `0x67d6` | **`+0x186`** |
| `__DATA_CONST.__objc_selrefs` | `0x9fe0` | `0xa0a8` | **`+0xc8`** |
| `__TEXT.__objc_methlist` | `0xfa3c` | `0xfb04` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0x9830` | `0x98f0` | **`+0xc0`** |
| `__TEXT.__const` | `0x89c8` | `0x8a78` | **`+0xb0`** |
| `__AUTH_CONST.__const` | `0xa218` | `0xa2b0` | **`+0x98`** |
| `__DATA_CONST.__const` | `0x58f0` | `0x5978` | **`+0x88`** |
| `__AUTH_CONST.__objc_const` | `0x1bc10` | `0x1bc70` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x2a48` | `0x29f8` | **`-0x50`** |
| `__TEXT.__swift5_reflstr` | `0xb4cc` | `0xb50c` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x7958` | `0x7990` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x2b8` | `0x2e8` | **`+0x30`** |
| `__DATA.__data` | `0x5270` | `0x5290` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x16b0` | `0x1698` | **`-0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x43d8` | `0x43f0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2d00` | `0x2d10` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2308` | `0x2318` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x9b0` | `0x9c0` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x3118` | `0x3128` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x29b4` | `0x29c4` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xbbc` | `0xbc8` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x25a2` | `0x25ac` | **`+0xa`** |
| `__DATA_CONST.__objc_classlist` | `0x4c0` | `0x4b8` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x1334` | `0x1338` | **`+0x4`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Functions: 15126
-  Symbols:   10795
-  CStrings:  4309
+  Functions: 15195
+  Symbols:   10825
+  CStrings:  4350
Symbols:
+ +[AXCustomizableMouse _isGameControllerForUsagePairs:]
+ +[AXTripleClickHelpers _toggleSpeakScreenForSceneID:]
+ +[AXTripleClickHelpers toggleSpeakScreenUsingAppAtPoint:]
+ -[AXAirPodSettingsManager _saveDeviceInfoForAddress:productID:]
+ -[AXBackBoardServer presentAccessibilityShortcutChooser]
+ -[AXBuddyDataPackage darkModeActive]
+ -[AXBuddyDataPackage setDarkModeActive:]
+ -[AXControlsSettingsObserver _enqueueKind:]
+ -[AXControlsSettingsObserver _enqueueKindsForNotificationName:]
+ -[AXControlsSettingsObserver _requestCoalescedReload]
+ -[AXControlsSettingsObserver init]
+ -[AXControlsSettingsObserver isObserving]
+ -[AXControlsSettingsObserver notificationToKinds]
+ -[AXControlsSettingsObserver pendingKinds]
+ -[AXControlsSettingsObserver reloadTimer]
+ -[AXControlsSettingsObserver setIsObserving:]
+ -[AXControlsSettingsObserver setNotificationToKinds:]
+ -[AXControlsSettingsObserver setPendingKinds:]
+ -[AXControlsSettingsObserver setReloadTimer:]
+ -[AXCustomizableMouse isGameController]
+ -[AXCustomizableMouse setIsGameController:]
+ -[AXIPCServer _checkEntitlementForMessage:clientPort:auditToken:entitlementCompletion:]
+ -[AXIPCServer _querySecTaskForAuditToken:entitlements:grantedEntitlement:]
+ -[AXSpringBoardServer performArrangementSplitForLeftBundleIdentifier:rightBundleIdentifier:]
+ -[AXVoiceOverAutomationClient _navigateInteract:timeout:error:]
+ GCC_except_table102
+ GCC_except_table1125
+ GCC_except_table119
+ GCC_except_table1226
+ GCC_except_table131
+ GCC_except_table1317
+ GCC_except_table1340
+ GCC_except_table136
+ GCC_except_table1375
+ GCC_except_table1411
+ GCC_except_table1440
+ GCC_except_table150
+ GCC_except_table1503
+ GCC_except_table1527
+ GCC_except_table1531
+ GCC_except_table1533
+ GCC_except_table1536
+ GCC_except_table1542
+ GCC_except_table157
+ GCC_except_table1632
+ GCC_except_table1640
+ GCC_except_table1647
+ GCC_except_table1651
+ GCC_except_table1658
+ GCC_except_table1661
+ GCC_except_table1663
+ GCC_except_table1667
+ GCC_except_table1670
+ GCC_except_table1672
+ GCC_except_table1801
+ GCC_except_table1837
+ GCC_except_table1838
+ GCC_except_table1839
+ GCC_except_table1841
+ GCC_except_table1842
+ GCC_except_table1843
+ GCC_except_table1844
+ GCC_except_table2168
+ GCC_except_table2171
+ GCC_except_table2174
+ GCC_except_table2176
+ GCC_except_table2178
+ GCC_except_table2180
+ GCC_except_table2182
+ GCC_except_table225
+ GCC_except_table2270
+ GCC_except_table2308
+ GCC_except_table2375
+ GCC_except_table2410
+ GCC_except_table2446
+ GCC_except_table2455
+ GCC_except_table2470
+ GCC_except_table249
+ GCC_except_table2493
+ GCC_except_table2627
+ GCC_except_table2686
+ GCC_except_table2707
+ GCC_except_table2861
+ GCC_except_table291
+ GCC_except_table2931
+ GCC_except_table2941
+ GCC_except_table2943
+ GCC_except_table2950
+ GCC_except_table3064
+ GCC_except_table3076
+ GCC_except_table3408
+ GCC_except_table3412
+ GCC_except_table3437
+ GCC_except_table3441
+ GCC_except_table3546
+ GCC_except_table3559
+ GCC_except_table3569
+ GCC_except_table3674
+ GCC_except_table3679
+ GCC_except_table3765
+ GCC_except_table398
+ GCC_except_table4259
+ GCC_except_table4267
+ GCC_except_table4268
+ GCC_except_table4276
+ GCC_except_table4277
+ GCC_except_table4285
+ GCC_except_table4289
+ GCC_except_table4291
+ GCC_except_table4397
+ GCC_except_table4410
+ GCC_except_table4623
+ GCC_except_table4627
+ GCC_except_table4632
+ GCC_except_table4654
+ GCC_except_table4826
+ GCC_except_table4860
+ GCC_except_table4903
+ GCC_except_table4922
+ GCC_except_table648
+ GCC_except_table651
+ GCC_except_table653
+ GCC_except_table682
+ GCC_except_table710
+ GCC_except_table727
+ GCC_except_table796
+ GCC_except_table800
+ GCC_except_table849
+ GCC_except_table912
+ GCC_except_table961
+ GCC_except_table973
+ GCC_except_table977
+ GCC_except_table990
+ _AXAudioChannelNameForPort
+ _CFRunLoopPerformBlock
+ _OBJC_CLASS_$_CBDiscovery
+ _OBJC_IVAR_$_AXBuddyDataPackage._darkModeActive
+ _OBJC_IVAR_$_AXControlsSettingsObserver._isObserving
+ _OBJC_IVAR_$_AXControlsSettingsObserver._notificationToKinds
+ _OBJC_IVAR_$_AXControlsSettingsObserver._pendingKinds
+ _OBJC_IVAR_$_AXControlsSettingsObserver._reloadTimer
+ _OBJC_IVAR_$_AXCustomizableMouse._isGameController
+ __AXVOIsServiceReachable
+ __AXVOLookupServicePort.name
+ __AXVOLookupServicePort.once
+ __AXVOWaitForPhrase
+ ___53-[AXControlsSettingsObserver _requestCoalescedReload]_block_invoke
+ ___54-[AXSpringBoardServer showAlert:withHandler:withData:]_block_invoke_3
+ ___54-[AXSpringBoardServer showAlert:withHandler:withData:]_block_invoke_4
+ ___54-[AXSpringBoardServer showAlert:withHandler:withData:]_block_invoke_5
+ ___55-[AXVoiceOverAutomationClient _navigate:timeout:error:]_block_invoke
+ ___63-[AXVoiceOverAutomationClient _navigateInteract:timeout:error:]_block_invoke
+ ___64-[AXVoiceOverAutomationClient enableVoiceOverWithTimeout:error:]_block_invoke_2
+ ___87-[AXIPCServer _checkEntitlementForMessage:clientPort:auditToken:entitlementCompletion:]_block_invoke
+ ___87-[AXIPCServer _checkEntitlementForMessage:clientPort:auditToken:entitlementCompletion:]_block_invoke_2
+ ___87-[AXIPCServer _checkEntitlementForMessage:clientPort:auditToken:entitlementCompletion:]_block_invoke_3
+ ____AXVOLookupServicePort_block_invoke
+ ____AXVOWaitForPhrase_block_invoke
+ ____AXVOWarmUpVoiceOver_block_invoke
+ ___block_descriptor_112_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_113_e8_32s40s48s56s64s72bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8
+ ___block_descriptor_40_e8_32s_e15_"NSString"8?0ls32l8
+ ___block_descriptor_40_e8_32s_e8_v16?0q8ls32l8
+ ___block_descriptor_48_e8_32s40bs_e5_B8?0ls40l8s32l8
+ ___block_descriptor_56_e8_32s40bs48r_e5_B8?0ls40l8s32l8r48l8
+ ___block_descriptor_56_e8_32s40s48bs_e8_v12?0B8ls48l8s32l8s40l8
+ ___block_descriptor_56_e8_32s40s48w_e24_v32?0"NSValue"8Q16^B24ls32l8w48l8s40l8
+ ___block_descriptor_56_e8_32s40w_e5_v8?0lw40l8s32l8
+ ___swift_closure_destructor.705Tm
+ __checkEntitlementForMessage:clientPort:auditToken:entitlementCompletion:.SecurityCheckQueue
+ __checkEntitlementForMessage:clientPort:auditToken:entitlementCompletion:.onceToken
+ _getSpeakThisServicesClass
+ _kAXSButtonShapesEnabledNotification
+ _keypath_get.452Tm
+ _keypath_get.492Tm
+ _keypath_get.516Tm
+ _keypath_get.616Tm
+ _keypath_set.667Tm
+ _objc_sync_enter
+ _objc_sync_exit
+ _strdup
+ _symbolic _____yypG s23_ContiguousArrayStorageC
- -[AXAirPodSettingsManager _saveDeviceInfoForAddress:productID:bluetoothDevice:]
- -[AXIPCDelayedMessage .cxx_destruct]
- -[AXIPCDelayedMessage completion]
- -[AXIPCDelayedMessage initWithMessage:completion:]
- -[AXIPCDelayedMessage message]
- -[AXIPCDelayedMessage setCompletion:]
- -[AXIPCDelayedMessage setMessage:]
- -[AXIPCServer _clientHasEntitlementWithPort:auditToken:message:completion:]
- -[AXIPCServer _hasEntitlement:entitlements:clientPort:auditToken:message:completion:]
- -[AXIPCServer delayedMessages]
- -[AXIPCServer setDelayedMessages:]
- -[AXVoiceOverAutomationClient _navigateInteract:error:]
- GCC_except_table101
- GCC_except_table1114
- GCC_except_table116
- GCC_except_table1215
- GCC_except_table128
- GCC_except_table130
- GCC_except_table1306
- GCC_except_table1329
- GCC_except_table1364
- GCC_except_table1400
- GCC_except_table1429
- GCC_except_table147
- GCC_except_table1493
- GCC_except_table1502
- GCC_except_table1526
- GCC_except_table1530
- GCC_except_table1532
- GCC_except_table1535
- GCC_except_table154
- GCC_except_table1541
- GCC_except_table1631
- GCC_except_table1639
- GCC_except_table1646
- GCC_except_table1650
- GCC_except_table1657
- GCC_except_table1660
- GCC_except_table1662
- GCC_except_table1666
- GCC_except_table1669
- GCC_except_table1671
- GCC_except_table1820
- GCC_except_table2143
- GCC_except_table2146
- GCC_except_table2149
- GCC_except_table2151
- GCC_except_table2153
- GCC_except_table2155
- GCC_except_table2157
- GCC_except_table222
- GCC_except_table2244
- GCC_except_table2282
- GCC_except_table2349
- GCC_except_table2358
- GCC_except_table2420
- GCC_except_table2429
- GCC_except_table2444
- GCC_except_table246
- GCC_except_table2473
- GCC_except_table2607
- GCC_except_table2666
- GCC_except_table2687
- GCC_except_table2841
- GCC_except_table286
- GCC_except_table2911
- GCC_except_table2921
- GCC_except_table2923
- GCC_except_table2930
- GCC_except_table3044
- GCC_except_table3056
- GCC_except_table3388
- GCC_except_table3392
- GCC_except_table3417
- GCC_except_table3421
- GCC_except_table3526
- GCC_except_table3539
- GCC_except_table3549
- GCC_except_table3654
- GCC_except_table3659
- GCC_except_table3745
- GCC_except_table392
- GCC_except_table4239
- GCC_except_table4247
- GCC_except_table4248
- GCC_except_table4256
- GCC_except_table4257
- GCC_except_table4265
- GCC_except_table4269
- GCC_except_table4271
- GCC_except_table4377
- GCC_except_table4390
- GCC_except_table4603
- GCC_except_table4607
- GCC_except_table4612
- GCC_except_table4634
- GCC_except_table4804
- GCC_except_table4838
- GCC_except_table4881
- GCC_except_table4900
- GCC_except_table636
- GCC_except_table639
- GCC_except_table672
- GCC_except_table700
- GCC_except_table717
- GCC_except_table780
- GCC_except_table786
- GCC_except_table839
- GCC_except_table902
- GCC_except_table951
- GCC_except_table963
- GCC_except_table967
- GCC_except_table980
- _AXDeviceProcessLAStorageError
- _AXDeviceSetAssistantWhileFaceDownEnabled
- _AXDeviceSetKShotPreboardEnabled
- _AXDeviceSetLAStorageKey
- _CFRunLoopSourceCreate
- _CFRunLoopSourceSignal
- _OBJC_CLASS_$_AXIPCDelayedMessage
- _OBJC_IVAR_$_AXIPCDelayedMessage._completion
- _OBJC_IVAR_$_AXIPCDelayedMessage._message
- _OBJC_IVAR_$_AXIPCServer._delayedMessages
- _OBJC_METACLASS_$_AXIPCDelayedMessage
- __OBJC_$_INSTANCE_METHODS_AXIPCDelayedMessage
- __OBJC_$_INSTANCE_VARIABLES_AXIPCDelayedMessage
- __OBJC_$_PROP_LIST_AXIPCDelayedMessage
- __OBJC_CLASS_RO_$_AXIPCDelayedMessage
- __OBJC_METACLASS_RO_$_AXIPCDelayedMessage
- ___75-[AXIPCServer _clientHasEntitlementWithPort:auditToken:message:completion:]_block_invoke
- ___85-[AXIPCServer _handleIncomingMessage:securityToken:auditToken:clientPort:completion:]_block_invoke_2
- ___85-[AXIPCServer _hasEntitlement:entitlements:clientPort:auditToken:message:completion:]_block_invoke
- ___85-[AXIPCServer _hasEntitlement:entitlements:clientPort:auditToken:message:completion:]_block_invoke_2
- ___AXDeviceProcessLAStorageError_block_invoke
- ___AXDeviceSetLAStorageKey_block_invoke
- ___block_descriptor_40_e8_32bs_e17_v16?0"NSError"8ls32l8
- ___block_descriptor_40_e8_32s_e36_B32?0"AXIPCDelayedMessage"8Q16^B24ls32l8
- ___block_descriptor_48_e8_32s40s_e8_B12?0B8ls32l8s40l8
- ___block_descriptor_48_e8_32w_e5_v8?0lw32l8
- ___block_descriptor_72_e8_32s40bs48r56r_e5_v8?0lr48l8s40l8s32l8r56l8
- ___block_descriptor_72_e8_32s_e18_B16?0"NSString"8ls32l8
- ___swift_closure_destructor.699Tm
- __hasEntitlement:entitlements:clientPort:auditToken:message:completion:.SecurityCheckQueue
- __hasEntitlement:entitlements:clientPort:auditToken:message:completion:.SourceRef
- __hasEntitlement:entitlements:clientPort:auditToken:message:completion:.onceToken
- __passiveEventHandler
- _keypath_get.446Tm
- _keypath_get.486Tm
- _keypath_get.510Tm
- _keypath_get.610Tm
- _keypath_set.661Tm
- _malloc_type_realloc
CStrings:
+ "$previousScanningMode"
+ "%02x:%02x:%02x:%02x:%02x:%02x"
+ "@\"NSString\"8@?0"
+ "AXControlsSettingsObserver.reloadCoalesce"
+ "AXControlsSettingsObserver: Reloading control kind %@"
+ "AXControlsSettingsObserver: startObserving called while already observing; ignoring"
+ "AccessibilityAppleWatchRemoteScreenEnabledWidgetID"
+ "AccessibilityAssistiveTouchEnabledWidgetID"
+ "AccessibilityButtonShapesEnabledWidgetID"
+ "AccessibilityClassicInvertEnabledWidgetID"
+ "AccessibilityColorFiltersEnabledWidgetID"
+ "AccessibilityColorFiltersPickerWidgetID"
+ "AccessibilityFullKeyboardAccessEnabledWidgetID"
+ "AccessibilityGuestPassEnabledWidgetID"
+ "AccessibilityGuidedAccessEnabledWidgetID"
+ "AccessibilityHoverTextEnabledWidgetID"
+ "AccessibilityHoverTypingWidgetID"
+ "AccessibilityIncreaseContrastEnabledWidgetID"
+ "AccessibilityLeftRightBalanceEnabledWidgetID"
+ "AccessibilityLiveCaptionsEnabledWidgetID"
+ "AccessibilityNameRecognitionEnabledWidgetID"
+ "AccessibilityOnDeviceEyeTrackingEnabledWidgetID"
+ "AccessibilityReaderEnabledWidgetID"
+ "AccessibilityReduceMotionDimFlashingLightsEnabledWidgetID"
+ "AccessibilityReduceMotionEnabledWidgetID"
+ "AccessibilityReduceTransparencyEnabledWidgetID"
+ "AccessibilityReduceWhitePointEnabledWidgetID"
+ "AccessibilitySmartInvertEnabledWidgetID"
+ "AccessibilitySwitchControlEnabledWidgetID"
+ "AccessibilityVoiceControlEnabledWidgetID"
+ "AccessibilityVoiceOverEnabledWidgetID"
+ "AccessibilityZoomEnabledWidgetID"
+ "Applying air pods settings to: %@"
+ "Applying dark mode preference: %d"
+ "AssistiveTouchPreviousScanningModePreference"
+ "AudioChannelName_%@"
+ "Center"
+ "ChannelLayout_%@"
+ "Enabling live captions %{bool}d (liveCaptions: %{bool}d, liveTranscribe: %{bool}d)"
+ "Left"
+ "LeftCenter"
+ "Passing automation touch through to app (automationTrueTouch off): sender=0x%llx"
+ "RearLeft"
+ "RearRight"
+ "Recap"
+ "Right"
+ "RightCenter"
+ "SoundDetection_Medina_KShotEnrollment"
+ "Timed out enabling VoiceOver"
+ "VoiceOver warmup: spoke=%d after %.3fs (cap %.1fs)"
+ "bootstrap_look_up failed: %d"
+ "com.apple.accessibility.%@.button"
+ "com.apple.accessibility.%@.picker"
+ "com.apple.accessibility.AccessibilityShortcut.button"
+ "com.apple.accessibility.musichaptics"
+ "darkModeActive"
+ "deleteGuestPassProfile: rejected invalid profile name"
+ "leftBundleIdentifier"
+ "no VoiceOver speech within %.1fs"
+ "rightBundleIdentifier"
+ "storeGuestPassProfile: rejected invalid profile name"
+ "v32@?0@\"NSValue\"8Q16^B24"
- "%@ Always Listen for Siri Preboard."
- "%@ Sound Detection KShot Preboard."
- "/%@"
- "Applying airpod settings to: %@"
- "B12@?0B8"
- "B16@?0@\"NSString\"8"
- "B32@?0@\"AXIPCDelayedMessage\"8Q16^B24"
- "BTLocalDeviceGetConnectedDevices failed: %d"
- "ChannelLayout_Center"
- "ChannelLayout_Left"
- "ChannelLayout_LeftCenter"
- "ChannelLayout_RearLeft"
- "ChannelLayout_RearRight"
- "ChannelLayout_Right"
- "ChannelLayout_RightCenter"
- "Enabling live captions %@"
- "Enrolling in"
- "Timed out enabling VoiceOverTouch"
- "Unenrolling from"
- "realloc failed. Expect pain soon."
- "v16@?0@\"NSError\"8"
```
