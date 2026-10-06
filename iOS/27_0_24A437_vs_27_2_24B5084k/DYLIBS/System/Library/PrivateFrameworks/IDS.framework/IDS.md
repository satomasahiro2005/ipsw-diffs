## IDS

> `/System/Library/PrivateFrameworks/IDS.framework/IDS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b5880` | `0x1bd37c` | **`+0x7afc`** |
| `__TEXT.__oslogstring` | `0x1b774` | `0x1bdf8` | **`+0x684`** |
| `__TEXT.__eh_frame` | `0x3180` | `0x33d8` | **`+0x258`** |
| `__TEXT.__const` | `0x5fe8` | `0x6108` | **`+0x120`** |
| `__AUTH.__data` | `0x1480` | `0x1598` | **`+0x118`** |
| `__DATA.__bss` | `0x9910` | `0x9a10` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x17d4` | `0x1894` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x6f88` | `0x7030` | **`+0xa8`** |
| `__TEXT.__swift5_typeref` | `0x1c5c` | `0x1d00` | **`+0xa4`** |
| `__TEXT.__swift5_reflstr` | `0xe3c` | `0xec3` | **`+0x87`** |
| `__TEXT.__constg_swiftt` | `0x1658` | `0x16d4` | **`+0x7c`** |
| `__AUTH_CONST.__const` | `0x5540` | `0x55a8` | **`+0x68`** |
| `__AUTH_CONST.__cfstring` | `0x76e0` | `0x7740` | **`+0x60`** |
| `__DATA.__data` | `0x2910` | `0x2958` | **`+0x48`** |
| `__TEXT.__cstring` | `0x11b26` | `0x11b56` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x19c` | `0x188` | **`-0x14`** |
| `__DATA_CONST.__const` | `0x5410` | `0x5420` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x250` | `0x25c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1ec0` | `0x1ec8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1ac8` | `0x1ad0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x6d48` | `0x6d50` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xdc3c` | `0xdc44` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x3bc` | `0x3c4` | **`+0x8`** |

### Other Changes

```diff

-2003.100.1.2.1
+2003.200.33.2.5

-  Functions: 9466
-  Symbols:   1874
-  CStrings:  3878
+  Functions: 9515
+  Symbols:   1877
+  CStrings:  3892
Symbols:
+ _IDSGroupAgentRemoteAppIntentsAppSvcName
+ _IDSGroupSessionClientSessionExperimentsKey
+ _IDSServiceNameRemoteAppIntents
CStrings:
+ " => Delegate %p responds to: %@, passing along protobuf: %p"
+ " => Delegate %p responds unhandled protobuf passing along protobuf: %p"
+ "-seed"
+ ".clientSessionExperiments(["
+ "<LinkContext %p> linkID %d (UUID:%@, QRSessionID:%@) networkType %u connectionType %s maxMTU %u estimatedConstantOverhead %u RATType %lu maxBitrate %u (remote networkType %u connectionType %s RATType %lu), relay(provider:%d, token:%dB) serverIsDegraded: %@ localLinkFlags 0x%x remoteLinkFlags 0x%x, localDataSoMask: %u, remoteDataSoMask: %u, virtualRelayLink: %@, delegatedLinkID %d, localInterfaceName: %@, relayProtocolStack: %@, isPartialTLEForUPlusOneEnabled: %@, quality metadata: %@, localLinkTechnology: %u, localLinkTransport: %u, connections: %@, featureFlags: %@, qrExperiments: %@"
+ "IDSGroupSession.cryptors: cryptor stream for topic=%s source=%s closed with error: %s"
+ "IDSGroupSession.cryptors: no cryptor backend available for topic=%s; returning an empty stream, session was likely invalidated"
+ "No local key material found. Skip completion handler update."
+ "RealTimeGroupSessionCryptorBackend.invalidate: dropped invalidation of %ld %s key(s), backend is shut down"
+ "RealTimeGroupSessionCryptorBackend.logHandovers: handed cryptor to subscriber=%llu, topic=%s, encryptionKeyID=%s, decryptionKeys=%ld"
+ "RealTimeGroupSessionCryptorBackend.logKeySetChange: %s %ld new %s key(s): %s; rotated=%{bool}d, totalKeys=%ld"
+ "RealTimeGroupSessionCryptorBackend.logKeySetChange: %s %s key(s) but no locally-generated key is available; cannot encrypt, so no cryptor is handed to subscribers"
+ "RealTimeGroupSessionCryptorBackend.logKeySetChange: %s %s key(s): removed=%ld, rotated=%{bool}d, encryptionKeyID=%s, totalKeys=%ld"
+ "RealTimeGroupSessionCryptorBackend.receive: dropped %ld %s key(s), backend is shut down"
+ "RealTimeGroupSessionCryptorBackend.subscribe: subscriber=%llu for topic=%s source=%s finished immediately, backend is shut down"
+ "RealTimeGroupSessionCryptorBackend.subscribe: subscriber=%llu registered for topic=%s source=%s; handed cryptor from cached material, encryptionKeyID=%s, decryptionKeys=%ld"
+ "RealTimeGroupSessionCryptorBackend.subscribe: subscriber=%llu registered for topic=%s source=%s; no locally-generated key yet, no cryptor handed over"
+ "XPC has informed us that a fatal error has occurred, we will not be attempting to reconnect any further"
+ "_IDSRealTimeGroupSessionCryptorBackend.logDropped: %ld of %ld %s key material dict(s) failed to parse and were dropped before reaching the cryptor"
+ "_IDSRealTimeGroupSessionCryptorBackend.shutdown: shutting down cryptor backend, all subscriber streams will finish"
+ "com.apple.private.alloy.remoteappintents"
+ "remoteappintents"
- " => Delgate %p responds to: %@, passing along protobuf: %p"
- " => Delgate %p responds unhandled protobuf passing along protobuf: %p"
- "%s: no cryptor backend available; returning an empty stream (session likely invalidated)"
- "<LinkContext %p> linkID %d (UUID:%@, QRSessionID:%@) networkType %u connectionType %s maxMTU %u estimatedConstantOverhead %u RATType %lu maxBitrate %u (remote networkType %u connectionType %s RATType %lu), relay(provider:%d, token:%dB) serverIsDegraded: %@ localLinkFlags 0x%x remoteLinkFlags 0x%x, localDataSoMask: %u, remoteDataSoMask: %u, virtualRelayLink: %@, delegatedLinkID %d, localInterfaceName: %@, relayProtocolStack: %@, isPartialTLEForUPlusOneEnabled: %@, quality metadata: %@, connections: %@, featureFlags: %@, qrExperiments: %@"
- "No local key material found. Skip completion handler udpate."
- "RealTimeGroupSessionCryptor"
- "XPC has informed us that a fatal error has occured, we will not be attempting to reconnect any further"
- "cryptors(forTopic:keyMaterialSource:strategy:_:)"
```
