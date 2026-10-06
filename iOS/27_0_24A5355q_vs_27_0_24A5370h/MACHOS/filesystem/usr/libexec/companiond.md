## companiond

> `/usr/libexec/companiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7eb94` | `0x894b4` | **`+0xa920`** |
| `__TEXT.__eh_frame` | `0x3f98` | `0x4cb0` | **`+0xd18`** |
| `__TEXT.__auth_stubs` | `0x2b50` | `0x2d60` | **`+0x210`** |
| `__TEXT.__unwind_info` | `0x2358` | `0x2520` | **`+0x1c8`** |
| `__DATA_CONST.__const` | `0x2418` | `0x25d0` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0x3edb` | `0x404b` | **`+0x170`** |
| `__TEXT.__const` | `0x1f56` | `0x20b6` | **`+0x160`** |
| `__TEXT.__swift5_capture` | `0x674` | `0x784` | **`+0x110`** |
| `__DATA_CONST.__auth_got` | `0x15b8` | `0x16c0` | **`+0x108`** |
| `__TEXT.__cstring` | `0x2521` | `0x2625` | **`+0x104`** |
| `__DATA.__objc_const` | `0x7540` | `0x7640` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0x7a4` | `0x894` | **`+0xf0`** |
| `__DATA.__data` | `0x1db0` | `0x1e70` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0xbd2` | `0xc86` | **`+0xb4`** |
| `__TEXT.__swift_as_cont` | `0x2ec` | `0x390` | **`+0xa4`** |
| `__TEXT.__objc_methname` | `0x6015` | `0x60b5` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0xc88` | `0xd10` | **`+0x88`** |
| `__TEXT.__swift5_fieldmd` | `0x80c` | `0x86c` | **`+0x60`** |
| `__TEXT.__swift_as_ret` | `0x174` | `0x1c0` | **`+0x4c`** |
| `__TEXT.__swift_as_entry` | `0x174` | `0x1a8` | **`+0x34`** |
| `__DATA_CONST.__auth_ptr` | `0x550` | `0x560` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x8a8` | `0x8b8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-520.0.0.0.0
+524.0.16.0.0

+  - /System/Library/PrivateFrameworks/FindMyLocate.framework/FindMyLocate

-  Functions: 2205
-  Symbols:   1223
-  CStrings:  1925
+  Functions: 2312
+  Symbols:   1273
+  CStrings:  1943
Symbols:
+ _$s12FindMyLocate12ClientOriginO5otheryA2CmFWC
+ _$s12FindMyLocate12ClientOriginOMa
+ _$s12FindMyLocate13RequestOriginVMa
+ _$s12FindMyLocate13RequestOriginVyAcA06ClientE0OcfC
+ _$s12FindMyLocate6DeviceV06isThisD0Sbvg
+ _$s12FindMyLocate6DeviceVMa
+ _$s12FindMyLocate7SessionC27activeLocationSharingDevice6cachedAA0H0VSb_tYaKF
+ _$s12FindMyLocate7SessionC27activeLocationSharingDevice6cachedAA0H0VSb_tYaKFTu
+ _$s12FindMyLocate7SessionCMa
+ _$s12FindMyLocate7SessionCyAcA13RequestOriginVYacfc
+ _$s12FindMyLocate7SessionCyAcA13RequestOriginVYacfcTu
+ _$s14CoreUtilsSwift14CUOPACKDecoderC6decode_4fromxxm_10Foundation4DataVtKSeRzlF
+ _$s14CoreUtilsSwift14CUOPACKDecoderCACycfc
+ _$s14CoreUtilsSwift14CUOPACKDecoderCMa
+ _$s14CoreUtilsSwift14CUOPACKEncoderC13ConfigurationV7defaultAEvgZ
+ _$s14CoreUtilsSwift14CUOPACKEncoderC13ConfigurationVMa
+ _$s14CoreUtilsSwift14CUOPACKEncoderC13configurationA2C13ConfigurationV_tcfc
+ _$s14CoreUtilsSwift14CUOPACKEncoderC6encodey10Foundation4DataVxKSERzlF
+ _$s14CoreUtilsSwift14CUOPACKEncoderCMa
+ _$s14CoreUtilsSwift7CUErrorC9userError_10underlyingACSo06CUUserF4CodeV_SSSgs0F0_pSgtcfc
+ _$s14CoreUtilsSwift9CUWeakBoxV4itemxSgvg
+ _$s14CoreUtilsSwift9CUWeakBoxVMn
+ _$s14CoreUtilsSwift9CUWeakBoxVyACyxGxcfC
+ _$s17CompanionServices19CPSRequesterMessageO14SessionEndInfoV9sessionIDAESS_tcfC
+ _$s17CompanionServices19CPSRequesterMessageO14SessionEndInfoV9sessionIDSSvg
+ _$s17CompanionServices19CPSRequesterMessageO14SessionEndInfoVMa
+ _$s17CompanionServices19CPSRequesterMessageO15sessionEventAckyA2CmFWC
+ _$s17CompanionServices19CPSRequesterMessageO16SessionStartInfoV13configuration9sessionIDAeA0C20UseCaseConfigurationV_SStcfC
+ _$s17CompanionServices19CPSRequesterMessageO16SessionStartInfoV13configurationAA0C20UseCaseConfigurationVvg
+ _$s17CompanionServices19CPSRequesterMessageO16SessionStartInfoV9sessionIDSSvg
+ _$s17CompanionServices19CPSRequesterMessageO16SessionStartInfoVMa
+ _$s17CompanionServices19CPSRequesterMessageO17sessionEndRequestyA2C07SessionF4InfoV_tcACmFWC
+ _$s17CompanionServices19CPSRequesterMessageO19sessionStartRequestyA2C07SessionF4InfoV_tcACmFWC
+ _$s17CompanionServices19CPSRequesterMessageOMa
+ _$s17CompanionServices19CPSResponderMessageO11SessionInfoVAEycfC
+ _$s17CompanionServices19CPSResponderMessageO11SessionInfoVMa
+ _$s17CompanionServices19CPSResponderMessageO12sessionEventyA2C07SessionF4InfoV_tcACmFWC
+ _$s17CompanionServices19CPSResponderMessageO16SessionEventInfoV5event9sessionIDAeA0cF0O_SStcfC
+ _$s17CompanionServices19CPSResponderMessageO16SessionEventInfoV5eventAA0cF0Ovg
+ _$s17CompanionServices19CPSResponderMessageO16SessionEventInfoVMa
+ _$s17CompanionServices19CPSResponderMessageO18sessionEndResponseyA2C11SessionInfoV_tcACmFWC
+ _$s17CompanionServices19CPSResponderMessageO20sessionStartResponseyA2C11SessionInfoV_tcACmFWC
+ _$s17CompanionServices19CPSResponderMessageO9sessionIDSSSgvg
+ _$s17CompanionServices19CPSResponderMessageOMa
+ _$s17CompanionServices19CPSXPCServerRequestO14requesterEventyACSS_AA19CPSRequesterSessionC0F0OtcACmFWC
+ _$s17CompanionServices22CPSScalablePipeMessageO9requesteryAcA012CPSRequesterE0O_tcACmFWC
+ _$s17CompanionServices22CPSScalablePipeMessageO9responderyAcA012CPSResponderE0O_tcACmFWC
+ _$s17CompanionServices22CPSScalablePipeMessageOMn
+ _$s17CompanionServices23CPSXPCRequesterStopInfoV9sessionIDSSvg
+ _$s17CompanionServices24CPSXPCRequesterStartInfoV9sessionIDSSvg
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV10transportsSayAC9TransportOGSgvg
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV6TargetO8meDeviceyA2EmFWC
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV6TargetOMa
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV6TargetOSQAAMc
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV7targetsSayAC6TargetOGSgvg
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV9TransportO21bluetoothScalablePipeyA2EmFWC
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV9TransportO5nexusyA2EmFWC
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV9TransportOMa
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV9TransportOSQAAMc
+ _$sSS14_fromSubstringySSSshFZ
+ _$sSo12CBConnectionC17CompanionServicesE19cpsScalablePipeSend7messageAC011CPSScalableF7MessageOAG_tYaKF
+ _$sSo12CBConnectionC17CompanionServicesE19cpsScalablePipeSend7messageAC011CPSScalableF7MessageOAG_tYaKFTu
+ _$sSsySsSScfC
- _$s10Foundation19PropertyListDecoderC6decode_4fromxxm_AA4DataVtKSeRzlFTj
- _$s10Foundation19PropertyListDecoderCACycfc
- _$s10Foundation19PropertyListDecoderCMa
- _$s10Foundation19PropertyListEncoderC6encodeyAA4DataVxKSERzlFTj
- _$s10Foundation19PropertyListEncoderCACycfc
- _$s10Foundation19PropertyListEncoderCMa
- _$s17CompanionServices19CPSXPCServerRequestO14requesterEventyACs6UInt64V_AA19CPSRequesterSessionC0F0OtcACmFWC
- _$s17CompanionServices23CPSXPCRequesterStopInfoV9sessionIDs6UInt64Vvg
- _$s17CompanionServices24CPSXPCRequesterStartInfoV9sessionIDs6UInt64Vvg
- _$sSsN
- _$sSss23CustomStringConvertiblesWP
- _$ss6HasherV5_hash4seed_S2i_s6UInt64VtFZ
- _swift_retain_x10
CStrings:
+ "### session ended: sid=%s, client=%{public}s, session not found"
+ "No bluetooth device"
+ "No device session"
+ "No device sessionID"
+ "Requester not available"
+ "Responder not available"
+ "ScalablePipe: sessionID="
+ "Send start failed: no transport"
+ "[%s] ### No XPC connection to report event: %s"
+ "[%s] ### bluetooth scalable pipe session register failed: no requester daemon"
+ "[%s] ### report event failed: nexus, event=%s, error=%@"
+ "[%s] ### report event failed: scalablePipe, event=%s, error=%@"
+ "[%s] bluetooth scalable pipe session start: sessionID=%s"
+ "[%s] bluetooth scalable pipe session stop: sessionID=%s"
+ "[%s] report response event ignored: no transport, event=%s"
+ "[%s] responder event received: %s"
+ "[%s] set up: scalablePipe, sessionID=%s"
+ "[%s] system monitor stop"
+ "_bluetoothScalablePipeConnection"
+ "_bluetoothScalablePipeEnabled"
+ "_bluetoothScalablePipeSessionID"
+ "_requesterDaemon"
+ "session ended: sid=%s, client=%{public}s, up=%s"
+ "sessionEndResponse not expected as request"
+ "sessionEventAck not expected as request"
+ "sessionStartResponse not expected as request"
- "### session ended: sid=%llu, client=%{public}s, session not found"
- "No underlying connection"
- "Send end with no nexus session"
- "Send start with no nexus session"
- "[%s] ### report event failed: event=%s, error=%@"
- "[%s] report response event ignored: no nexus session, event=%s"
- "[%s] responder message: event=%s"
- "session ended: sid=%llu, client=%{public}s, up=%s"
```
