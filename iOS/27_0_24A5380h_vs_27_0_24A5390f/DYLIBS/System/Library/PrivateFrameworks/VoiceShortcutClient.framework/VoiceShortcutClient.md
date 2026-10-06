## VoiceShortcutClient

> `/System/Library/PrivateFrameworks/VoiceShortcutClient.framework/VoiceShortcutClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1549cc` | `0x154d38` | **`+0x36c`** |
| `__AUTH_CONST.__cfstring` | `0x19a40` | `0x19ce0` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0x181ac` | `0x183e2` | **`+0x236`** |
| `__DATA_CONST.__const` | `0x3750` | `0x37d8` | **`+0x88`** |
| `__TEXT.__eh_frame` | `0x6578` | `0x64f8` | **`-0x80`** |
| `__DATA.__data` | `0x4618` | `0x4648` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x60d0` | `0x6100` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xcdec` | `0xce1c` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1a6a8` | `0x1a688` | **`-0x20`** |
| `__AUTH.__data` | `0x1a70` | `0x1a80` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7190` | `0x71a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1210` | `0x1218` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x1ec` | `0x1e4` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xd14` | `0xd10` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0xf8` | `0xf4` | **`-0x4`** |
| `__TEXT.__oslogstring` | `0x3f5d` | `0x3f5a` | **`-0x3`** |

### Other Changes

```diff

-5032.5.0.0.0
+5034.0.12.100.0

-  Functions: 10845
-  Symbols:   11681
-  CStrings:  4396
+  Functions: 10850
+  Symbols:   11704
+  CStrings:  4418
Symbols:
+ -[VCAccessSpecifier allowLinkContextualActionRunningForBundleIdentifier:intentIdentifier:]
+ -[WFExternalUIPresenter updateOpensIntent:completionHandler:]
+ -[WFSageWorkflowRunnerClient updateOpensIntent:completionHandler:]
+ -[WFSiriWorkflowRunnerClient updateOpensIntent:completionHandler:]
+ -[WFWorkflowIcon initWithBackgroundColorValue:glyphCharacter:]
+ -[WFWorkflowIcon initWithBackgroundColorValue:glyphCharacter:symbolOverride:]
+ -[WFWorkflowIcon initWithPaletteColor:glyphCharacter:]
+ GCC_except_table1002
+ GCC_except_table1145
+ GCC_except_table1149
+ GCC_except_table1172
+ GCC_except_table1173
+ GCC_except_table1182
+ GCC_except_table1253
+ GCC_except_table1284
+ GCC_except_table1329
+ GCC_except_table1330
+ GCC_except_table1420
+ GCC_except_table1424
+ GCC_except_table1459
+ GCC_except_table1477
+ GCC_except_table1504
+ GCC_except_table1509
+ GCC_except_table1515
+ GCC_except_table1564
+ GCC_except_table1565
+ GCC_except_table1576
+ GCC_except_table1581
+ GCC_except_table1654
+ GCC_except_table1655
+ GCC_except_table1714
+ GCC_except_table1790
+ GCC_except_table1807
+ GCC_except_table1856
+ GCC_except_table1881
+ GCC_except_table1943
+ GCC_except_table1946
+ GCC_except_table1955
+ GCC_except_table1965
+ GCC_except_table1986
+ GCC_except_table2113
+ GCC_except_table2136
+ GCC_except_table2179
+ GCC_except_table2208
+ GCC_except_table2263
+ GCC_except_table2274
+ GCC_except_table2299
+ GCC_except_table2322
+ GCC_except_table2330
+ GCC_except_table2407
+ GCC_except_table2472
+ GCC_except_table2479
+ GCC_except_table2487
+ GCC_except_table2705
+ GCC_except_table2758
+ GCC_except_table2762
+ GCC_except_table2767
+ GCC_except_table2798
+ GCC_except_table2918
+ GCC_except_table2921
+ GCC_except_table2934
+ GCC_except_table2939
+ GCC_except_table2964
+ GCC_except_table3181
+ GCC_except_table3251
+ GCC_except_table3263
+ GCC_except_table3266
+ GCC_except_table3353
+ GCC_except_table3506
+ GCC_except_table3507
+ GCC_except_table3574
+ GCC_except_table3661
+ GCC_except_table3680
+ GCC_except_table3681
+ GCC_except_table3682
+ GCC_except_table3689
+ GCC_except_table3697
+ GCC_except_table3698
+ GCC_except_table3699
+ GCC_except_table3701
+ GCC_except_table3741
+ GCC_except_table3840
+ GCC_except_table3869
+ GCC_except_table3870
+ GCC_except_table3871
+ GCC_except_table4080
+ GCC_except_table4090
+ GCC_except_table4093
+ GCC_except_table4095
+ GCC_except_table4103
+ GCC_except_table4208
+ GCC_except_table4212
+ GCC_except_table4225
+ GCC_except_table4332
+ GCC_except_table4383
+ GCC_except_table4412
+ GCC_except_table4426
+ GCC_except_table4429
+ GCC_except_table4434
+ GCC_except_table4438
+ GCC_except_table4441
+ GCC_except_table4446
+ GCC_except_table4449
+ GCC_except_table4456
+ GCC_except_table4461
+ GCC_except_table4466
+ GCC_except_table4483
+ GCC_except_table4487
+ GCC_except_table4500
+ GCC_except_table4518
+ GCC_except_table869
+ _NSCalendarIdentifierGregorian
+ _VCAppBundleIdentifierForBundleIdentifier
+ _WFLinkEntityPropertyDenyList
+ _WFShortcutSourceActiveStarterShortcut
+ _WFShortcutSourceAddToSiri
+ _WFShortcutSourceAppShortcut
+ _WFShortcutSourceAutomatorMigration
+ _WFShortcutSourceCloudLink
+ _WFShortcutSourceDefaultShortcut
+ _WFShortcutSourceDescribeAShortcut
+ _WFShortcutSourceEditorDocumentMenu
+ _WFShortcutSourceFileKnownContacts
+ _WFShortcutSourceFilePersonal
+ _WFShortcutSourceFilePublic
+ _WFShortcutSourceGallery
+ _WFShortcutSourceNotifyMeWhen
+ _WFShortcutSourceOnDevice
+ _WFShortcutSourceSiriTopLevelShortcut
+ _WFShortcutSourceUnknown
+ _WFWorkflowRunSourceNotifyMeWhen
+ ___61-[WFExternalUIPresenter updateOpensIntent:completionHandler:]_block_invoke
+ ___66-[WFSageWorkflowRunnerClient updateOpensIntent:completionHandler:]_block_invoke
- -[VCAccessSpecifier allowLinkContextualActionRunningForBundleIdentifier:]
- -[WFWorkflowIcon customImageData]
- -[WFWorkflowIcon initWithBackgroundColorValue:glyphCharacter:customImageData:]
- -[WFWorkflowIcon initWithBackgroundColorValue:glyphCharacter:customImageData:symbolOverride:]
- -[WFWorkflowIcon initWithPaletteColor:glyphCharacter:customImageData:]
- GCC_except_table1001
- GCC_except_table1143
- GCC_except_table1147
- GCC_except_table1169
- GCC_except_table1170
- GCC_except_table1180
- GCC_except_table1251
- GCC_except_table1282
- GCC_except_table1321
- GCC_except_table1324
- GCC_except_table1418
- GCC_except_table1422
- GCC_except_table1457
- GCC_except_table1475
- GCC_except_table1502
- GCC_except_table1507
- GCC_except_table1513
- GCC_except_table1558
- GCC_except_table1563
- GCC_except_table1574
- GCC_except_table1579
- GCC_except_table1652
- GCC_except_table1653
- GCC_except_table1712
- GCC_except_table1788
- GCC_except_table1805
- GCC_except_table1854
- GCC_except_table1875
- GCC_except_table1937
- GCC_except_table1942
- GCC_except_table1953
- GCC_except_table1961
- GCC_except_table1984
- GCC_except_table2109
- GCC_except_table2132
- GCC_except_table2175
- GCC_except_table2205
- GCC_except_table2260
- GCC_except_table2271
- GCC_except_table2296
- GCC_except_table2319
- GCC_except_table2324
- GCC_except_table2402
- GCC_except_table2467
- GCC_except_table2474
- GCC_except_table2482
- GCC_except_table2699
- GCC_except_table2752
- GCC_except_table2756
- GCC_except_table2761
- GCC_except_table2792
- GCC_except_table2912
- GCC_except_table2915
- GCC_except_table2922
- GCC_except_table2933
- GCC_except_table2952
- GCC_except_table3175
- GCC_except_table3245
- GCC_except_table3257
- GCC_except_table3260
- GCC_except_table3335
- GCC_except_table3500
- GCC_except_table3501
- GCC_except_table3568
- GCC_except_table3655
- GCC_except_table3674
- GCC_except_table3675
- GCC_except_table3676
- GCC_except_table3683
- GCC_except_table3685
- GCC_except_table3686
- GCC_except_table3693
- GCC_except_table3695
- GCC_except_table3735
- GCC_except_table3834
- GCC_except_table3863
- GCC_except_table3864
- GCC_except_table3865
- GCC_except_table4074
- GCC_except_table4081
- GCC_except_table4084
- GCC_except_table4089
- GCC_except_table4097
- GCC_except_table4202
- GCC_except_table4206
- GCC_except_table4219
- GCC_except_table4326
- GCC_except_table4377
- GCC_except_table4406
- GCC_except_table4411
- GCC_except_table4414
- GCC_except_table4428
- GCC_except_table4432
- GCC_except_table4435
- GCC_except_table4437
- GCC_except_table4440
- GCC_except_table4450
- GCC_except_table4455
- GCC_except_table4460
- GCC_except_table4477
- GCC_except_table4481
- GCC_except_table4494
- GCC_except_table4512
- GCC_except_table868
- _OBJC_IVAR_$_WFWorkflowIcon._customImageData
CStrings:
+ "%s %{public}@ may not run an action for %{public}@"
+ "%s No LSBundleRecord for %{public}@ (%{public}@)"
+ "-[VCAccessSpecifier allowLinkContextualActionRunningForBundleIdentifier:intentIdentifier:]"
+ "ConversationEntity"
+ "GUID"
+ "MessageEntity"
+ "ShortcutSourceActiveStarterShortcut"
+ "ShortcutSourceAddToSiri"
+ "ShortcutSourceAppShortcut"
+ "ShortcutSourceAutomatorMigration"
+ "ShortcutSourceCloudLink"
+ "ShortcutSourceDefaultShortcut"
+ "ShortcutSourceDescribeAShortcut"
+ "ShortcutSourceEditorDocumentMenu"
+ "ShortcutSourceFileKnownContacts"
+ "ShortcutSourceFilePersonal"
+ "ShortcutSourceFilePublic"
+ "ShortcutSourceGallery"
+ "ShortcutSourceOnDevice"
+ "ShortcutSourceUnknown"
+ "VCAppBundleIdentifierForBundleIdentifier"
+ "com.apple.private.appintents.attribution.bundle-identifier"
+ "conversationGUID"
+ "notify-my-when"
+ "transferGUID"
- "%s Couldn't get LSBundleRecord from task, leaving associated app bundle identifier as nil (%{public}@)"
- "-[VCAccessSpecifier associatedAppBundleIdentifierFromBundleRecord]"
- "customImageData"
```
