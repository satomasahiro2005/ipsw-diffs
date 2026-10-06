## SiriInstrumentation

> `/System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x2b020` | `0x140` | **`-0x2aee0`** |
| `__DATA_DIRTY.__objc_data` | `0x17970` | `0x42850` | **`+0x2aee0`** |
| `__DATA_DIRTY.__data` | `0x238` | `0x518` | **`+0x2e0`** |
| `__TEXT.__text` | `0xddefb4` | `0xddf1d4` | **`+0x220`** |
| `__DATA.__data` | `0x36c0` | `0x3540` | **`-0x180`** |
| `__AUTH.__data` | `0x160` | `—` | **`-0x160`** |
| `__AUTH_CONST.__objc_const` | `0x184b20` | `0x184b80` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x10fec4` | `0x10ff04` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x13160` | `0x13168` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x34590` | `0x34598` | **`+0x8`** |
| `__AUTH_CONST.__const` | `0x27211` | `0x27218` | **`+0x7`** |
| `__TEXT.__cstring` | `0x98e0b` | `0x98e0c` | **`+0x1`** |

### Other Changes

```diff

-3605.27.1.1.1
+3605.29.1.0.0

-  Functions: 96249
-  Symbols:   134766
+  Functions: 96254
+  Symbols:   134773
Symbols:
+ -[GMSSchemaGMSExtendedInferenceMetrics deleteRoutingDecision]
+ -[GMSSchemaGMSExtendedInferenceMetrics hasRoutingDecision]
+ -[GMSSchemaGMSExtendedInferenceMetrics routingDecision]
+ -[GMSSchemaGMSExtendedInferenceMetrics setHasRoutingDecision:]
+ -[GMSSchemaGMSExtendedInferenceMetrics setRoutingDecision:]
+ OBJC_IVAR_$_GMSSchemaGMSExtendedInferenceMetrics._routingDecision
+ _OBJC_IVAR_$_GMSSchemaGMSExtendedInferenceMetrics._hasRoutingDecision
```
