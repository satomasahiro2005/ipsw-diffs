## WiFiAnalytics

> `/System/Library/PrivateFrameworks/WiFiAnalytics.framework/WiFiAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__common` | `0x11d0` | `0x410` | **`-0xdc0`** |
| `__DATA_DIRTY.__common` | `0x28` | `0xde8` | **`+0xdc0`** |
| `__TEXT.__text` | `0x154f00` | `0x155a10` | **`+0xb10`** |
| `__TEXT.__cstring` | `0x148ee` | `0x14deb` | **`+0x4fd`** |
| `__TEXT.__oslogstring` | `0x11cf5` | `0x119f4` | **`-0x301`** |
| `__AUTH_CONST.__const` | `0x1520` | `0x1280` | **`-0x2a0`** |
| `__AUTH_CONST.__objc_const` | `0x16c20` | `0x16dc0` | **`+0x1a0`** |
| `__DATA_DIRTY.__objc_data` | `0x2a08` | `0x2b48` | **`+0x140`** |
| `__AUTH.__objc_data` | `0x548` | `0x458` | **`-0xf0`** |
| `__TEXT.__objc_methlist` | `0x105e0` | `0x10678` | **`+0x98`** |
| `__DATA_CONST.__objc_selrefs` | `0x8c80` | `0x8cd8` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x2a10` | `0x2a30` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xfdc` | `0xff4` | **`+0x18`** |
| `__DATA.__bss` | `0x28` | `0x1c` | **`-0xc`** |
| `__DATA_CONST.__const` | `0x1f80` | `0x1f88` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7b8` | `0x7c0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x480` | `0x488` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x388` | `0x390` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x160` | `0x168` | **`+0x8`** |

### Other Changes

```diff

-825.53.0.0.0
+825.56.0.0.0

-  Functions: 6038
-  Symbols:   8780
-  CStrings:  4071
+  Functions: 6051
+  Symbols:   8837
+  CStrings:  4075
Symbols:
+ +[WAUtil getMessageInstanceForKey:andGroupType:encodedSizeOut:]
+ -[WAClient _failInvocation:withError:]
+ -[WAModelTemplateLRU .cxx_destruct]
+ -[WAModelTemplateLRU _removeKey:]
+ -[WAModelTemplateLRU budgetEncodedBytes]
+ -[WAModelTemplateLRU entryCount]
+ -[WAModelTemplateLRU evictionCount]
+ -[WAModelTemplateLRU initWithBudgetBytes:]
+ -[WAModelTemplateLRU removeAllObjects]
+ -[WAModelTemplateLRU setTemplate:forKey:encodedSize:]
+ -[WAModelTemplateLRU templateForKey:]
+ -[WAModelTemplateLRU totalEncodedBytes]
+ GCC_except_table109
+ GCC_except_table125
+ GCC_except_table133
+ GCC_except_table136
+ GCC_except_table149
+ GCC_except_table155
+ GCC_except_table162
+ GCC_except_table168
+ GCC_except_table186
+ GCC_except_table192
+ GCC_except_table198
+ GCC_except_table204
+ GCC_except_table210
+ GCC_except_table215
+ GCC_except_table44
+ GCC_except_table46
+ GCC_except_table50
+ GCC_except_table52
+ GCC_except_table54
+ GCC_except_table64
+ GCC_except_table71
+ GCC_except_table77
+ GCC_except_table83
+ GCC_except_table89
+ GCC_except_table95
+ _OBJC_CLASS_$_NSMutableOrderedSet
+ _OBJC_CLASS_$_WAModelTemplateLRU
+ _OBJC_IVAR_$_WAModelTemplateLRU._budgetEncodedBytes
+ _OBJC_IVAR_$_WAModelTemplateLRU._evictionCount
+ _OBJC_IVAR_$_WAModelTemplateLRU._keyToEncodedSize
+ _OBJC_IVAR_$_WAModelTemplateLRU._keyToTemplate
+ _OBJC_IVAR_$_WAModelTemplateLRU._lruOrder
+ _OBJC_IVAR_$_WAModelTemplateLRU._totalEncodedBytes
+ _OBJC_METACLASS_$_WAModelTemplateLRU
+ __OBJC_$_INSTANCE_METHODS_WAModelTemplateLRU
+ __OBJC_$_INSTANCE_VARIABLES_WAModelTemplateLRU
+ __OBJC_$_PROP_LIST_WAModelTemplateLRU
+ __OBJC_CLASS_RO_$_WAModelTemplateLRU
+ __OBJC_METACLASS_RO_$_WAModelTemplateLRU
+ ___101-[WAClient updateRoamPoliciesAndSummarizeAnalyticsForNetwork:maxAgeInDays:andReply:queuedInvocation:]_block_invoke_3
+ ___38-[WAClient _failInvocation:withError:]_block_invoke
+ ___49-[WAClient _killDaemonAndReply:queuedInvocation:]_block_invoke_3
+ ___50-[WAClient _getDpsStatsandReply:queuedInvocation:]_block_invoke_2
+ ___52-[WAClient _getUsageStatsandReply:queuedInvocation:]_block_invoke_2
+ ___56-[WAClient _clearMessageStoreAndReply:queuedInvocation:]_block_invoke_3
+ ___60-[WAClient _registerMessageGroup:andReply:queuedInvocation:]_block_invoke_2
+ ___62-[WAClient _processManagedFault:at:andReply:queuedInvocation:]_block_invoke_2
+ ___63-[WAClient _submitMessage:groupType:andReply:queuedInvocation:]_block_invoke_3
+ ___64-[WAClient _sendMemoryPressureRequestAndReply:queuedInvocation:]_block_invoke_3
+ ___65-[WAClient _triggerQueryForNWActivity:andReply:queuedInvocation:]_block_invoke_2
+ ___68-[WAClient _getMessagesModelForGroupType:andReply:queuedInvocation:]_block_invoke_3
+ ___68-[WAClient _signalPotentialNewIORChannelsAndReply:queuedInvocation:]_block_invoke_2
+ ___70-[WAClient _getDeviceAnalyticsConfigurationAndReply:queuedInvocation:]_block_invoke_2
+ ___70-[WAClient _issueIOReportManagementCommand:andReply:queuedInvocation:]_block_invoke_2
+ ___71-[WAClient _setDeviceAnalyticsConfiguration:andReply:queuedInvocation:]_block_invoke_3
+ ___74-[WAClient _triggerQueryForNWActivityWithPeers:andReply:queuedInvocation:]_block_invoke_2
+ ___75-[WAClient _triggerDeviceAnalyticsStoreMigrationAndReply:queuedInvocation:]_block_invoke_2
+ ___78-[WAClient _getNewMessageForKey:groupType:withCopy:andReply:queuedInvocation:]_block_invoke_3
+ ___80-[WAClient _lqmCrashTracerNotifyForInterfaceWithName:andReply:queuedInvocation:]_block_invoke_3
+ ___87-[WAClient _lqmCrashTracerReceiveBlock:forInterfaceWithName:andReply:queuedInvocation:]_block_invoke_3
+ ___88-[WAClient _trapCrashMiniTracerDumpReadyForInterfaceWithName:andReply:queuedInvocation:]_block_invoke_3
+ ___91-[WAClient _updateRoamPoliciesForSourceBssid:andUpdateRoamCache:andReply:queuedInvocation:]_block_invoke_2
+ ___93-[WAClient _triggerDatapathDiagnosticsAndCollectUpdates:waMessage:andReply:queuedInvocation:]_block_invoke_2
+ ___95-[WAClient convertWiFiStatsIntoPercentile:analysisGroup:groupTarget:andReply:queuedInvocation:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
- GCC_except_table105
- GCC_except_table114
- GCC_except_table119
- GCC_except_table127
- GCC_except_table132
- GCC_except_table141
- GCC_except_table147
- GCC_except_table153
- GCC_except_table160
- GCC_except_table166
- GCC_except_table172
- GCC_except_table184
- GCC_except_table190
- GCC_except_table196
- GCC_except_table202
- GCC_except_table208
- GCC_except_table213
- GCC_except_table75
- GCC_except_table81
- ___block_descriptor_32_e17_v16?0"NSError"8l
CStrings:
+ "%{public}s::%d:Evicted template key=%@ encodedBytes=%lu (totalAfter=%lu, budget=%lu)"
+ "%{public}s::%d:WAModelTemplateLRU: accounting drift detected, totalBytes=%lu < entrySize=%lu for key=%@"
+ "%{public}s::%d:XPC: WAClient - %@ - error: %@"
+ "+[WAUtil getMessageInstanceForKey:andGroupType:encodedSizeOut:]"
+ "-[WAClient _failInvocation:withError:]"
+ "-[WAClient _getDeviceAnalyticsConfigurationAndReply:queuedInvocation:]_block_invoke_2"
+ "-[WAClient _getDpsStatsandReply:queuedInvocation:]_block_invoke_2"
+ "-[WAClient _getUsageStatsandReply:queuedInvocation:]_block_invoke_2"
+ "-[WAClient _issueIOReportManagementCommand:andReply:queuedInvocation:]_block_invoke_2"
+ "-[WAClient _processManagedFault:at:andReply:queuedInvocation:]_block_invoke_2"
+ "-[WAClient _registerMessageGroup:andReply:queuedInvocation:]_block_invoke_2"
+ "-[WAClient _signalPotentialNewIORChannelsAndReply:queuedInvocation:]_block_invoke_2"
+ "-[WAClient _triggerDatapathDiagnosticsAndCollectUpdates:waMessage:andReply:queuedInvocation:]_block_invoke_2"
+ "-[WAClient _triggerDeviceAnalyticsStoreMigrationAndReply:queuedInvocation:]_block_invoke_2"
+ "-[WAClient _triggerQueryForNWActivity:andReply:queuedInvocation:]_block_invoke_2"
+ "-[WAClient _triggerQueryForNWActivityWithPeers:andReply:queuedInvocation:]_block_invoke_2"
+ "-[WAClient _updateRoamPoliciesForSourceBssid:andUpdateRoamCache:andReply:queuedInvocation:]_block_invoke_2"
+ "-[WAClient convertWiFiStatsIntoPercentile:analysisGroup:groupTarget:andReply:queuedInvocation:]_block_invoke_2"
+ "-[WAModelTemplateLRU _removeKey:]"
+ "-[WAModelTemplateLRU setTemplate:forKey:encodedSize:]"
+ "WiFiAnalytics-825.56 Jul  1 2026 23:27:25"
- "%{public}s::%d:XPC: WAClient - _issueIOReportManagementCommand - error: %@"
- "%{public}s::%d:XPC: WAClient - _sendMemoryPressureRequestAndReply - error: %@"
- "%{public}s::%d:XPC: WAClient - clearMessageStoreAndReply - error: %@"
- "%{public}s::%d:XPC: WAClient - error: %@"
- "%{public}s::%d:XPC: WAClient - getDeviceAnalyticsConfigurationAndReply - error: %@"
- "%{public}s::%d:XPC: WAClient - getDpsStatsandReply - error: %@"
- "%{public}s::%d:XPC: WAClient - getMessagesModelAndReply - error: %@"
- "%{public}s::%d:XPC: WAClient - getNewMessageForKey - error: %@"
- "%{public}s::%d:XPC: WAClient - killDaemonAndReply - error: %@"
- "%{public}s::%d:XPC: WAClient - lqmCrashTracerNotify - error: %@"
- "%{public}s::%d:XPC: WAClient - lqmCrashTracerReceiveBlock - error: %@"
- "%{public}s::%d:XPC: WAClient - registerMessageGroup - error: %@"
- "%{public}s::%d:XPC: WAClient - setDeviceAnalyticsConfiguration - error: %@"
- "%{public}s::%d:XPC: WAClient - submitMessage - error: %@"
- "%{public}s::%d:XPC: WAClient - trapCrashMiniTracerDumpReady - error: %@"
- "+[WAUtil getMessageInstanceForKey:andGroupType:]"
- "WiFiAnalytics-825.53 Jun 16 2026 21:43:37"
```
