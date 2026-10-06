## TrialServer

> `/System/Library/PrivateFrameworks/TrialServer.framework/TrialServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1518d4` | `0x152b1c` | **`+0x1248`** |
| `__TEXT.__cstring` | `0x16925` | `0x16ae5` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0x1def5` | `0x1e09f` | **`+0x1aa`** |
| `__AUTH_CONST.__cfstring` | `0xee80` | `0xf020` | **`+0x1a0`** |
| `__TEXT.__objc_methlist` | `0xc7ac` | `0xc86c` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x6938` | `0x69e8` | **`+0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x182e0` | `0x18348` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x6570` | `0x65d8` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x43a8` | `0x4400` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x7f28` | `0x7f74` | **`+0x4c`** |
| `__DATA_CONST.__objc_arraydata` | `0x388` | `0x398` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x968` | `0x970` | **`+0x8`** |
| `__TEXT.__const` | `0xeec` | `0xef4` | **`+0x8`** |

### Other Changes

```diff

-511.0.0.0.0
+511.1.2.0.0

-  Functions: 4979
-  Symbols:   9387
-  CStrings:  4227
+  Functions: 4999
+  Symbols:   9422
+  CStrings:  4253
Symbols:
+ -[TRIDServer _handlePowerlogTaskingNotificationWithContext:]
+ -[TRIExternalParameterManager _fetchSafariSearchEngine]
+ -[TRIExternalParameterManager _loadGuardedDataFromCachedDictionary:]
+ -[TRIExternalParameterManager _processSafariSearchEngineBiomeEvent:streamError:]
+ -[TRIExternalParameterManager _subscribeToSafariSearchEngineUpdate]
+ -[TRIExternalParameterManager safariSearchEngine]
+ -[TRIPersistentUserSettings persistActivePowerlogTaskRequestNames:]
+ -[TRIPersistentUserSettings persistedActivePowerlogTaskRequestNames]
+ -[TRISystemConfiguration safariSearchEngine]
+ -[TRISystemConfiguration(Server) activePowerlogTaskRequestNames]
+ -[TRISystemConfiguration(Server) lastPowerlogUploadDate]
+ -[TRISystemInfo _getSafariSearchEngine]
+ -[TRISystemInfo safariSearchEngine]
+ -[TRISystemInfo setSafariSearchEngine:]
+ OBJC_IVAR_$_TRIExternalParameterGuardedData.guardedSafariSearchEngine
+ _CFStringCreateWithCString
+ _OBJC_IVAR_$_TRISystemInfo._safariSearchEngine
+ _TRIPersistentActivePowerlogTaskRequestNames
+ _TRISystemCovariate_ActivePowerlogTaskRequestNames
+ _TRISystemCovariate_DaysSinceLastPowerlogUpload
+ _TRISystemCovariate_SafariSearchEngine
+ __CFPreferencesAppSynchronizeWithContainer
+ __CFPreferencesCopyAppValueWithContainer
+ ___49-[TRIExternalParameterManager safariSearchEngine]_block_invoke
+ ___55-[TRIExternalParameterManager _fetchSafariSearchEngine]_block_invoke
+ ___67-[TRIExternalParameterManager _subscribeToSafariSearchEngineUpdate]_block_invoke
+ ___68-[TRIExternalParameterManager _loadGuardedDataFromCachedDictionary:]_block_invoke
+ ___80-[TRIExternalParameterManager _processSafariSearchEngineBiomeEvent:streamError:]_block_invoke
+ ___block_descriptor_40_e8_32w_e34_v24?0"NSDictionary"8"NSError"16lw32l8
+ ___block_descriptor_48_e8_32s40r_e41_v16?0"TRIExternalParameterGuardedData"8ls32l8r40l8
+ ___block_descriptor_48_e8_32s40s_e15_"NSString"8?0ls32l8s40l8
+ __powerlogSetting
+ _container_system_group_path_for_identifier
+ _kPowerlogLastUploadDateKey
+ _kPowerlogPreferenceDomain
+ _kPowerlogTaskingRequestsKey
- ___54-[TRIExternalParameterManager initWithProvider:paths:]_block_invoke
CStrings:
+ "-[TRIDServer _handlePowerlogTaskingNotificationWithContext:]"
+ "@\"NSString\"8@?0"
+ "ActivePowerlogTaskRequestNames"
+ "DaysSinceLastPowerlogUpload"
+ "Empty event for %@"
+ "Error reading %@ data stream: %{public}@"
+ "External parameter changed, sending SystemInfo update notification."
+ "Failed to look up %{public}s container, error %llu"
+ "Invalid type for %@ event: %{public}@"
+ "PLLastUploadDate"
+ "PLTaskingRequests"
+ "Powerlog tasking notification relevancy: %d"
+ "Reading SafariSearchEngine from Biome."
+ "Safari.SearchEngine"
+ "SafariSearchEngine"
+ "Sep  4 2026"
+ "Subscribing to SafariSearchEngine changes from Biome."
+ "TaskedOTA"
+ "TrialXP-511.1.2"
+ "Updaing Safari.SearchEngine to %{public}@"
+ "Update event received for %@."
+ "com.apple.powerlog.tasking_completed"
+ "com.apple.powerlog.tasking_received"
+ "com.apple.powerlogd"
+ "com.apple.triald.persisted.activePowerlogTaskRequestNames"
+ "safariSearchEngine"
+ "searchEngineIdentifier"
+ "systemgroup.com.apple.powerlog"
- "Aug  8 2026"
- "TrialXP-511"
```
