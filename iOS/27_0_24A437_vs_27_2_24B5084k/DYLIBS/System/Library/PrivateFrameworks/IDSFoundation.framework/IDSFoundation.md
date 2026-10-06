## IDSFoundation

> `/System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4eda4c` | `0x4f3188` | **`+0x573c`** |
| `__DATA.__bss` | `0x66270` | `0x677f0` | **`+0x1580`** |
| `__TEXT.__const` | `0x3f790` | `0x40330` | **`+0xba0`** |
| `__AUTH_CONST.__const` | `0x1a0c0` | `0x1a650` | **`+0x590`** |
| `__TEXT.__cstring` | `0x34c6d` | `0x3516d` | **`+0x500`** |
| `__TEXT.__oslogstring` | `0x2ba9a` | `0x2bf5a` | **`+0x4c0`** |
| `__AUTH_CONST.__cfstring` | `0x2cd80` | `0x2d000` | **`+0x280`** |
| `__TEXT.__swift5_typeref` | `0xb6b4` | `0xb8f2` | **`+0x23e`** |
| `__TEXT.__constg_swiftt` | `0xc85c` | `0xca84` | **`+0x228`** |
| `__DATA.__data` | `0xf2e8` | `0xf4d8` | **`+0x1f0`** |
| `__TEXT.__swift5_fieldmd` | `0xb6b4` | `0xb870` | **`+0x1bc`** |
| `__TEXT.__unwind_info` | `0x143c8` | `0x14570` | **`+0x1a8`** |
| `__TEXT.__gcc_except_tab` | `0xbb58` | `0xbcdc` | **`+0x184`** |
| `__AUTH_CONST.__objc_const` | `0x3eca8` | `0x3ee28` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0x164a4` | `0x16624` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0x1bbc4` | `0x1bc94` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x6b56` | `0x6c06` | **`+0xb0`** |
| `__TEXT.__swift5_proto` | `0x33dc` | `0x3488` | **`+0xac`** |
| `__DATA_CONST.__objc_selrefs` | `0xb120` | `0xb190` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x7620` | `0x7688` | **`+0x68`** |
| `__AUTH.__objc_data` | `0xa6d8` | `0xa738` | **`+0x60`** |
| `__TEXT.__swift5_types` | `0xeb0` | `0xee4` | **`+0x34`** |
| `__TEXT.__swift5_builtin` | `0x398` | `0x3c0` | **`+0x28`** |
| `__DATA.__common` | `0x1b0` | `0x1c8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x28b8` | `0x28d0` | **`+0x18`** |
| `__AUTH.__data` | `0xb0d8` | `0xb0c8` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2a28` | `0x2a30` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x600` | `0x608` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x98` | `0x9c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x330` | `0x334` | **`+0x4`** |

### Other Changes

```diff

-2003.100.1.2.1
+2003.200.33.2.5

-  Functions: 31701
-  Symbols:   5093
-  CStrings:  8389
+  Functions: 31861
+  Symbols:   5102
+  CStrings:  8416
Symbols:
+ OBJC_IVAR_$_IDSGlobalLink._clientSessionExperiments
+ OBJC_IVAR_$_IDSGlobalLink._defaultPathEvaluator
+ OBJC_IVAR_$_IDSGlobalLink._lastReportedLocalAvailableInterfaces
+ OBJC_IVAR_$_IDSGlobalLink._localAvailableInterfacesChanged
+ OBJC_IVAR_$_IDSGlobalLink._remoteAvailableInterfaces
+ _IDSGroupSessionClientSessionExperimentsKey
+ __isCompanionLinkInterface
+ _kIDSDiagnosticExtensionEntitlement
+ _nw_interface_get_index
CStrings:
+ "<%@: %p keyType: %ld, diversifier: %@, preferredLocalURI: %@>"
+ "IDSSessionInfoMetadataSerializer"
+ "PRIVACY: refusing to build connection data because P2P is not allowed"
+ "PRIVACY: refusing to serialize connection data for %@ because IP disclosure is not allowed"
+ "RealTimeGroupSessionCryptor"
+ "_cellularPathEvaluator update received"
+ "_processCommandRelayInterfaceInfo: invalid counter, ignore."
+ "_processCommandRelayInterfaceInfo: no candidate pair for %@, ignore."
+ "_processCommandRelayInterfaceInfo: old ack (counter:%u), ignore."
+ "_processCommandRelayInterfaceInfo: old counter %u, already acked."
+ "_processCommandRelayInterfaceInfo: receive relay interface info (counter:%u)."
+ "_processCommandRelayInterfaceInfo: receive relay interface info ack (counter:%u)."
+ "_sendRelayInterfaceInfo: peer has not advertised interface types, skip."
+ "_sendRelayInterfaceInfo: send relay interface info (counter:%u) using %@."
+ "_sendRelayInterfaceInfo: strategy does not use multiple links, no peer needs our interface changes."
+ "_setupRelayConnectionForNetworkAddressChanges: using path from change, status [%d]."
+ "_wifiPathEvaluator update received"
+ "com.apple.ids.ctpnr.callback"
+ "com.apple.private.ids.diagnosticextension"
+ "could not allocate %zu bytes to serialize string"
+ "cse_%@"
+ "default interface from path change [%@:%d], cellular:%d."
+ "gs-client-session-experiments-key"
+ "iMessageAccountRegions"
+ "invalid default interface from path change [%@:%d]."
+ "not serializing string of %zu UTF-8 bytes: too long for the wire format"
+ "pLU"
+ "process delayed cell interfaces:%@ (uponPathChange:%@)"
+ "receive remote available interfaces: %@"
+ "receive(%u) invalid indication message length (max %u)"
- "<%@: %p keyType: %ld, diversifier: %@>"
- "P2P is not allowed, skip processing remote connection data."
- "process delayed cell interfaces:%@"
```
