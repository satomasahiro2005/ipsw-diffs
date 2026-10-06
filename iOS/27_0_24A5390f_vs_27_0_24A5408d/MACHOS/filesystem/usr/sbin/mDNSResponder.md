## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10aa28` | `0x10abd0` | **`+0x1a8`** |
| `__TEXT.__const` | `0x14f4` | `0x14bc` | **`-0x38`** |
| `__TEXT.__cstring` | `0x17ab8` | `0x17aed` | **`+0x35`** |
| `__TEXT.__oslogstring` | `0x210d6` | `0x210ca` | **`-0xc`** |
| `__TEXT.__unwind_info` | `0x16d8` | `0x16e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3109.0.0.0.0
+3111.0.5.0.1

-  Functions: 1870
-  Symbols:   4151
-  CStrings:  4777
+  Functions: 1872
+  Symbols:   4153
+  CStrings:  4778
Symbols:
+ GCC_except_table1250
+ GCC_except_table1256
+ GCC_except_table1419
+ GCC_except_table1602
+ GCC_except_table1835
+ GCC_except_table487
+ _downgrade_question_awdl_inclusion
+ _mDNS_DowngradeAuthRecordAWDLInclusion_internal
+ _mDNS_StopQueryWithRemoves
+ _mdns_clock_monotonic_ns
- GCC_except_table1249
- GCC_except_table1255
- GCC_except_table1418
- GCC_except_table1601
- GCC_except_table1833
- GCC_except_table486
- _DowngradeAuthRecordAWDLInclusion
- __mdns_powerlog_get_monotonic_time_ns
CStrings:
+ "RmvAutoBrowseDomain: ignoring remove event for system-wide local domain"
+ "clock_gettime_nsec_np(CLOCK_MONOTONIC_RAW) error: %{mdns:err}d"
+ "mDNSResponder-3111.0.5.0.1"
+ "mDNS_DowngradeAuthRecordAWDLInclusion"
+ "mDNS_DowngradeServiceSetAWDLInclusion"
- "AWDLTimeoutNotificationHandler: Downgrading kDNSServiceFlagsIncludeAWDL questions and AuthRecords"
- "clock_gettime_nsec_np() returned 0: %{mdns:err}d"
- "mDNSCoreDowngradeAWDLInclusion"
- "mDNSResponder-3109"
```
