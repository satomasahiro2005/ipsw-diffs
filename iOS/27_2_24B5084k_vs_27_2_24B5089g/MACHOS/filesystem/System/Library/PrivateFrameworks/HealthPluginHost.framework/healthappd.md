## healthappd

> `/System/Library/PrivateFrameworks/HealthPluginHost.framework/healthappd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34c0c` | `0x36a94` | **`+0x1e88`** |
| `__DATA.__data` | `0x1058` | `0x1138` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x1e91` | `0x1f71` | **`+0xe0`** |
| `__TEXT.__eh_frame` | `0x4f0` | `0x5b8` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0x28a0` | `0x2900` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x8b8` | `0x910` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x828` | `0x880` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0x66c` | `0x6bc` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x1458` | `0x1488` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x6bc` | `0x6e6` | **`+0x2a`** |
| `__TEXT.__swift5_reflstr` | `0x9ed` | `0xa0d` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x468` | `0x480` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x434` | `0x440` | **`+0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x5b0` | `0x5bc` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x1330` | `0x1338` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xc` | `0x14` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xc` | `0x14` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 740
-  Symbols:   1015
-  CStrings:  402
+  Functions: 762
+  Symbols:   1031
+  CStrings:  405
Symbols:
+ _$s14HealthPlatform0A27AppOrchestrationCoordinatorP35gatherIHAGatedDailyAnalyticsPayload10completionyySDySSypGSg_s5Error_pSgtYbc_tFTq
+ _$s14HealthPlatform0A27AppOrchestrationCoordinatorP39gatherUnrestrictedDailyAnalyticsPayload10completionyySDySSypGSg_s5Error_pSgtYbc_tFTq
+ _$s14HealthPlatform0A41AppPluginDailyAnalyticsPayloadContributorMp
+ _$s14HealthPlatform30DailyAnalyticsPayloadCollectorV014gatherIHAGatedE0SDySSypGyYaF
+ _$s14HealthPlatform30DailyAnalyticsPayloadCollectorV014gatherIHAGatedE0SDySSypGyYaFTu
+ _$s14HealthPlatform30DailyAnalyticsPayloadCollectorV018gatherUnrestrictedE0SDySSypGyYaF
+ _$s14HealthPlatform30DailyAnalyticsPayloadCollectorV018gatherUnrestrictedE0SDySSypGyYaFTu
+ _$s14HealthPlatform30DailyAnalyticsPayloadCollectorV12contributors21environmentDataSource11healthStoreACSayAA0a9AppPlugincdE11Contributor_pG_So022HKAnalyticsEnvironmentiJ0CSo08HKHealthL0CtcfC
+ _$s14HealthPlatform30DailyAnalyticsPayloadCollectorVMa
+ _$s14HealthPlatform30DailyAnalyticsPayloadCollectorVMn
+ _$s15Synchronization5MutexVMa
+ _$sSdN
+ _$sSiN
+ _OBJC_CLASS_$_HKAnalyticsEnvironmentDataSource
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_storeEnumTagSinglePayloadGeneric
CStrings:
+ "[%{public}s] Could not gather IH&A gated daily analytics payload: %{public}s"
+ "[%{public}s] Could not gather unrestricted daily analytics payload: %{public}s"
+ "[%{public}s] Found %ld daily analytics payload contributor(s)."
```
