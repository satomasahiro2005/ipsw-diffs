## NexusDaemon

> `/System/Library/PrivateFrameworks/NexusDaemon.framework/NexusDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70498` | `0x72768` | **`+0x22d0`** |
| `__TEXT.__eh_frame` | `0xd20` | `0xe90` | **`+0x170`** |
| `__DATA.__bss` | `0x700` | `0x600` | **`-0x100`** |
| `__AUTH_CONST.__objc_const` | `0x1b60` | `0x1a88` | **`-0xd8`** |
| `__AUTH.__data` | `0xc28` | `0xb98` | **`-0x90`** |
| `__AUTH_CONST.__const` | `0x1b20` | `0x1b70` | **`+0x50`** |
| `__TEXT.__const` | `0xdd8` | `0xe28` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xb18` | `0xb60` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0xd80` | `0xdc0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x2811` | `0x2851` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x1037` | `0x1070` | **`+0x39`** |
| `__TEXT.__swift5_reflstr` | `0xf68` | `0xf31` | **`-0x37`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__constg_swiftt` | `0x500` | `0x4f0` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0xc0c` | `0xc1c` | **`+0x10`** |
| `__DATA.__common` | `0x180` | `0x178` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x60` | `0x58` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x40` | `0x38` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-900.25.0.0.0
+900.37.0.0.0

-  Functions: 1047
-  Symbols:   590
-  CStrings:  338
+  Functions: 1058
+  Symbols:   595
+  CStrings:  340
Symbols:
+ _OBJC_CLASS_$__TtC11NexusDaemon13NXCloudDaemon
+ _OBJC_METACLASS_$__TtC11NexusDaemon13NXCloudDaemon
+ __DATA__TtC11NexusDaemon13NXCloudDaemon
+ __INSTANCE_METHODS__TtC11NexusDaemon13NXCloudDaemon
+ __IVARS__TtC11NexusDaemon13NXCloudDaemon
+ __METACLASS_DATA__TtC11NexusDaemon13NXCloudDaemon
+ __PROPERTIES__TtC11NexusDaemon13NXCloudDaemon
+ __PROTOCOLS__TtC11NexusDaemon13NXCloudDaemon
+ ___swift_closure_destructor.173Tm
+ ___swift_closure_destructor.177Tm
+ ___swift_closure_destructor.180Tm
+ ___swift_closure_destructor.41Tm
+ ___swift_memcpy32_4
+ __swift_stdlib_bridgeErrorToNSError
+ _swift_getForeignTypeMetadata
+ _symbolic $s11NexusDaemon05NXSubB0P
+ _symbolic SDyS2SG
+ _symbolic SS3key_SS5valuet
+ _symbolic Say______pG 11NexusDaemon05NXSubB0P
+ _symbolic _____ 11NexusDaemon07NXCloudB0C
+ _symbolic _____ So13audit_token_ta
+ _symbolic _____Sg 11NexusDaemon07NXCloudB0C
+ _symbolic _____Sg So13audit_token_ta
+ _symbolic _____SgXw 11NexusDaemon07NXCloudB0C
+ _symbolic _____SgXwz_Xx 11NexusDaemon07NXCloudB0C
+ _symbolic _____Sg_ABt 5Nexus17NXDiscoveryResultV
+ _symbolic ______A7At s6UInt32V
+ _symbolic ______p 11NexusDaemon05NXSubB0P
+ _symbolic _____ySS3key_SS5valuetG s23_ContiguousArrayStorageC
+ _symbolic _____y______pG s23_ContiguousArrayStorageC 11NexusDaemon05NXSubE0P
+ _type_layout_string So13audit_token_ta
- _OBJC_CLASS_$__TtC11NexusDaemon13NXCloudServer
- _OBJC_METACLASS_$__TtC11NexusDaemon13NXCloudServer
- __DATA__TtC11NexusDaemon13NXCloudServer
- __DATA__TtC11NexusDaemon20NXDiagnosticsManager
- __INSTANCE_METHODS__TtC11NexusDaemon13NXCloudServer
- __IVARS__TtC11NexusDaemon13NXCloudServer
- __IVARS__TtC11NexusDaemon20NXDiagnosticsManager
- __METACLASS_DATA__TtC11NexusDaemon13NXCloudServer
- __METACLASS_DATA__TtC11NexusDaemon20NXDiagnosticsManager
- __PROPERTIES__TtC11NexusDaemon13NXCloudServer
- __PROTOCOLS__TtC11NexusDaemon13NXCloudServer
- ___swift_closure_destructor.172Tm
- ___swift_closure_destructor.176Tm
- ___swift_closure_destructor.179Tm
- ___swift_destroy_boxed_opaque_existential_1Tm
- _symbolic $s11NexusDaemon15NXDaemonManagerP
- _symbolic Say______pG 11NexusDaemon15NXDaemonManagerP
- _symbolic _____ 11NexusDaemon13NXCloudServerC
- _symbolic _____ 11NexusDaemon20NXDiagnosticsManagerC
- _symbolic _____Sg 11NexusDaemon13NXCloudServerC
- _symbolic _____Sg 11NexusDaemon20NXDiagnosticsManagerC
- _symbolic _____SgXw 11NexusDaemon13NXCloudServerC
- _symbolic _____SgXw 11NexusDaemon20NXDiagnosticsManagerC
- _symbolic _____SgXwz_Xx 11NexusDaemon13NXCloudServerC
- _symbolic ______p 11NexusDaemon15NXDaemonManagerP
- _symbolic _____y______pG s23_ContiguousArrayStorageC 11NexusDaemon15NXDaemonManagerP
CStrings:
+ "### Create IDSService failed: serviceID=%s"
+ "### Register DiagnosticShow request handler failed: error=%@"
+ "### Request handler failed: requestName=%s, client=%s, error=%s"
+ "### Send operation event failed: operationUUID=%s, event=%s, error=%@"
+ "### Send operation event send failed: operationUUID=%s, event=%s, error=%@"
+ "Connection failed: peer=%s, error=%@"
+ "Connection waiting: peer=%s, error=%@"
+ "DiagnosticShow requested"
+ "Missing entitlement: "
+ "NexusDaemon.NXCloudDaemon"
- "### Register DiagnosticShow request handler failed: %s"
- "### Request handler failed: requestName=%s, client%s, error=%s"
- "### Send operation event failed: operationUUID=%s, event=%s, error=%s"
- "### Send operation event send failed: operationUUID=%s, event=%s,\nerror=%s"
- "Connection failed: peer=%s, error=%s"
- "Connection waiting: peer=%s, error=%s)"
- "NexusDaemon.NXCloudServer"
- "No request names"
```
