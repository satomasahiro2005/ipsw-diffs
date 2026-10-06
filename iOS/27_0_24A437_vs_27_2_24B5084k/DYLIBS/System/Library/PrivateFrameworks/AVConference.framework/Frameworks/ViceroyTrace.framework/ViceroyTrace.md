## ViceroyTrace

> `/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ViceroyTrace.framework/ViceroyTrace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb93fc` | `0xba000` | **`+0xc04`** |
| `__TEXT.__oslogstring` | `0xf32a` | `0xf4ee` | **`+0x1c4`** |
| `__TEXT.__cstring` | `0xf46e` | `0xf612` | **`+0x1a4`** |
| `__AUTH_CONST.__cfstring` | `0xee00` | `0xefa0` | **`+0x1a0`** |
| `__TEXT.__objc_methlist` | `0x9338` | `0x93e0` | **`+0xa8`** |
| `__AUTH_CONST.__objc_const` | `0x17918` | `0x179b0` | **`+0x98`** |
| `__DATA_CONST.__objc_selrefs` | `0x4700` | `0x4740` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1870` | `0x1898` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x21fc` | `0x220c` | **`+0x10`** |

### Other Changes

```diff

-2235.63.1.2.0
+2260.9.1.0.0

-  Functions: 4249
-  Symbols:   6736
-  CStrings:  3352
+  Functions: 4262
+  Symbols:   6753
+  CStrings:  3373
Symbols:
+ -[CallSegment localLinkTransport]
+ -[CallSegment setLocalLinkTransport:]
+ -[MultiwayCall jbInitialRampStats]
+ -[MultiwayCall setJBInitialRampStats:]
+ -[MultiwaySegment reportingCurrentTime]
+ -[VCAggregator reportingCurrentTime]
+ -[VCAggregatorMultiway addJBInitialRampTelemetryForCall:callReport:]
+ -[VCAggregatorMultiway addJBInitialRampTelemetryToSessionReport:]
+ -[VCAggregatorMultiway jbInitialRampStatsForSession]
+ -[VCAggregatorMultiway updateJBRampMetrics:]
+ -[VCAggregatorMultiway writeJBInitialRampStats:toReport:]
+ -[VCReportingCommon reportingCurrentTime]
+ GCC_except_table1350
+ GCC_except_table144
+ GCC_except_table146
+ GCC_except_table462
+ _OBJC_IVAR_$_CallSegment._localLinkTransport
+ _OBJC_IVAR_$_MultiwayCall._hasJBInitialRampStats
+ _OBJC_IVAR_$_MultiwayCall._jbInitialRampStats
+ _OBJC_IVAR_$_VCAggregatorFaceTime._localLinkTransport
+ ___44-[VCAggregatorMultiway updateJBRampMetrics:]_block_invoke
- GCC_except_table1344
- GCC_except_table143
- GCC_except_table145
- GCC_except_table460
CStrings:
+ " [%s] %s:%d %@(%p) JB ramp metrics payload missing participant UUID. Ignoring ..."
+ " [%s] %s:%d JB ramp metrics for unknown participant=%@. Ignoring ..."
+ " [%s] %s:%d JB ramp metrics payload missing participant UUID. Ignoring ..."
+ " [%s] %s:%d VCAggregatorMultiway: skipping uplink segment flush. currentUplinkSegmentKey=%@, currentUplinkSegmentStreamGroups=%u"
+ "-[RTCReportingAgent reportSegment:withMessageType:clientType:]"
+ "-[VCAggregatorMultiway updateJBRampMetrics:]"
+ "-[VCAggregatorMultiway updateJBRampMetrics:]_block_invoke"
+ "JBIRAVGOOO"
+ "JBIRHSA"
+ "JBIRMAXOOO"
+ "JBIRNAP"
+ "JBIRNOOO"
+ "JBIRNP"
+ "JBInitialRampAvgOOOTimeDisplacementMs"
+ "JBInitialRampHasSufficientAudioPackets"
+ "JBInitialRampMaxOOOTimeDisplacementMs"
+ "JBInitialRampNumAudioPackets"
+ "JBInitialRampNumOOOPackets"
+ "JBInitialRampNumPackets"
+ "ReportingVC [%s] %s:%d reportSegment: dropping report with no metrics. method=%u, messageType=%u"
+ "cse_"
```
