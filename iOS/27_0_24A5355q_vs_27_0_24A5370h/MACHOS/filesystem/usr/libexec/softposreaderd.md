## softposreaderd

> `/usr/libexec/softposreaderd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x419478` | `0x41de1c` | **`+0x49a4`** |
| `__TEXT.__cstring` | `0x1130b` | `0x1187b` | **`+0x570`** |
| `__DATA.__bss` | `0x15be0` | `0x15ce0` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0xc890` | `0xc924` | **`+0x94`** |
| `__DATA_CONST.__const` | `0x18170` | `0x181e0` | **`+0x70`** |
| `__TEXT.__const` | `0x88260` | `0x882d0` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0xcbee` | `0xcb7e` | **`-0x70`** |
| `__DATA.__objc_const` | `0x91b8` | `0x9178` | **`-0x40`** |
| `__TEXT.__constg_swiftt` | `0x78f4` | `0x7910` | **`+0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0xe28` | `0xe40` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4da8` | `0x4dc0` | **`+0x18`** |
| `__DATA.__data` | `0xc778` | `0xc788` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x4220` | `0x4230` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x429d` | `0x428d` | **`-0x10`** |
| `__DATA.__objc_data` | `0x21b0` | `0x21a8` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x2118` | `0x2120` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xcd4` | `0xcdc` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x528` | `0x52c` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x39c` | `0x3a0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-50.27.0.0.0
+50.30.0.0.0

-  Functions: 6108
-  Symbols:   1681
-  CStrings:  3528
+  Functions: 6131
+  Symbols:   1683
+  CStrings:  3552
Symbols:
+ _$s20KernelManagerLibrary8BeeStateV7versionSSSgvg
+ _$s9SEService10SESnapshotCMn
+ _$ss6UInt32VMn
- _$ss15CollectionOfOneVMn
CStrings:
+ ", paymentAppletVersion: "
+ ", stingerConfigID: "
+ ", stingerVersion: "
+ "Appended entry of size: %ld"
+ "Could not provide device protection timer duration: %@"
+ "Could not provide device protection timer duration: negative duration"
+ "Failed to get device state after successful installation: %@"
+ "Got current SE snapshot: %{public}s"
+ "No TPID for KernelToken"
+ "Secure Reader Blob Failed"
+ "_readCard(parameters:delegate:)"
+ "afterPostReadProcessing()"
+ "decodeKCSOTAResponse(json:)"
+ "decodeKernelConfig(json:)"
+ "decodeLRPConfig(json:)"
+ "getDeletableClients()"
+ "getEncryptionResults(payload:lrSessionID:)"
+ "getUnifiedReaderBAASigner()"
+ "getWallTime(currentCpuTime:currentRtcResetCount:storedData:)"
+ "handleSessionDidReceiveThermalIndication(deviceIsTooHot:session:)"
+ "handleUpdate(event:)"
+ "init(dictionary:)"
+ "init(mpocMonitorManager:mpocAttestationManager:safAllowedDuration:queue:certificateManager:signerFactory:secureTimeKeeper:auditor:analytics:managedData:systemInfo:secureElement:enforceJCOPVersion:profileManager:vtidIdentityManager:launchFeedbackFramework:payAppletTagParser:)"
+ "init(oasisService:)"
+ "init(parameters:panKEK:pinKEK:ecdsaCertificate:delegate:)"
+ "init(parameters:panKEK:pinKEK:timekeeper:ecdsaCertificate:delegate:analytics:)"
+ "init(persist:auditorFactory:certificateVerifierFactory:analytics:systemInfo:secureElement:secureTimeKeeper:unifiedReaderTimeKeeper:randomNumberGenerator:settings:)"
+ "init(secureTimeKeeper:caLogger:)"
+ "init(session:utilityProvider:)"
+ "init(storageURL:seid:isProduction:)"
+ "makeUnifiedReader()"
+ "makeUnifiedReaderPINController()"
+ "paymentAppletVersion"
+ "shouldUseUnifiedReader()"
+ "translateTrackError(_:)"
+ "unifiedReaderPINControllerProxy(reply:)"
- ".appendEvent(%s), hex: %s"
- "Could not provide the device protection timer duration: %@"
- "Error on getAppletVersion: %s"
- "Error on retrieveGlobalID: %s"
- "GlobalId: %{public}s"
- "TPID of KernelToken: %{public}s"
- "applet version array bad length"
- "applet version not acceptable"
- "applet version: %{public}s"
- "appletService"
- "global config ID is absent"
- "init(mpocMonitorManager:mpocAttestationManager:safAllowedDuration:queue:certificateManager:signerFactory:secureTimeKeeper:auditor:analytics:managedData:systemInfo:secureElement:enforceJCOPVersion:profileManager:vtidIdentityManager:launchFeedbackFramework:payAppletTagParser:appletService:)"
```
