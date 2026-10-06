## IDSFoundation

> `/System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f3188` | `0x500fa0` | **`+0xde18`** |
| `__TEXT.__oslogstring` | `0x2bf5a` | `0x2cf7a` | **`+0x1020`** |
| `__TEXT.__cstring` | `0x3516d` | `0x35c1d` | **`+0xab0`** |
| `__AUTH_CONST.__const` | `0x1a650` | `0x1ab58` | **`+0x508`** |
| `__AUTH_CONST.__cfstring` | `0x2d000` | `0x2d4c0` | **`+0x4c0`** |
| `__DATA.__bss` | `0x677f0` | `0x67c00` | **`+0x410`** |
| `__TEXT.__const` | `0x40330` | `0x406f0` | **`+0x3c0`** |
| `__TEXT.__gcc_except_tab` | `0xbcdc` | `0xc018` | **`+0x33c`** |
| `__DATA_DIRTY.__objc_data` | `0x11d0` | `0x14f0` | **`+0x320`** |
| `__AUTH.__objc_data` | `0xa738` | `0xa468` | **`-0x2d0`** |
| `__TEXT.__objc_methlist` | `0x1bc94` | `0x1bf64` | **`+0x2d0`** |
| `__AUTH_CONST.__objc_const` | `0x3ee28` | `0x3f0d8` | **`+0x2b0`** |
| `__TEXT.__unwind_info` | `0x14570` | `0x147e0` | **`+0x270`** |
| `__DATA_DIRTY.__data` | `0x50` | `0x1f8` | **`+0x1a8`** |
| `__DATA_CONST.__objc_selrefs` | `0xb190` | `0xb310` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0x16624` | `0x16784` | **`+0x160`** |
| `__AUTH.__data` | `0xb0c8` | `0xafd8` | **`-0xf0`** |
| `__TEXT.__constg_swiftt` | `0xca84` | `0xcb54` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0xb870` | `0xb938` | **`+0xc8`** |
| `__TEXT.__swift5_capture` | `0x15a4` | `0x1668` | **`+0xc4`** |
| `__TEXT.__swift5_typeref` | `0xb8f2` | `0xb9a6` | **`+0xb4`** |
| `__DATA.__data` | `0xf4d8` | `0xf580` | **`+0xa8`** |
| `__TEXT.__swift5_reflstr` | `0x6c06` | `0x6c76` | **`+0x70`** |
| `__DATA.__common` | `0x1c8` | `0x220` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x7688` | `0x76d0` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x2a30` | `0x2a60` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1500` | `0x1530` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x28d0` | `0x28f8` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x3488` | `0x34b0` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0xc30` | `0xc48` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x958` | `0x970` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0xee4` | `0xef8` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x608` | `0x618` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x3ac` | `0x3b8` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x12b8` | `0x12c0` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0xf8` | `0x100` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x334` | `0x33c` | **`+0x8`** |

### Other Changes

```diff

-2003.200.33.2.5
+2003.200.44.0.0

+  - /System/Library/PrivateFrameworks/ApplePushService.framework/ApplePushService

-  Functions: 31861
-  Symbols:   5102
-  CStrings:  8416
+  Functions: 32051
+  Symbols:   5113
+  CStrings:  8493
Symbols:
+ OBJC_IVAR_$_IDSGFTGL._virtualRelayDrainLeeway
+ OBJC_IVAR_$_IDSGlobalLink._clientSupportsLinkDraining
+ OBJC_IVAR_$_IDSGlobalLink._everBuiltLocalRemoteRelayLinkIDs
+ OBJC_IVAR_$_IDSGlobalLink._linkDrainEnabledResolved
+ _APSEnvironmentProduction
+ _GLUtilGetRemoteReportTransportFromCandidatePair
+ _GLUtilGetReportTransportFromCandidatePair
+ _IDSServicePropertyReadOnlyControlCategories
+ _kIDSOffGridEntitlement
+ _kIDSPairedDeviceManagerEntitlement
+ _kIDSPinnedIdentityEntitlement
CStrings:
+ "**** Invalid Service Definition: %@ declares out of range ControlCategory %lu, treating it as uncategorised"
+ "Ack message too short: %lu bytes, need at least %lu\n"
+ "Announce link drain (%d) %@ for IDSSessionID: %@ QRSessionID: %@ and %@, reason: %@"
+ "Cancel link drain (%d) %@ for IDSSessionID: %@ QRSessionID: %@ and %@"
+ "FirewallMultiCategory"
+ "FragmentedMessage too short for header: %lu bytes, need at least %d\n"
+ "FragmentedMessage: have %u pieces, %u expected (claimed count exceeds available), bailing"
+ "GlobalLink is disconnecting"
+ "Handshake message too short: %lu bytes, need at least %lu\n"
+ "IDSSocketPairResourceTransferReceiver: resume chunk too short for byteOffset: %lu bytes"
+ "IDSStalledConnectRetryPlugin.update: %s: connecting for %s with no result reported; treating the connect request as lost so the link can be retried (attempt %ld of %ld)"
+ "IDSStalledConnectRetryPlugin.update: %s: still connecting after %ld reset(s); leaving it failed so the connect controllers stop offering it"
+ "ITWServiceDiscovery"
+ "LinkDrain"
+ "LinkEngineConnectBestController.update: %s: %s -> connected (wanted again)"
+ "LinkEngineConnectBestController.update: %s: %s -> draining"
+ "No valid virtual candidate pair. Drop incoming packet %zuB for pairing %@ (%s) on channel %@, local address [%s], remote address [%s]"
+ "OTREncryptedMessage too short for header: %lu bytes, need at least %lu\n"
+ "OTRMessage too short for header: %lu bytes, need at least %lu\n"
+ "ReadOnlyControlCategories"
+ "Stalled Connect Retry"
+ "WebKit"
+ "WebKitServerBag"
+ "[U+1] %@ is only %.3fs old; not yet counting it as an alternative media path"
+ "[U+1] VR drain leeway: %.3fs"
+ "[U+1] announcing drain of virtual candidate pair %@ riding on relay link (%d)"
+ "[U+1] peer flagged remote relay link %04x draining; draining our VR link %@"
+ "[U+1] peer no longer flags remote relay link %04x draining; resuming our VR link %@"
+ "[U+1] peer will not honour a drain (capability %04X); leaving the VR links on relay link (%d) alone until it is removed"
+ "[U+1] relay link (%d) is staying; clearing pending-removal state on virtual candidate pair %@"
+ "_IDSGLLinkEngine.init: Single stack interface: %{bool}d (multi-stack disabled: %{bool}d, single-stack disabled: %{bool}d), preferred family: %s (name: %s, defaults: %s, experiments: %s, server bag: %s)"
+ "_IDSGLLinkEngine.init: Stalled connect retry thresholds: %s (defaults: %s, experiments: %s), disabled: %{bool}d"
+ "_IDSGLLinkEngine.scheduleProtocolDelayReveals: glProtocolDelay in effect: %s"
+ "_IDSGLLinkEngine.scheduleProtocolDelayReveals: glProtocolDelay: releasing rungs due at %s"
+ "_localCapabilityFlags: will honour link drain"
+ "_translateLinkTransportTypeForCandidatePair: %d -> %d (glLinkProtocol %ld, linkEngine %@)"
+ "applyDrain: %@ cannot drain (feature/client/delegate); leaving the link untouched for the ordinary teardown"
+ "applyDrain: %@ is only [%s]; nothing to drain"
+ "applyDrain: %@ is the last usable media path; leaving the request standing"
+ "applyDrain: %@ telling client and peer now"
+ "candidate pair revived from [%s] to [%s] without a new attempt - a late reply to a request we had given up on. Whatever the client was told about this link is now stale: %@"
+ "candidatePairsFromRelayInterfaceInfo: isIPv6: %@, type: %lu, RAT: %u, transport: %ld, plainTCP: %@, relayLinkID: %04x, MTU: %u, linkFlags: 0x%x, dataSoMasks: 0x%x"
+ "clearing pending-removal state for revived candidatePair: %@"
+ "com.apple.private.ids.offgrid"
+ "com.apple.private.ids.paired-device-manager"
+ "com.apple.private.ids.pinned-identity"
+ "com.apple.webkit.bag"
+ "configureGLExperiments: link drain resolved to %@ (published to client as %@)"
+ "connect request for link %@ was not attempted (%s); reporting it as not connected so LinkEngine can retry it"
+ "connection %s -> %s failed with error %d; reporting it so the link stops being treated as usable"
+ "could not reopen TCP connection"
+ "could not reopen the TCP connection for %@; the allocbind would have gone into a closed socket"
+ "createRelayInterfaceInfoFromCandidatePairs: family: %d, transport: %ld, plainTCP: %@, RAT: %u, relay LinkID: %04x, MTU: %u, linkFlags: 0x%x, dataSoMasks: 0x%x"
+ "ids-qr-drain-leeway-ms"
+ "ids-qr-link-drain-enabled"
+ "ids-qr-single-stack-family"
+ "idsQRDrainLeewayMs"
+ "idsQRLinkDrainEnabled"
+ "idsQRSingleStackFamily"
+ "idsQRStalledConnectThresholds"
+ "idsdrn"
+ "ignoring NWLink connection error: it is from a stale H2 connection on local port %u, but %@ is using port %u"
+ "isRecoverable"
+ "never-built"
+ "no link that is staying can carry the request for group %@, session %@; falling back to retiring link %d"
+ "nothing to unallocbind for %@ (state [%s]); reporting the disconnect so LinkEngine stops waiting on it"
+ "reconnecting %@ over H2..."
+ "reconnecting %@ over H3..."
+ "removed"
+ "reopened the TCP connection for %@ on local port %u"
+ "session wants neither join nor info"
+ "setClientSupportsLinkDraining: %@"
+ "setSharedSessionHasJoined: joined; re-driving links in case an allocbind was dropped pre-join"
+ "shared session not yet joined"
+ "shouldReconnect"
+ "single stack interface"
+ "stalled connect retry"
+ "underlyingConnection for %s closed after its candidate pair had gone; nothing to do"
+ "underlyingConnectionDidFail: %@ is already [%s]; leaving it alone"
+ "underlyingConnectionDidFail: error %d killed the connection under %@ (was [%s]); telling the client and LinkEngine"
+ "undoDrain: %@"
- "No valid virtual candidate pair. Drop incoming packet %zuB on channel %@, local address [%s], remote address [%s]"
- "_translateLinkTransportTypeWhenH2Enabled: %d -> %d"
- "candidatePairsFromRelayInterfaceInfo: isIPv6: %@, type: %lu, RAT: %u, transport: %ld, relayLinkID: %04x, MTU: %u, linkFlags: 0x%x, dataSoMasks: 0x%x"
- "createRelayInterfaceInfoFromCandidatePairs: family: %d, transport: %ld, RAT: %u, relay LinkID: %04x, MTU: %u, linkFlags: 0x%x, dataSoMasks: 0x%x"
```
