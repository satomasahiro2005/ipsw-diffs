## ShareReporting

> `/System/Library/PrivateFrameworks/ShareReporting.framework/ShareReporting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x240c0` | `0x24790` | **`+0x6d0`** |
| `__TEXT.__cstring` | `0xe34` | `0xd35` | **`-0xff`** |
| `__TEXT.__eh_frame` | `0x1600` | `0x16c0` | **`+0xc0`** |
| `__TEXT.__const` | `0x3f18` | `0x3ef4` | **`-0x24`** |
| `__TEXT.__swift5_reflstr` | `0x8a2` | `0x891` | **`-0x11`** |
| `__AUTH_CONST.__const` | `0x2768` | `0x2778` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xd08` | `0xcf8` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x8d2` | `0x8c8` | **`-0xa`** |
| `__AUTH_CONST.__auth_got` | `0x5b8` | `0x5b0` | **`-0x8`** |

### Other Changes

```diff

-95.0.0.0.0
+104.0.0.0.0

-  Functions: 1176
-  Symbols:   490
-  CStrings:  106
+  Functions: 1177
+  Symbols:   488
+  CStrings:  108
Symbols:
+ ___swift_allocate_boxed_opaque_existential_0
+ _swift_allocBox
+ _swift_release_x28
+ _symbolic ScCySb______pG s5ErrorP
+ _symbolic ScCy___________pG 14ShareReporting18SRReportPayloadXpcC s5ErrorP
+ _symbolic ScCyyt______pG s5ErrorP
- _objc_release_x25
- _objc_release_x27
- _swift_release_x22
- _swift_release_x27
- _symbolic SccySb______pG s5ErrorP
- _symbolic Sccy___________pG 14ShareReporting18SRReportPayloadXpcC s5ErrorP
- _symbolic Sccyyt______pG s5ErrorP
- _symbolic _____yypG s23_ContiguousArrayStorageC
CStrings:
+ "ShareReporting/CoreAnalyticsManager.swift"
+ "ShareReporting/SRReportingService.swift"
+ "ShareReporting/ShareReportingServerClient.swift"
+ "_createCheckedThrowingContinuation(_:)"
+ "facetimemessagestored"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/ShareReporting/SRReportingService.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/ShareReporting/ShareReportingServerClient.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/TrustKit/Source/CoreAnalyticsManager.swift"
```
