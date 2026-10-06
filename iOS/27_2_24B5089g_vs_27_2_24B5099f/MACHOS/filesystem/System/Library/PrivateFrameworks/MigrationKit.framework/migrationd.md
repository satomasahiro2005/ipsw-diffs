## migrationd

> `/System/Library/PrivateFrameworks/MigrationKit.framework/migrationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b7f0` | `0x1dcc8` | **`+0x24d8`** |
| `__TEXT.__eh_frame` | `0x14e0` | `0x1700` | **`+0x220`** |
| `__TEXT.__cstring` | `0x43c` | `0x53c` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x984` | `0xa14` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x7a0` | `0x830` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x11e0` | `0x1260` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x878` | `0x8f0` | **`+0x78`** |
| `__DATA_CONST.__auth_got` | `0x8f8` | `0x938` | **`+0x40`** |
| `__DATA.__data` | `0x5d0` | `0x5f0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x410` | `0x430` | **`+0x20`** |
| `__TEXT.__const` | `0x6aa` | `0x6ca` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x58b` | `0x5ab` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x440` | `0x460` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x1c4` | `0x1e0` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0x4ab` | `0x4c5` | **`+0x1a`** |
| `__TEXT.__objc_methlist` | `0x44c` | `0x464` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0xaed` | `0xb05` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x428` | `0x440` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0xa0` | `0xb4` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__DATA.__objc_const` | `0x720` | `0x728` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xa4` | `0xac` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1439.0.0.0.0
+1441.40.1.0.0

-  Functions: 453
-  Symbols:   484
-  CStrings:  244
+  Functions: 474
+  Symbols:   499
+  CStrings:  256
Symbols:
+ _$s12MigrationKit20TransferCancelOriginO04userD0yA2CmFWC
+ _$s12MigrationKit20TransferCancelOriginO8uiExitedyA2CmFWC
+ _$s12MigrationKit20TransferCancelOriginO9uiCrashedyA2CmFWC
+ _$s12MigrationKit20TransferCancelOriginOMa
+ _$s12MigrationKit20TransferCancelOriginOMn
+ _$s12MigrationKit21TransferCancelContextV6origin7message15underlyingError8function4file4lineAcA0cD6OriginO_SSs0I0_pSgs12StaticStringVAOSutcfC
+ _$s12MigrationKit21TransferCancelContextV6originAA0cD6OriginOvg
+ _$s12MigrationKit21TransferCancelContextVMa
+ _$s12MigrationKit21TransferCancelContextVMn
+ _$s12MigrationKit27AppContentTelemetryBackstopO15registerHandleryyFZ
+ _$s12MigrationKit27AppContentTelemetryBackstopO9reconcileyyYaFZ
+ _$s12MigrationKit27AppContentTelemetryBackstopO9reconcileyyYaFZTu
+ _$s12MigrationKit6ClientC25currentTelemetrySessionIDs6UInt16VSgyYaFTjTu
+ _$s12MigrationKit6ClientC6cancel0D7ContextyAA014TransferCancelE0VSg_tYaFTjTu
+ _$s12MigrationKit6ServerC25currentTelemetrySessionIDs6UInt16VSgyYaFTjTu
+ _$s12MigrationKit6ServerC6cancel0D7ContextyAA014TransferCancelE0VSg_tYaFTjTu
+ _$sSS10describingSSx_tclufC
+ _$ss11_StringGutsV4growyySiF
- _$s12MigrationKit6ClientC6cancelyyYaFTjTu
- _$s12MigrationKit6ServerC6cancelyyYaFTjTu
- _swift_retain_x28
CStrings:
+ "UI connection interrupted: "
+ "UI connection invalidated: "
+ "User cancelled migration from the UI"
+ "cancel(cancelContext:)"
+ "cancel(origin: %{public}s)"
+ "com.apple.migrationd.deferred-tasks"
+ "didUpdateTelemetrySessionID:"
+ "interrupted(pid:processName:)"
+ "invalidated(pid:processName:)"
+ "no telemetry session id to push to the cellular client."
+ "pushing the telemetry session id. session_id=%hu"
+ "v20@0:8S16"
```
