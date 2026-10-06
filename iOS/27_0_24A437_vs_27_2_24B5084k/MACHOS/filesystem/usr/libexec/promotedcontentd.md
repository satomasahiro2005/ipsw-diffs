## promotedcontentd

> `/usr/libexec/promotedcontentd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3db4b4` | `0x3dcae4` | **`+0x1630`** |
| `__DATA.__data` | `0xe578` | `0xe998` | **`+0x420`** |
| `__DATA.__objc_const` | `0x2b398` | `0x2b750` | **`+0x3b8`** |
| `__TEXT.__const` | `0x2b1da` | `0x2b45a` | **`+0x280`** |
| `__DATA.__bss` | `0xdec0` | `0xe0c0` | **`+0x200`** |
| `__TEXT.__constg_swiftt` | `0x6420` | `0x65bc` | **`+0x19c`** |
| `__TEXT.__swift5_fieldmd` | `0x49d8` | `0x4b5c` | **`+0x184`** |
| `__TEXT.__objc_classname` | `0x4c07` | `0x4d87` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x1123c` | `0x113ac` | **`+0x170`** |
| `__TEXT.__swift5_reflstr` | `0x3706` | `0x3846` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x2701d` | `0x2711d` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x1c400` | `0x1c4f0` | **`+0xf0`** |
| `__DATA.__objc_data` | `0x9848` | `0x9908` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x15e05` | `0x15e95` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x70a0` | `0x7128` | **`+0x88`** |
| `__TEXT.__swift5_typeref` | `0x4366` | `0x43d8` | **`+0x72`** |
| `__TEXT.__objc_methtype` | `0x513d` | `0x518d` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x1a1e0` | `0x1a220` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x5d50` | `0x5d80` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0xfe8` | `0x1010` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x850` | `0x870` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x2eb8` | `0x2ed0` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x5c8` | `0x5e0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x9480` | `0x9490` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1618` | `0x1628` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x18d8` | `0x18e0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x124` | `0x128` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-557.1.33.0.0
+557.2.8.0.0

-  Functions: 11744
-  Symbols:   2298
-  CStrings:  11663
+  Functions: 11786
+  Symbols:   2300
+  CStrings:  11683
Symbols:
+ _APSimulateCrashNoKillProcessWithoutABCReport
+ _AnalyticsSendEventLazy
CStrings:
+ "@\"NSDictionary\"8@?0"
+ "Database config saved to UserDefaults. busyTimeout: %ld, coreAnalyticsThresholdMs: %ld"
+ "Database config saved to UserDefaults. busyTimeout: %ld, coreAnalyticsThresholdMs: %ld, slowQueryThresholdMs: %ld"
+ "Database.CoreAnalyticsThresholdMs"
+ "Database.SlowQueryThresholdMs"
+ "Depositing age noising application diagnostic sample %s"
+ "Error: Config download failed"
+ "Error: Config extraction failed"
+ "Triaging age noising application diagnostics for actual birth year: %{sensitive}s, noised birth year: %{sensitive}s, eligibility: %s"
+ "[SLPFlagCheck] Captured incrementalityAppStoreSLP=%{public}d at request time"
+ "_TtC16promotedcontentd20DatabaseConfigSyncer"
+ "_TtC16promotedcontentd39TracingAgeNoisingApplicationDiagnostics"
+ "_TtC16promotedcontentd40NullAgeNoisingApplicationDiagnosticDepot"
+ "_TtC16promotedcontentd42DepositingAgeNoisingApplicationDiagnostics"
+ "_TtC16promotedcontentd43TracingAgeNoisingApplicationDiagnosticDepot"
+ "_TtC16promotedcontentd49CoreAnalyticsAgeNoisingApplicationDiagnosticDepot"
+ "_TtC16promotedcontentd51PredeterminedAgeNoisingQualifierConfigurationSource"
+ "accountInfo"
+ "ageNoisingApplicationDiagnosticDepot"
+ "ageNoisingConfiguration"
+ "depot"
+ "incrementalityAppStoreSLPEnabled"
+ "isInternalBuild"
+ "promotedcontentd.DatabaseConfigSyncer"
+ "randomGenerator"
+ "setFlagEnabledAtRequest:"
+ "tracedDepot"
+ "tracedDiagnostics"
- "Database busy timeout saved to UserDefaults: %ld"
- "Off"
- "On"
- "Sending CoreAnalytics event '%s' with payload: %s"
- "_TtC16promotedcontentd25DatabaseBusyTimeoutSyncer"
- "_TtC16promotedcontentd45DefaultAgeNoisingQualifierConfigurationSource"
- "promotedcontentd.DatabaseBusyTimeoutSyncer"
- "storefrontIDSource"
```
