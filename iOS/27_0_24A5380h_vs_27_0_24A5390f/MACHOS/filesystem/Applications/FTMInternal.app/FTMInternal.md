## FTMInternal

> `/Applications/FTMInternal.app/FTMInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bc590` | `0x2b4f5c` | **`-0x7634`** |
| `__TEXT.__cstring` | `0x11540` | `0x10fc0` | **`-0x580`** |
| `__DATA_CONST.__const` | `0xb3c8` | `0xb0a8` | **`-0x320`** |
| `__TEXT.__eh_frame` | `0x2f08` | `0x2e28` | **`-0xe0`** |
| `__TEXT.__const` | `0x9234` | `0x91e4` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x5760` | `0x5718` | **`-0x48`** |
| `__TEXT.__objc_stubs` | `0x8960` | `0x8920` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0xcbd2` | `0xcc12` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x3490` | `0x34c0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xb48` | `0xb68` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x406c` | `0x404c` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x25814` | `0x25834` | **`+0x20`** |
| `__DATA.__objc_data` | `0x69b8` | `0x69a0` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x1a58` | `0x1a70` | **`+0x18`** |
| `__DATA.__data` | `0x6a48` | `0x6a38` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x10d0` | `0x10c0` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2e7a` | `0x2e6a` | **`-0x10`** |
| `__DATA.__common` | `0x230` | `0x228` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0xad40` | `0xad48` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xd00` | `0xd08` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-39.0.0.0.0
+39.1.0.0.0

-  Functions: 13969
-  Symbols:   1451
-  CStrings:  11476
+  Functions: 13957
+  Symbols:   1455
+  CStrings:  11439
Symbols:
+ _$s10Foundation4DateV1soiyA2C_SdtFZ
+ _$s10Foundation6LocaleVMn
+ _$sSS9hasPrefixySbSSF
+ _$sSy10FoundationE7compare_7options5range6localeSo18NSComparisonResultVqd___So22NSStringCompareOptionsVSnySS5IndexVGSgAA6LocaleVSgtSyRd__lF
CStrings:
+ "CT - getCurrentCellInfo error: %{public}s"
+ "Metric received %{public}s"
+ "SCell getSupportedMCCs  %{public}s"
+ "containsString:"
+ "queueMetricSet"
+ "syncMetricModels removeAll1: remaining count=%d"
+ "syncMetricModels removeAll2: remaining count=%d"
- "5G"
- "AllMetricsViewModel - processNewMetric isCompleted"
- "AllMetricsViewModel - processNewMetric notification called"
- "Appdelegate - applicationDidEnterBackground ABMWrapper.sharedInstance  returned nil"
- "CT - 1"
- "CT - getCurrentCellInfo error: %{private}s"
- "Data received from CT %{private}s"
- "ECN011~CT %{private}@ - %{private}@"
- "KCTCellMonitorBandInfo"
- "Metric received from AWD %{private}s"
- "Other LTE Bands~"
- "RAT"
- "RSCP11~CT %{private}@ - %{private}@"
- "RSRP11~CT %{private}@ - %{private}@"
- "RSRP11~CT~5G %{private}@ - %{private}@"
- "SCell getSupportedMCCs "
- "SNR11~CT %{private}@ - %{private}@"
- "SNR11~CT~5G %{private}@ - %{private}@"
- "SwiftUI Scene Phase - Background ABMWrapper.sharedInstance  returned nil"
- "SwiftUI Scene Phase - Background successfully removed AWDConfig"
- "SwiftUI Scene Phase - Inactive ABMWrapper.sharedInstance  returned nil"
- "SwiftUI Scene Phase - Inactive successfully removed AWDConfig"
- "avg_values_phy_cell_id"
- "avg_values_sinr0"
- "avg_values_sinr1"
- "ecn0_ct"
- "kCTCellMonitorARFCN"
- "kCTCellMonitorCellId"
- "kCTCellMonitorLAC"
- "kCTCellMonitorMCC"
- "kCTCellMonitorMNC"
- "kCTCellMonitorPCI"
- "kCTCellMonitorPID"
- "kCTCellMonitorRadioAccessTechnologyLTE"
- "kCTCellMonitorSCN"
- "kCTCellMonitorTAC"
- "kCTCellMonitorUARFCN"
- "metricDataLoadGraph"
- "queueMetricGraph"
- "rscp_ct"
- "rsrp_ct"
- "signalStrengthChanged 5G Data"
- "snr_ct"
- "successfully started listening ABM applicationDidBecomeActive"
```
