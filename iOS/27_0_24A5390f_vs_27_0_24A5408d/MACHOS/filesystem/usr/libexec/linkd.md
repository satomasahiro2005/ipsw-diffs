## linkd

> `/usr/libexec/linkd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b429c` | `0x1b95fc` | **`+0x5360`** |
| `__DATA.__bss` | `0x7670` | `0x7cf0` | **`+0x680`** |
| `__TEXT.__const` | `0xa300` | `0xa760` | **`+0x460`** |
| `__TEXT.__oslogstring` | `0x628f` | `0x658f` | **`+0x300`** |
| `__TEXT.__eh_frame` | `0x153ac` | `0x1565c` | **`+0x2b0`** |
| `__DATA.__data` | `0x74c8` | `0x7670` | **`+0x1a8`** |
| `__TEXT.__swift5_typeref` | `0x4c7c` | `0x4dcc` | **`+0x150`** |
| `__TEXT.__auth_stubs` | `0x3b10` | `0x3c50` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x7718` | `0x7800` | **`+0xe8`** |
| `__DATA.__objc_const` | `0x35b0` | `0x3688` | **`+0xd8`** |
| `__DATA_CONST.__const` | `0x10c48` | `0x10d10` | **`+0xc8`** |
| `__DATA_CONST.__auth_got` | `0x1d90` | `0x1e30` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x35dc` | `0x3674` | **`+0x98`** |
| `__TEXT.__cstring` | `0x454f` | `0x45cf` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x2884` | `0x28fc` | **`+0x78`** |
| `__TEXT.__objc_methname` | `0x5dcd` | `0x5e2d` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x688` | `0x6e8` | **`+0x60`** |
| `__DATA.__objc_data` | `0xb00` | `0xb58` | **`+0x58`** |
| `__DATA_CONST.__auth_ptr` | `0x23b0` | `0x23f8` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x4eb8` | `0x4efc` | **`+0x44`** |
| `__TEXT.__objc_classname` | `0xc1b` | `0xc5b` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x3b00` | `0x3b40` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0xc50` | `0xc88` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x5ac` | `0x5e0` | **`+0x34`** |
| `__DATA_CONST.__got` | `0xee8` | `0xf18` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x21c` | `0x244` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x2371` | `0x2391` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0xa90` | `0xab0` | **`+0x20`** |
| `__DATA.__common` | `0xfa0` | `0xfb8` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1460` | `0x1478` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x14ec` | `0x1504` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0xa50` | `0xa64` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x320` | `0x32c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x148` | `0x150` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-301.0.45.4.101
+301.0.51.1.102

+  - /System/Library/PrivateFrameworks/PowerLog.framework/PowerLog

-  Functions: 11185
-  Symbols:   1749
-  CStrings:  1864
+  Functions: 11269
+  Symbols:   1776
+  CStrings:  1883
Symbols:
+ _$s10Foundation8TimeZoneV10identifierACSgSSh_tcfC
+ _$s12LinkMetadata17UniqueBundleCacheC5label6sourceACSS_AA0cD7HashMapCtcfc
+ _$s12LinkMetadata19UniqueBundleHashMapC6bundle3forSo8NSBundleCSg10Foundation3URLV_tF
+ _$s12LinkMetadata19UniqueBundleHashMapC6sharedACvgZ
+ _$s12LinkMetadata19UniqueBundleHashMapCMa
+ _$s12LinkMetadata29LNBundleValidationInformationC8lsRecordSo08LSBundleG0CSgvgTj
+ _$s15AppIntentsIndex08MetadataC0V07processD13ForNextBundle11bundleCache08prebuiltD8Providers6ResultOyAC08IndexingM0VAA0hN7FailureVGSg04LinkD006UniquehJ0C_AO08PrebuiltdL0_pSgtKF
+ _$s15AppIntentsIndex08MetadataC0V14IndexingResultV10queryCountSivg
+ _$s15AppIntentsIndex08MetadataC0V14IndexingResultV10totalCountSivg
+ _$s15AppIntentsIndex08MetadataC0V14IndexingResultV11entityCountSivg
+ _$s15AppIntentsIndex08MetadataC0V14IndexingResultV11intentCountSivg
+ _$s15AppIntentsIndex08MetadataC0V14IndexingResultV13estimatedSizeSivg
+ _$s15AppIntentsIndex08MetadataC0V14IndexingResultV16bundleIdentifierSSvg
+ _$s15AppIntentsIndex08MetadataC0V14IndexingResultV7endDate10Foundation0H0Vvg
+ _$s15AppIntentsIndex08MetadataC0V14IndexingResultV9enumCountSivg
+ _$s15AppIntentsIndex08MetadataC0V14IndexingResultV9startDate10Foundation0H0Vvg
+ _$s15AppIntentsIndex08MetadataC0V14IndexingResultVMa
+ _$s15AppIntentsIndex08MetadataC0V14IndexingResultVMn
+ _$sSo17OS_dispatch_queueC8DispatchE20AutoreleaseFrequencyO8workItemyA2EmFWC
+ _$sSo24OS_dispatch_queue_serialC8DispatchE10AttributesVMa
+ _$sSo24OS_dispatch_queue_serialC8DispatchE10AttributesVMn
+ _$sSo24OS_dispatch_queue_serialC8DispatchE10AttributesVs10SetAlgebraACMc
+ _$sSo24OS_dispatch_queue_serialC8DispatchE5label3qos10attributes20autoreleaseFrequency6targetABSS_AC0E3QoSVAbCE10AttributesVSo0a1_b1_C0CACE011AutoreleaseJ0OANSgtcfC
+ _$sSo33OS_dispatch_queue_serial_executorC8DispatchE23asUnownedSerialExecutorSceyF
+ _NSFileProtectionCompleteUntilFirstUserAuthentication
+ _NSFileProtectionKey
+ _OBJC_CLASS_$_OS_dispatch_queue_serial
+ _PPSCreateTelemetryIdentifier
+ _PPSSendTelemetry
- _$s12LinkMetadata17UniqueBundleCacheC5labelACSS_tcfc
- _$s15AppIntentsIndex08MetadataC0V07processD13ForNextBundle11bundleCache08prebuiltD8Providers6ResultOySSAA0H15IndexingFailureVGSg04LinkD006UniquehJ0C_AM08PrebuiltdL0_pSgtKF
CStrings:
+ "Client %{public}s disconnected"
+ "Failed to generate powerlog telemetry identifier"
+ "No unique bundle for %{public}s; localization cache will not be retained for this connection"
+ "_TtCC10LinkDaemon24MetadataIndexCoordinator15WriteSerializer"
+ "__pps_timeSensitiveEntryDate"
+ "appintents-backup"
+ "com.apple.linkd.metadata.writes"
+ "fetchProcessInstanceIdentifiersGroupedByBundleIdentifierWithReply:"
+ "fileExistsAtPath:"
+ "restrictionsDidChange: fanout to %{public}ld subscriber(s) pids=[%{public}s]"
+ "setAttributes:ofItemAtPath:error:"
+ "subscribe: pid %{public}d added, reusing held os_transaction (subscribers=%{public}ld)"
+ "subscribe: pid %{public}d already subscribed (subscribers=%{public}ld)"
+ "subscribe: pid %{public}d is first subscriber — acquired os_transaction (subscribers=%{public}ld)"
+ "uniqueBundle"
+ "unsubscribe: pid %{public}d removed, os_transaction still held (subscribers=%{public}ld)"
+ "unsubscribe: pid %{public}d was last subscriber — released os_transaction (subscribers=0)"
+ "unsubscribe: pid %{public}d was not a subscriber (subscribers=%{public}ld)"
+ "writeSerializer"
+ "yyyy-MM-dd HH:mm:ss.SSS"
- "restrictionsDidChange: fanout to %{public}ld subscriber(s)"
```
