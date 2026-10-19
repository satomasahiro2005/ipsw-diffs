## APTransport

> `/System/Library/PrivateFrameworks/APTransport.framework/APTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb7180` | `0xb72cc` | **`+0x14c`** |
| `__AUTH_CONST.__cfstring` | `0x6660` | `0x6680` | **`+0x20`** |
| `__TEXT.__cstring` | `0x30ebf` | `0x30ec3` | **`+0x4`** |

### Other Changes

```diff

-  Functions: 5364
-  Symbols:   4423
-  CStrings:  4587
+  Functions: 5366
+  Symbols:   4425
+  CStrings:  4588
Symbols:
+ _APSIsHomeTheaterSurroundEnabled
+ _APSSurroundToOdeonFallbackEnabled
Functions:
~ _APAdvertiserInfoCopyAirPlayDataWithNANServiceType : 3244 -> 3336
~ __APAdvertiserInfoAddAirPlayData : 3416 -> 3496
~ _APAdvertiserInfoCopyClusterCompatibleAirPlayData : 2320 -> 2408
~ _APAdvertiserInfoCopyAirPlayDataWithNANServiceType.cold.40 : 56 -> 36
+ _APAdvertiserInfoCopyAirPlayDataWithNANServiceType.cold.43
~ _APAdvertiserInfoCopyClusterCompatibleAirPlayData.cold.15 : 48 -> 36
~ _APAdvertiserInfoCopyClusterCompatibleAirPlayData.cold.16 : 36 -> 48
~ _APAdvertiserInfoCopyClusterCompatibleAirPlayData.cold.29 : 48 -> 36
+ _APAdvertiserInfoCopyClusterCompatibleAirPlayData.cold.32
CStrings:
+ "pgs"
```
