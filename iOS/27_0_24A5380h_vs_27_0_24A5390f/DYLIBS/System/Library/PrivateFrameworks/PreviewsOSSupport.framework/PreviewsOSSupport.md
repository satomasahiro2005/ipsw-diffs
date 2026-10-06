## PreviewsOSSupport

> `/System/Library/PrivateFrameworks/PreviewsOSSupport.framework/PreviewsOSSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b910` | `0x2ca1c` | **`+0x110c`** |
| `__AUTH_CONST.__objc_const` | `0x2188` | `0x2440` | **`+0x2b8`** |
| `__AUTH.__data` | `0x6c0` | `0x740` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1460` | `0x14e0` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x2788` | `0x2710` | **`-0x78`** |
| `__DATA.__data` | `0x1068` | `0x10d8` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0xe10` | `0xdb8` | **`-0x58`** |
| `__TEXT.__const` | `0x2ff8` | `0x3038` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x118e` | `0x11bd` | **`+0x2f`** |
| `__AUTH_CONST.__auth_got` | `0xb40` | `0xb58` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xd08` | `0xd20` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0xb44` | `0xb50` | **`+0xc`** |
| `__AUTH.__objc_data` | `0x3f8` | `0x3f0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x368` | `0x360` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0x2c1` | `0x2c3` | **`+0x2`** |
| `__TEXT.__swift5_reflstr` | `0x94a` | `0x948` | **`-0x2`** |

### Other Changes

```diff

-24.0.37.0.0
+24.0.41.0.0

-  Functions: 1199
-  Symbols:   713
-  CStrings:  140
+  Functions: 1213
+  Symbols:   716
+  CStrings:  141
Symbols:
+ ___swift_memcpy40_8
+ _objc_retain_x27
+ _symbolic Iegh_
+ _symbolic IeyBh_
+ _symbolic So19UVServiceHubMessageCIeghg_
+ _symbolic So19UVServiceHubMessageCIeghg_Ieghg_
+ _symbolic So19UVServiceHubMessageCIeyBhy_
+ _symbolic So19UVServiceHubMessageCIeyBhy_IeyBhy_
+ _symbolic _____Sg 17PreviewsOSSupport19CrashReportListenerC13ObserverProxyC
+ _symbolic _____Sg 17PreviewsOSSupport23PreviewAssertionManagerC7Storage33_5CA3FDFC8E253B83EE48BAF559EE2BF2LLV07CountedD0V
+ _symbolic ___________pSgSo7NSErrorCSgIeyBhyy_ So14NSSecureCodingP So8NSObjectP
+ _symbolic ___________pSg______pSgIeghgg_ So14NSSecureCodingP So8NSObjectP s5ErrorP
+ _symbolic _____ySo12RBSAssertionCG 20PreviewsFoundationOS17UncheckedSendableV
+ _symbolic _____ySo12RBSAssertionCGSg 20PreviewsFoundationOS17UncheckedSendableV
+ _symbolic y_____Ybc 17PreviewsOSSupport19CrashReportListenerC13ObserverProxyC14DiagnosticsLogV
+ _symbolic yp
- _objc_retain_x12
- _symbolic Ieg_
- _symbolic IeyB_
- _symbolic So12RBSAssertionC
- _symbolic So12RBSAssertionCSg
- _symbolic So19UVServiceHubMessageCIegg_
- _symbolic So19UVServiceHubMessageCIegg_Iegg_
- _symbolic So19UVServiceHubMessageCIeyBy_
- _symbolic So19UVServiceHubMessageCIeyBy_IeyBy_
- _symbolic ___________pSgSo7NSErrorCSgIeyByy_ So14NSSecureCodingP So8NSObjectP
- _symbolic ___________pSg______pSgIeggg_ So14NSSecureCodingP So8NSObjectP s5ErrorP
- _symbolic y_____c 17PreviewsOSSupport19CrashReportListenerC13ObserverProxyC14DiagnosticsLogV
- _type_layout_string 17PreviewsOSSupport23PreviewAssertionManagerC7Storage33_5CA3FDFC8E253B83EE48BAF559EE2BF2LLV07CountedD0V
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewsOSSupport/Sources/PreviewsOSSupport/ServiceHub Integration/ServiceHubPipeService.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewsOSSupport/Sources/PreviewsOSSupport/ServiceHub Integration/ServiceHubPreviewService.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewsOSSupport/Sources/PreviewsOSSupport/Shell Connection/ShellConnection+Interface.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewsOSSupport/Sources/PreviewsOSSupport/Shell Connection/ShellConnection+Role.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewsOSSupport/Sources/PreviewsOSSupport/Shell Connection/ShellConnection.swift"
+ "init(types:)"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewsOSSupport/Sources/PreviewsOSSupport/ServiceHubPipeService.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewsOSSupport/Sources/PreviewsOSSupport/ServiceHubPreviewService.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewsOSSupport/Sources/PreviewsOSSupport/ShellConnection+Interface.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewsOSSupport/Sources/PreviewsOSSupport/ShellConnection+Role.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewsOSSupport/Sources/PreviewsOSSupport/ShellConnection.swift"
```
