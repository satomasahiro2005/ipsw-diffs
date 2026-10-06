## riskdatad

> `/usr/libexec/riskdatad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x522fc` | `0x5435c` | **`+0x2060`** |
| `__DATA.__bss` | `0x2300` | `0x2680` | **`+0x380`** |
| `__TEXT.__const` | `0x28f0` | `0x2bc0` | **`+0x2d0`** |
| `__TEXT.__eh_frame` | `0x3ff0` | `0x4290` | **`+0x2a0`** |
| `__DATA.__data` | `0x1660` | `0x1790` | **`+0x130`** |
| `__DATA.__objc_const` | `0xcb8` | `0xd88` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x13b0` | `0x1470` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x6c8` | `0x778` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0xc68` | `0xcea` | **`+0x82`** |
| `__TEXT.__constg_swiftt` | `0x814` | `0x87c` | **`+0x68`** |
| `__TEXT.__swift5_reflstr` | `0x5be` | `0x61e` | **`+0x60`** |
| `__DATA.__objc_data` | `0x2d0` | `0x320` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x2000` | `0x2050` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x500` | `0x540` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x61c` | `0x65c` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x158` | `0x190` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0x298` | `0x2c8` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1008` | `0x1030` | **`+0x28`** |
| `__TEXT.__swift5_acfuncs` | `0x140` | `0x168` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x40c` | `0x434` | **`+0x28`** |
| `__DATA.__common` | `0x138` | `0x158` | **`+0x20`** |
| `__TEXT.__cstring` | `0xc91` | `0xcb1` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x200` | `0x220` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x11c` | `0x138` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x1c0` | `0x1dc` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x688` | `0x680` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x68` | `0x6c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-27.2.2.0.0
+27.2.5.0.0

-  Functions: 1181
-  Symbols:   862
-  CStrings:  261
+  Functions: 1226
+  Symbols:   875
+  CStrings:  267
Symbols:
+ _$s11Distributed0A23TargetInvocationDecoderP18decodeNextArgumentqd__yKlFTj
+ _$s17CoreODIEssentials10P2PNetworkC24requestPayloadsFromPeersSaySDyS2SGGyYaF
+ _$s17CoreODIEssentials10P2PNetworkC24requestPayloadsFromPeersSaySDyS2SGGyYaFTu
+ _$s17CoreODIEssentials10P2PNetworkC3ttlACs8DurationV_tcfc
+ _$s17CoreODIEssentials10P2PNetworkCMa
+ _$s17CoreODIEssentials26DaemonInternalDefaultsKeysV27forcedConsentCooldownPeriodSSvgZ
+ _$s7CoreODI18OnDeviceSPIServiceMp
+ _$s7CoreODI18OnDeviceSPIServiceP11Distributed0F5ActorTb
+ _$s7CoreODI18OnDeviceSPIServiceP15diagnosticsToolAA14ActorReferenceCyAA01$cD22SPIDiagnosticsProtocolCGyKFTq
+ _$s7CoreODI18OnDeviceSPIServiceP15diagnosticsToolAA14ActorReferenceCyAA01$cD22SPIDiagnosticsProtocolCGyYaKFTqTE
+ _$s7CoreODI18OnDeviceSPIServiceP7session17serviceIdentifier8dsidType9startDate18locationBundlePath0mnH0AA14ActorReferenceCyAA01$cD18SPISessionProtocolCGSgSo20ODIServiceProviderIda_So11ODITypeOfIDV10Foundation0L0VSSSgAWtKFTq
+ _$s7CoreODI18OnDeviceSPIServiceP7session17serviceIdentifier8dsidType9startDate18locationBundlePath0mnH0AA14ActorReferenceCyAA01$cD18SPISessionProtocolCGSgSo20ODIServiceProviderIda_So11ODITypeOfIDV10Foundation0L0VSSSgAWtYaKFTqTE
+ _$s7CoreODI19$OnDeviceSPIServiceC11Distributed01_F9ActorStubAAMc
+ _$s7CoreODI19$OnDeviceSPIServiceCMa
+ _$s7CoreODI30OnDeviceSPIDiagnosticsProtocolMp
+ _$s7CoreODI30OnDeviceSPIDiagnosticsProtocolP11Distributed0G5ActorTb
+ _$s7CoreODI30OnDeviceSPIDiagnosticsProtocolP11diagnostics6actionySS_tYaFTq
+ _$s7CoreODI30OnDeviceSPIDiagnosticsProtocolP11diagnostics6actionySS_tYaKFTqTE
+ _$s7CoreODI31$OnDeviceSPIDiagnosticsProtocolCMa
+ _$s7CoreODI31$OnDeviceSPIDiagnosticsProtocolCMn
+ _$sSo14NSUserDefaultsC17CoreODIEssentialsE11internalInt6forKeySiSgSS_tF
- _$s14XPCDistributed9XPCSystemC17InvocationDecoderV18decodeNextArgumentxyKSeRzSERzlF
- _$s7CoreODI25OnDeviceSPISessionServiceMp
- _$s7CoreODI25OnDeviceSPISessionServiceP11Distributed0G5ActorTb
- _$s7CoreODI25OnDeviceSPISessionServiceP7session17serviceIdentifier8dsidType9startDate18locationBundlePath0noI0AA14ActorReferenceCyAA01$cdE8ProtocolCGSgSo20ODIServiceProviderIda_So11ODITypeOfIDV10Foundation0M0VSSSgAWtKFTq
- _$s7CoreODI25OnDeviceSPISessionServiceP7session17serviceIdentifier8dsidType9startDate18locationBundlePath0noI0AA14ActorReferenceCyAA01$cdE8ProtocolCGSgSo20ODIServiceProviderIda_So11ODITypeOfIDV10Foundation0M0VSSSgAWtYaKFTqTE
- _$s7CoreODI26$OnDeviceSPISessionServiceC11Distributed01_G9ActorStubAAMc
- _$s7CoreODI26$OnDeviceSPISessionServiceCMa
- _swift_conformsToProtocol2
CStrings:
+ "Action %s not recognized"
+ "Action received %s"
+ "Overriding cooldown period through internal defaults to %ld seconds"
+ "P2P: discovered: %s"
+ "_TtC9riskdatad22OnDeviceSPIServiceImpl"
+ "_TtC9riskdatad26OnDeviceSPIDiagnosticsImpl"
+ "xpc-SPIDiagnostics"
- "_TtC9riskdatad29OnDeviceSPISessionServiceImpl"
```
