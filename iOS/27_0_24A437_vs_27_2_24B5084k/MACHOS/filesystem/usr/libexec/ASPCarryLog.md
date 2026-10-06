## ASPCarryLog

> `/usr/libexec/ASPCarryLog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27524` | `0x2a0b0` | **`+0x2b8c`** |
| `__TEXT.__cstring` | `0x8e3f` | `0x93e7` | **`+0x5a8`** |
| `__TEXT.__oslogstring` | `0x1637` | `0x1b12` | **`+0x4db`** |
| `__DATA_CONST.__cfstring` | `0x15c0` | `0x1a60` | **`+0x4a0`** |
| `__TEXT.__objc_stubs` | `0x2d20` | `0x2fa0` | **`+0x280`** |
| `__TEXT.__objc_methname` | `0x30e0` | `0x324e` | **`+0x16e`** |
| `__DATA_CONST.__const` | `0x348` | `0x430` | **`+0xe8`** |
| `__TEXT.__const` | `0x1f4` | `0x2d4` | **`+0xe0`** |
| `__DATA.__objc_selrefs` | `0xdc0` | `0xe60` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0xb90` | `0xbf0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x528` | `0x580` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x14a0` | `0x14d8` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x5e0` | `0x610` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1c0` | `0x1d0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-849.0.11.0.0
+849.40.12.0.1

-  Functions: 526
-  Symbols:   253
-  CStrings:  2532
+  Functions: 556
+  Symbols:   261
+  CStrings:  2639
Symbols:
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSMutableData
+ ___memcpy_chk
+ _archive_read_data
+ _archive_read_open_memory
+ _archive_read_support_filter_gzip
+ _archive_read_support_format_raw
+ _strnlen
CStrings:
+ "%@.tar"
+ "%@/DebugData"
+ "%@/DebugData/debug_data_UNKNOWN_serial_%@_%@.bin"
+ "%@/DebugData/debug_data_version_%u_event_%s_serial_%@_%@"
+ "%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%u,%d,%d"
+ ",%u"
+ ",new_column_%u"
+ "?"
+ "Band_Id,Valid,Cycles,Band_Next,flags,flags_protection_type,flags_mode,flags_retrace,flags_gc_can,flags_gc_must,flags_rfu1,flags_Special,flags_erased,flags_invalid_parity,flags_so_band,flags_rfu,flags_rd_clear_pending,flags_rfu_2,Flow,Age,Recent,state_gc_was,state_gc_aux,state_gc_rd,state_reuse,state_pend_close,state_open_excessively,state_to_invalidate,states_rfu,Sequence,Block_Next,Slc_Bitmap,Temperature_min,Temperature_max"
+ "Bands-snap schema mismatch; wrote raw blob to %s"
+ "Bands-snap tunnel unsupported or returned no data; omitting file"
+ "DEBUG_DATA_EMPTY"
+ "DEBUG_DATA_MASS_SCAN"
+ "DEBUG_DATA_TEST"
+ "Debug data buffer too small (%zu bytes), no compressed payload"
+ "Debug data file at %s; test hook %u"
+ "Debug data flagged non-compressed; dumping body raw"
+ "Debug data payload sub-version mismatch (got %u, expected %u); dumping inflated bin"
+ "Debug data raw-header version mismatch (got %u, expected %u); dumping raw bin"
+ "DebugData decoder element_size out of range at idx %zu (esize %zu); skipping rest of info"
+ "Failed to inflate debug data payload"
+ "Failed to rename bands-snap CSV from %s to %s"
+ "Failed to tar debug data folder"
+ "Failed to tar non-compressed debug data"
+ "Failed to tar sub-version-mismatch debug data"
+ "Failed to trim debug data hidden region"
+ "Failed to write bands-snap fallback to %s"
+ "Failed to write geometry to %s"
+ "Failed to write header JSON to %s: %s"
+ "Failed to write inflated payload to %s"
+ "Failed to write non-compressed payload to %s"
+ "Failed to write payload to %s"
+ "Failed to write raw debug-data dump to %s"
+ "Fetched %zu bytes of NAND debug data (%zu bytes after raw header)"
+ "No NAND debug data held by firmware"
+ "Pilot scan tunnel unsupported or returned no data; omitting file"
+ "[%@][New Debug Data][%@]"
+ "_collectDebugData"
+ "_writeSupplementaryDebugFilesTo:"
+ "addObjectsFromArray:"
+ "array"
+ "arrayWithCapacity:"
+ "bands_snapshot.bin"
+ "bands_snapshot.tmp.csv"
+ "bands_snapshot_v%u.csv"
+ "bin"
+ "buildNumber"
+ "buildVersion"
+ "bytes"
+ "capacityGB"
+ "data"
+ "dataWithBytes:length:"
+ "dataWithLength:"
+ "debugDataCompressionFailed"
+ "debugDataDumpSuccess"
+ "debugDataGetFail"
+ "debugDataGetSuccess"
+ "debugDataHandoffToRxBurn"
+ "debugDataRequestDropped"
+ "debugDataRequestDump"
+ "debugDataTrimCalled"
+ "deviceTemperature"
+ "dictionary"
+ "earlyExit"
+ "event"
+ "event=%@"
+ "event=UNKNOWN"
+ "failedBandsBM"
+ "firmware_info.json"
+ "ftl_counters.json"
+ "geometry.txt"
+ "getDebugData:"
+ "header"
+ "header.json"
+ "hostWrite"
+ "idleStackFlowVCurveCDPAtSlowGC"
+ "info"
+ "initWithBytes:length:encoding:"
+ "isCompressed"
+ "lbaRuns"
+ "longVersion"
+ "msp"
+ "mspVersion"
+ "msp_counters.json"
+ "mutableBytes"
+ "nandType"
+ "nandVendor"
+ "nandWrite"
+ "numValidPilotScanBands"
+ "numberWithUnsignedChar:"
+ "numberWithUnsignedShort:"
+ "payload.bin"
+ "pilotScanBands"
+ "pilot_scan.json"
+ "sanitizeDoneTime"
+ "sanitizeReject"
+ "sanitizeStartTime"
+ "sanitizeStatus"
+ "setLength:"
+ "size"
+ "stringWithUTF8String:"
+ "subdataWithRange:"
+ "sweepInfo unavailable; omitting firmware_info.json"
+ "timer64"
+ "timer_read64_synced"
+ "trimDebugData"
+ "type"
+ "uploadDebugData:description:logType:"
- "idleStackPurgeableValidityCurveAtSlowGC"
```
