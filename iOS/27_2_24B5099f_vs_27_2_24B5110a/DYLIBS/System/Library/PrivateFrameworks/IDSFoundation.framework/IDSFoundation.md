## IDSFoundation

> `/System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x502048` | `0x50fe70` | **`+0xde28`** |
| `__TEXT.__oslogstring` | `0x2d0ba` | `0x2d96a` | **`+0x8b0`** |
| `__AUTH_CONST.__const` | `0x1abb8` | `0x1ae70` | **`+0x2b8`** |
| `__TEXT.__const` | `0x406f0` | `0x409a0` | **`+0x2b0`** |
| `__TEXT.__cstring` | `0x35dad` | `0x3604d` | **`+0x2a0`** |
| `__DATA.__bss` | `0x67c20` | `0x67ea0` | **`+0x280`** |
| `__TEXT.__unwind_info` | `0x14818` | `0x149b0` | **`+0x198`** |
| `__TEXT.__swift5_fieldmd` | `0xb938` | `0xba50` | **`+0x118`** |
| `__AUTH.__data` | `0xafd8` | `0xb0e8` | **`+0x110`** |
| `__TEXT.__swift5_reflstr` | `0x6c76` | `0x6d66` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0xcb54` | `0xcc3c` | **`+0xe8`** |
| `__AUTH_CONST.__cfstring` | `0x2d680` | `0x2d720` | **`+0xa0`** |
| `__DATA.__data` | `0xf580` | `0xf610` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0xc018` | `0xc0a8` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0xb9a6` | `0xba36` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x1bfdc` | `0x1c04c` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x3f250` | `0x3f2b0` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x167b4` | `0x16814` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xb350` | `0xb380` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x2a68` | `0x2a90` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x76e8` | `0x7700` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x34b0` | `0x34c8` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0xef8` | `0xf10` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x3b8` | `0x3c4` | **`+0xc`** |
| `__DATA.__common` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1570` | `0x1578` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x33c` | `0x344` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x9c` | `0xa0` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x618` | `0x61c` | **`+0x4`** |

### Other Changes

```diff

-2003.200.61.0.0
+2003.200.71.2.3

-  Functions: 32071
-  Symbols:   5129
-  CStrings:  8514
+  Functions: 32169
+  Symbols:   5133
+  CStrings:  8536
Symbols:
+ _IDSGroupSessionClientParametersKey
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
CStrings:
+ "%@ is marked for final disconnection - cancelling and creating new connection"
+ "IDSGLLinkEngineCommon.linkConnectNotAttempted: %s: connect request was not attempted (%ld attempt(s) in a row came back with nothing); connectable again, but not before %s"
+ "IDSGLLinkEngineCommon.linkConnectNotAttempted: %s: no link"
+ "IDSGLLinkEngineCommon.linkConnectNotAttempted: %s: not awaiting a connect (%s); nothing to report"
+ "IDSGLLinkEngineCommon.linkDidDisconnect: %s (attempt ending: %s)"
+ "IDSGLLinkEngineCommon.linkDidDisconnect: %s: disconnected before the connect attempt got anywhere (%ld in a row); not offering it again before %s"
+ "IDSGLLinkEngineCommon.linkDidFail: %s: failed before the connect attempt got anywhere (%ld in a row); not offering it again before %s"
+ "IDSGLLinkEngineCommon.resetConnectEligibility: explicit connect request: cleared backoff and stalled-connect counts; failed links offered again: %s"
+ "LinkEngineConnectBestController.logIfOfferedInPlaceOfHeldLinks: %s: offered in place of higher-priority %s, held after connect attempts that achieved nothing. They are offered again when their hold ends, and take over from this link if they connect."
+ "LinkEngineConnectBestController.update: %s: %s wants a retry, but is held until %s"
+ "LinkEngineConnectBestController.update: %s: %s, but held until %s"
+ "LinkEngineConnectFirstController.logIfOfferedInPlaceOfHeldLinks: %s: offered in place of higher-priority %s, held after connect attempts that achieved nothing. If this link connects first it is kept, and %s will not be offered again until it fails."
+ "LinkEngineConnectFirstController.update: %s: %s wants a retry, but is held until %s"
+ "LinkEngineConnectFirstController.update: %s: %s, but held until %s"
+ "LinkEngine[%s].get: %ld there is another scheduled update. triggering... (%s)"
+ "_IDSGLLinkEngine.init: Connect bounce backoff: disabled=%{bool}d"
+ "_IDSGLLinkEngine.init: Pre-join connect hold: disabled=%{bool}d"
+ "_connectWithSessionInfo%@: session is now joining; giving every link another chance"
+ "_relayConnectionBehaviorForSession[%@]: shared session has not joined, but the pre-join hold is disabled (pjh); connecting, and the send path will refuse"
+ "_relayConnectionBehaviorForSession[%@]: shared session has not joined; holding off connecting new links"
+ "connect bounce backoff"
+ "connectRelayLinkFromCandidate[%@]: update state (%s->%s) for %@ before info request."
+ "connectRelayLinkFromCandidate[%@]: update state (%s->%s) for %@; LinkEngine is retrying it."
+ "connectTCP: %@ is marked for final disconnection - cancelling and creating new connection"
+ "gs-client-parameters-key"
+ "info request would be refused while the pair is disconnecting"
+ "pre join connect hold"
+ "setSharedSessionHasJoined: %@; re-driving links"
- "IDSGLLinkEngineCommon.linkDidDisconnect: %s"
- "LinkEngineConnectBestController.update: %s: %s -> connecting (retry plugin)"
- "LinkEngine[%s].shouldContinueUpdating.get: %ld there is another scheduled update. triggering... (%s)"
- "setSharedSessionHasJoined: joined; re-driving links in case an allocbind was dropped pre-join"
- "this H/2 connection cannot be reused"
- "this QUIC connection cannot be reused"
```
