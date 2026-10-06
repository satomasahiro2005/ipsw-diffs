## wifid

> `/usr/sbin/wifid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c1f4c` | `0x1c3224` | **`+0x12d8`** |
| `__TEXT.__cstring` | `0x75423` | `0x758b2` | **`+0x48f`** |
| `__TEXT.__objc_methname` | `0x1b14f` | `0x1b37f` | **`+0x230`** |
| `__TEXT.__objc_stubs` | `0x14e40` | `0x14fa0` | **`+0x160`** |
| `__DATA_CONST.__cfstring` | `0x1c6a0` | `0x1c7a0` | **`+0x100`** |
| `__DATA.__objc_const` | `0xd390` | `0xd480` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x2904` | `0x29a8` | **`+0xa4`** |
| `__TEXT.__objc_methlist` | `0x6820` | `0x68a0` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x6328` | `0x6390` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x7ba8` | `0x7c00` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x4568` | `0x45a0` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x2bc0` | `0x2bf0` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x15f0` | `0x1608` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x13e0` | `0x13f8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xa14` | `0xa28` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-2027.18.0.0.0
+2027.24.0.0.0

-  Functions: 8785
-  Symbols:   1345
-  CStrings:  17300
+  Functions: 8809
+  Symbols:   1348
+  CStrings:  17347
Symbols:
+ _nw_path_get_status
+ _nw_path_is_constrained
+ _nw_path_is_expensive
CStrings:
+ "%s Suboptimal WiFi but Cell is bad or constrained, overriding TrgDisc decision"
+ "%s: Already associated to CarPlay network, but UUID was %s (%{public}@ -> %{public}@). Registering UUID and replaying link-up event."
+ "%s: NAN realtime mode changed: %d -> %d"
+ "%s: Nan RealTime is active"
+ "%s: Not allowed as nan realtime traffic active"
+ "%s: Not changing AppRoamPolicy due to AWDL/NAN realtime session in progress"
+ "%s: Will not queue NDD request - hosting AWDL/NAN session"
+ "%s: Will not queue scan request - hosting AWDL/NAN session and isLPSCSupported=%d"
+ "%s: action=%d rssi=%d band=%d cell=%lu entryBoost=%d impactBoost=%d waitBoost=%d wait=%.1fs augLQA=%d augReason=0x%x edgeBSS=%d autoLeaveRssi=%d entryThreshold=%d Signals[RnfOff:%s CellBadOrConstrained:%s Exclusion:%s AutoLeave:%s Poor2G:%s Cheap5G:%s CellFair:%s DriveLong:%s RtApp:%s RoamFailNoCand:%s MultiAp:%s CarPlayNet:%s]"
+ "%s: cell score bad / no cell / roaming, promoting WiFi to primary immediately"
+ "%s: could not determine current interface, skipping link-up replay"
+ "%s: hiddenChanged=%d captiveChanged=%d pskToOpen=%d didLowDataModeChanged=%d didWpa3Change=%d addedAtChanged=%d userJoinedAtChanged=%d autoJoinedAtChanged=%d, didPrivacyProxyPreferenceChange=%d didConnectivityAssistPreferenceChange=%d autoJoinChanged=%d"
+ "%s: isAwdlRealTimeModeActive=%d isNanRealTimeModeActive=%d"
+ "%s: restoring previous network to %@"
+ "%s: setting misBand to 2G due to NAN RealTime"
+ "-[WiFiUserInteractionMonitor _initPrivate]_block_invoke_6"
+ "AudioAccessory"
+ "ConnectivityAssistEnabled"
+ "MIGRATION: %s Starting SoftAp on 2.4GHz (RegulatoryRestricted: %d, Infra6G: %d, InfraBWHigherThan80MHz:%d, isChip160MHzCapable:%d, Infra5G_DFS:%d AWDLRealTimeMode:%d NANRealTimeMode:%d)"
+ "Multi channel scan attempt not permitted because AWDL/NAN real time mode is active"
+ "NAN real time mode is active"
+ "Rejecting sensing: AWDLEnabled:%d AssistedDiscHostedNetwork:%d RealTimeMode:%d NANRealTimeMode:%d MISScanBlocked:%d AutoJoinBusy:%d\n"
+ "T@\"NSObject<OS_nw_path_monitor>\",&,N,V_cellPathMonitor"
+ "TB,N,V_nanRealTimeModeActive"
+ "TB,V_cellPathConstrained"
+ "TB,V_cellPathExpensive"
+ "TB,V_cellPathSatisfied"
+ "Unhandled WiFiAwareTerminationReason %d"
+ "WiFiLQAMgrNanRealTimeModeStatus"
+ "WiFiManager-2027.24 Jul 11 2026 04:27:09"
+ "WiFiManager-2027.24 Jul 11 2026 04:27:52"
+ "WiFiNetworkGetConnectivityAssistEnabled"
+ "WiFiNetworkSetConnectivityAssistEnabled"
+ "__WiFiDeviceManagerAwareRealTimeModeUpdatedHandler"
+ "__WiFiManagerCopyCurrentAssociatedInterfaceName"
+ "_cellPathConstrained"
+ "_cellPathExpensive"
+ "_cellPathMonitor"
+ "_cellPathSatisfied"
+ "_nanRealTimeModeActive"
+ "cellPathConstrained"
+ "cellPathExpensive"
+ "cellPathMonitor"
+ "cellPathMonitor create failed"
+ "cellPathMonitor started on internalQueue"
+ "cellPathMonitor update: satisfied=%d constrained=%d expensive=%d"
+ "cellPathSatisfied"
+ "changed"
+ "isCellQualityBadOrConstrained"
+ "isCellQualityBadUnknownOrConstrained"
+ "isCellularDataConstrained"
+ "isConnectivityAssistEnabled"
+ "nanRealTimeModeActive"
+ "not previously registered"
+ "scoreTD_aggressiveTDIndependentOfRnf"
+ "scoreTD_fastTDOneVoteAtBadRSSI"
+ "scoreTD_requiresFgNwApp"
+ "scoreTD_txPerAggressiveAveraging"
+ "scoreTD_txPerMinFrames"
+ "scoreTD_txPerSmoothingAlpha"
+ "scoreTD_waitShortSuppressedOnICGate"
+ "setCellPathConstrained:"
+ "setCellPathExpensive:"
+ "setCellPathMonitor:"
+ "setCellPathSatisfied:"
+ "setConnectivityAssistEnabled:"
+ "setNanRealTimeModeActive:"
- "%s Suboptimal WiFi but Cell is bad or worse overriding TrgDisc decision"
- "%s: Not changing AppRoamPolicy due to AWDL realtime session in progress"
- "%s: Un-registering with coex manager"
- "%s: Will not queue NDD request - hosting AWDL session"
- "%s: Will not queue scan request - hosting AWDL session and isLPSCSupported=%d"
- "%s: action=%d rssi=%d band=%d cell=%lu entryBoost=%d impactBoost=%d waitBoost=%d wait=%.1fs augLQA=%d augReason=0x%x edgeBSS=%d autoLeaveRssi=%d entryThreshold=%d Signals[RnfOff:%s CellBad:%s Exclusion:%s AutoLeave:%s Poor2G:%s Cheap5G:%s CellFair:%s DriveLong:%s RtApp:%s RoamFailNoCand:%s MultiAp:%s CarPlayNet:%s]"
- "%s: cell score bad or no cell, promoting WiFi to primary immediately"
- "%s: hiddenChanged=%d captiveChanged=%d pskToOpen=%d didLowDataModeChanged=%d didWpa3Change=%d addedAtChanged=%d userJoinedAtChanged=%d autoJoinedAtChanged=%d, didPrivacyProxyPreferenceChange=%d autoJoinChanged=%d"
- "%s: isAwdlRealTimeModeActive"
- "-[WiFiUserInteractionMonitor _initPrivate]_block_invoke_3"
- "AudioAccessory1,"
- "AudioAccessory5,"
- "AudioAccessory6,"
- "MIGRATION: %s Starting SoftAp on 2.4GHz (RegulatoryRestricted: %d, Infra6G: %d, InfraBWHigherThan80MHz:%d, isChip160MHzCapable:%d, Infra5G_DFS:%d AWDLRealTimeMode:%d)"
- "Multi channel scan attempt not permitted because AWDL real time mode is active"
- "Rejecting sensing: AWDLEnabled:%d AssistedDiscHostedNetwork:%d RealTimeMode:%d MISScanBlocked:%d AutoJoinBusy:%d\n"
- "WiFiManager-2027.18 Jul  1 2026 23:36:07"
- "WiFiManager-2027.18 Jul  1 2026 23:36:58"
- "isCellScoreBadOrWorse"
- "isCellScoreBadOrWorseOrUnknown"
```
