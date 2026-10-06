## DiagnosticRequest

> `/System/Library/PrivateFrameworks/DiagnosticRequest.framework/DiagnosticRequest`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfca4` | `0xfc7c` | **`-0x28`** |

### Other Changes

```diff

-460.0.0.0.0
+464.0.0.0.0
Functions:
~ __tailspinRequestShared : 672 -> 668
~ _DRValidateCKRecordDictionary : 1124 -> 1120
~ -[DRSubscriptionManager _processNewEvent:] : 748 -> 744
~ -[DRSubscriptionManager _broadcastErrorForTeamID:error:] : 320 -> 316
~ -[DRSubscriptionManager _completeSubscriptionRequestForTeamID:config:event:] : 520 -> 516
~ __xpcArrayForStringArray : 320 -> 316
~ __DPClientLogRequestBaseMessage : 1412 -> 1400
~ __DPCSubmitLogToCKContainerRequestMessage : 2096 -> 2092
```
