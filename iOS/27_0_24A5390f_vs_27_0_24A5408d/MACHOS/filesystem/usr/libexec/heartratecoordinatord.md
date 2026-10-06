## heartratecoordinatord

> `/usr/libexec/heartratecoordinatord`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26e6c` | `0x27c68` | **`+0xdfc`** |
| `__TEXT.__objc_methname` | `0x5119` | `0x52de` | **`+0x1c5`** |
| `__DATA_CONST.__cfstring` | `0x2020` | `0x21c0` | **`+0x1a0`** |
| `__TEXT.__objc_stubs` | `0x3fe0` | `0x4180` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x2191` | `0x22cd` | **`+0x13c`** |
| `__TEXT.__gcc_except_tab` | `0x439c` | `0x44d8` | **`+0x13c`** |
| `__DATA.__objc_const` | `0x2c18` | `0x2d50` | **`+0x138`** |
| `__TEXT.__objc_methlist` | `0x19f4` | `0x1abc` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x3ae8` | `0x3bab` | **`+0xc3`** |
| `__TEXT.__unwind_info` | `0x1238` | `0x12b8` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x11f0` | `0x1258` | **`+0x68`** |
| `__DATA.__objc_data` | `0x640` | `0x690` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x1c3b` | `0x1c0f` | **`-0x2c`** |
| `__TEXT.__objc_classname` | `0x38b` | `0x3a8` | **`+0x1d`** |
| `__DATA.__objc_ivar` | `0x288` | `0x298` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x238` | `0x240` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xa0` | `0xa8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-41.1.0.0.0
+42.0.0.0.0

-  Functions: 919
-  Symbols:   209
-  CStrings:  1600
+  Functions: 939
+  Symbols:   210
+  CStrings:  1632
Symbols:
+ _OBJC_CLASS_$_NSNull
CStrings:
+ "HRCRecentHighConfidenceStats"
+ "Source controller: platinum foreground HRNN active changed to %{BOOL}u"
+ "_deliverRecentHighConfidenceHeartRates"
+ "_foregroundHRNNActive"
+ "_foregroundHRNNActiveDidChange:"
+ "_handlePlatinumForegroundHRNNActiveChanged:"
+ "_notifiedForegroundHRNNActive"
+ "_notifyDelegateForegroundHRNNActiveIfChanged"
+ "_pendingRecentHighConfidenceHeartRatesRequest"
+ "_setForegroundHRNNActive:"
+ "clientDidServeRecentHighConfidenceHeartRatesWithSourceType:processName:"
+ "deferring recent high confidence HRs request for %{public}@ until foreground HRNN is active"
+ "foregroundHRNNActive"
+ "foregroundHRNNActive : %{BOOL}u"
+ "foregroundHRNNActiveDidChange:"
+ "isForegroundHRNNActive"
+ "isPublishableSample:"
+ "null"
+ "pct_context_background"
+ "pct_context_background_tachogram"
+ "pct_context_breathe"
+ "pct_context_ecg"
+ "pct_context_not_set"
+ "pct_context_oxygen_saturation"
+ "pct_context_sedentary"
+ "pct_context_sleep_mode_sedentary"
+ "pct_context_streaming_ppg"
+ "pct_context_walking"
+ "pct_context_wheelchair_motion"
+ "pct_context_workout"
+ "publishable_count"
+ "recordRecentHighConfidenceHeartRatesServed:sourceType:processName:windowStats:"
+ "setForegroundHRNNActive:"
+ "setForegroundHRNNActiveHandler:"
+ "statsForWindow:"
+ "total_count"
+ "v48@0:8d16q24@32@40"
+ "\xa1"
- "clientDidServeRecentHighConfidenceHeartRatesWithCount:sourceType:processName:"
- "hr_count"
- "recordRecentHighConfidenceHeartRatesServed:ageSeconds:sourceType:processName:"
- "v40@0:8q16q24@\"NSString\"32"
- "v40@0:8q16q24@32"
- "v48@0:8q16d24q32@40"
```
