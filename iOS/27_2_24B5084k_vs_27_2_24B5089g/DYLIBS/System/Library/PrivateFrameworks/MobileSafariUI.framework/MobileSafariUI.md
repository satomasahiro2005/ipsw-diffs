## MobileSafariUI

> `/System/Library/PrivateFrameworks/MobileSafariUI.framework/MobileSafariUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2eedf4` | `0x2f1504` | **`+0x2710`** |
| `__AUTH_CONST.__objc_const` | `0x33470` | `0x33808` | **`+0x398`** |
| `__DATA_DIRTY.__data` | `0x12e8` | `0x15d8` | **`+0x2f0`** |
| `__TEXT.__constg_swiftt` | `0x1f38` | `0x20f0` | **`+0x1b8`** |
| `__TEXT.__const` | `0x4e60` | `0x5010` | **`+0x1b0`** |
| `__TEXT.__swift5_typeref` | `0x6499` | `0x6607` | **`+0x16e`** |
| `__DATA.__bss` | `0x3ae0` | `0x39c0` | **`-0x120`** |
| `__AUTH_CONST.__const` | `0x8930` | `0x8a40` | **`+0x110`** |
| `__DATA_DIRTY.__bss` | `0xb90` | `0xca0` | **`+0x110`** |
| `__TEXT.__objc_methlist` | `0x24db4` | `0x24e9c` | **`+0xe8`** |
| `__TEXT.__gcc_except_tab` | `0x1f60c` | `0x1f6d0` | **`+0xc4`** |
| `__TEXT.__swift5_fieldmd` | `0x1000` | `0x10c0` | **`+0xc0`** |
| `__DATA_DIRTY.__objc_data` | `0x4640` | `0x46e0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x102a8` | `0x10338` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x187b8` | `0x18830` | **`+0x78`** |
| `__DATA.__data` | `0x9be8` | `0x9c28` | **`+0x40`** |
| `__TEXT.__cstring` | `0x10ae4` | `0x10b14` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1100` | `0x1130` | **`+0x30`** |
| `__AUTH.__data` | `0x1160` | `0x1180` | **`+0x20`** |
| `__AUTH.__objc_data` | `0x3330` | `0x3350` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2df0` | `0x2e10` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0xa20` | `0xa40` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x160` | `0x174` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x3810` | `0x3820` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x2528` | `0x2538` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x200` | `0x210` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0xc` | `0x1c` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x20dc` | `0x20e4` | **`+0x8`** |

### Other Changes

```diff

-625.2.4.1.0
+625.2.5.10.1

-  Functions: 16283
-  Symbols:   23044
-  CStrings:  3286
+  Functions: 16332
+  Symbols:   23092
+  CStrings:  3287
Symbols:
+ -[BrowserController foregroundReturnAnalyticsTracker]
+ -[TabCollectionViewManager evaluatePostponedSnapshotInvalidations]
+ -[TabDocument URLFromSafariSpecificScheme]
+ -[TabDocument _clearNavigationSourceForNavigationURL:]
+ -[TabDocument _enableEnhancedSecurityIfRequiredForWebpagePreferences:isForMainFrameNavigation:]
+ -[TabDocument _webViewDidCompleteApplePayPayment:]
+ -[TabDocument setURLFromSafariSpecificScheme:]
+ GCC_except_table1016
+ GCC_except_table1027
+ GCC_except_table1230
+ GCC_except_table1437
+ GCC_except_table428
+ GCC_except_table483
+ GCC_except_table531
+ GCC_except_table537
+ GCC_except_table541
+ GCC_except_table579
+ GCC_except_table623
+ GCC_except_table646
+ GCC_except_table678
+ GCC_except_table690
+ GCC_except_table697
+ GCC_except_table710
+ GCC_except_table716
+ GCC_except_table718
+ GCC_except_table725
+ GCC_except_table741
+ GCC_except_table762
+ GCC_except_table784
+ GCC_except_table791
+ GCC_except_table798
+ GCC_except_table821
+ GCC_except_table852
+ GCC_except_table871
+ GCC_except_table887
+ GCC_except_table902
+ GCC_except_table919
+ GCC_except_table928
+ GCC_except_table942
+ GCC_except_table947
+ GCC_except_table956
+ GCC_except_table958
+ GCC_except_table966
+ GCC_except_table979
+ GCC_except_table982
+ GCC_except_table984
+ GCC_except_table991
+ _OBJC_CLASS_$_ForegroundReturnAnalyticsTracker
+ _OBJC_IVAR_$_BrowserController._foregroundReturnAnalyticsTracker
+ _OBJC_IVAR_$_TabDocument._URLFromSafariSpecificScheme
+ _OBJC_METACLASS_$_ForegroundReturnAnalyticsTracker
+ __DATA_ForegroundReturnAnalyticsTracker
+ __DATA__TtC14MobileSafariUIP33_931067328ED9C6352E1E8EF25122437F17PendingResolution
+ __DATA__TtC14MobileSafariUIP33_931067328ED9C6352E1E8EF25122437F34DefaultForegroundReturnRateLimiter
+ __DATA__TtCE14MobileSafariUICSo32ForegroundReturnAnalyticsTrackerP33_931067328ED9C6352E1E8EF25122437F23DefaultOutcomeScheduler
+ __INSTANCE_METHODS_ForegroundReturnAnalyticsTracker
+ __IVARS_ForegroundReturnAnalyticsTracker
+ __IVARS__TtC14MobileSafariUIP33_931067328ED9C6352E1E8EF25122437F17PendingResolution
+ __IVARS__TtC14MobileSafariUIP33_931067328ED9C6352E1E8EF25122437F34DefaultForegroundReturnRateLimiter
+ __METACLASS_DATA_ForegroundReturnAnalyticsTracker
+ __METACLASS_DATA__TtC14MobileSafariUIP33_931067328ED9C6352E1E8EF25122437F17PendingResolution
+ __METACLASS_DATA__TtC14MobileSafariUIP33_931067328ED9C6352E1E8EF25122437F34DefaultForegroundReturnRateLimiter
+ __METACLASS_DATA__TtCE14MobileSafariUICSo32ForegroundReturnAnalyticsTrackerP33_931067328ED9C6352E1E8EF25122437F23DefaultOutcomeScheduler
+ __PROTOCOLS_ForegroundReturnAnalyticsTracker
+ ___109-[TabController _closeTabs:animated:allowAddingToRecentlyClosedTabs:keepWebViewAlive:showAutoCloseTabsAlert:]_block_invoke_3
+ ___29-[TabController _detachTabs:]_block_invoke
+ ___39-[BrowserController didEnterBackground]_block_invoke_3
+ _symbolic $s14MobileSafariUI19CurrentDateProviderP
+ _symbolic $s14MobileSafariUI28ForegroundReturnEventLoggingP
+ _symbolic $s14MobileSafariUI28ForegroundReturnRateLimitingP
+ _symbolic $sSo32ForegroundReturnAnalyticsTrackerC14MobileSafariUIE17OutcomeSchedulingP
+ _symbolic So32ForegroundReturnAnalyticsTrackerC
+ _symbolic So32ForegroundReturnAnalyticsTrackerCSgXw
+ _symbolic _____ 14MobileSafariUI17PendingResolution33_931067328ED9C6352E1E8EF25122437FLLC
+ _symbolic _____ 14MobileSafariUI26DefaultCurrentDateProvider33_931067328ED9C6352E1E8EF25122437FLLV
+ _symbolic _____ 14MobileSafariUI34DefaultForegroundReturnRateLimiter33_931067328ED9C6352E1E8EF25122437FLLC
+ _symbolic _____ 14MobileSafariUI35DefaultForegroundReturnEventLogging33_931067328ED9C6352E1E8EF25122437FLLV
+ _symbolic _____ 8Dispatch0A8WorkItemC
+ _symbolic _____ So32ForegroundReturnAnalyticsTrackerC14MobileSafariUIE23DefaultOutcomeScheduler33_931067328ED9C6352E1E8EF25122437FLLC
+ _symbolic ______pSg 14MobileSafariUI19CurrentDateProviderP
+ _symbolic ______pSg 14MobileSafariUI28ForegroundReturnEventLoggingP
+ _symbolic ______pSg 14MobileSafariUI28ForegroundReturnRateLimitingP
- -[BrowserController _flushPendingSnapshotsDidComplete]
- -[TabDocument _clearNavigationSource]
- GCC_except_table1436
- GCC_except_table427
- GCC_except_table451
- GCC_except_table479
- GCC_except_table533
- GCC_except_table542
- GCC_except_table565
- GCC_except_table578
- GCC_except_table590
- GCC_except_table602
- GCC_except_table611
- GCC_except_table625
- GCC_except_table657
- GCC_except_table699
- GCC_except_table708
- GCC_except_table763
- GCC_except_table770
- GCC_except_table790
- GCC_except_table816
- GCC_except_table830
- GCC_except_table833
- GCC_except_table840
- GCC_except_table864
- GCC_except_table868
- GCC_except_table872
- GCC_except_table886
- GCC_except_table918
- GCC_except_table923
- GCC_except_table927
- GCC_except_table930
- GCC_except_table965
- ___54-[BrowserController _flushPendingSnapshotsDidComplete]_block_invoke
CStrings:
+ "ForegroundReturnAnalyticsTracker.lastLoggedDate"
```
