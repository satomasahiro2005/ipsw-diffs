## SecureMessagingAgentCore

> `/System/Library/PrivateFrameworks/SecureMessagingAgentCore.framework/SecureMessagingAgentCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x9ccf` | `0x9c6f` | **`-0x60`** |
| `__TEXT.__text` | `0x1476fc` | `0x1476b8` | **`-0x44`** |

### Other Changes

```diff

-59.200.31.0.0
+59.200.41.0.0

-  CStrings:  686
+  CStrings:  685
Functions:
~ _$s24SecureMessagingAgentCore27KDSRegistrationStateMachineC9heartbeat11transactionySo06OS_os_I0_p_tYaFTY2_ : 556 -> 612
~ _$s24SecureMessagingAgentCore27KDSRegistrationStateMachineC11getIdentity33_229819B7868B1079C93FA683752F9003LLyyYaKFTY6_ : 528 -> 348
~ _$s24SecureMessagingAgentCore27KDSRegistrationStateMachineC15rollCertificateyyF : 936 -> 992
CStrings:
- "getIdentity loaded a new credential, marking cert as updated so groups roll their keys."
```
