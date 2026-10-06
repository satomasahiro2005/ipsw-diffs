## CaptiveNetworkSupport

> `/System/Library/SystemConfiguration/CaptiveNetworkSupport.bundle/CaptiveNetworkSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x228e` | `0x2286` | **`-0x8`** |
| `__TEXT.__text` | `0x2ffa8` | `0x2ffa0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x938` | `0x940` | **`+0x8`** |

### Other Changes

```diff

-538.0.0.0.1
+539.0.0.0.0
Functions:
~ _GetUserPreferredSubscriptionContext : 632 -> 628
~ _CopyMobileEquipmentInfo : 1084 -> 1080
~ _WebSheetStateCleanup : 468 -> 464
~ _CNSPreferences : 568 -> 572
~ _copy_network_dict : 900 -> 888
~ _CNSServerConnectionEstablish : 2012 -> 2008
~ _NetIFCopyAllServiceInformation : 324 -> 316
~ _dataCopyHexString : 120 -> 136
~ _CNSServer_server_routine : 64 -> 68
~ _CNSServer_server : 156 -> 160
CStrings:
+ "CaptiveNetworkSupport-539"
- "CaptiveNetworkSupport-538.0.0.0.1"
```
