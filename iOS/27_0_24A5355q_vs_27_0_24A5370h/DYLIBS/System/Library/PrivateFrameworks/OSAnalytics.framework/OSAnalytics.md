## OSAnalytics

> `/System/Library/PrivateFrameworks/OSAnalytics.framework/OSAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4af4c` | `0x4b01c` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0xdf0` | `0xdf8` | **`+0x8`** |

### Other Changes

```diff

-1049.0.0.502.1
+1056.0.3.0.0
Functions:
~ _ns2xpc : 936 -> 928
~ ___OSASanitizePath_block_invoke.47 : 1728 -> 1724
~ _OSASanitizePath : 2480 -> 2476
~ -[OSAJetsamReport acquireJetsamDataWithFlags:] : 996 -> 952
~ -[OSABinaryImageCatalog reportUsedImagesFullInfoUsingBlock:] : 376 -> 372
~ -[OSAReport saveWithOptions:] : 1160 -> 1156
~ -[OSAJetsamReport fetchWiredMemoryInfo] : 1172 -> 1192
~ -[NSMutableDictionary(OSALogTrackerExtension) osa_logTracker_isLog:byKey:count:withinLimit:withOptions:errorDescription:] : 2196 -> 2204
~ ___49+[OSAReport findBundleAtPath:withKeys:bundleURL:]_block_invoke_2 : 1032 -> 1024
~ -[OSAReport getSyslogForPids:andOptionalSenders:additionalPredicates:] : 2284 -> 2276
~ ___openR3_block_invoke : 1192 -> 1188
~ __WriteStackshotReport : 840 -> 836
~ __WriteCrashReportWithStackshot : 688 -> 684
~ _WriteSystemMemoryResetReportWithPids : 340 -> 348
~ -[OSAStackShotReport acquireStackshot] : 1264 -> 1272
~ -[OSAStackShotReport exceptionCodesDescription] : 264 -> 260
~ -[OSAStackShotReport decodeKCDataWithBlock:withTuning:usingCatalog:] : 18620 -> 19148
~ _DecodeThreadFlags : 392 -> 368
~ +[OSATasking normalizeInstructions:forSamplingKey:] : 464 -> 460
~ +[OSATasking preference:alreadySetInInstructions:] : 536 -> 524
~ -[OSAOsLogPackParser filterOutSensitiveParts:withFormats:] : 616 -> 612
~ -[OSAOsLogPackParser compose:] : 392 -> 388
~ -[OSAOsLogPackParser extractArguments:] : 404 -> 400
~ -[OSAJetsamReport instrumentEvents:] : 1460 -> 1452
~ -[OSAJetsamReport generateLogAtLevel:withBlock:] : 4916 -> 4832
~ ___37-[OSASystemConfiguration internalKey]_block_invoke.385 : 1372 -> 1368
~ _OSASyncCrashReporter : 952 -> 948
~ _getVolumes : 308 -> 324
~ -[OSALog initWithPath:forRouting:usingConfig:options:error:] : 2860 -> 2856
~ +[OSALog cleanupForUser:] : 856 -> 848
~ +[OSALog scanLogs:from:options:] : 2332 -> 2316
~ ___32+[OSALog scanLogs:from:options:]_block_invoke : 680 -> 676
~ +[OSALog iterateLogsWithOptions:usingBlock:] : 1632 -> 1628
~ +[OSALog createRetiredDirectoriesForUser:] : 804 -> 796
~ +[OSAStateMonitor checkAndReportCALogStates] : 676 -> 660
~ +[OSAStateMonitor processCALogEvent:eventPayload:into:] : 2744 -> 2720
~ +[OSAStateMonitor evaluateCALogStates:] : 1940 -> 1932
~ -[OSABinaryImageCatalog setRootedCacheLibs:count:] : 152 -> 168
~ -[OSABinaryImageCatalog reportUsedImages] : 332 -> 328
~ -[OSAExclaveContainer getFramesForThread:usingCatalog:] : 1308 -> 1304
~ -[OSALegacyXform formatCallstacks:withImages:macosStyle:] : 1704 -> 1712
~ -[OSALegacyXform formatImages:macosStyle:] : 1020 -> 1028
~ -[OSALegacyXform formatLastException:withImages:] : 440 -> 436
~ -[OSALegacyXform _hexDump:offset:indicator:] : 556 -> 572
~ -[OSALegacyXform _getValueForKey:fromBody:orHeader:] : 700 -> 704
~ -[OSALegacyXform transformLines:withDefinitions:body:header:error:streamingBlock:] : 1900 -> 1896
~ ___82-[OSALegacyXform transformLines:withDefinitions:body:header:error:streamingBlock:]_block_invoke : 2576 -> 2564
~ +[OSALegacyXform rollSchemaForward:] : 3396 -> 3384
~ ____CRGetAnonHostUUID_block_invoke : 1508 -> 1516
~ ___rtc_internal_block_invoke.62 : 1620 -> 1616
~ sub_1ad28c8f4 -> sub_1ad6b39f8 : 784 -> 788
~ sub_1ad28d83c -> sub_1ad6b4944 : 2660 -> 2648
~ sub_1ad28e6a8 -> sub_1ad6b57a4 : 1576 -> 1588
~ sub_1ad28f978 -> sub_1ad6b6a80 : 112 -> 108
~ sub_1ad28f9e8 -> sub_1ad6b6aec : 944 -> 908
~ sub_1ad290228 -> sub_1ad6b7308 : 280 -> 276
~ sub_1ad290798 -> sub_1ad6b7874 : 692 -> 684
~ sub_1ad290a4c -> sub_1ad6b7b20 : 376 -> 372
~ sub_1ad292204 -> sub_1ad6b92d4 : 528 -> 532
~ sub_1ad293480 -> sub_1ad6ba554 : 692 -> 688
```
