## ScreenTimeCore

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf2d20` | `0xf3a7c` | **`+0xd5c`** |
| `__TEXT.__eh_frame` | `0x3b40` | `0x3d90` | **`+0x250`** |
| `__DATA_CONST.__const` | `0x1c78` | `0x1d48` | **`+0xd0`** |
| `__TEXT.__cstring` | `0xa45c` | `0xa52c` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0xba7a` | `0xbafa` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x3d78` | `0x3df8` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x144e` | `0x14cc` | **`+0x7e`** |
| `__TEXT.__objc_methlist` | `0xa0f0` | `0xa140` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x32d8` | `0x3308` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x53a8` | `0x53d8` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0xa58` | `0xa84` | **`+0x2c`** |
| `__AUTH_CONST.__cfstring` | `0x97c0` | `0x97e0` | **`+0x20`** |
| `__DATA.__data` | `0x2190` | `0x21b0` | **`+0x20`** |
| `__TEXT.__const` | `0x3288` | `0x32a8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x79e` | `0x7be` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x168` | `0x188` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x13190` | `0x13178` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1180` | `0x1190` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x210` | `0x220` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x148` | `0x158` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x9a8` | `0x9b4` | **`+0xc`** |
| `__AUTH.__data` | `0x4f8` | `0x500` | **`+0x8`** |
| `__AUTH.__objc_data` | `0x31a0` | `0x31a8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xe98` | `0xe90` | **`-0x8`** |

### Other Changes

```diff

-645.1.100.0.0
+649.0.0.0.0

-  Functions: 5821
-  Symbols:   6728
-  CStrings:  2231
+  Functions: 5840
+  Symbols:   6742
+  CStrings:  2237
Symbols:
+ -[STCommunicationClient _authenticateForCommunicationConfigurationOverrideWithUserInterfaceStyle:completionHandler:]
+ -[STCommunicationClient authenticateForCommunicationConfigurationOverrideWithUserInterfaceStyle:completionHandler:]
+ -[STConcretePasscodeAuthenticationProviderService authenticatePasscodeWithCommunicationServiceProxy:userInterfaceStyle:completionHandler:]
+ -[STManagementState _resolveOneMoreMinuteViaSettings:proxy:completionHandler:]
+ -[STManagementState familyDevicesForAltDSID:forceRefresh:ineligibleOnly:completionHandler:]
+ -[STManagementState isFamilyMemberEligibleForMigrationUIWithAltDSID:forceRefresh:completionHandler:]
+ GCC_except_table188
+ GCC_except_table191
+ GCC_except_table200
+ GCC_except_table203
+ GCC_except_table209
+ _STRemoteAlertConfigurationContextKeyUserInterfaceStyle
+ ___100-[STManagementState isFamilyMemberEligibleForMigrationUIWithAltDSID:forceRefresh:completionHandler:]_block_invoke
+ ___100-[STManagementState isFamilyMemberEligibleForMigrationUIWithAltDSID:forceRefresh:completionHandler:]_block_invoke_2
+ ___116-[STCommunicationClient _authenticateForCommunicationConfigurationOverrideWithUserInterfaceStyle:completionHandler:]_block_invoke
+ ___138-[STConcretePasscodeAuthenticationProviderService authenticatePasscodeWithCommunicationServiceProxy:userInterfaceStyle:completionHandler:]_block_invoke
+ ___78-[STManagementState _resolveOneMoreMinuteViaSettings:proxy:completionHandler:]_block_invoke
+ ___78-[STManagementState _resolveOneMoreMinuteViaSettings:proxy:completionHandler:]_block_invoke_2
+ ___78-[STManagementState _resolveOneMoreMinuteViaSettings:proxy:completionHandler:]_block_invoke_3
+ ___78-[STManagementState _resolveOneMoreMinuteViaSettings:proxy:completionHandler:]_block_invoke_4
+ ___91-[STManagementState familyDevicesForAltDSID:forceRefresh:ineligibleOnly:completionHandler:]_block_invoke
+ ___91-[STManagementState familyDevicesForAltDSID:forceRefresh:ineligibleOnly:completionHandler:]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e28_v24?0"NSUUID"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32s_e74_v24?0"<STManagementStateServerInterface>"8?<v?"NSNumber""NSError">16ls32l8
+ ___block_descriptor_48_e8_32s40bs_e28_v24?0"NSUUID"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e35_v16?0?<v?"NSNumber""NSError">8ls32l8s40l8
+ ___block_descriptor_64_e8_32s40bs48bs56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___swift_closure_destructor.27Tm
+ _swift_retain_x8
+ _symbolic SbIegy_
+ _symbolic ScTy_____Sg_____GSg 26ScreenTimeSettingsServices0ab10WebBrowserC0C s5NeverO
+ _symbolic So6NSUUIDCSgSo7NSErrorCSgIeyByy_
+ _symbolic _____IeyBy_ 10ObjectiveC8ObjCBoolV
+ _symbolic _____SgIeAgHr_ 26ScreenTimeSettingsServices0ab10WebBrowserC0C
+ _symbolic _____SgXw So38STScreenTimeWebBrowserSettingsObserverC06ScreenB4CoreE0E033_C1D88EBD6D178F2084F8C827022CEF0ELLC
+ _symbolic _____SgXwz_Xx So38STScreenTimeWebBrowserSettingsObserverC06ScreenB4CoreE0E033_C1D88EBD6D178F2084F8C827022CEF0ELLC
+ _symbolic _____XDXMT So29STScreenTimeWebBrowserHistoryC06ScreenB4CoreE5Store33_C1361D6D4F858D96C532ECBA2F242AACLLC
- -[STManagementState deviceListForAltDSID:forceRefresh:completionHandler:]
- -[STManagementState isFamilyEligibleForUpgradeWithAltDSID:forceRefresh:completionHandler:]
- GCC_except_table189
- GCC_except_table192
- GCC_except_table201
- GCC_except_table204
- GCC_except_table210
- __OBJC_$_PROP_LIST_STScreenTimeSettingsWebBrowserHistoryStoring
- __PROPERTIES_STScreenTimeWebBrowserHistory
- __PROPERTIES__TtCE14ScreenTimeCoreCSo29STScreenTimeWebBrowserHistoryP33_C1361D6D4F858D96C532ECBA2F242AAC5Store
- ___119-[STConcretePasscodeAuthenticationProviderService authenticatePasscodeWithCommunicationServiceProxy:completionHandler:]_block_invoke
- ___73-[STManagementState deviceListForAltDSID:forceRefresh:completionHandler:]_block_invoke
- ___73-[STManagementState deviceListForAltDSID:forceRefresh:completionHandler:]_block_invoke_2
- ___76-[STManagementState shouldAllowOneMoreMinuteForWebDomain:completionHandler:]_block_invoke_3
- ___76-[STManagementState shouldAllowOneMoreMinuteForWebDomain:completionHandler:]_block_invoke_4
- ___83-[STManagementState shouldAllowOneMoreMinuteForBundleIdentifier:completionHandler:]_block_invoke_3
- ___83-[STManagementState shouldAllowOneMoreMinuteForBundleIdentifier:completionHandler:]_block_invoke_4
- ___85-[STManagementState shouldAllowOneMoreMinuteForCategoryIdentifier:completionHandler:]_block_invoke_3
- ___85-[STManagementState shouldAllowOneMoreMinuteForCategoryIdentifier:completionHandler:]_block_invoke_4
- ___90-[STManagementState isFamilyEligibleForUpgradeWithAltDSID:forceRefresh:completionHandler:]_block_invoke
- ___90-[STManagementState isFamilyEligibleForUpgradeWithAltDSID:forceRefresh:completionHandler:]_block_invoke_2
- ___96-[STCommunicationClient authenticateForCommunicationConfigurationOverrideWithCompletionHandler:]_block_invoke
- ___swift_closure_destructor.20Tm
CStrings:
+ "Authenticating for communication configuration override (style: %ld)"
+ "Prompted for passcode authentication (style: %ld)"
+ "STRemoteAlertConfigurationContextKeyUserInterfaceStyle"
+ "v16@?0@?<v@?@\"NSNumber\"@\"NSError\">8"
+ "v24@?0@\"<STManagementStateServerInterface>\"8@?<v@?@\"NSNumber\"@\"NSError\">16"
+ "v24@?0@\"NSUUID\"8@\"NSError\"16"
```
