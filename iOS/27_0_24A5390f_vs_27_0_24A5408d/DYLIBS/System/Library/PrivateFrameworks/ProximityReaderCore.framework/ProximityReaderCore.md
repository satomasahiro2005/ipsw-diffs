## ProximityReaderCore

> `/System/Library/PrivateFrameworks/ProximityReaderCore.framework/ProximityReaderCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1449ec` | `0x144f88` | **`+0x59c`** |
| `__DATA.__bss` | `0x3bcc0` | `0x3be60` | **`+0x1a0`** |
| `__TEXT.__const` | `0x1f948` | `0x1fa88` | **`+0x140`** |
| `__TEXT.__eh_frame` | `0x6b24` | `0x6c38` | **`+0x114`** |
| `__TEXT.__oslogstring` | `0x3c86` | `0x3d26` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x4488` | `0x44f0` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0x613c` | `0x6198` | **`+0x5c`** |
| `__TEXT.__swift5_typeref` | `0x68d2` | `0x692a` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x5a40` | `0x5a98` | **`+0x58`** |
| `__AUTH_CONST.__const` | `0x130c8` | `0x13090` | **`-0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x6cb0` | `0x6cdc` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x17e8` | `0x17c8` | **`-0x20`** |
| `__AUTH.__objc_data` | `0x1ac8` | `0x1ae0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xa60` | `0xa78` | **`+0x18`** |
| `__AUTH.__data` | `0x3438` | `0x3448` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1158` | `0x1168` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x1cb0` | `0x1cc0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x3b72` | `0x3b82` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x190` | `0x19c` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x14c` | `0x158` | **`+0xc`** |
| `__TEXT.__swift5_protos` | `0x40` | `0x44` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x958` | `0x95c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-150.32.0.0.0
+150.35.0.0.0

-  Functions: 9007
-  Symbols:   3509
-  CStrings:  1134
+  Functions: 9031
+  Symbols:   3513
+  CStrings:  1133
Symbols:
+ ___swift_closure_destructor.27Tm
+ _associated conformance 19ProximityReaderCore08IdentityB13ErrorInternalV4CodeO25DocumentExpiredCodingKeys33_752396CC7D4E54DF673B77F741858BBELLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 19ProximityReaderCore08IdentityB13ErrorInternalV4CodeO25DocumentExpiredCodingKeys33_752396CC7D4E54DF673B77F741858BBELLOs0J3KeyAAs28CustomDebugStringConvertible
+ _symbolic $s19ProximityReaderCore25AnalyticsSessionProvidingP
+ _symbolic SSSg_Sb10hasChangedt
+ _symbolic _____ 19ProximityReaderCore08IdentityB13ErrorInternalV4CodeO25DocumentExpiredCodingKeys33_752396CC7D4E54DF673B77F741858BBELLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 19ProximityReaderCore08IdentityE13ErrorInternalV4CodeO25DocumentExpiredCodingKeys33_752396CC7D4E54DF673B77F741858BBELLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 19ProximityReaderCore08IdentityE13ErrorInternalV4CodeO25DocumentExpiredCodingKeys33_752396CC7D4E54DF673B77F741858BBELLO
- ___swift_closure_destructor.15Tm
- _symbolic _____ySsG 17_StringProcessing5RegexV
- _symbolic _____ySs_G 17_StringProcessing5RegexV5MatchV
- _symbolic _____ySs_GSg 17_StringProcessing5RegexV5MatchV
CStrings:
+ "Ignoring connectionEnded during intentional retry"
+ "MerchantKit-150.35"
+ "Not starting pairing (state/session busy) for: %hhu"
+ "Pairing session to: %hhu failed: %@"
+ "Retrying data session after spontaneous %s in [%s] (attempt %ld)"
+ "customerURL"
+ "pnoBrandSelection"
+ "pnoSelectionAvailable"
+ "pnoSelectionList"
+ "readerDocumentExpired"
+ "useMockBrand"
+ "webSocketURL"
- "/^[a-fA-F0-9]+$/"
- "Already pairing with a device: %hhu"
- "MerchantKit-150.32"
- "Pairing session to: %@ failed to start: %@"
- "autoMenu"
- "bypassAckCertificateValidation"
- "bypassBIPServer"
- "clientURL"
- "hostWebSocket"
- "skipNdefURL"
- "skipRelayID"
- "useMockBrandURL"
- "useTestBAA"
```
