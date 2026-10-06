## ARKitDaemon

> `/System/Library/PrivateFrameworks/ARKitDaemon.framework/ARKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe078` | `0xe050` | **`-0x28`** |

### Other Changes

```diff

-779.0.0.0.5
+781.0.1.0.4
Functions:
~ -[ARDaemon printInfo] : 596 -> 592
~ ___92-[ARDaemonServiceListener initWithDelegate:watchdogMonitor:isInProcess:serviceRestrictions:]_block_invoke : 372 -> 368
~ -[ARDaemonServiceListener listener:shouldAcceptNewConnection:] : 1124 -> 1120
~ -[ARGeoTrackingTechniqueService technique:didOutputResultData:timestamp:context:] : 1072 -> 1056
~ -[ARServer _addServices:] : 1756 -> 1752
~ -[ARServer commitServices:] : 744 -> 740
~ -[ARServer _updateAlgorithmConfigurationWithServices:] : 608 -> 604
```
