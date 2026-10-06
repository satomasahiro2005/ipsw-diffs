## WorkflowUI

> `/System/Library/PrivateFrameworks/WorkflowUI.framework/WorkflowUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a05e8` | `0x2a3338` | **`+0x2d50`** |
| `__TEXT.__oslogstring` | `0x1e07` | `0x215e` | **`+0x357`** |
| `__TEXT.__eh_frame` | `0x6fc4` | `0x7264` | **`+0x2a0`** |
| `__TEXT.__swift5_typeref` | `0x2b4ae` | `0x2b6c0` | **`+0x212`** |
| `__TEXT.__cstring` | `0xb999` | `0xbb93` | **`+0x1fa`** |
| `__AUTH.__objc_data` | `0x7b98` | `0x7d40` | **`+0x1a8`** |
| `__AUTH_CONST.__objc_const` | `0x159c0` | `0x15b00` | **`+0x140`** |
| `__TEXT.__const` | `0x1ebc0` | `0x1ed00` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0xaac8` | `0xabe8` | **`+0x120`** |
| `__TEXT.__constg_swiftt` | `0xa750` | `0xa810` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x13308` | `0x133a8` | **`+0xa0`** |
| `__DATA.__bss` | `0x18010` | `0x18090` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1b60` | `0x1bc8` | **`+0x68`** |
| `__TEXT.__dlopen_cstrs` | `—` | `0x64` | **`+0x64`** |
| `__AUTH_CONST.__cfstring` | `0x23c0` | `0x2420` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x992c` | `0x998c` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x6cd8` | `0x6d30` | **`+0x58`** |
| `__DATA.__data` | `0xc530` | `0xc580` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x6bcc` | `0x6c1c` | **`+0x50`** |
| `__AUTH.__data` | `0x6618` | `0x6658` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x6263` | `0x62a3` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x360` | `0x380` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x3888` | `0x38a0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xa54` | `0xa6c` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x1d38` | `0x1d50` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x43d0` | `0x43e8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x2860` | `0x2870` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x790` | `0x7a0` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x170` | `0x180` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x7d8` | `0x7e0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x188` | `0x190` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xcb0` | `0xcb4` | **`+0x4`** |

### Other Changes

```diff

-5111.0.2.0.0
+5113.0.1.1.1

+  - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking

-  Functions: 19740
-  Symbols:   10106
-  CStrings:  1418
+  Functions: 19812
+  Symbols:   10146
+  CStrings:  1439
Symbols:
+ +[WFHomeScreenWallpaperFetcher fetchHomeScreenWallpaperPNGDataWithCompletion:]
+ GCC_except_table1034
+ GCC_except_table1139
+ GCC_except_table1197
+ GCC_except_table1244
+ GCC_except_table1291
+ GCC_except_table1292
+ GCC_except_table1301
+ GCC_except_table1409
+ GCC_except_table1410
+ GCC_except_table1420
+ GCC_except_table1498
+ GCC_except_table1499
+ GCC_except_table1613
+ GCC_except_table1620
+ GCC_except_table1635
+ GCC_except_table1652
+ GCC_except_table1685
+ GCC_except_table1705
+ GCC_except_table1716
+ GCC_except_table1745
+ GCC_except_table1791
+ GCC_except_table1807
+ GCC_except_table1908
+ GCC_except_table1911
+ GCC_except_table201
+ GCC_except_table286
+ GCC_except_table321
+ GCC_except_table390
+ GCC_except_table391
+ GCC_except_table545
+ GCC_except_table595
+ GCC_except_table820
+ GCC_except_table967
+ GCC_except_table990
+ GCC_except_table998
+ _OBJC_CLASS_$_PRSPosterSnapshotRequest
+ _OBJC_CLASS_$_WFAutomationNotificationListViewController
+ _OBJC_CLASS_$_WFHomeScreenWallpaperFetcher
+ _OBJC_METACLASS_$_WFAutomationNotificationListViewController
+ _OBJC_METACLASS_$_WFHomeScreenWallpaperFetcher
+ _PosterBoardServicesLibraryCore.frameworkLibrary
+ _WFMakeAutomationNotificationListViewController
+ __DATA_WFAutomationNotificationListViewController
+ __INSTANCE_METHODS_WFAutomationNotificationListViewController
+ __IVARS_WFAutomationNotificationListViewController
+ __METACLASS_DATA_WFAutomationNotificationListViewController
+ __OBJC_$_CLASS_METHODS_WFHomeScreenWallpaperFetcher
+ __OBJC_CLASS_RO_$_WFHomeScreenWallpaperFetcher
+ __OBJC_METACLASS_RO_$_WFHomeScreenWallpaperFetcher
+ ___78+[WFHomeScreenWallpaperFetcher fetchHomeScreenWallpaperPNGDataWithCompletion:]_block_invoke
+ ___PosterBoardServicesLibraryCore_block_invoke
+ ___block_descriptor_40_e8_32bs_e41_v32?0"NSString"8"NSData"16"NSError"24ls32l8
+ ___block_descriptor_48_e8_32s40s_e20_v20?0B8"NSError"12ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56s_e20_v20?0B8"NSError"12ls32l8s40l8s48l8s56l8
+ ___getPRSExternalSystemServiceClass_block_invoke
+ __sl_dlopen
+ _associated conformance 10WorkflowUI30NotificationAutomationListView33_37C2C5D8F69473AABA2373A85B417463LLV05SwiftB00F0AA4BodyAeFP_AeF
+ _audit_stringPosterBoardServices
+ _getPRSExternalSystemServiceClass.softClass
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA4ViewPAAE9listStyleyQrqd__AA04ListG0Rd__lFQOyAA0H0Vys5NeverOAA7ForEachVySay08WorkflowB027ConfiguredAutomationRowDataVGSo19WFUnifiedTriggerKeyCAN0noE0VGG_AA05PlainhG0VQo_AA12_FrameLayoutVGAaDHPqd0__AaDHD3_AZHO_A0_AA0E8ModifierHPyHCHC
+ _symbolic SccySo28PRSActivePosterConfigurationC______pG s5ErrorP
+ _symbolic Sccy___________pG 10Foundation4DataV s5ErrorP
+ _symbolic So19WFUnifiedTriggerKeyC______t 11WorkflowKit36WFUnifiedAutomationTriggerDescriptorC
+ _symbolic _____ 10WorkflowUI30NotificationAutomationListView33_37C2C5D8F69473AABA2373A85B417463LLV
+ _symbolic _____ 10WorkflowUI42WFAutomationNotificationListViewControllerC
+ _symbolic _____Sg 10WorkflowUI27ConfiguredAutomationRowDataV
+ _symbolic __________Iegnr_ 10WorkflowUI27ConfiguredAutomationRowDataV AA0dE4ViewV
+ _symbolic _____ySay_____GSo19WFUnifiedTriggerKeyC_____G 7SwiftUI7ForEachV 08WorkflowB027ConfiguredAutomationRowDataV AD0gH4ViewV
+ _symbolic _____ySo19WFUnifiedTriggerKeyC_____G s17_NativeDictionaryV 11WorkflowKit36WFUnifiedAutomationTriggerDescriptorC
+ _symbolic _____ySo19WFUnifiedTriggerKeyC_____G s18_DictionaryStorageC 11WorkflowKit36WFUnifiedAutomationTriggerDescriptorC
+ _symbolic _____ySo19WFUnifiedTriggerKeyC______tG s23_ContiguousArrayStorageC 11WorkflowKit36WFUnifiedAutomationTriggerDescriptorC
+ _symbolic _____y_____G 7SwiftUI19UIHostingControllerC 08WorkflowB030NotificationAutomationListView33_37C2C5D8F69473AABA2373A85B417463LLV
+ _symbolic _____y__________ySay_____GSo19WFUnifiedTriggerKeyC_____GG 7SwiftUI4ListV s5NeverO AA7ForEachV 08WorkflowB027ConfiguredAutomationRowDataV AH0iJ4ViewV
+ _symbolic _____y_____y__________ySay_____GSo19WFUnifiedTriggerKeyC_____GG______Qo_ 7SwiftUI4ViewPAAE9listStyleyQrqd__AA04ListE0Rd__lFQO AA0F0V s5NeverO AA7ForEachV 08WorkflowB027ConfiguredAutomationRowDataV AL0lmC0V AA05PlainfE0V
+ _symbolic _____y_____y_____y__________ySay_____GSo19WFUnifiedTriggerKeyC_____GG______Qo______G 7SwiftUI15ModifiedContentV AA4ViewPAAE9listStyleyQrqd__AA04ListG0Rd__lFQO AA0H0V s5NeverO AA7ForEachV 08WorkflowB027ConfiguredAutomationRowDataV AN0noE0V AA05PlainhG0V AA12_FrameLayoutV
+ _type_layout_string 10WorkflowUI30NotificationAutomationListView33_37C2C5D8F69473AABA2373A85B417463LLV
+ _type_layout_string So7CGPointV
- GCC_except_table1029
- GCC_except_table1134
- GCC_except_table1192
- GCC_except_table1239
- GCC_except_table1286
- GCC_except_table1287
- GCC_except_table1296
- GCC_except_table1404
- GCC_except_table1405
- GCC_except_table1415
- GCC_except_table1493
- GCC_except_table1494
- GCC_except_table1608
- GCC_except_table1615
- GCC_except_table1630
- GCC_except_table1647
- GCC_except_table1680
- GCC_except_table1700
- GCC_except_table1711
- GCC_except_table1740
- GCC_except_table1786
- GCC_except_table1802
- GCC_except_table1898
- GCC_except_table1906
- GCC_except_table281
- GCC_except_table316
- GCC_except_table385
- GCC_except_table386
- GCC_except_table540
- GCC_except_table590
- GCC_except_table815
- GCC_except_table962
- GCC_except_table985
- GCC_except_table993
- ___block_descriptor_64_e8_32s40s48s56s_e8_v12?0B8ls32l8s40l8s48l8s56l8
- _swift_deallocPartialClassInstance
- _symbolic _____y__________ySbGG 7SwiftUI15ModifiedContentV 18WorkflowUIServices8IconViewV AA30_EnvironmentKeyWritingModifierV
- _type_layout_string So6CGSizeV
CStrings:
+ "%s Cancelling the interaction card because the device wasn’t unlocked: %{public}@"
+ "%s Not editing the parameter because the device wasn’t unlocked: %{public}@"
+ "%s Not showing the action interface because the device wasn’t unlocked: %{public}@"
+ "-[WFAskParameterDialogViewController modalButtonTapped:]_block_invoke"
+ "-[WFCompactHostingViewController handlePendingRequest]_block_invoke_4"
+ "Can't perform privacy reset: the workflow has no database or reference, so there is no smart prompt state to delete"
+ "Can't save deletion authorization status: the workflow has no database or reference, so we shouldn't be showing any smart prompts for it"
+ "Can't save smart prompt status: the workflow has no database or reference, so we shouldn't be showing any smart prompts for it"
+ "Class getPRSExternalSystemServiceClass(void)_block_invoke"
+ "Failed to fetch active poster with error: %@"
+ "Failed to fetch home screen poster snapshot with error: %@"
+ "Failed to fetch home screen wallpaper with error: %@"
+ "Initializing SmartPromptsViewModel without a database; no smart prompt state is available for this workflow"
+ "PRSExternalSystemService"
+ "Unable to find class %s"
+ "WFHomeScreenWallpaperFetcher.m"
+ "WorkflowUI.WFAutomationNotificationListViewController"
+ "WorkflowUI/NotificationAutomationListView.swift"
+ "init(coder:) is not supported"
+ "softlink:r:path:/System/Library/PrivateFrameworks/PosterBoardServices.framework/PosterBoardServices"
+ "v32@?0@\"NSString\"8@\"NSData\"16@\"NSError\"24"
+ "void *PosterBoardServicesLibrary(void)"
- "Could not init SmartPromptsViewModel because database or reference were nil"
```
