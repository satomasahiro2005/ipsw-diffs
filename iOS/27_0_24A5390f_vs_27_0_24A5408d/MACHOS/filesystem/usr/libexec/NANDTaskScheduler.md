## NANDTaskScheduler

> `/usr/libexec/NANDTaskScheduler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf904` | `0xfdb4` | **`+0x4b0`** |
| `__TEXT.__oslogstring` | `0x2fcf` | `0x30f5` | **`+0x126`** |
| `__TEXT.__objc_methname` | `0x15fe` | `0x16b2` | **`+0xb4`** |
| `__DATA_CONST.__cfstring` | `0xa80` | `0xb20` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x1600` | `0x16a0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x12b4` | `0x1323` | **`+0x6f`** |
| `__DATA.__objc_selrefs` | `0x6d8` | `0x700` | **`+0x28`** |
| `__DATA_CONST.__objc_intobj` | `0x18` | `0x30` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1c0` | `0x1d0` | **`+0x10`** |
| `__DATA.__common` | `0x68` | `0x70` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-849.0.5.0.0
+849.0.11.0.0

-  Symbols:   199
-  CStrings:  753
+  Symbols:   201
+  CStrings:  771
Symbols:
+ _OBJC_CLASS_$_BGSystemTaskProgressMetrics
+ _OBJC_CLASS_$_NSNumber
Functions:
~ sub_100007b10 : 284 -> 324
~ sub_100007c2c -> sub_100007c54 : 624 -> 748
~ sub_10000a354 -> sub_10000a3f8 : 7988 -> 8280
~ sub_10000d008 -> sub_10000d1d0 : 292 -> 320
~ sub_10000db18 -> sub_10000dcfc : 3072 -> 3788
CStrings:
+ "Failed to deregister selfActivations throughput: %@"
+ "Failed to register selfActivations throughput tracking: %@"
+ "Failed to report pctToHigh progress: %s"
+ "Failed to report pctToMed progress: %s"
+ "IdleStack poll: hourly stats pctToMed=%u pctToHigh=%u"
+ "Limited ping flavor (%s)."
+ "Restored limitedFlvr: %d"
+ "Task state saved persistently: stage=%d, sbarIdx=%u, priority=%d, limitedFlvr=%d"
+ "boolForKey:"
+ "dLastSelfActivations"
+ "dLimitedFlvr"
+ "idlestack.pctToHigh"
+ "idlestack.pctToMed"
+ "idlestack.selfActivations"
+ "initWithIdentifier:taskName:qos:workloadCategory:expectedMetricValue:itemsCompleted:totalItemCount:"
+ "new"
+ "numberWithUnsignedInt:"
+ "reportProgressMetrics:error:"
+ "report_hourly_stats - unexpected buf len %zu\n"
+ "resumed"
+ "setBool:forKey:"
- "Limited ping flavor requested."
- "No new slowInlineGC this round."
- "Task state saved persistently: stage=%d, sbarIdx=%u, priority=%d"
```
