## ScreenTimeCore

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe58e0` | `0xe6444` | **`+0xb64`** |
| `__TEXT.__oslogstring` | `0xb3ba` | `0xb43a` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1bf0` | `0x1c40` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x9ba0` | `0x9bf0` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x1b8c` | `0x1bcc` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x12928` | `0x12958` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x6ce` | `0x6fe` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x51b0` | `0x51d8` | **`+0x28`** |
| `__TEXT.__const` | `0x2ec8` | `0x2ee8` | **`+0x20`** |
| `__TEXT.__cstring` | `0xa14c` | `0xa15c` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x8d4` | `0x8e0` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x10ce` | `0x10d8` | **`+0xa`** |
| `__AUTH.__objc_data` | `0x3c50` | `0x3c58` | **`+0x8`** |
| `__DATA.__data` | `0x1f38` | `0x1f40` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3998` | `0x3990` | **`-0x8`** |

### Other Changes

```diff

-637.0.102.0.0
+640.0.100.0.0

-  Functions: 5471
-  Symbols:   6556
-  CStrings:  2195
+  Functions: 5481
+  Symbols:   6565
+  CStrings:  2196
Symbols:
+ -[STAppInfoCache _appInfoForBundleIdentifier:localOnly:usingFetcher:]
+ -[STAppInfoCache _appInfoForBundleIdentifier:usingFetcher:]
+ -[STAppInfoCache _fetchSyncedInstalledAppInfoForBundleIdentifier:usingFetcher:]
+ -[STAppInfoCache appInfoForBundleIdentifier:usingFetcher:]
+ -[STManagementState enableRemoteManagementForDSID:completionHandler:]
+ -[STManagementState setCommunicationSafetyEnabled:completionHandler:]
+ -[STManagementState setWebFilterState:completionHandler:]
+ GCC_except_table100
+ GCC_except_table124
+ GCC_except_table127
+ GCC_except_table130
+ GCC_except_table133
+ GCC_except_table142
+ GCC_except_table145
+ GCC_except_table148
+ GCC_except_table151
+ GCC_except_table154
+ GCC_except_table183
+ GCC_except_table186
+ GCC_except_table195
+ GCC_except_table198
+ GCC_except_table204
+ GCC_except_table37
+ GCC_except_table49
+ GCC_except_table62
+ GCC_except_table66
+ ___57-[STManagementState setWebFilterState:completionHandler:]_block_invoke
+ ___57-[STManagementState setWebFilterState:completionHandler:]_block_invoke_2
+ ___69-[STAppInfoCache _appInfoForBundleIdentifier:localOnly:usingFetcher:]_block_invoke
+ ___69-[STManagementState enableRemoteManagementForDSID:completionHandler:]_block_invoke
+ ___69-[STManagementState enableRemoteManagementForDSID:completionHandler:]_block_invoke_2
+ ___69-[STManagementState enableRemoteManagementForDSID:completionHandler:]_block_invoke_3
+ ___69-[STManagementState enableRemoteManagementForDSID:completionHandler:]_block_invoke_4
+ ___69-[STManagementState setCommunicationSafetyEnabled:completionHandler:]_block_invoke
+ ___69-[STManagementState setCommunicationSafetyEnabled:completionHandler:]_block_invoke_2
+ ___79-[STAppInfoCache _fetchSyncedInstalledAppInfoForBundleIdentifier:usingFetcher:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
+ ___block_descriptor_57_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
+ _symbolic SaySSGSSc
- -[STAppInfoCache _appInfoForBundleIdentifier:]
- -[STAppInfoCache _fetchSyncedInstalledAppInfoForBundleIdentifier:]
- GCC_except_table122
- GCC_except_table125
- GCC_except_table128
- GCC_except_table131
- GCC_except_table140
- GCC_except_table143
- GCC_except_table146
- GCC_except_table149
- GCC_except_table152
- GCC_except_table181
- GCC_except_table184
- GCC_except_table193
- GCC_except_table196
- GCC_except_table202
- GCC_except_table50
- GCC_except_table69
- ___47-[STManagementState isRestrictionsPasscodeSet:]_block_invoke_2
- ___55-[STAppInfoCache appInfoForBundleIdentifier:localOnly:]_block_invoke
- ___58-[STManagementState screenTimeStateWithCompletionHandler:]_block_invoke_4
- ___60-[STManagementState setScreenTimeEnabled:completionHandler:]_block_invoke_4
- ___62-[STManagementState screenTimeSyncStateWithCompletionHandler:]_block_invoke_4
- ___64-[STManagementState communicationPoliciesWithCompletionHandler:]_block_invoke_4
- ___66-[STAppInfoCache _fetchSyncedInstalledAppInfoForBundleIdentifier:]_block_invoke
- ___67-[STManagementState setScreenTimeSyncingEnabled:completionHandler:]_block_invoke_4
- ___72-[STManagementState authenticateRestrictionsPasscode:completionHandler:]_block_invoke_4
- ___73-[STManagementState isAppAndWebsiteActivityEnabledWithCompletionHandler:]_block_invoke_4
- ___89-[STManagementState disableAppAndWebsiteActivityDueToThirdPartyAppWithCompletionHandler:]_block_invoke_4
- ___94-[STManagementState restrictionsPasscodeEntryAttemptCountAndTimeoutDateWithCompletionHandler:]_block_invoke_5
CStrings:
+ "    Using equivalent installed app as metadata source for:%{private}s. Equivalent installed app bundle ID: %{private}s"
+ "-[STAppInfoCache _appInfoForBundleIdentifier:usingFetcher:]"
+ "-[STAppInfoCache _fetchSyncedInstalledAppInfoForBundleIdentifier:usingFetcher:]_block_invoke"
- "-[STAppInfoCache _appInfoForBundleIdentifier:]"
- "-[STAppInfoCache _fetchSyncedInstalledAppInfoForBundleIdentifier:]_block_invoke"
```
