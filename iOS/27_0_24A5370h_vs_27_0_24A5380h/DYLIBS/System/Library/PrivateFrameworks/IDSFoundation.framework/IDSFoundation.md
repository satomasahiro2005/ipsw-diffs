## IDSFoundation

> `/System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e4b3c` | `0x4e6b20` | **`+0x1fe4`** |
| `__DATA.__bss` | `0x65340` | `0x65a60` | **`+0x720`** |
| `__AUTH.__objc_data` | `0xa188` | `0xa598` | **`+0x410`** |
| `__DATA_DIRTY.__objc_data` | `0x1590` | `0x11d0` | **`-0x3c0`** |
| `__AUTH_CONST.__cfstring` | `0x2c740` | `0x2ca40` | **`+0x300`** |
| `__AUTH_CONST.__objc_const` | `0x3e688` | `0x3e938` | **`+0x2b0`** |
| `__TEXT.__const` | `0x3ee60` | `0x3f110` | **`+0x2b0`** |
| `__TEXT.__cstring` | `0x3450d` | `0x3477d` | **`+0x270`** |
| `__TEXT.__oslogstring` | `0x2b65a` | `0x2b88a` | **`+0x230`** |
| `__TEXT.__eh_frame` | `0x15eb4` | `0x160d4` | **`+0x220`** |
| `__TEXT.__objc_methlist` | `0x1b8ec` | `0x1ba5c` | **`+0x170`** |
| `__AUTH_CONST.__const` | `0x19cc0` | `0x19e18` | **`+0x158`** |
| `__DATA.__data` | `0xf2b0` | `0xf190` | **`-0x120`** |
| `__TEXT.__unwind_info` | `0x14100` | `0x141e8` | **`+0xe8`** |
| `__TEXT.__constg_swiftt` | `0xc62c` | `0xc6e0` | **`+0xb4`** |
| `__DATA_CONST.__objc_selrefs` | `0xafd8` | `0xb088` | **`+0xb0`** |
| `__TEXT.__gcc_except_tab` | `0xb80c` | `0xb880` | **`+0x74`** |
| `__TEXT.__swift5_fieldmd` | `0xb568` | `0xb5c8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x74d8` | `0x7518` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x3364` | `0x339c` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x6a86` | `0x6ab6` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x287c` | `0x289c` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x1538` | `0x1558` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x29d8` | `0x29f0` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0xc18` | `0xc30` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x110` | `0xf8` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x14d0` | `0x14e0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xb20` | `0xb30` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xb574` | `0xb568` | **`-0xc`** |
| `__TEXT.__swift5_types` | `0xe8c` | `0xe98` | **`+0xc`** |
| `__AUTH.__data` | `0xaff8` | `0xb000` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x12a0` | `0x12a8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x38c` | `0x394` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x314` | `0x31c` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x94` | `0x98` | **`+0x4`** |

### Other Changes

```diff

-1996.100.2.2.2
+1998.100.2.0.0

-  Functions: 31524
-  Symbols:   5073
-  CStrings:  8319
+  Functions: 31551
+  Symbols:   5086
+  CStrings:  8352
Symbols:
+ OBJC_IVAR_$_IDSGFTGL._groupAgentLocalPublicKeyBlob
+ OBJC_IVAR_$_IDSPushHandler._priorityBoostedTopics
+ _IDSGlobalLinkAttributeGroupAgentPublicKeyKey
+ _IDSServicePropertyPriorityBoost
+ _OBJC_CLASS_$_IDSUTunControlChannelRestartMetric
+ _OBJC_METACLASS_$_IDSUTunControlChannelRestartMetric
+ _kCTPhoneNumberRegistrationRequestIdKey
+ _kIDSGlobalLinkGroupAgentPublicKeyParticipantIDKey
+ _kIDSGlobalLinkGroupAgentPublicKeyPayloadKey
+ _kIDSGlobalLinkGroupAgentPublicKeyRelayIDKey
+ _kIDSGlobalLinkGroupAgentPublicKeySignedPayloadKey
+ _kIDSTapToRadarDeviceClassesKey
+ _kIDSTapToRadarRemoteDeviceSelectionsKey
+ _kIDSUTunControlChannelRestartMetricName
+ _swiftIDSAreIDsEquivalent
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "<IDSEndpointTransparency: opt: %@ validation: %@ error: %@>"
+ "Constructing phone number registration request { mechanism: %@, requestID: %@ }"
+ "DeviceClasses"
+ "Forwarding pnrRequestSent — requestID matches outstanding { self: %@, requestID: %@ }"
+ "Forwarding pnrResponseReceived — requestID matches outstanding { self: %@, requestID: %@ }"
+ "IDSSendMessageCKVMessageCondition is an empty type with no values"
+ "IDSSendMessageCapabilityMessageCondition is an empty type with no values"
+ "IDSSendMessageCapabilityURICondition is an empty type with no values"
+ "Ignoring pnrRequestSent — requestID does not match outstanding { self: %@, callback: %@, outstanding: %@ }"
+ "Ignoring pnrResponseReceived — requestID does not match outstanding { self: %@, callback: %@, outstanding: %@ }"
+ "Issuing phone number registration request { self: %@, pushToken: %@, attemptCount: %@, mechanisms: %@, context: %@, mechanism: %@, requestID: %@ }"
+ "LinkDiscardedBetterAlternative"
+ "LinkDiscardedDuplicateSession"
+ "LinkDiscardedEarlierLink"
+ "LinkDiscardedNoLongerConnecting"
+ "PriorityBoost"
+ "RemoteDeviceSelections"
+ "UTunControlChannelRestartMetric"
+ "[U+1] _processCommandRelayInterfaceInfo received remote key material from fromParticipantIDs %@ to local participantIDs %@"
+ "[U+1] _sendRelayInterfaceInfo piggybacking group agent key material message %d bytes"
+ "cyc"
+ "failed"
+ "failover"
+ "fallback"
+ "gl-group-agent-public-key-key"
+ "h2fb"
+ "ignored"
+ "in"
+ "ktState"
+ "ktValidation2"
+ "ld"
+ "ok"
+ "out"
+ "pid"
+ "recvubrsp"
+ "retry-healthy"
+ "retry-unhealthy"
+ "sendubreq"
+ "sp"
+ "treePopulating == "
- "<IDSEndpointTransparency: %@ error: %@>"
- "Constructing phone number registration request { mechanism: %@ }"
- "IDSWillSendContext: failed to encode policyResult; willSend context will round-trip without it"
- "Issuing phone number registration request { pushToken: %@, attemptCount: %@, mechanisms: %@, context: %@, mechanism: %@ }"
- "failing"
- "optout-failing"
- "optout-success"
```
