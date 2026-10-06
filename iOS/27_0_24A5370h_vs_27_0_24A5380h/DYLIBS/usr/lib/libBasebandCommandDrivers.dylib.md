## libBasebandCommandDrivers.dylib

> `/usr/lib/libBasebandCommandDrivers.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1720c` | `0x172e0` | **`+0xd4`** |
| `__TEXT.__cstring` | `0x2a82` | `0x2aca` | **`+0x48`** |

### Other Changes

```diff

-1570.0.0.0.0
+1576.0.0.0.0

-  Functions: 546
-  Symbols:   1497
-  CStrings:  562
+  Functions: 547
+  Symbols:   1498
+  CStrings:  571
Symbols:
+ __ZN5radio8asStringERKNS_12AntennaStateE
Functions:
~ __ZNK3awd16AwdCommandDriver40handleBatchMetricGroupListForReport_syncERNSt3__113unordered_mapIjNS1_6vectorINS_20BatchMetricGroupInfoENS1_9allocatorIS4_EEEENS1_4hashIjEENS1_8equal_toIjEENS5_INS1_4pairIKjS7_EEEEEE : 1204 -> 1196
+ __ZN5radio8asStringERKNS_12AntennaStateE
CStrings:
+ "ARM41 Int Enforce"
+ "AppleBasebandManager-AppleBasebandServices_Manager-1576"
+ "Dynamic"
+ "Limit"
+ "Lower"
+ "Port A"
+ "Port B"
+ "Port C"
+ "Port D"
+ "Upper"
- "AppleBasebandManager-AppleBasebandServices_Manager-1570"
```
