## amsondevicestoraged

> `/System/Library/PrivateFrameworks/OnDeviceStorage.framework/Support/amsondevicestoraged`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcd44` | `0xd2fc` | **`+0x5b8`** |
| `__TEXT.__oslogstring` | `—` | `0x150` | **`+0x150`** |
| `__DATA.__objc_const` | `0x168` | `0xd8` | **`-0x90`** |
| `__TEXT.__cstring` | `0xb1` | `0x51` | **`-0x60`** |
| `__DATA.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x1b0` | `0x1e0` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x9c0` | `0x9f0` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x80` | `0x60` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x470` | `0x490` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x4e8` | `0x500` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x14` | `—` | **`-0x14`** |
| `__TEXT.__const` | `0x438` | `0x428` | **`-0x10`** |
| `__TEXT.__objc_classname` | `0x44` | `0x34` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x20` | `0x18` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x8` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x9` | `0x1` | **`-0x8`** |
| `__TEXT.__objc_methname` | `0x55` | `0x4f` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__linkguard`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3.0.59.0.0
+3.1.10.0.0

+  - /usr/lib/libsqlite3.dylib

-  Functions: 199
-  Symbols:   253
+  - /usr/lib/swift/libswiftos.dylib
+  Functions: 204
+  Symbols:   257
Symbols:
+ _$s18OnDeviceFoundation13loggableErrorySSs0E0_pF
+ _$s19OnDeviceStorageCore12PluckRequestV_12connectionId07profileH0AcA11Expressible_p_S2StcfC
+ _$s19OnDeviceStorageCore13DeleteRequestV_12connectionId07profileH0AcA11Expressible_p_S2StcfC
+ _$s19OnDeviceStorageCore13InsertRequestV_10batchIndex13isLastInBatch12connectionId07profileN0AcA11Expressible_p_SiSbS2StAA11ClientErrorOYKcfC
+ _$s19OnDeviceStorageCore13SelectRequestV_10batchIndex0G8RowCount12connectionId07profileL0AcA11Expressible_p_S2iS2StAA11ClientErrorOYKcfC
+ _$s19OnDeviceStorageCore13UpdateRequestV_12connectionId07profileH0AcA11Expressible_p_S2StcfC
+ _$s19OnDeviceStorageCore17ConnectionRequestV12connectionId10credential07profileH0ACSS_AA17CredentialPayloadOSStcfC
+ _$s19OnDeviceStorageCore18ScalarValueRequestV_12connectionId07profileI0AcA11Expressible_p_S2StcfC
+ _$s19OnDeviceStorageCore20DisconnectionRequestV12connectionId07profileH0ACSS_SStcfC
+ _$s21OnDeviceStorageDaemon10ClientInfoV13forDirectCall8bundleId07profileK0ACSS_SStFZ
+ _$s2os6LoggerV14OnDeviceDaemonE9lifecycleACvgZ
+ _$s2os6LoggerV9logObjectSo03OS_a1_C0Cvg
+ _$s2os6LoggerVMa
+ _$sSS8UTF8ViewV13_foreignCountSiyF
+ _$sSo13os_log_type_ta0A0E4infoABvgZ
+ _$sSo13os_log_type_ta0A0E5errorABvgZ
+ _$ss11_StringGutsV16_foreignCopyUTF84intoSiSgSrys5UInt8VG_tF
+ _$ss11_StringGutsVN
+ _$ss13_StringObjectV10sharedUTF8SRys5UInt8VGvg
+ _$ss20__StaticArrayStorageCN
+ _$ss5UInt8VMn
+ __os_log_impl
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftos
+ _memcpy
+ _objc_release_x19
+ _os_log_type_enabled
+ _sqlite3_config
+ _swift_errorRetain
+ _swift_slowDealloc
- _$s18OnDeviceFoundation10LogMessageV13stringLiteralACSS_tcfC
- _$s18OnDeviceFoundation10LogMessageV19StringInterpolationV06appendG04safeyypSg_tF
- _$s18OnDeviceFoundation10LogMessageV19StringInterpolationV13appendLiteralyySSF
- _$s18OnDeviceFoundation10LogMessageV19StringInterpolationV15literalCapacity18interpolationCountAESi_SitcfC
- _$s18OnDeviceFoundation10LogMessageV19StringInterpolationVMa
- _$s18OnDeviceFoundation10LogMessageV19stringInterpolationA2C06StringG0V_tcfC
- _$s18OnDeviceFoundation10LogMessageVMa
- _$s18OnDeviceFoundation10LogMessageVMn
- _$s18OnDeviceFoundation6LoggerPAAE4infoyyAA10LogMessageVd_tF
- _$s18OnDeviceFoundation6LoggerPAAE5erroryyAA10LogMessageVd_tF
- _$s18OnDeviceFoundation8OSLoggerV0aB6DaemonE9lifecycleACvgZ
- _$s18OnDeviceFoundation8OSLoggerVAA6LoggerAAWP
- _$s18OnDeviceFoundation8OSLoggerVMa
- _$s19OnDeviceStorageCore12PluckRequestV_12connectionId04userH0AcA11Expressible_p_S2StcfC
- _$s19OnDeviceStorageCore13DeleteRequestV_12connectionId04userH0AcA11Expressible_p_S2StcfC
- _$s19OnDeviceStorageCore13InsertRequestV_10batchIndex13isLastInBatch12connectionId04userN0AcA11Expressible_p_SiSbS2StAA11ClientErrorOYKcfC
- _$s19OnDeviceStorageCore13SelectRequestV_10batchIndex0G8RowCount12connectionId04userL0AcA11Expressible_p_S2iS2StAA11ClientErrorOYKcfC
- _$s19OnDeviceStorageCore13UpdateRequestV_12connectionId04userH0AcA11Expressible_p_S2StcfC
- _$s19OnDeviceStorageCore17ConnectionRequestV12connectionId10credential04userH0ACSS_AA17CredentialPayloadOSStcfC
- _$s19OnDeviceStorageCore18ScalarValueRequestV_12connectionId04userI0AcA11Expressible_p_S2StcfC
- _$s19OnDeviceStorageCore20DisconnectionRequestV12connectionId04userH0ACSS_SStcfC
- _$s21OnDeviceStorageDaemon10ClientInfoV13forDirectCall8bundleId04userK0ACSS_SStFZ
- _OBJC_CLASS_$_NSObject
- _OBJC_METACLASS_$_NSObject
- _swift_allocBox
- _swift_getErrorValue
CStrings:
+ "Disabled process-wide SQLite lookaside buffers"
+ "‼️ Daemon launch failed: %{public}s"
+ "‼️ SQLite rejected the lookaside configuration (%d), so lookaside buffers stay enabled"
+ "‼️ SQLite was already initialized, so lookaside buffers stay enabled"
- "LinkGuardian"
- "check"
- "v16@0:8"
- "‼️ Daemon launch failed: "
```
