## OctagonTrust

> `/System/Library/PrivateFrameworks/OctagonTrust.framework/OctagonTrust`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23888` | `0x242a0` | **`+0xa18`** |
| `__TEXT.__gcc_except_tab` | `0x92c` | `0x94c` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x360` | `0x368` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5b8` | `0x5b0` | **`-0x8`** |

### Other Changes

```diff

-62426.0.0.0.4
+62460.0.22.0.0

-  Symbols:   1196
+  Symbols:   1197
Symbols:
+ __OctagonSignpostLogMetricDeltas
+ ___block_descriptor_97_e8_32s40r_e17_v16?0"NSError"8ls32l8r40l8
- ___block_descriptor_65_e8_32s40r_e17_v16?0"NSError"8ls32l8r40l8
Functions:
~ -[OTCurrentSecureElementIdentities dictionaryRepresentation] : 524 -> 520
~ -[OTCurrentSecureElementIdentities writeTo:] : 348 -> 344
~ -[OTCurrentSecureElementIdentities copyWithZone:] : 404 -> 400
~ -[OTCurrentSecureElementIdentities mergeFrom:] : 384 -> 380
~ +[OTClique(Framework) newFriendsWithContextData:resetReason:error:] : 2216 -> 2396
~ +[OTClique(Framework) filterViableSOSRecords:] : 320 -> 316
~ +[OTClique(Framework) sortListPrioritizingiOSRecords:] : 468 -> 464
~ +[OTClique(Framework) filterRecords:] : 2276 -> 2260
~ +[OTClique(Framework) fetchAndHandleEscrowRecords:shouldFilter:error:] : 2428 -> 2604
~ +[OTClique(Framework) handleRecoveryResults:recoveredInformation:record:performedSilentBurn:error:] : 3988 -> 4100
~ ___99+[OTClique(Framework) handleRecoveryResults:recoveredInformation:record:performedSilentBurn:error:]_block_invoke : 700 -> 856
~ +[OTClique(Framework) performEscrowRecovery:cdpContext:escrowRecord:error:] : 4452 -> 5116
~ +[OTClique(Framework) recordMatchingLabel:allRecords:] : 340 -> 336
~ +[OTClique(Framework) performSilentEscrowRecovery:cdpContext:allRecords:error:] : 4264 -> 4868
~ ___47+[OTClique(Framework) totalTrustedPeers:error:]_block_invoke : 276 -> 272
~ ___46+[OTClique(Framework) trustedFullPeers:error:]_block_invoke : 276 -> 272
~ ___59+[OTClique(Framework) escrowCheck:isBackgroundCheck:error:]_block_invoke : 296 -> 292
~ +[OTClique(Framework) performEscrowRecoveryWithContextData:escrowArguments:error:] : 5756 -> 6532
~ -[OTInheritanceKey wrapWithWrappingKey:error:] : 692 -> 696
~ +[OTInheritanceKey base32:len:] : 456 -> 412
~ +[OTInheritanceKey unbase32:len:] : 412 -> 416
~ +[OTInheritanceKey printableWithData:checksumSize:error:] : 848 -> 856
~ -[OTInheritanceKey unwrapWithError:] : 788 -> 792
~ -[NSError(UsefulConstructors) formatAsNestedJSON] : 864 -> 860
```
