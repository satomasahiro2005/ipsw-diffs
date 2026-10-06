## JetEngine

> `/System/Library/PrivateFrameworks/JetEngine.framework/JetEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4bf5d0` | `0x4c4608` | **`+0x5038`** |
| `__DATA.__bss` | `0x36530` | `0x36ab0` | **`+0x580`** |
| `__TEXT.__cstring` | `0x12bd6` | `0x12fe6` | **`+0x410`** |
| `__TEXT.__const` | `0x9bc88` | `0x9bfe8` | **`+0x360`** |
| `__AUTH_CONST.__const` | `0x32bc8` | `0x32eb0` | **`+0x2e8`** |
| `__DATA.__data` | `0xdd38` | `0xdf58` | **`+0x220`** |
| `__TEXT.__unwind_info` | `0x11a40` | `0x11b68` | **`+0x128`** |
| `__TEXT.__eh_frame` | `0x25d3c` | `0x25e3c` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0xc308` | `0xc3d4` | **`+0xcc`** |
| `__AUTH_CONST.__objc_const` | `0xa1f0` | `0xa280` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x77c` | `0x80c` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x7aeb` | `0x7b7b` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0x15c` | `0x1e4` | **`+0x88`** |
| `__TEXT.__swift5_assocty` | `0x18f0` | `0x1968` | **`+0x78`** |
| `__TEXT.__constg_swiftt` | `0xda4c` | `0xdac0` | **`+0x74`** |
| `__TEXT.__swift5_typeref` | `0xf226` | `0xf296` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x2b30` | `0x2b98` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x1dd4` | `0x1e24` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x1360` | `0x13a0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1908` | `0x1940` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x2180` | `0x21ac` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0xfa8` | `0xfc0` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x1414` | `0x13fc` | **`-0x18`** |
| `__TEXT.__swift_as_entry` | `0x9f4` | `0x9e4` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0xe0` | `0xec` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x1070` | `0x107c` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0xa8c` | `0xa80` | **`-0xc`** |
| `__AUTH.__data` | `0x7e28` | `0x7e30` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x8880` | `0x887c` | **`-0x4`** |

### Other Changes

```diff

-10.0.47.0.0
+10.1.8.0.0

-  Functions: 22723
-  Symbols:   7431
-  CStrings:  1916
+  Functions: 22818
+  Symbols:   7458
+  CStrings:  1941
Symbols:
+ -[JEHashTreatmentAction customTraversal]
+ -[JEHashTreatmentAction didResolveSecret]
+ -[JEHashTreatmentAction resolveSecret]
+ -[JEHashTreatmentAction resolvedSecret]
+ -[JEHashTreatmentAction setCustomTraversal:]
+ -[JEHashTreatmentAction setDidResolveSecret:]
+ -[JEHashTreatmentAction setResolvedSecret:]
+ GCC_except_table2
+ GCC_except_table4
+ _OBJC_IVAR_$_JEHashTreatmentAction._customTraversal
+ _OBJC_IVAR_$_JEHashTreatmentAction._didResolveSecret
+ _OBJC_IVAR_$_JEHashTreatmentAction._resolvedSecret
+ ___38-[JEHashTreatmentAction resolveSecret]_block_invoke
+ ___swift_memcpy184_8
+ _associated conformance 9JetEngine18AssetPendingOriginOSHAASQ
+ _associated conformance 9JetEngine29LocaleUserPreferenceOverridesVSHAASQ
+ _associated conformance 9JetEngine29LocaleUserPreferenceOverridesVs10SetAlgebraAASQ
+ _associated conformance 9JetEngine29LocaleUserPreferenceOverridesVs10SetAlgebraAAs25ExpressibleByArrayLiteral
+ _associated conformance 9JetEngine29LocaleUserPreferenceOverridesVs9OptionSetAASY
+ _associated conformance 9JetEngine29LocaleUserPreferenceOverridesVs9OptionSetAAs0H7Algebra
+ _symbolic _____ 9JetEngine18AssetPendingOriginO
+ _symbolic _____ 9JetEngine19MetricsCommonFieldsV
+ _symbolic _____ 9JetEngine29LocaleUserPreferenceOverridesV
+ _symbolic _____Sg 10Foundation6LocaleV17MeasurementSystemV
+ _symbolic _____Sg 10Foundation6LocaleV7WeekdayO
+ _symbolic _____Sg 10Foundation6LocaleV9HourCycleO
+ _symbolic _____y_____G 9JetEngine14DaemonResponseO AA0c2NoD0V
+ _symbolic _____y_____G 9JetEngine27LowMemoryMetricsEventLinterC AA08StandardE13FieldsBuilderV
+ _type_layout_string 9JetEngine19MetricsCommonFieldsV
+ _type_layout_string 9JetEngine29LocaleUserPreferenceOverridesV
- ___39-[JEHashTreatmentAction hashOf:userId:]_block_invoke
- ___swift_closure_destructor.37Tm
- ___swift_memcpy168_8
CStrings:
+ " = 'push' THEN pending_origin ELSE "
+ " END,\n    modified_at = "
+ ",\n    pending_origin = "
+ ",\n    pending_origin = CASE WHEN pending = 1 AND pending_origin IN ('checkpoint', 'apsReconnect') AND "
+ ",\n    schedule_to = "
+ "ALTER TABLE push_subscription ADD COLUMN pending_origin TEXT"
+ "AssetPushSubscriptionSQLiteStore DB migration to v7..."
+ "DaemonSession.sendSync"
+ "Error occurred when sending synchronous request to daemon: "
+ "JetEngine: Ignoring unparseable metrics field filter predicate \"%@\": %@"
+ "JetEngine: Ignoring unparseable metrics filter predicate \"%@\": %@"
+ "MetricsCommonFields: use the typed property for '"
+ "Received an XPC error sending synchronous request: "
+ "Sending synchronous prewarm request to daemon"
+ "Sending synchronous request to daemon: "
+ "UPDATE push_subscription SET\n    pending = 1,\n    download_attempts = 0,\n    schedule_from = "
+ "UPDATE push_subscription SET pending = 0, download_attempts = NULL, schedule_from = NULL, schedule_to = NULL, priority = NULL, server_timestamp = NULL, pending_origin = NULL, modified_at = "
+ "XPC session (sendSync) cancelled: "
+ "apsReconnect"
+ "checkpoint"
+ "customTraversal"
+ "dictionaryOfArrays"
+ "pendingOriginRaw"
+ "push"
+ "push304Retry"
+ "sendSync complete"
+ "✅ AssetPushSubscriptionSQLiteStore DB migration to v7 complete"
- "Sending one-way prewarm request to daemon"
- "UPDATE push_subscription SET pending = 0, download_attempts = NULL, schedule_from = NULL, schedule_to = NULL, priority = NULL, server_timestamp = NULL, modified_at = "
```
