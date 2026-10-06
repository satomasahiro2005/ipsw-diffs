## Polaris

> `/System/Library/PrivateFrameworks/Polaris.framework/Polaris`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x5d8` | `0x438` | **`-0x1a0`** |
| `__DATA_DIRTY.__objc_data` | `0x1cc8` | `0x1e68` | **`+0x1a0`** |
| `__AUTH.__data` | `0x228` | `0x128` | **`-0x100`** |
| `__DATA_DIRTY.__data` | `0x25c0` | `0x26c0` | **`+0x100`** |
| `__TEXT.__text` | `0x18e200` | `0x18e16c` | **`-0x94`** |
| `__TEXT.__oslogstring` | `0xeb81` | `0xebd1` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x35d4` | `0x35ac` | **`-0x28`** |
| `__TEXT.__gcc_except_tab` | `0x4c18` | `0x4c40` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x918` | `0x938` | **`+0x20`** |
| `__TEXT.__const` | `0x80ec` | `0x80cc` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x2253` | `0x2241` | **`-0x12`** |
| `__DATA.__data` | `0x2cb8` | `0x2ca8` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x36d8` | `0x36e8` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-256.0.2.500.1
+256.0.3.0.0

-  Functions: 7540
-  Symbols:   7981
-  CStrings:  3680
+  Functions: 7539
+  Symbols:   7977
+  CStrings:  3681
Symbols:
+ GCC_except_table105
+ GCC_except_table107
+ GCC_except_table167
+ GCC_except_table290
+ GCC_except_table297
+ __ZL16ps_ca_send_eventPKcPv
+ __ZNSt3__14pairIKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEN4PSSG15ResourceOptionsEEC1B9fqe220106IJRS7_EJEEENS_21piecewise_construct_tENS_5tupleIJDpT_EEENSE_IJDpT0_EEE
+ ____ZL16ps_ca_send_eventPKcPv_block_invoke
+ ___ps_ca_send_event_block_invoke
- GCC_except_table104
- GCC_except_table106
- GCC_except_table166
- GCC_except_table289
- GCC_except_table296
- ____ZL20sendEntriesFromArrayNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEPvP16ps_ca_arr_args_s_block_invoke
- ____ZN21PSCoreAnalyticsServer9sendEntryENSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEEPvP16ps_ca_arr_args_s_block_invoke
- ____right_strap_send_ca_event_block_invoke
- ___ps_gsm_create_source_internal_block_invoke
- _get_type_metadata 15Synchronization5MutexVy14PolarisRuntime14EndpointServer_pG noncopyable
- _get_type_metadata 15Synchronization5MutexVy7Polaris12GraphManagerC11CrashReasonOG noncopyable
- _get_type_metadata 15Synchronization5MutexVy7Polaris12GraphManagerC14SubmittedStateVGSg noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "01:19:35"
+ "Jun 27 2026"
+ "Sender PID: %d does not match polarisd pid: %d. Ignoring PSSG_MESSAGE_RESOURCE_STATE_UPDATE."
- "22:02:11"
- "Jun 16 2026"
```
