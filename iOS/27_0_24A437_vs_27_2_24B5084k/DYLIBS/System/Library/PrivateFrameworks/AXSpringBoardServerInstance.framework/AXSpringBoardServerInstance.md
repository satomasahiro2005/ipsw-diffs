## AXSpringBoardServerInstance

> `/System/Library/PrivateFrameworks/AXSpringBoardServerInstance.framework/AXSpringBoardServerInstance`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e36c` | `0x3ee34` | **`+0xac8`** |
| `__TEXT.__oslogstring` | `0x18b9` | `0x19da` | **`+0x121`** |
| `__AUTH_CONST.__cfstring` | `0x6ac0` | `0x6be0` | **`+0x120`** |
| `__TEXT.__cstring` | `0x66a5` | `0x6799` | **`+0xf4`** |
| `__TEXT.__objc_methlist` | `0x33d4` | `0x3414` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2978` | `0x29b0` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0xb6c` | `0xba0` | **`+0x34`** |
| `__AUTH_CONST.__const` | `0xcc0` | `0xca0` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x1248` | `0x1268` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xbe8` | `0xbe0` | **`-0x8`** |

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Functions: 1372
-  Symbols:   2704
-  CStrings:  1116
+  Functions: 1381
+  Symbols:   2715
+  CStrings:  1128
Symbols:
+ -[AXSBSettingsLoader _removeStaleBuddyTripleClickOptionForReason:needsFirstBootIODFlow:]
+ -[AXSBSettingsLoader _setupModeDidChange]
+ -[AXSpringBoardServerSideAppManager _activeDisplayConfigurationForTransaction]
+ -[AXSpringBoardServerSideAppManager _launchEntityForApplicationOnActiveDisplay:]
+ -[AXSpringBoardServerSideAppManager _requestTransactionWithPrimaryEntity:sideEntity:floatingEntity:spaceConfiguration:floatingConfiguration:displayConfiguration:]
+ -[AXSpringBoardServerSideAppManager _targetableActiveBuiltInScene]
+ GCC_except_table1046
+ GCC_except_table1051
+ GCC_except_table1055
+ GCC_except_table1063
+ GCC_except_table1083
+ GCC_except_table1094
+ GCC_except_table1102
+ GCC_except_table1114
+ GCC_except_table1132
+ GCC_except_table1170
+ GCC_except_table253
+ GCC_except_table275
+ GCC_except_table279
+ GCC_except_table281
+ GCC_except_table283
+ GCC_except_table285
+ GCC_except_table288
+ GCC_except_table291
+ GCC_except_table293
+ GCC_except_table295
+ GCC_except_table297
+ GCC_except_table299
+ GCC_except_table301
+ GCC_except_table303
+ GCC_except_table305
+ GCC_except_table311
+ GCC_except_table321
+ GCC_except_table331
+ GCC_except_table361
+ GCC_except_table369
+ GCC_except_table392
+ GCC_except_table422
+ GCC_except_table425
+ GCC_except_table428
+ GCC_except_table438
+ GCC_except_table460
+ GCC_except_table464
+ GCC_except_table467
+ GCC_except_table470
+ GCC_except_table473
+ GCC_except_table476
+ GCC_except_table493
+ GCC_except_table495
+ GCC_except_table500
+ GCC_except_table502
+ GCC_except_table504
+ GCC_except_table507
+ GCC_except_table518
+ GCC_except_table520
+ GCC_except_table522
+ GCC_except_table524
+ GCC_except_table526
+ GCC_except_table531
+ GCC_except_table535
+ GCC_except_table538
+ GCC_except_table540
+ GCC_except_table542
+ GCC_except_table544
+ GCC_except_table547
+ GCC_except_table549
+ GCC_except_table557
+ GCC_except_table559
+ GCC_except_table563
+ GCC_except_table565
+ GCC_except_table567
+ GCC_except_table571
+ GCC_except_table574
+ GCC_except_table576
+ GCC_except_table578
+ GCC_except_table581
+ GCC_except_table584
+ GCC_except_table588
+ GCC_except_table597
+ GCC_except_table600
+ GCC_except_table613
+ GCC_except_table615
+ GCC_except_table635
+ GCC_except_table637
+ GCC_except_table642
+ GCC_except_table644
+ GCC_except_table660
+ GCC_except_table730
+ GCC_except_table782
+ GCC_except_table801
+ GCC_except_table829
+ GCC_except_table924
+ GCC_except_table928
+ GCC_except_table968
+ GCC_except_table973
+ GCC_except_table975
+ ___162-[AXSpringBoardServerSideAppManager _requestTransactionWithPrimaryEntity:sideEntity:floatingEntity:spaceConfiguration:floatingConfiguration:displayConfiguration:]_block_invoke
+ ___162-[AXSpringBoardServerSideAppManager _requestTransactionWithPrimaryEntity:sideEntity:floatingEntity:spaceConfiguration:floatingConfiguration:displayConfiguration:]_block_invoke_2
+ ___162-[AXSpringBoardServerSideAppManager _requestTransactionWithPrimaryEntity:sideEntity:floatingEntity:spaceConfiguration:floatingConfiguration:displayConfiguration:]_block_invoke_3
+ ___59+[AXSBSettingsLoader _initializeDelayedSpringBoardSettings]_block_invoke_5
+ ___59+[AXSBSettingsLoader _initializeDelayedSpringBoardSettings]_block_invoke_6
+ ___59+[AXSBSettingsLoader _initializeDelayedSpringBoardSettings]_block_invoke_7
+ ___67-[AXSpringBoardServerHelper _displayViewController:withCompletion:]_block_invoke_2
+ ___80-[AXSpringBoardServerSideAppManager _launchEntityForApplicationOnActiveDisplay:]_block_invoke
+ ___80-[AXSpringBoardServerSideAppManager _launchEntityForApplicationOnActiveDisplay:]_block_invoke_2
+ ___80-[AXSpringBoardServerSideAppManager _launchEntityForApplicationOnActiveDisplay:]_block_invoke_3
+ ___80-[AXSpringBoardServerSideAppManager _launchEntityForApplicationOnActiveDisplay:]_block_invoke_4
+ ___80-[AXSpringBoardServerSideAppManager _launchEntityForApplicationOnActiveDisplay:]_block_invoke_5
+ ___block_descriptor_88_e8_32s40s48s56s64s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- -[AXSpringBoardServerSideAppManager _requestTransactionWithPrimaryEntity:sideEntity:floatingEntity:spaceConfiguration:floatingConfiguration:]
- GCC_except_table1045
- GCC_except_table1050
- GCC_except_table1054
- GCC_except_table1060
- GCC_except_table1062
- GCC_except_table1076
- GCC_except_table1087
- GCC_except_table1095
- GCC_except_table1107
- GCC_except_table1125
- GCC_except_table1163
- GCC_except_table272
- GCC_except_table276
- GCC_except_table280
- GCC_except_table282
- GCC_except_table284
- GCC_except_table287
- GCC_except_table290
- GCC_except_table292
- GCC_except_table294
- GCC_except_table296
- GCC_except_table298
- GCC_except_table300
- GCC_except_table302
- GCC_except_table304
- GCC_except_table310
- GCC_except_table320
- GCC_except_table330
- GCC_except_table360
- GCC_except_table368
- GCC_except_table391
- GCC_except_table421
- GCC_except_table424
- GCC_except_table427
- GCC_except_table437
- GCC_except_table459
- GCC_except_table463
- GCC_except_table465
- GCC_except_table468
- GCC_except_table471
- GCC_except_table474
- GCC_except_table492
- GCC_except_table494
- GCC_except_table499
- GCC_except_table501
- GCC_except_table503
- GCC_except_table506
- GCC_except_table517
- GCC_except_table519
- GCC_except_table521
- GCC_except_table523
- GCC_except_table525
- GCC_except_table530
- GCC_except_table534
- GCC_except_table537
- GCC_except_table539
- GCC_except_table541
- GCC_except_table543
- GCC_except_table546
- GCC_except_table548
- GCC_except_table556
- GCC_except_table558
- GCC_except_table562
- GCC_except_table564
- GCC_except_table566
- GCC_except_table570
- GCC_except_table573
- GCC_except_table575
- GCC_except_table577
- GCC_except_table580
- GCC_except_table583
- GCC_except_table587
- GCC_except_table596
- GCC_except_table599
- GCC_except_table612
- GCC_except_table614
- GCC_except_table634
- GCC_except_table636
- GCC_except_table641
- GCC_except_table643
- GCC_except_table659
- GCC_except_table729
- GCC_except_table781
- GCC_except_table800
- GCC_except_table828
- GCC_except_table923
- GCC_except_table927
- GCC_except_table967
- GCC_except_table972
- GCC_except_table974
- ___141-[AXSpringBoardServerSideAppManager _requestTransactionWithPrimaryEntity:sideEntity:floatingEntity:spaceConfiguration:floatingConfiguration:]_block_invoke
- ___141-[AXSpringBoardServerSideAppManager _requestTransactionWithPrimaryEntity:sideEntity:floatingEntity:spaceConfiguration:floatingConfiguration:]_block_invoke_2
- ___141-[AXSpringBoardServerSideAppManager _requestTransactionWithPrimaryEntity:sideEntity:floatingEntity:spaceConfiguration:floatingConfiguration:]_block_invoke_3
- ___55-[AXSpringBoardServerSideAppManager launchApplication:]_block_invoke
- ___76-[AXSpringBoardServerSideAppManager launchApplicationWithFullConfiguration:]_block_invoke
- ___block_descriptor_80_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
- _objc_retain_x27
CStrings:
+ "CSNotificationDispatcher"
+ "Checking for stale Buddy triple click option (%{public}@): Buddy completed: %{BOOL}d, needs first boot IOD flow: %{BOOL}d, has Buddy option: %{BOOL}d, options: %@"
+ "FAILED to acquire"
+ "Not locking keyboard focus for presentation window (SB secure window: %d, FKA enabled: %d)"
+ "Presentation window focus lock: %@"
+ "PresentedAlert"
+ "SBInBuddyModeDidChangeNotification"
+ "SpringBoard launch"
+ "acquired"
+ "fbsDisplayConfiguration"
+ "focusLockSpringBoardWindowScene:forAccessibilityReason:"
+ "integratedDisplayWindowScene"
+ "requestTransitionWithOptions:displayConfiguration:builder:validator:"
+ "setup mode changed"
- "SBNotificationDestination"
- "requestTransitionWithOptions:builder:validator:"
```
