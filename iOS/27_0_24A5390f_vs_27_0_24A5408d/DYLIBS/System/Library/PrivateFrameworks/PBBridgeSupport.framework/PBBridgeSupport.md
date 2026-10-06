## PBBridgeSupport

> `/System/Library/PrivateFrameworks/PBBridgeSupport.framework/PBBridgeSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x435d8` | `0x436b4` | **`+0xdc`** |
| `__TEXT.__cstring` | `0x5e49` | `0x5f10` | **`+0xc7`** |
| `__AUTH_CONST.__cfstring` | `0x5820` | `0x58a0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x5144` | `0x516c` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1408` | `0x1428` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2570` | `0x2588` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xfe8` | `0xff0` | **`+0x8`** |

### Other Changes

```diff

-1359.3.0.0.0
+1359.7.0.0.0

-  Functions: 1860
-  Symbols:   3265
-  CStrings:  1132
+  Functions: 1863
+  Symbols:   3272
+  CStrings:  1136
Symbols:
+ +[PBBridgeCAReporter recordTinkerUnsupportedRegionPairingAlertShown]
+ +[PBBridgeCAReporter recordTinkerUnsupportedRegionUnpairingAlertResponse:]
+ +[PBBridgeCAReporter recordTinkerUnsupportedRegionUnpairingAlertShown]
+ _PBCATinkerUnsupportedRegionPairingAlertID
+ _PBCATinkerUnsupportedRegionProceededToUnpair
+ _PBCATinkerUnsupportedRegionUnpairingResponseID
+ _PBCATinkerUnsupportedRegionUnpairingShownID
CStrings:
+ "ProceededToUnpair"
+ "com.apple.Bridge.TinkerUnsupportedRegion.PairingAlert"
+ "com.apple.Bridge.TinkerUnsupportedRegion.UnpairingAlert.Response"
+ "com.apple.Bridge.TinkerUnsupportedRegion.UnpairingAlert.Shown"
```
