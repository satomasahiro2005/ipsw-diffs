## appleaccountd

> `/usr/libexec/appleaccountd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ef6b0` | `0x3f2bd0` | **`+0x3520`** |
| `__TEXT.__oslogstring` | `0x2095d` | `0x20c9d` | **`+0x340`** |
| `__DATA.__objc_const` | `0x1dde0` | `0x1e0f0` | **`+0x310`** |
| `__DATA.__bss` | `0x13b80` | `0x13980` | **`-0x200`** |
| `__DATA_CONST.__const` | `0x13e40` | `0x13f60` | **`+0x120`** |
| `__TEXT.__cstring` | `0x4599` | `0x46a9` | **`+0x110`** |
| `__TEXT.__eh_frame` | `0x147c4` | `0x146cc` | **`-0xf8`** |
| `__TEXT.__swift5_capture` | `0x654c` | `0x65fc` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0xc578` | `0xc5f4` | **`+0x7c`** |
| `__TEXT.__swift5_typeref` | `0x7921` | `0x7993` | **`+0x72`** |
| `__TEXT.__const` | `0x133b0` | `0x13350` | **`-0x60`** |
| `__DATA.__data` | `0x142c0` | `0x14300` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x7795` | `0x77d5` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x4d00` | `0x4d40` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x660c` | `0x6638` | **`+0x2c`** |
| `__TEXT.__swift5_reflstr` | `0x66b5` | `0x66d5` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x84f0` | `0x8510` | **`+0x20`** |
| `__DATA.__objc_data` | `0x3348` | `0x3360` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1710` | `0x1720` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1570` | `0x1580` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x11d0` | `0x11c4` | **`-0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x1670` | `0x1678` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xc7c` | `0xc74` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x224` | `0x22c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x884` | `0x87c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-1064.0.0.0.0
+1067.0.0.0.0

-  Functions: 10230
-  Symbols:   1814
-  CStrings:  4164
+  Functions: 10245
+  Symbols:   1815
+  CStrings:  4183
Symbols:
+ _$s12AppleAccount21DeviceListFetchResultV10versionTagSSSgvg
+ _$s12AppleAccount9SetupBaseC7context4base16btAddressMonitor0G13StateProvider5queueACyxGAA09BluetoothD13ConfigurationV_xSo13CBActivatable_So013CBAdvertisingH9ReportingpAA0mjK0CSo012OS_dispatch_L0Ctcfc
+ _$s8Dispatch0A3QoSV13userInitiatedACvgZ
+ _AKDeviceListChangedNotification
+ _NSLocalizedDescriptionKey
- _$s10Foundation6LocaleVMa
- _$s10Foundation6LocaleVMn
- _$s12AppleAccount9SetupBaseC7context4base16btAddressMonitor0G13StateProviderACyxGAA09BluetoothD13ConfigurationV_xSo13CBActivatable_So013CBAdvertisingH9ReportingpAA0ljK0Ctcfc
- _$sSy10FoundationE7compare_7options5range6localeSo18NSComparisonResultVqd___So22NSStringCompareOptionsVSnySS5IndexVGSgAA6LocaleVSgtSyRd__lF
CStrings:
+ " %s Skipping duplicate resolved handle: %s"
+ " Trusted Contacts Preflight"
+ "AppInstallObserver: Handling distributed notification. Event: %s"
+ "AppInstallObserver: Missing bundleIDs for state-change notification."
+ "AppInstallObserver: state change for %s"
+ "Cached %ld devices (serveEnabled: %{bool}d)"
+ "Caller-initiated force refresh, bypassing cache reads"
+ "Cloud sync failed before %s; deferring readiness checks: %s"
+ "Dataclass App Install Observer - State change for %s"
+ "Device list changed notification received: %s"
+ "Device list fetch ETag — prior: %{private,mask.hash}s, fresh: %{private,mask.hash}s"
+ "PCS keys upload completed successfully (retries: %{public}ld). Status code: %{public}ld"
+ "PCS keys upload failed with HTTP status %{public}ld."
+ "PCS keys upload returned HTTP 500 (server could not decrypt). Re-running flow with re-encrypted keys. Retries remaining: %{public}ld"
+ "PCS keys upload returned no response."
+ "PCS pre-encryption blob for services [%{public}s] (base64): %{private}s"
+ "accuracyRecorder"
+ "attachPdpStateAndHealth: pdpHealth unavailable (property nil, cache nil)"
+ "attachPdpStateAndHealth: pdpHealth=%@ attached"
+ "attachPdpStateAndHealth: pdpState=%lu source=%s"
+ "com.apple.LaunchServices.applicationStateChanged"
+ "com.apple.appleaccount.setupbase"
+ "com.apple.appleaccountd.identity.background-refresh"
+ "com.apple.appleaccountd.identity.background-upload"
+ "com.apple.authkit.device-list-category-changed"
+ "initWithUnsignedInteger:"
+ "isWalrusPreEncryptionBlobLoggingEnabled"
- "AppInstallObserver: Handling distributed notification."
- "Cached %ld devices with TTL %fs"
- "Caller-initiated force refresh, bypassing cache reads (writes %s)"
- "Device list changed notification received"
- "PCS keys upload completed successfully."
- "Rejecting outdated version: new='%{private,mask.hash}s' < current='%{private,mask.hash}s'"
- "Skipping cache write — kill switch engaged"
- "com.apple.authkit.trusted-device-list-changed"
```
