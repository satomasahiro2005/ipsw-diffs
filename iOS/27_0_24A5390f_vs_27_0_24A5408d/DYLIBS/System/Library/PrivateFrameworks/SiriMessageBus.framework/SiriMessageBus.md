## SiriMessageBus

> `/System/Library/PrivateFrameworks/SiriMessageBus.framework/SiriMessageBus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b68c` | `0x10c630` | **`+0xfa4`** |
| `__TEXT.__unwind_info` | `0x3b98` | `0x3e28` | **`+0x290`** |
| `__TEXT.__eh_frame` | `0x9930` | `0x9ab0` | **`+0x180`** |
| `__AUTH_CONST.__objc_const` | `0xba18` | `0xbb20` | **`+0x108`** |
| `__AUTH_CONST.__const` | `0x6558` | `0x65f8` | **`+0xa0`** |
| `__TEXT.__const` | `0x5700` | `0x5740` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x2317` | `0x2349` | **`+0x32`** |
| `__TEXT.__swift5_capture` | `0x199c` | `0x19c4` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x770` | `0x794` | **`+0x24`** |
| `__DATA.__data` | `0x1188` | `0x11a8` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x238c` | `0x23ac` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x46c` | `0x488` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x1494` | `0x14ac` | **`+0x18`** |
| `__TEXT.__cstring` | `0x3a9a` | `0x3a8a` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x8f63` | `0x8f53` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1380` | `0x138c` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x2e0` | `0x2ec` | **`+0xc`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-3600.54.17.0.0
+3600.54.24.11.1

-  Functions: 6022
-  Symbols:   1861
-  CStrings:  782
+  Functions: 6064
+  Symbols:   1865
+  CStrings:  783
Symbols:
+ _OUTLINED_FUNCTION_535
+ _symbolic IeghH_
+ _symbolic ScCySo8SAPersonCSg_____G s5NeverO
+ _symbolic So8SAPersonCSg
+ _symbolic _____Sg 10Foundation4DataV
+ _symbolic ______p 14SiriMessageBus18IFProxySELFLoggingP
- _symbolic _____Sg 22IntelligenceFlowShared17StructuredContextV011SiriRequestE0V4UserV
- _symbolic _____Sg 22IntelligenceFlowShared17StructuredContextV011SiriRequestE0V6MeCardV
CStrings:
+ "Device unlock failed"
+ "IntelligenceFlowProxy: Sending SystemResponseRendered with device unlock ActionRequirementResolution to IF"
+ "IntelligenceFlowProxy: Sent SystemResponseRendered with DeviceUnlockResolution to IF: %s"
+ "[SiriXAgent] %s clearing %ld tracked aceId(s)"
+ "[SiriXAgent] %s failed to deserialize response command for aceId %s: %@"
+ "[SiriXAgent] %s invoking completion after decode for aceId %s"
+ "[SiriXAgent] %s no responseCommandData for aceId %s (nil or timed out)"
+ "[SiriXAgent]: Handling command: "
+ "clearSiriXAgentAceIds()"
+ "unredactedMeCard"
- "IntelligenceFlowProxy: Sending UserTurnStarted[ExecutorRequest] with ActionRequirementResolution to IF"
- "IntelligenceFlowProxy: Sent SiriActivatedMessage with ActionRequirementResolution to IF: %s"
- "[SiriXAgent] %s fail to deser response command associated with aceId %s"
- "[SiriXAgent] %s invoking completion block after deser for aceId %s"
- "[SiriXAgent] %s received nil responseCommandData for aceId %s"
- "[SiriXAgent] %s returns after nil deserialization for aceId %s"
- "[SiriXAgent]:handle(_:withExecutionContextMatching:completion:)"
- "[SiriXAgent]:topicChangeDetected(requestId:)"
- "com.apple.siri.AgentDispatcherServiceHelper"
```
