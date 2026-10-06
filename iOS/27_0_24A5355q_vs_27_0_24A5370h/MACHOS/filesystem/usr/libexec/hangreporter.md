## hangreporter

> `/usr/libexec/hangreporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22420` | `0x23978` | **`+0x1558`** |
| `__DATA_CONST.__cfstring` | `0x4bc0` | `0x5200` | **`+0x640`** |
| `__TEXT.__objc_methname` | `0x53c6` | `0x5751` | **`+0x38b`** |
| `__TEXT.__objc_stubs` | `0x2d60` | `0x30a0` | **`+0x340`** |
| `__DATA.__objc_const` | `0x2730` | `0x2a10` | **`+0x2e0`** |
| `__TEXT.__cstring` | `0x3f0e` | `0x4132` | **`+0x224`** |
| `__TEXT.__objc_methlist` | `0xfd4` | `0x1144` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x4be1` | `0x4d39` | **`+0x158`** |
| `__DATA.__objc_selrefs` | `0x10a0` | `0x1178` | **`+0xd8`** |
| `__DATA.__objc_data` | `0x410` | `0x4b0` | **`+0xa0`** |
| `__DATA.__data` | `0x6f0` | `0x750` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x14d8` | `0x1530` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x520` | `0x578` | **`+0x58`** |
| `__DATA_CONST.__objc_intobj` | `0x90` | `0xc0` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x135` | `0x160` | **`+0x2b`** |
| `__TEXT.__objc_methtype` | `0x87b` | `0x89d` | **`+0x22`** |
| `__DATA.__bss` | `0x1e8` | `0x208` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x26c` | `0x28c` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xed0` | `0xef0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x778` | `0x788` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x68` | `0x78` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xba8` | `0xbb4` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x280` | `0x288` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__const` | `0x2b8` | `0x2b0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_doubleobj`

### Other Changes

```diff

-412.0.0.0.0
+415.0.0.0.0

-  Functions: 652
-  Symbols:   328
-  CStrings:  1939
+  Functions: 684
+  Symbols:   331
+  CStrings:  2039
Symbols:
+ _OBJC_CLASS_$_NSCharacterSet
+ _objc_setProperty_nonatomic_copy
+ _os_variant_has_internal_content
CStrings:
+ "!"
+ "-"
+ "<HTLostPerfInterval: reason=%@ [%llu..%llu]>"
+ "<LostPerfEvent: stateName=%@ stateID=0x%llx severity=%ld residencyMs=%llums>"
+ "@32@0:8@16Q24"
+ "@40@0:8Q16@24Q32"
+ "@68@0:8@16@24i32Q36Q44Q52C60S64"
+ "ADAPTDIS"
+ "ARCHILIM"
+ "ARCHTEMP"
+ "ARCHTRTL"
+ "BATTEMP"
+ "BLKDSLOT"
+ "CLKILIM"
+ "CLKTEMP"
+ "CLKTRTL"
+ "CPUZONE"
+ "DRAMTEMP"
+ "EMPTYBAT"
+ "FANNOISE"
+ "FASTCHRG"
+ "FASTTEMP"
+ "FDIE_LTS"
+ "HEATPIPE"
+ "HIP"
+ "HTLostPerf: Residency conversion overflow for state '%{public}@' (ID: 0x%llx), MATU value %llu would exceed milliseconds_t max. Clamped to UINT64_MAX."
+ "HTLostPerf: Unknown Lost Perf state name '%{public}@' (ID: 0x%llx), defaulting to low severity for consistent light black coloring"
+ "HTLostPerf: failed to serialize lost-perf payload: %{public}@"
+ "HTLostPerfInterval"
+ "INTELBAT"
+ "LONGCHRG"
+ "LOWPOWER"
+ "LTSVCAP"
+ "LostPerfEvent"
+ "NANDTEMP"
+ "NONE"
+ "NSCopying"
+ "OTHER"
+ "PKGZONE"
+ "PMUEM"
+ "PMUTEMP"
+ "PREPCKUP"
+ "PSUTEMP"
+ "SDIETEMP"
+ "SKINTEMP"
+ "SLOWTEMP"
+ "SMCPOWER"
+ "SUSTAIN"
+ "SYSZONE"
+ "T@\"NSString\",C,N,V_reason"
+ "T@\"NSString\",R,C,V_bundleIdentifier"
+ "T@\"NSString\",R,N,V_stateName"
+ "TDDBVCAP"
+ "TQ,N,V_endMATU"
+ "TQ,N,V_startMATU"
+ "TQ,R,N,V_residencyMs"
+ "TQ,R,N,V_stateID"
+ "Tq,R,N,V_severity"
+ "UPO-AV"
+ "[({<"
+ "_bundleIdentifier"
+ "_endMATU"
+ "_reason"
+ "_residencyMs"
+ "_severity"
+ "_startMATU"
+ "_stateID"
+ "_stateName"
+ "appendInterval:coalescingWithTailOf:"
+ "applicationBundleIdentifierFromLaunchdLabel:"
+ "arrayWithCapacity:"
+ "calculateSeverityFromStateName:"
+ "characterSetWithCharactersInString:"
+ "coalescedIntervalsFromSampleStore:"
+ "endMATU"
+ "end_ms"
+ "fileSystemRepresentation"
+ "hangtracer.performance"
+ "initWithData:encoding:"
+ "initWithInfo:bundleIdentifier:pid:spawnTimestamp:exitTimestamp:exitReasonCode:exitReasonNamespace:jetsam_priority:"
+ "initWithStateID:stateName:residencyMATU:"
+ "integerValue"
+ "intervalFromSALostPerfEvent:"
+ "intervals"
+ "intervalsByClippingIntervals:toWindowStart:end:"
+ "jsonStringForIntervals:hangStartMATU:"
+ "lostPerf"
+ "lostPerfEvents"
+ "rangeOfCharacterFromSet:"
+ "residencyMs"
+ "resources"
+ "security bounds safety"
+ "setEndMATU:"
+ "setStartMATU:"
+ "severity"
+ "severityToStatesMapping"
+ "startMATU"
+ "start_ms"
+ "stateID"
+ "stateName"
+ "stateNameToSeverityMapping"
+ "substringToIndex:"
- "@60@0:8@16i24Q28Q36Q44C52S56"
- "initWithInfo:pid:spawnTimestamp:exitTimestamp:exitReasonCode:exitReasonNamespace:jetsam_priority:"
```
