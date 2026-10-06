## CoreODI

> `/System/Library/PrivateFrameworks/CoreODI.framework/CoreODI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5727c` | `0x59ffc` | **`+0x2d80`** |
| `__DATA.__bss` | `0x9780` | `0x9e80` | **`+0x700`** |
| `__TEXT.__const` | `0x7e02` | `0x8242` | **`+0x440`** |
| `__TEXT.__eh_frame` | `0x4820` | `0x4ba8` | **`+0x388`** |
| `__DATA_DIRTY.__bss` | `0x24a0` | `0x21a0` | **`-0x300`** |
| `__TEXT.__swift5_typeref` | `0x1cf5` | `0x1e45` | **`+0x150`** |
| `__TEXT.__unwind_info` | `0x1cb0` | `0x1db0` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0xef0` | `0xfa0` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x145c` | `0x1504` | **`+0xa8`** |
| `__AUTH.__data` | `0x100` | `0x170` | **`+0x70`** |
| `__DATA_DIRTY.__data` | `0x13c0` | `0x1430` | **`+0x70`** |
| `__TEXT.__cstring` | `0x1b24` | `0x1b94` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x48` | `0xa0` | **`+0x58`** |
| `__TEXT.__swift5_acfuncs` | `0x2a8` | `0x2f8` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x12dc` | `0x1320` | **`+0x44`** |
| `__TEXT.__swift_as_cont` | `0x320` | `0x364` | **`+0x44`** |
| `__AUTH_CONST.__cfstring` | `0x1380` | `0x13c0` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x2e0` | `0x318` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x2dc8` | `0x2df8` | **`+0x30`** |
| `__DATA.__common` | `0x10` | `0x30` | **`+0x20`** |
| `__DATA.__data` | `0xd10` | `0xd30` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x608` | `0x628` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x5e4` | `0x604` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x1a0` | `0x1c0` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x188` | `0x1a4` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x288` | `0x278` | **`-0x10`** |
| `__DATA_DIRTY.__common` | `0x90` | `0x80` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa68` | `0xa60` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x88` | `0x90` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x528` | `0x520` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x20` | `0x24` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1a4` | `0x1a8` | **`+0x4`** |

### Other Changes

```diff

-27.2.2.0.0
+27.2.5.0.0

-  Functions: 2169
-  Symbols:   1093
-  CStrings:  270
+  Functions: 2243
+  Symbols:   1113
+  CStrings:  274
Symbols:
+ _ODIAttributeKeyPeerEmails
+ _ODIAttributeKeyPeerPhoneNumbers
+ __DATA__TtC7CoreODI19$OnDeviceSPIService
+ __DATA__TtC7CoreODI31$OnDeviceSPIDiagnosticsProtocol
+ __IVARS__TtC7CoreODI19$OnDeviceSPIService
+ __IVARS__TtC7CoreODI31$OnDeviceSPIDiagnosticsProtocol
+ __METACLASS_DATA__TtC7CoreODI19$OnDeviceSPIService
+ __METACLASS_DATA__TtC7CoreODI31$OnDeviceSPIDiagnosticsProtocol
+ ___swift_closure_destructor.74Tm
+ _associated conformance 7CoreODI19$OnDeviceSPIServiceC11Distributed01_F9ActorStubAaD0fG0
+ _associated conformance 7CoreODI19$OnDeviceSPIServiceC11Distributed0F5ActorAA0G6SystemAdEP_AD0fgH0
+ _associated conformance 7CoreODI19$OnDeviceSPIServiceC11Distributed0F5ActorAASH
+ _associated conformance 7CoreODI19$OnDeviceSPIServiceC11Distributed0F5ActorAAs12Identifiable
+ _associated conformance 7CoreODI19$OnDeviceSPIServiceCSHAASQ
+ _associated conformance 7CoreODI19$OnDeviceSPIServiceCs12IdentifiableAA2IDsADP_SH
+ _associated conformance 7CoreODI31$OnDeviceSPIDiagnosticsProtocolC11Distributed01_G9ActorStubAaD0gH0
+ _associated conformance 7CoreODI31$OnDeviceSPIDiagnosticsProtocolC11Distributed0G5ActorAA0H6SystemAdEP_AD0ghI0
+ _associated conformance 7CoreODI31$OnDeviceSPIDiagnosticsProtocolC11Distributed0G5ActorAASH
+ _associated conformance 7CoreODI31$OnDeviceSPIDiagnosticsProtocolC11Distributed0G5ActorAAs12Identifiable
+ _associated conformance 7CoreODI31$OnDeviceSPIDiagnosticsProtocolCSHAASQ
+ _associated conformance 7CoreODI31$OnDeviceSPIDiagnosticsProtocolCs12IdentifiableAA2IDsADP_SH
+ _generic environment 7CoreODI18OnDeviceSPIServiceRz11Distributed01_F9ActorStubRzl
+ _generic environment 7CoreODI18OnDeviceSPIServiceRzl
+ _generic environment 7CoreODI30OnDeviceSPIDiagnosticsProtocolRz11Distributed01_G9ActorStubRzl
+ _generic environment 7CoreODI30OnDeviceSPIDiagnosticsProtocolRzl
+ _symbolic $s7CoreODI18OnDeviceSPIServiceP
+ _symbolic $s7CoreODI30OnDeviceSPIDiagnosticsProtocolP
+ _symbolic SSx______p_____Rz_____RzlIetMHgTgzo_ s5ErrorP 7CoreODI30OnDeviceSPIDiagnosticsProtocolP 11Distributed01_H9ActorStubP
+ _symbolic SSx______p_____RzlIetWHgTgzo_ s5ErrorP 7CoreODI30OnDeviceSPIDiagnosticsProtocolP
+ _symbolic _____ 7CoreODI19$OnDeviceSPIServiceC
+ _symbolic _____ 7CoreODI31$OnDeviceSPIDiagnosticsProtocolC
+ _symbolic _______________SSSgADx_____y_____GSg______p_____Rz_____RzlIetMHgTyTnTgTgTgozo_ So20ODIServiceProviderIda So11ODITypeOfIDV 10Foundation4DateV 7CoreODI14ActorReferenceC AH27$OnDeviceSPISessionProtocolC s5ErrorP AH0mN10SPIServiceP 11Distributed01_sK4StubP
+ _symbolic _______________SSSgADx_____y_____GSg______p_____RzlIetWHgTyTnTgTgTgozo_ So20ODIServiceProviderIda So11ODITypeOfIDV 10Foundation4DateV 7CoreODI14ActorReferenceC AH27$OnDeviceSPISessionProtocolC s5ErrorP AH0mN10SPIServiceP
+ _symbolic _____y_____G 7CoreODI14ActorReferenceC AA31$OnDeviceSPIDiagnosticsProtocolC
+ _symbolic x_____y_____G______p_____Rz_____RzlIetMHgozo_ 7CoreODI14ActorReferenceC AA31$OnDeviceSPIDiagnosticsProtocolC s5ErrorP AA0eF10SPIServiceP 11Distributed01_kC4StubP
+ _symbolic x_____y_____G______p_____RzlIetWHgozo_ 7CoreODI14ActorReferenceC AA31$OnDeviceSPIDiagnosticsProtocolC s5ErrorP AA0eF10SPIServiceP
- __DATA__TtC7CoreODI26$OnDeviceSPISessionService
- __IVARS__TtC7CoreODI26$OnDeviceSPISessionService
- __METACLASS_DATA__TtC7CoreODI26$OnDeviceSPISessionService
- ___swift_closure_destructor.76Tm
- _associated conformance 7CoreODI26$OnDeviceSPISessionServiceC11Distributed01_G9ActorStubAaD0gH0
- _associated conformance 7CoreODI26$OnDeviceSPISessionServiceC11Distributed0G5ActorAA0H6SystemAdEP_AD0ghI0
- _associated conformance 7CoreODI26$OnDeviceSPISessionServiceC11Distributed0G5ActorAASH
- _associated conformance 7CoreODI26$OnDeviceSPISessionServiceC11Distributed0G5ActorAAs12Identifiable
- _associated conformance 7CoreODI26$OnDeviceSPISessionServiceCSHAASQ
- _associated conformance 7CoreODI26$OnDeviceSPISessionServiceCs12IdentifiableAA2IDsADP_SH
- _generic environment 7CoreODI25OnDeviceSPISessionServiceRz11Distributed01_G9ActorStubRzl
- _generic environment 7CoreODI25OnDeviceSPISessionServiceRzl
- _symbolic $s7CoreODI25OnDeviceSPISessionServiceP
- _symbolic _____ 7CoreODI26$OnDeviceSPISessionServiceC
- _symbolic _______________SSSgADx_____y_____GSg______p_____Rz_____RzlIetMHgTyTnTgTgTgozo_ So20ODIServiceProviderIda So11ODITypeOfIDV 10Foundation4DateV 7CoreODI14ActorReferenceC AH27$OnDeviceSPISessionProtocolC s5ErrorP AH0mnO7ServiceP 11Distributed01_sK4StubP
- _symbolic _______________SSSgADx_____y_____GSg______p_____RzlIetWHgTyTnTgTgTgozo_ So20ODIServiceProviderIda So11ODITypeOfIDV 10Foundation4DateV 7CoreODI14ActorReferenceC AH27$OnDeviceSPISessionProtocolC s5ErrorP AH0mnO7ServiceP
CStrings:
+ "$s7CoreODI19$OnDeviceSPIServiceC7session17serviceIdentifier8dsidType9startDate18locationBundlePath0mnH0AA14ActorReferenceCyAA01$cD18SPISessionProtocolCGSgSo20ODIServiceProviderIda_So11ODITypeOfIDV10Foundation0L0VSSSgAWtYaKFTE"
+ "diagnostics(action:)"
+ "diagnosticsTool()"
+ "peerEmails"
+ "peerPhoneNumbers"
- "$s7CoreODI26$OnDeviceSPISessionServiceC7session17serviceIdentifier8dsidType9startDate18locationBundlePath0noI0AA14ActorReferenceCyAA01$cdE8ProtocolCGSgSo20ODIServiceProviderIda_So11ODITypeOfIDV10Foundation0M0VSSSgAWtYaKFTE"
```
