## AudioAnalyticsExternal

> `/System/Library/PrivateFrameworks/AudioAnalyticsExternal.framework/AudioAnalyticsExternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68b2c` | `0x6c170` | **`+0x3644`** |
| `__DATA_DIRTY.__data` | `0x20e8` | `0x26c0` | **`+0x5d8`** |
| `__DATA_DIRTY.__bss` | `0x1c00` | `0x2180` | **`+0x580`** |
| `__DATA.__bss` | `0x10e0` | `0xc60` | **`-0x480`** |
| `__AUTH.__data` | `0x750` | `0x4f8` | **`-0x258`** |
| `__DATA.__data` | `0x550` | `0x370` | **`-0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x2088` | `0x2178` | **`+0xf0`** |
| `__TEXT.__swift5_reflstr` | `0x1b2a` | `0x1c1a` | **`+0xf0`** |
| `__TEXT.__swift5_fieldmd` | `0x180c` | `0x18e4` | **`+0xd8`** |
| `__TEXT.__const` | `0x3208` | `0x32d8` | **`+0xd0`** |
| `__TEXT.__constg_swiftt` | `0x1398` | `0x143c` | **`+0xa4`** |
| `__AUTH_CONST.__const` | `0x2178` | `0x2200` | **`+0x88`** |
| `__TEXT.__cstring` | `0x18ca` | `0x194a` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x2afe` | `0x2b6e` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0xfa8` | `0x1018` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0xde0` | `0xe48` | **`+0x68`** |
| `__DATA_DIRTY.__objc_data` | `0x5a0` | `0x5f0` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0xe88` | `0xe66` | **`-0x22`** |
| `__AUTH_CONST.__auth_got` | `0x1270` | `0x1290` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x588` | `0x570` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0x1b0` | `0x1c8` | **`+0x18`** |
| `__DATA.__common` | `0x78` | `0x68` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x168` | `0x170` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xd8` | `0xe0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x17c` | `0x184` | **`+0x8`** |
| `__TEXT.__swift5_types2` | `0x4` | `0xc` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x12c` | `0x130` | **`+0x4`** |

### Other Changes

```diff

-294.0.0.0.0
+295.0.0.0.0

-  Functions: 1422
+  Functions: 1458

-  CStrings:  360
+  CStrings:  366
Symbols:
+ __DATA__TtC22AudioAnalyticsExternal19PencilSummaryWorker
+ __IVARS__TtC22AudioAnalyticsExternal19PencilSummaryWorker
+ __METACLASS_DATA__TtC22AudioAnalyticsExternal19PencilSummaryWorker
+ ___swift_memcpy48_8
+ _swift_initStructMetadata
+ _symbolic _____ 18AudioAnalyticsBase12PeriodicGateV
+ _symbolic _____ 22AudioAnalyticsExternal12SessionState33_31EF00105F3513EC64E6BEE9F1AC57CBLLV
+ _symbolic _____ 22AudioAnalyticsExternal13PencilSummary33_31EF00105F3513EC64E6BEE9F1AC57CBLLV
+ _symbolic _____ 22AudioAnalyticsExternal19PencilSummaryWorkerC
+ _symbolic _____Sg s6UInt64V
- _get_type_metadata 15Synchronization5MutexVy18AudioAnalyticsBase10PreferenceVySbGG noncopyable
- _get_type_metadata 15Synchronization5MutexVy22AudioAnalyticsExternal15OverloadOptionsVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy22AudioAnalyticsExternal15TailspinOptionsVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy22AudioAnalyticsExternal17TailspinCaseStateVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy22AudioAnalyticsExternal21DriverSnapshotManagerC5State33_F3112A0FED6FC212BEFC7E14C11181D4LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVys6UInt32VG noncopyable
- _get_type_metadata 15Synchronization6AtomicVySdG noncopyable
- _get_type_metadata 18AudioAnalyticsBase12PeriodicGateV noncopyable
- _get_type_metadata 22AudioAnalyticsExternal0A17AlarmHealthReport33_873B3386D84C490C95523F8AF5345809LLV noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "Pencil message contains invalid session time. { seconds=%f }"
+ "PencilSummaryWorker: summary message dropped"
+ "pencil_app_bundle_id"
+ "pencil_message_count"
+ "pencil_session_seconds"
+ "pencil_total_seconds"
```
