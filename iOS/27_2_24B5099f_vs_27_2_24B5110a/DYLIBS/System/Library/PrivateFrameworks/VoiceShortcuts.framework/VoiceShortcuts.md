## VoiceShortcuts

> `/System/Library/PrivateFrameworks/VoiceShortcuts.framework/VoiceShortcuts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xe764` | `0xe94f` | **`+0x1eb`** |
| `__TEXT.__text` | `0x13f44c` | `0x13f328` | **`-0x124`** |
| `__TEXT.__cstring` | `0xe1fc` | `0xe2ba` | **`+0xbe`** |
| `__TEXT.__eh_frame` | `0x8908` | `0x8980` | **`+0x78`** |
| `__AUTH_CONST.__const` | `0xab38` | `0xab88` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x20f8` | `0x20b8` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x4440` | `0x4478` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x4e58` | `0x4e90` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x9d68` | `0x9d98` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1ce8` | `0x1d10` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x534c` | `0x5374` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x315c` | `0x3180` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x3e00` | `0x3e20` | **`+0x20`** |
| `__TEXT.__const` | `0x6c28` | `0x6c48` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x18a0` | `0x1888` | **`-0x18`** |
| `__AUTH.__data` | `0x11f0` | `0x11e0` | **`-0x10`** |
| `__DATA.__data` | `0x2660` | `0x2650` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x2a10` | `0x2a20` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x35b1` | `0x35a1` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x3a0` | `0x3a4` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x74c` | `0x750` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x324` | `0x328` | **`+0x4`** |

### Other Changes

```diff

-5113.0.1.1.1
+5114.0.8.3.0

-  Functions: 8041
-  Symbols:   5268
-  CStrings:  2201
+  Functions: 8053
+  Symbols:   5275
+  CStrings:  2212
Symbols:
+ -[VCCKShortcutSyncService setSyncLogUploadDebouncer:]
+ -[VCCKShortcutSyncService syncLogUploadDebouncer]
+ -[VCCKShortcutSyncService uploadSyncLogsFromDebouncer:]
+ -[WFTriggerNotificationScheduler isHiddenTriggerKey:]
+ GCC_except_table1051
+ GCC_except_table1068
+ GCC_except_table1072
+ GCC_except_table1098
+ GCC_except_table1157
+ GCC_except_table1165
+ GCC_except_table1168
+ GCC_except_table1174
+ GCC_except_table1225
+ GCC_except_table1271
+ GCC_except_table1275
+ GCC_except_table1294
+ GCC_except_table1304
+ GCC_except_table1310
+ GCC_except_table1342
+ GCC_except_table1346
+ GCC_except_table1364
+ GCC_except_table1368
+ GCC_except_table1382
+ GCC_except_table1384
+ GCC_except_table1388
+ GCC_except_table1406
+ GCC_except_table1409
+ GCC_except_table1423
+ GCC_except_table231
+ GCC_except_table303
+ GCC_except_table325
+ GCC_except_table389
+ GCC_except_table411
+ GCC_except_table494
+ GCC_except_table575
+ GCC_except_table576
+ GCC_except_table589
+ GCC_except_table600
+ GCC_except_table629
+ GCC_except_table788
+ GCC_except_table922
+ GCC_except_table948
+ GCC_except_table954
+ GCC_except_table956
+ GCC_except_table974
+ _OBJC_CLASS_$_WFDateComponentsPickerParameter
+ _OBJC_CLASS_$_WFDateComponentsSubstitutableState
+ _OBJC_IVAR_$_VCCKShortcutSyncService._syncLogUploadDebouncer
+ ___55-[VCCKShortcutSyncService uploadSyncLogsFromDebouncer:]_block_invoke
+ ___block_descriptor_40_e8_32s_e20_v20?0B8"NSError"12ls32l8
+ _symbolic _____Sg 10Foundation14DateComponentsV
- GCC_except_table1046
- GCC_except_table1063
- GCC_except_table1067
- GCC_except_table1093
- GCC_except_table1152
- GCC_except_table1158
- GCC_except_table1160
- GCC_except_table1164
- GCC_except_table1220
- GCC_except_table1266
- GCC_except_table1270
- GCC_except_table1284
- GCC_except_table1299
- GCC_except_table1305
- GCC_except_table1337
- GCC_except_table1341
- GCC_except_table1359
- GCC_except_table1363
- GCC_except_table1377
- GCC_except_table1379
- GCC_except_table1383
- GCC_except_table1401
- GCC_except_table1404
- GCC_except_table1418
- GCC_except_table230
- GCC_except_table302
- GCC_except_table324
- GCC_except_table387
- GCC_except_table406
- GCC_except_table489
- GCC_except_table570
- GCC_except_table571
- GCC_except_table584
- GCC_except_table595
- GCC_except_table624
- GCC_except_table783
- GCC_except_table917
- GCC_except_table943
- GCC_except_table949
- GCC_except_table951
- GCC_except_table969
- _OBJC_CLASS_$_WFDateSubstitutableState
- _symbolic _____y_____G s11_SetStorageC 10Foundation8CalendarV9ComponentO
- _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation8CalendarV9ComponentO
CStrings:
+ "%s Could not retire hidden trigger %{public}@ to level Never: %{public}@"
+ "%s Failed to upload sync logs: %{public}@"
+ "%s Hidden trigger %{public}@ fired a background running notification activity; retiring it without posting"
+ "%s No daemon-side handling for action (%{public}@) in category (%{public}@)"
+ "%s Not scheduling background running notification for hidden trigger %{public}@"
+ "%s Skipping registration of hidden trigger %{public}@ for background running notifications"
+ "%s Uploaded sync logs"
+ "-[VCCKShortcutSyncService uploadSyncLogsFromDebouncer:]_block_invoke"
+ "Failed to delete record zone: %@"
+ "Failed to save record zone: %@"
+ "VCCKShortcutSyncService.uploadSyncLogs"
+ "com.apple.shortcuts.VCCKShortcutSyncService.syncLogUpload"
+ "register-triggers-time-change"
- "Failed to delete record zone: %@. %@"
- "Failed to save record zone: %@. %@"
```
