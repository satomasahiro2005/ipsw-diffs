## MobileAssetDaemon

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/MobileAssetDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x261884` | `0x262998` | **`+0x1114`** |
| `__TEXT.__oslogstring` | `0x5e40d` | `0x5e7cd` | **`+0x3c0`** |
| `__AUTH_CONST.__objc_const` | `0x18ed0` | `0x18f30` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x12c04` | `0x12c54` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xaec0` | `0xaf08` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x32820` | `0x32860` | **`+0x40`** |
| `__DATA_CONST.__objc_arraydata` | `0xec0` | `0xef8` | **`+0x38`** |
| `__TEXT.__cstring` | `0x3f146` | `0x3f116` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x1040` | `0x1060` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1210` | `0x1228` | **`+0x18`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x330` | `0x348` | **`+0x18`** |
| `__DATA.__bss` | `0x550` | `0x560` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xda84` | `0xda74` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x4818` | `0x4828` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1810` | `0x1818` | **`+0x8`** |

### Other Changes

```diff

-2215.0.13.0.0
+2215.0.16.0.0

-  Functions: 7268
-  Symbols:   11412
-  CStrings:  10947
+  Functions: 7280
+  Symbols:   11431
+  CStrings:  10960
Symbols:
+ +[DownloadManager getAssetAudienceForPalletUpdateMode:]
+ +[DownloadManager getPallasServerURLForPalletUpdateMode:]
+ -[DownloadManager syncSplunkTasksWithRetryCount:]
+ -[MADAnalyticsManager _sendViaSessionIfApplicable:assetType:]
+ -[MADAnalyticsManager activeSessionId]
+ -[MADAnalyticsManager isGMSRelevantAssetType:]
+ -[MADAnalyticsManager sessionQueue]
+ -[MADAnalyticsManager setActiveSessionId:]
+ -[MADAnalyticsManager setSessionQueue:]
+ -[MADAutoAssetControlManager _logSetConfigurationEntries:forSetConfiguration:issuingDebugLog:]
+ GCC_except_table156
+ GCC_except_table173
+ GCC_except_table175
+ _AnalyticsCreateSession
+ _AnalyticsEndSession
+ _AnalyticsSendEventWithSession
+ _OBJC_IVAR_$_MADAnalyticsManager._activeSessionId
+ _OBJC_IVAR_$_MADAnalyticsManager._sessionQueue
+ ___46-[MADAnalyticsManager isGMSRelevantAssetType:]_block_invoke
+ ___49-[DownloadManager syncSplunkTasksWithRetryCount:]_block_invoke
+ ___49-[DownloadManager syncSplunkTasksWithRetryCount:]_block_invoke_2
+ ___61-[MADAnalyticsManager _sendViaSessionIfApplicable:assetType:]_block_invoke
+ _isGMSRelevantAssetType:.onceToken
+ _isGMSRelevantAssetType:.types
- +[MADAutoAssetStager controlAlteredSetConfiguration:]
- -[MADAutoAssetControlManager _logSetConfigurationEntries:forSetConfiguration:]
- -[MADAutoAssetStager action_AlteredDecideSameSetConfiguration:error:]
- ___34-[DownloadManager syncSplunkTasks]_block_invoke
- ___34-[DownloadManager syncSplunkTasks]_block_invoke_2
CStrings:
+ "\n[AUTO-SECURE][AUTO-PERSONALIZATION-GRAFT-SET] {%{public}@} Recorded locker file for asset being grafted | BundlePath:%{public}@ | LockerPath:%{public}@"
+ "\n[AUTO-SECURE][AUTO-PERSONALIZATION-GRAFT-SET] {%{public}@} Unable to determine locker file path for secure asset | BundlePath:%{public}@"
+ "%{public}@ {%{public}@}\n[CALCULATE_DOWNLOAD_SPACE] total required space for downloading set | totalRequiredSpace:%lld bytes | finalDownloadPolicy:%d | totalExpectedBytes:%ld | expectedTimeRemainingSecs:%ld | remainingAssetCount:%ld"
+ "Failed to fetch Pallas URL for pallet update mode | error:%{public}@"
+ "Failed to fetch audience for pallet update mode | error:%{public}@"
+ "Loaded built-in MobileAssetDaemon_Framework Jul 11 2026 05:39:25"
+ "Max retries exhausted. Giving up on state sync"
+ "Overriding config for pallet update mode | AssetAudience:%{public}@"
+ "Pallet mode override"
+ "Retrying sync of splunk state"
+ "Splunk session object not yet set up. Defering state sync"
+ "Successful"
+ "UAF.FM.Overrides"
+ "UAF.FM.Visual"
+ "[AUTO-SECURE][AUTO-GRAFT] Recorded locker file for asset being grafted | BundlePath:%{public}@ | LockerPath:%{public}@"
+ "[AUTO-SECURE][AUTO-GRAFT]: Asset being grafted has no locker file | BundlePath:%{public}@"
+ "[CoreAnalytics-Session] AnalyticsCreateSession returned nil"
+ "[CoreAnalytics-Session] Ended session: %{public}@"
+ "[CoreAnalytics-Session] Started session: %{public}@"
+ "[PallasNonce:%{public}@] Pallas JWS parsing did not yield 3 elements, elements: %lu"
+ "com.apple.mobileassetd.analyticsSessionQueue"
+ "if.planner"
+ "if.planner.overrides"
+ "modelcatalog"
+ "siri.understanding"
+ "siri.understanding.nl.overrides"
- "%{public}@ {%{public}@}\n[CALCULATE_DOWNLOAD_SPACE] total required space for downloading set | totalRequiredSpace:%lld bytes | finalDownloadPolicy:%d"
- "AlteredDecideSameSetConfiguration"
- "ClientAlteredForgetDetermine"
- "ControlAlteredSetConfiguration"
- "Customer In-Box-Updater"
- "Internal In-Box-Updater"
- "Loaded built-in MobileAssetDaemon_Framework Jun 27 2026 04:21:22"
- "MADStager:AlteredDecideSameSetConfiguration"
- "[PallasNonce:%{public}@] Pallas JWS parsing did not yield 3 elements, elements: %lu bytes: %{public}@"
- "cd060049-2465-43e3-bbb5-d769a66da2d7"
- "ffc25f86-b83c-4139-b8ad-91131d0e5429"
- "https://gdmf-auth-stg.apple.com/v2/assets"
- "{controlAlteredSetConfiguration} failed to locate shared AutoAssetStager"
```
