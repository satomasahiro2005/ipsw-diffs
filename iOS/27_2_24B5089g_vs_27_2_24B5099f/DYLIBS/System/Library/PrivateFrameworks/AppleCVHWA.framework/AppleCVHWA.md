## AppleCVHWA

> `/System/Library/PrivateFrameworks/AppleCVHWA.framework/AppleCVHWA`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbc518` | `0xbe81c` | **`+0x2304`** |
| `__TEXT.__cstring` | `0x8fa0` | `0x937b` | **`+0x3db`** |
| `__TEXT.__gcc_except_tab` | `0x5620` | `0x57a0` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x2c8` | `0x320` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x1840` | `0x1870` | **`+0x30`** |
| `__AUTH.__data` | `0x20` | `—` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0x1e18` | `0x1e38` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__TEXT.__const` | `0x3030` | `0x3040` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x3b9` | `0x3c4` | **`+0xb`** |
| `__AUTH_CONST.__auth_got` | `0x5e8` | `0x5f0` | **`+0x8`** |

### Other Changes

```diff

-4.4.13.0.0
+4.4.14.0.0

-  Functions: 1190
-  Symbols:   448
-  CStrings:  585
+  Functions: 1196
+  Symbols:   449
+  CStrings:  646
Symbols:
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE9push_backEc
CStrings:
+ " (ADVISORY)"
+ " (STALE, NOT COUNTED)"
+ " afterEntries="
+ " afterSets="
+ " beforeEntries="
+ " beforeSets="
+ " binLive= "
+ " binSets= "
+ " binsAtCap="
+ " cap="
+ " credibleEnd="
+ " delta="
+ " descIdOOR="
+ " emptySetsInRange="
+ " gap firstEmptySet="
+ " geom maxSets="
+ " hetMinimaSets="
+ " hwmeta setCount="
+ " integrity zeroTid="
+ " looksLiveEntries="
+ " looksLiveSets="
+ " map legend: N=liveCountInSet NxR=run of R such sets, 0=empty set"
+ " mapTruncated=1 (RLE exceeded the emit budget)"
+ " map["
+ " map[1/1] (empty)"
+ " mdDescCount= "
+ " numKps="
+ " numMinDescs="
+ " numTids="
+ " scanEnd="
+ " stride="
+ " sum="
+ " tail sets="
+ " tidInit="
+ " tidsOutOfRange="
+ " totalLive="
+ " trust="
+ " verdict="
+ "%{public}s"
+ "---- AppleCVHWA Flow2 binned-desc survey ends here ----"
+ "---- AppleCVHWA Flow2 binned-desc survey starts here ----"
+ "/"
+ "ABOVE_MAX"
+ "BUFFER_BLANK"
+ "IN_RANGE"
+ "NO_MISMATCH"
+ "OVER_COUNT"
+ "SURVEY_INCONSISTENT"
+ "TRUNCATED_AT_EMPTY_SET"
+ "TRUNCATED_AT_EMPTY_SET_PARTIAL"
+ "UNDER_COUNT_BINNED_OVERFLOW"
+ "UNDER_COUNT_UNEXPLAINED"
+ "UNKNOWN"
+ "ZERO_OR_UNPOPULATED"
+ "[CVHWA][fl2surv]"
+ "] "
+ "fl2surv"
+ "none"
+ "unavailable"
+ "w numMaxDescs="
+ "w sizeofStride="
```
