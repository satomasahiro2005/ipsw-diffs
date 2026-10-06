## ConditionInducer

> `/System/Library/PrivateFrameworks/ConditionInducer.framework/ConditionInducer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11818` | `0x117f4` | **`-0x24`** |

### Other Changes

```diff

-237.0.0.0.0
+250.0.0.0.0
Functions:
~ -[COConditionTask launchTask:] : 1596 -> 1584
~ _safeRemoveItemAtPathWithRegex : 744 -> 740
~ -[COStatusBar doTeardownOnStop] : 472 -> 468
~ +[COConditionSession _loadExternalConditionBundleInfo:supportedConditionData:error:] : 1460 -> 1456
~ +[COConditionSession getBundleURLsAtPath:] : 476 -> 472
~ +[COConditionSession bundleToDict:] : 1136 -> 1132
~ -[COConditionSession _setupBundleAtPath:withError:] : 828 -> 824
~ +[COConditionSession removeStaleConditions:] : 624 -> 612
~ +[COConditionSession listAvailableConditions] : 908 -> 900
~ -[COConditionSession startConditionWithCallback:teardownStartedCallback:teardownFinishedCallback:] : 2248 -> 2244
~ +[COConditionSession tearDownAllConditionsWithErrors:] : 1180 -> 1176
~ -[COConditionBundle conditions] : 604 -> 600
~ -[COConditionBundle isRunnable:] : 948 -> 944
~ -[ApplePMPPerfStateControl _enableConsistentPerfState:] : 556 -> 576
~ -[ApplePMPPerfStateControl _disableConsistentPerfState] : 516 -> 524
~ -[ApplePMPPerfStateControl .cxx_destruct] : 60 -> 68
```
