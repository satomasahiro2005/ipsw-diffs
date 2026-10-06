## WiFiAnalytics

> `/System/Library/PrivateFrameworks/WiFiAnalytics.framework/WiFiAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x156090` | `0x156160` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x10690` | `0x106a8` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x11b30` | `0x11b46` | **`+0x16`** |
| `__DATA_CONST.__objc_selrefs` | `0x8ce0` | `0x8cf0` | **`+0x10`** |
| `__DATA.__bss` | `0x1c` | `0x24` | **`+0x8`** |
| `__TEXT.__const` | `0x3d8` | `0x3e0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2a38` | `0x2a30` | **`-0x8`** |
| `__TEXT.__cstring` | `0x14e24` | `0x14e23` | **`-0x1`** |

### Other Changes

```diff

-825.58.0.0.0
+827.3.0.0.0

-  Functions: 6053
-  Symbols:   8840
+  Functions: 6056
+  Symbols:   8844
Symbols:
+ +[WAUtil setSamplingDisabledForTesting:]
+ -[WAEvent caSamplingPercentage]
+ -[WAEventRoamStatus caSamplingPercentage]
+ __samplingDisabledForTesting
Functions:
~ -[WAEvent submitEventToCA] : 140 -> 180
~ +[LinkChangePolicyHandler processJoinEvent:on:] : 2156 -> 2244
+ -[WAEvent eventDate]
~ +[WAUtil canPerformActionWithSamplingPercentage:] : 48 -> 72
+ +[WAUtil setSamplingDisabledForTesting:]
+ -[WAEventRoamStatus caSamplingPercentage]
CStrings:
+ "%{public}s::%d:User manual join ssid = %@ bssid = %@ joinReason = %@ subReason = %@, checking the most recent leave event from ssid = %@, bssid = %@, isLeaveByTD = %@ entity = %@ leaveReason = %@, isLeaveToManualJoinIntervalValid = %@ interval = %@, isLeaveFromSameJoinNetwork = %@, isAlreadyEdgeBSS = %@, neutralize auto-leave decision %@"
+ "WiFiAnalytics-827.3 Sep  4 2026 20:49:43"
- "%{public}s::%d:User manual join ssid = %@ bssid = %@ joinReason = %@ subReason = %@, checking the most recent leave event from ssid = %@, bssid = %@, isLeaveByTD = %@ entity = %@ leaveReason = %@, isLeaveToManualJoinIntervalValid = %@ interval = %@, isLeaveFromSameJoinNetwork = %@, disable isEdgeForLeave decision %@"
- "WiFiAnalytics-825.58 Aug 27 2026 20:48:17"
```
