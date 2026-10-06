## MailSearchSchemaManifest

> `/System/Library/PrivateFrameworks/MailSearchSchemaManifest.framework/MailSearchSchemaManifest`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc4cc` | `0xec9c` | **`+0x27d0`** |
| `__DATA.__bss` | `0x2c80` | `0x3280` | **`+0x600`** |
| `__TEXT.__const` | `0x215a` | `0x259a` | **`+0x440`** |
| `__TEXT.__cstring` | `0x1f32` | `0x22d2` | **`+0x3a0`** |
| `__AUTH_CONST.__const` | `0x100c` | `0x10cc` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x644` | `0x6ec` | **`+0xa8`** |
| `__TEXT.__swift5_assocty` | `0x450` | `0x4e0` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x408` | `0x498` | **`+0x90`** |
| `__DATA.__data` | `0x548` | `0x5a8` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x2f0` | `0x350` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x3d2` | `0x426` | **`+0x54`** |
| `__TEXT.__swift5_reflstr` | `0x1ce` | `0x205` | **`+0x37`** |
| `__TEXT.__swift5_proto` | `0x164` | `0x194` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0xb8` | `0xd0` | **`+0x18`** |

### Other Changes

```diff

-2.0.4.0.0
+2.0.6.0.0

-  Functions: 401
-  Symbols:   156
-  CStrings:  200
+  Functions: 455
+  Symbols:   168
+  CStrings:  226
Symbols:
+ _associated conformance 24MailSearchSchemaManifest015QueryMatchInfo_D0V17PoirotSchematizer07MessageD12ConstructingAaD0cdK0
+ _associated conformance 24MailSearchSchemaManifest016MessageFeatures_D0V17PoirotSchematizer0eD12ConstructingAaD0cdI0
+ _associated conformance 24MailSearchSchemaManifest017ResultsRankedGLP_D0V17PoirotSchematizer07MessageD12ConstructingAaD0cdK0
+ _associated conformance 24MailSearchSchemaManifest06Rankeda5Item_D0V17PoirotSchematizer07MessageD12ConstructingAaD0cdJ0
+ _associated conformance 24MailSearchSchemaManifest08L1Score_D0V17PoirotSchematizer07MessageD12ConstructingAaD0cdJ0
+ _associated conformance 24MailSearchSchemaManifest08L2Score_D0V17PoirotSchematizer07MessageD12ConstructingAaD0cdJ0
+ _symbolic _____ 24MailSearchSchemaManifest015QueryMatchInfo_D0V
+ _symbolic _____ 24MailSearchSchemaManifest016MessageFeatures_D0V
+ _symbolic _____ 24MailSearchSchemaManifest017ResultsRankedGLP_D0V
+ _symbolic _____ 24MailSearchSchemaManifest06Rankeda5Item_D0V
+ _symbolic _____ 24MailSearchSchemaManifest08L1Score_D0V
+ _symbolic _____ 24MailSearchSchemaManifest08L2Score_D0V
CStrings:
+ "apple.mail_search.ranker.L1Score"
+ "apple.mail_search.ranker.L2Score"
+ "apple.mail_search.ranker.MessageFeatures"
+ "apple.mail_search.ranker.QueryMatchInfo"
+ "apple.mail_search.ranker.RankedMailItem"
+ "apple.mail_search.ranker.ResultsRankedGLP"
+ "daysSinceReceived"
+ "engagementMultiplier"
+ "hasExactPhraseMatchInBody"
+ "hasExactPhraseMatchInRecipient"
+ "hasExactPhraseMatchInSender"
+ "hasExactPhraseMatchInSubject"
+ "lastTokenIsExactInSender"
+ "lastTokenIsExactInSubject"
+ "lastTokenMatchesSender"
+ "lastTokenMatchesSubject"
+ "qualityMultiplier"
+ "querymatchMultiplier"
+ "ranktrustMultiplier"
+ "recipientMatchCount"
+ "resultsRankedGLP"
+ "senderMatchCount"
+ "structuralMultiplier"
+ "subjectMatchCount"
+ "temporalMultiplier"
+ "totalQueryTokens"
```
