## SEService

> `/System/Library/PrivateFrameworks/SEService.framework/SEService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10bcac` | `0x10db44` | **`+0x1e98`** |
| `__TEXT.__eh_frame` | `0x62b8` | `0x6428` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x2c27` | `0x2d47` | **`+0x120`** |
| `__DATA.__bss` | `0x1a810` | `0x1a710` | **`-0x100`** |
| `__TEXT.__unwind_info` | `0x5040` | `0x5088` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x45a0` | `0x4560` | **`-0x40`** |
| `__TEXT.__const` | `0x172b0` | `0x17270` | **`-0x40`** |
| `__TEXT.__swift5_reflstr` | `0x17f2` | `0x1812` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x39ec` | `0x3a04` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x35c` | `0x374` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x2368` | `0x2378` | **`+0x10`** |
| `__TEXT.__cstring` | `0x8aa5` | `0x8a95` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x407a` | `0x4084` | **`+0xa`** |
| `__TEXT.__swift5_proto` | `0x12c4` | `0x12bc` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x138` | `0x140` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x10c` | `0x114` | **`+0x8`** |

### Other Changes

```diff

-70.31.1.0.0
+70.34.0.0.0

-  Functions: 6983
+  Functions: 6993

-  CStrings:  1315
+  CStrings:  1321
Symbols:
+ _objc_release_x10
+ _symbolic Si10statusCode_t
- _NSLog
- _associated conformance 9SEService28SESThirdPartyServiceReporterV9ErrorCodeOSHAASQ
CStrings:
+ "%s - error %{public}@ for %{public}s"
+ "%s - invalid report data %s"
+ "%s - invalid report data: %{public}@"
+ "SEProxyMS sent %@"
+ "SEProxyRT sent %@"
+ "SEproxyMS returned with error %{public}@ %@ %@ "
+ "SEproxyRT returned with error %{public}@ %@ %@ "
+ "performRequest(url:method:body:additionalHeaders:withIDMS:)"
+ "signReportPayload - SecKeyCreateSignature failed: %s"
+ "signReportPayload - deviceIdentity signing error: %{public}@"
- "%s - SecKeyCreateSignature failed: %s"
- "%s - deviceIdentity signing error: %{public}@"
- "SERT: remote transceiver returning %@ %@ %@"
- "SESERV: client returning %@ %@ %@"
```
