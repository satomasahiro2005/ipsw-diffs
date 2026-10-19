## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/AirPlayReceiver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17ccb4` | `0x17ce2c` | **`+0x178`** |
| `__AUTH_CONST.__auth_got` | `0x1e38` | `0x1e58` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0xba80` | `0xbaa0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x33395` | `0x33399` | **`+0x4`** |

### Other Changes

```diff

-  Symbols:   3606
-  CStrings:  5207
+  Symbols:   3610
+  CStrings:  5208
Symbols:
+ _APSGetClusterMemberIDForSurroundRole
+ _APSGetSurroundRoleFromClusterSummary
+ _APSIsHomeTheaterSurroundEnabled
+ _APSSurroundToOdeonFallbackEnabled
Functions:
~ ____IsWiFiDECaptureAllowed_block_invoke : 36 -> 40
~ _sysInfo_updatePrefs : 5388 -> 5440
~ _sysInfo_updateAdvertiserInfo : 3668 -> 3712
~ __APAdvertiserInfoAddAirPlayData : 3516 -> 3596
~ _APAdvertiserInfoCopyAirPlayDataWithNANServiceType : 3704 -> 3804
~ _APAdvertiserInfoCopyClusterCompatibleAirPlayData : 2640 -> 2736
CStrings:
+ "pgs"
```
