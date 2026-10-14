## MetricKitCore

> `/System/Library/PrivateFrameworks/MetricKitCore.framework/MetricKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d808` | `0x1dbbc` | **`+0x3b4`** |
| `__AUTH_CONST.__cfstring` | `0x9c0` | `0xac0` | **`+0x100`** |
| `__TEXT.__cstring` | `0xb52` | `0xc12` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x1d8` | `0x200` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x1b2c` | `0x1b3c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x13e0` | `0x13e8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x720` | `0x728` | **`+0x8`** |

### Other Changes

```diff

-369.40.1.0.0
+369.40.2.0.0

-  Functions: 830
-  Symbols:   1081
-  CStrings:  352
+  Functions: 832
+  Symbols:   1084
+  CStrings:  360
Symbols:
+ -[MXSourceHandler _reportDiagnosticDeliveryForDiagnostic:bundleID:outcome:]
+ ___75-[MXSourceHandler _reportDiagnosticDeliveryForDiagnostic:bundleID:outcome:]_block_invoke
+ ___block_descriptor_54_e8_32s_e19_"NSDictionary"8?0ls32l8
CStrings:
+ "com.apple.metrickitd.diagnosticDelivery"
+ "deliveryOutcome"
+ "hasAppLaunchDiagnostic"
+ "hasCPUExceptionDiagnostic"
+ "hasCrashDiagnostic"
+ "hasDiskWriteExceptionDiagnostic"
+ "hasHangDiagnostic"
+ "hasMemoryExceptionDiagnostic"
```
