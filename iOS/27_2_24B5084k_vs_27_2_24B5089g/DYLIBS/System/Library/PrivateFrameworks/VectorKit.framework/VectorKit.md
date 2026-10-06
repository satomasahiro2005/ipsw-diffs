## VectorKit

> `/System/Library/PrivateFrameworks/VectorKit.framework/VectorKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0xc2f8` | `0xc898` | **`+0x5a0`** |
| `__TEXT.__text` | `0x1221928` | `0x1221a4c` | **`+0x124`** |
| `__DATA_DIRTY.__bss` | `0x59078` | `0x590d8` | **`+0x60`** |
| `__TEXT.__const` | `0x792e8` | `0x79318` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x76148` | `0x7616c` | **`+0x24`** |
| `__TEXT.__oslogstring` | `0x1155f` | `0x11543` | **`-0x1c`** |

### Other Changes

```diff

-2043.31.6.17.7
+2044.31.6.17.11
Functions:
~ __ZN2md9GridLogic15runBeforeLayoutERKNS_13LayoutContextERKNS_17LogicDependenciesIJN3gdc8TypeListIJNS_17StyleLogicContextEEEENS6_IJNS_20TileSelectionContextEEEEEE20ResolvedDependenciesERNS_11GridContextE : 1692 -> 1836
~ __ZN2md9MapEngineC2Efffb16VKMapViewPurposeRKNSt3__110shared_ptrINS_11TaskContextEEE12VKMapPurposeONS2_10unique_ptrINS_16AnimationManagerENS2_14default_deleteISA_EEEERKN3geo10linear_mapINS_16MapEngineSettingExNS2_8equal_toISH_EENS2_9allocatorINS2_4pairISH_xEEEENS2_6vectorISM_SN_EEEEyP24GEOApplicationAuditTokenPKc : 180016 -> 180000
~ -[VKMapView _applyMapDisplayStyle:animated:duration:] : 1892 -> 2020
~ __ZN2md10StyleLogic19updateConfigurationE9VKMapType : 11888 -> 11908
~ -[VKTrafficFeature attributes] : 1432 -> 1448
CStrings:
+ "[StyleLogic:%p] requestDisplayStyle: clientTarget already at style:%s but transitionTargetStyle:%s was still stale -- correcting"
+ "[StyleLogic:%p] updateConfiguration same-manager switch: mapType:%@ carrying forward transitionTargetStyle:%s transitionAnimated:%s"
- "[StyleLogic:%p] requestDisplayStyle: clientTarget already matched requested style:%s animated:%s, but transitionTargetStyle:%s transitionAnimated:%s did not"
- "[StyleLogic:%p] updateConfiguration same-manager switch: mapType:%@ transitionTargetStyle:%s transitionAnimated:%s resetting to Day"
```
