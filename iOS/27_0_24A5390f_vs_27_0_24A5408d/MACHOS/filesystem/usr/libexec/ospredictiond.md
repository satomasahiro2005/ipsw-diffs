## ospredictiond

> `/usr/libexec/ospredictiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66d50` | `0x68734` | **`+0x19e4`** |
| `__TEXT.__objc_methname` | `0x15177` | `0x153ba` | **`+0x243`** |
| `__TEXT.__oslogstring` | `0x71ee` | `0x7327` | **`+0x139`** |
| `__DATA_CONST.__const` | `0x10d0` | `0x1160` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x92d0` | `0x9350` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x97e0` | `0x9860` | **`+0x80`** |
| `__DATA.__objc_const` | `0x10600` | `0x10670` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x870` | `0x8d0` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x3d10` | `0x3d60` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1490` | `0x14d0` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x2456` | `0x248d` | **`+0x37`** |
| `__DATA_CONST.__cfstring` | `0x62a0` | `0x62c0` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x270` | `0x288` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xdbc` | `0xdc4` | **`+0x8`** |
| `__TEXT.__cstring` | `0x55a0` | `0x55a7` | **`+0x7`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-284.0.0.0.0
+286.0.0.0.0

-  Functions: 3304
+  Functions: 3324

-  CStrings:  4766
+  CStrings:  4789
CStrings:
+ "%f-%lu"
+ "@32@0:8Q16^@24"
+ "Added Slot %ld, drain %ld"
+ "Date %@, Slot %ld, cumulative drain %f"
+ "Error getting battery stream in batteryDrainByTimeSlot: %s"
+ "Error getting battery stream in currentBatteryDrain: %s"
+ "Request for current battery drain, with time width %lu"
+ "Request for typical battery drain for reference days %lu, with time width %lu"
+ "T@\"NSMutableDictionary\",&,N,V_dateToWeekdayDrainMedian"
+ "T@\"NSMutableDictionary\",&,N,V_dateToWeekendDrainMedian"
+ "_dateToWeekdayDrainMedian"
+ "_dateToWeekendDrainMedian"
+ "batteryDrainByTimeSlot:dayType:"
+ "currentBatteryDrainAggregatedOverTimeWidth:withError:"
+ "currentBatteryDrainAggregatedOverTimeWidth:withHandler:"
+ "dateToWeekdayDrainMedian"
+ "dateToWeekendDrainMedian"
+ "hasBatteryPercentage"
+ "setDateToWeekdayDrainMedian:"
+ "setDateToWeekendDrainMedian:"
+ "typicalBatteryDrainWithReferenceDays:aggregatedOverTimeWidth:withError:"
+ "typicalBatteryDrainWithReferenceDays:aggregatedOverTimeWidth:withHandler:"
+ "v32@0:8Q16@?<v@?@\"NSArray\"@\"NSError\">24"
```
