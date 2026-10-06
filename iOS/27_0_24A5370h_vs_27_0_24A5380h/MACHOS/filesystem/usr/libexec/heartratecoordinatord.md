## heartratecoordinatord

> `/usr/libexec/heartratecoordinatord`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25a78` | `0x26e50` | **`+0x13d8`** |
| `__TEXT.__objc_methname` | `0x4dda` | `0x51ab` | **`+0x3d1`** |
| `__TEXT.__gcc_except_tab` | `0x4098` | `0x4374` | **`+0x2dc`** |
| `__TEXT.__objc_stubs` | `0x3d40` | `0x4000` | **`+0x2c0`** |
| `__DATA_CONST.__cfstring` | `0x1f80` | `0x2080` | **`+0x100`** |
| `__DATA_CONST.__const` | `0xc18` | `0xce0` | **`+0xc8`** |
| `__TEXT.__objc_methlist` | `0x1944` | `0x1a0c` | **`+0xc8`** |
| `__DATA.__objc_selrefs` | `0x1140` | `0x11f8` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x1190` | `0x1248` | **`+0xb8`** |
| `__DATA.__objc_const` | `0x2b98` | `0x2c48` | **`+0xb0`** |
| `__TEXT.__objc_methtype` | `0x1ba5` | `0x1c3e` | **`+0x99`** |
| `__TEXT.__cstring` | `0x211c` | `0x21b2` | **`+0x96`** |
| `__TEXT.__oslogstring` | `0x3a11` | `0x3a6f` | **`+0x5e`** |
| `__DATA_CONST.__got` | `0x210` | `0x228` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x280` | `0x28c` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-39.0.0.0.0
+40.0.0.0.0

-  Functions: 900
-  Symbols:   206
-  CStrings:  1560
+  Functions: 922
+  Symbols:   209
+  CStrings:  1603
Symbols:
+ _OBJC_CLASS_$_NSPredicate
+ _OBJC_CLASS_$_NSSortDescriptor
+ ___NSArray0__struct
CStrings:
+ "@\"NSArray\""
+ "@56@0:8@16@24@32@40@48"
+ "B24@?0@\"HRCHeartRateData\"8@\"NSDictionary\"16"
+ "T@\"HRCHeartRateData\",&,V_mostRecentHighConfidenceHeartRate"
+ "T@\"HRCHeartRateData\",R,N"
+ "T@\"NSArray\",&,V_heartRatesBuffer"
+ "T@\"NSArray\",R,N"
+ "_appendSampleToRollingBuffer:"
+ "_heartRatesBuffer"
+ "_heartRatesWithinWindow"
+ "_recentHighConfidenceHRBuffer"
+ "_reportRecentHighConfidenceHeartRateAnalytics:"
+ "_requestRecentHighConfidenceHeartRates"
+ "age_seconds"
+ "clientDidServeMostRecentHighConfidenceHeartRateWithSourceType:processName:"
+ "clientDidServeRecentHighConfidenceHeartRatesWithCount:sourceType:processName:"
+ "com.apple.hrc.recent_high_confidence_hr.stats"
+ "copy"
+ "dateWithTimeIntervalSinceNow:"
+ "filteredArrayUsingPredicate:"
+ "handleRecentHighConfidenceHeartRates:"
+ "heartRatesBuffer"
+ "initWithDelegate:onQueue:analyticsReporter:"
+ "initWithDelegate:remoteObjectProxy:onQueue:mostRecentHighConfidenceHR:recentHighConfidenceHRBuffer:"
+ "lastObject"
+ "mostRecentHeartRate"
+ "none"
+ "predicateWithBlock:"
+ "process_name"
+ "recent high confidence HRs requested by %{public}@, returning %lu samples, latest: %{public}@"
+ "recentHighConfidenceHeartRates"
+ "recordMostRecentHighConfidenceHeartRateServed:sourceType:processName:"
+ "recordRecentHighConfidenceHeartRatesServed:ageSeconds:sourceType:processName:"
+ "removeObjectAtIndex:"
+ "requestRecentHighConfidenceHeartRates"
+ "request_type"
+ "setHeartRatesBuffer:"
+ "sortDescriptorWithKey:ascending:"
+ "sortedArrayUsingDescriptors:"
+ "source_type"
+ "v24@0:8@\"NSArray\"16"
+ "v32@0:8q16@\"NSString\"24"
+ "v32@0:8q16@24"
+ "v40@0:8d16q24@32"
+ "v40@0:8q16q24@\"NSString\"32"
+ "v40@0:8q16q24@32"
+ "v48@0:8q16d24q32@40"
- "@48@0:8@16@24@32@40"
- "T@\"HRCHeartRateData\",&,N,V_mostRecentHighConfidenceHeartRate"
- "initWithDelegate:remoteObjectProxy:onQueue:mostRecentHighConfidenceHR:"
- "q"
```
