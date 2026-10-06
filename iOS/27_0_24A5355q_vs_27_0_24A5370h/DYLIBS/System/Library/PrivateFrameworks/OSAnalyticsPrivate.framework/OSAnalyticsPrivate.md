## OSAnalyticsPrivate

> `/System/Library/PrivateFrameworks/OSAnalyticsPrivate.framework/OSAnalyticsPrivate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a968` | `0x1a8f8` | **`-0x70`** |

### Other Changes

```diff

-1049.0.0.502.1
+1056.0.3.0.0
Functions:
~ -[OSASubmissionPolicy init] : 608 -> 604
~ -[OSASubmissionPolicy buildSubmissionTemplateForConfig:] : 988 -> 984
~ -[OSASubmitter processSubmissionJobs:usingConfig:summarize:] : 3100 -> 3088
~ -[OSASubmitter processJob:forRouting:including:usingConfig:taskings:summarize:additionalRequestHeaders:] : 5864 -> 5844
~ -[OSASubmitter submitLogsUsingPolicy:resultsCallback:] : 4172 -> 4152
~ +[OSASubmitter submissionPathsWithHomeDirectory:withProxies:] : 600 -> 596
~ -[OSADeviceRecoveryEnvHelper overrideMountPath:] : 388 -> 384
~ -[OSADeviceRecoveryEnvHelper releaseSandboxExtensions] : 412 -> 408
~ -[OSAHttpSubmitter postContent:withHeaders:toEndpoint:] : 968 -> 964
~ -[PCCIDSEndpoint deviceIds] : 2340 -> 2344
~ -[PCCIDSEndpoint isDeviceNearby:] : 392 -> 388
~ -[PCCBridgeEndpoint dealloc] : 532 -> 528
~ -[PCCBridgeEndpoint deviceIds] : 656 -> 652
~ -[PCCJob packageLog:forRouting:info:options:] : 1540 -> 1548
~ -[PCCProxiedDevice generateLogList:] : 1160 -> 1156
~ ___30-[PCCProxiedDevice startTimer]_block_invoke_2 : 816 -> 804
~ -[PCCProxyingDevice handleFile:from:metadata:] : 3752 -> 3744
~ -[PCCProxyingDevice updateProxiedDeviceMetadata:from:] : 1700 -> 1696
~ ___31-[PCCProxyingDevice startTimer]_block_invoke_2 : 740 -> 736
~ sub_28dda25a0 -> sub_28f111534 : 280 -> 276
```
