## ScreenCaptureKit

> `/System/Library/Frameworks/ScreenCaptureKit.framework/ScreenCaptureKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36770` | `0x368e8` | **`+0x178`** |
| `__AUTH_CONST.__cfstring` | `0x2420` | `0x24a0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x5bb8` | `0x5bf8` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x380c` | `0x384c` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x8ac0` | `0x8af0` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x22d0` | `0x22f0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xcf0` | `0xcf8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x594` | `0x598` | **`+0x4`** |

### Other Changes

```diff

-740.48.1.0.0
+740.53.1.0.0

-  Functions: 1441
-  Symbols:   2549
-  CStrings:  855
+  Functions: 1446
+  Symbols:   2555
+  CStrings:  859
Symbols:
+ -[RPReportingAgent serviceNameSupportsStopSource]
+ -[RPReportingAgent setStopSource:]
+ -[RPReportingAgent stopSource]
+ -[SCPreviewViewController dismiss]
+ -[SCRecordingEditor cleanupPresentationState]
+ _OBJC_IVAR_$_RPReportingAgent._stopSource
CStrings:
+ "HQLRRecording"
+ "STPS"
+ "SystemBroadcast"
+ "SystemRecording"
```
