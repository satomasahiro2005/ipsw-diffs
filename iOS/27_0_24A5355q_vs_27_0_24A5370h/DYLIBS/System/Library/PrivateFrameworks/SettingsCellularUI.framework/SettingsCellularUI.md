## SettingsCellularUI

> `/System/Library/PrivateFrameworks/SettingsCellularUI.framework/SettingsCellularUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x930dc` | `0x933c8` | **`+0x2ec`** |
| `__TEXT.__cstring` | `0x9076` | `0x910b` | **`+0x95`** |
| `__TEXT.__oslogstring` | `0x6bc4` | `0x6c56` | **`+0x92`** |
| `__AUTH_CONST.__cfstring` | `0x8700` | `0x8780` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x1804` | `0x1868` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0x102c8` | `0x10290` | **`-0x38`** |
| `__TEXT.__objc_methlist` | `0x9bcc` | `0x9c04` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x2320` | `0x2358` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x1398` | `0x1370` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x5c0` | `0x5e0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x5610` | `0x5628` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x62c` | `0x628` | **`-0x4`** |

### Other Changes

```diff

-737.0.0.0.0
+744.0.0.0.0

-  Functions: 3336
-  Symbols:   5595
-  CStrings:  2062
+  Functions: 3341
+  Symbols:   5598
+  CStrings:  2066
Symbols:
+ +[PSUIRemoveCellularPlanSpecifier keyForCellularPlanUniversalReference:planManagerCache:]
+ +[PSUIRemoveCellularPlanSpecifier specifierWithPlanReference:cellularPlanManager:planManagerCache:hostController:popViewControllerOnPlanDeletion:]
+ -[PSUICellularController getDiagnosticsStatusString:]
+ -[PSUICellularController simSetupFlowCompleted:]
+ -[PSUICellularDiagnosticsSpecifier initWithHostController:]
+ -[PSUICellularDiagnosticsSpecifier initWithRadioCache:hostController:]
+ -[PSUICellularPlanManagerCache quickSwitchCircleDevicesInfoDidChange:]
+ -[PSUINumberSharingDetailController _setupNumberMirroringPlacardGroupFooter:]
+ -[PSUINumberSharingSubgroup _willEnterForeground]
+ GCC_except_table102
+ GCC_except_table136
+ GCC_except_table41
+ GCC_except_table75
+ ___48-[PSUICellularController simSetupFlowCompleted:]_block_invoke
+ ___70-[PSUICellularPlanManagerCache quickSwitchCircleDevicesInfoDidChange:]_block_invoke
- -[PSUICellularDataSpecifier setAirplaneMode:]
- -[PSUICellularDiagnosticsSpecifier cellularIssueDetected]
- -[PSUICellularDiagnosticsSpecifier getDiagnosticsStatusString:]
- -[PSUITurnOnThisLineSpecifier simSetupFlowCompleted:]
- GCC_except_table101
- GCC_except_table135
- GCC_except_table40
- GCC_except_table73
- _OBJC_IVAR_$_PSUICellularDiagnosticsSpecifier._cellularIssueDetected
- ___53-[PSUITurnOnThisLineSpecifier simSetupFlowCompleted:]_block_invoke
- ___53-[PSUITurnOnThisLineSpecifier simSetupFlowCompleted:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s_e5_v8?0ls32l8s40l8
CStrings:
+ "-[PSUICellularDiagnosticsSpecifier initWithRadioCache:hostController:]"
+ "Airplane mode is on, ignoring setting of cellular data plan (cellular data plan cannot be changed while airplane mode is on)"
+ "Airplane mode is on, ignoring setting of cellular data switch (cellular data switch cannot be toggled while airplane mode is on)"
+ "CTQuickSwitchCircleDeviceInfo: %@"
+ "DELETE_ESIM_CONFIRMATION_TITLE"
+ "DELETE_ESIM_MESSAGE_NUMBER_%@"
+ "DELETE_ESIM_TITLE"
+ "NUM_MIRRORING_PLACARD_GROUP"
+ "QS_LAST_USED_ON_DEVICE_%@_%@_%@"
+ "QS_ORPHANED_PRIMARY_FOOTER_%@"
+ "QS_ORPHANED_SECONDARY_PLACARD_BODY_%@"
+ "Removing the object"
+ "We should %s show any voice and data switch: VoLTE: %s, 5GSA: %s, VoNR: %s, 2G: %s"
+ "formattedPhoneNumber"
+ "https://support.apple.com/127274"
- "%@%@\n\n%@"
- "-[PSUICellularDiagnosticsSpecifier initWithRadioCache:]"
- "Airplane mode is %s"
- "DELETE_ESIM_MESSAGE_CARRIER_%@_%@"
- "QS_LAST_USED_%@_%@"
- "SIM config switch flow cancelled — reverting toggle"
- "We should %s show any voice and data switch: VoLTE: %s, 5GSA: %s, VoNR: %s"
- "https://support.apple.com/ht212780"
- "learn-more://open?id=cellular"
- "transfer disabled item back as new item: %@. enable it."
- "yeah, the phone number transferred back"
```
