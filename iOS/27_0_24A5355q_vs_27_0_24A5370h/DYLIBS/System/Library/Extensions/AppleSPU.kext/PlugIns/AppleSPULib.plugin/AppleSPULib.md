## AppleSPULib

> `/System/Library/Extensions/AppleSPU.kext/PlugIns/AppleSPULib.plugin/AppleSPULib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4bb0` | `0x4c4c` | **`+0x9c`** |

### Other Changes

```diff

-1084.0.0.0.0
+1087.0.0.0.0
Functions:
~ sub_23cfc02bc -> sub_23e1352bc : 1020 -> 1016
~ __ZN12SPUDataQueue17get_extended_infoEjPm : 392 -> 520
~ __ZN12SPUDataQueue11enqueue_msgEjjPK9SPU_iovecj : 1444 -> 1476
```
