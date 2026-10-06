## AppleSPUHIDStatistics

> `/System/Library/HIDPlugins/AppleSPUHIDStatistics.plugin/AppleSPUHIDStatistics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x1480` | `0x1490` | **`+0x10`** |
| `__TEXT.__cstring` | `0x203e` | `0x2048` | **`+0xa`** |
| `__TEXT.__text` | `0xf508` | `0xf50c` | **`+0x4`** |

### Other Changes

```diff

-1084.0.0.0.0
+1087.0.0.0.0

-  CStrings:  449
+  CStrings:  450
Functions:
~ __ZN21AppleSPUHIDStatistics4openEP14__IOHIDSessionj : 160 -> 156
~ __ZN21AppleSPUHIDStatistics13publishADDataEP4AggDm : 648 -> 644
~ __ZN15profile_decoder13find_in_tableEPKNS_5entryEjj : 164 -> 172
~ __ZN15profile_decoder4dumpEPKvj : 536 -> 532
~ __Z20spu_log_get_aop_logsjmPFvPvPKcPKvmbES_ : 792 -> 796
~ __Z24spu_log_report_to_stringPKcPKvmbPcm : 260 -> 264
CStrings:
+ "immersion"
```
