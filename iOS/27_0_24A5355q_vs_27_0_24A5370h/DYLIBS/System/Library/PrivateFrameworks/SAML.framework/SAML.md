## SAML

> `/System/Library/PrivateFrameworks/SAML.framework/SAML`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd784` | `0xd6f8` | **`-0x8c`** |

### Other Changes

```diff

-607.0.0.0.0
+608.0.0.0.0
Functions:
~ -[SAMLConditions audienceRestrictions] : 372 -> 368
~ -[SAMLConditions proxyRestrictions] : 328 -> 324
~ -[SAMLAttributeQueryElement samlAttributes] : 304 -> 300
~ -[XMLWrapperElement getElementsByTagName:] : 360 -> 356
~ -[XMLWrapperElement reorderChildElements] : 316 -> 312
~ -[XMLWrapperElement xmlNode:] : 772 -> 760
~ -[SAMLScoping requesterIds] : 336 -> 332
~ -[SAMLScoping idpList] : 348 -> 344
~ -[SAMLResponse attributes] : 408 -> 404
~ -[SAMLResponse subject] : 300 -> 296
~ -[SAMLResponse hasValidAuthentication] : 352 -> 348
~ -[SAMLResponse isValid:] : 644 -> 640
~ -[SAMLResponse authorizationStatusForResource:] : 320 -> 316
~ -[SAMLSignatureReference transforms] : 412 -> 408
~ -[SAMLKeyRetrievalMethod transforms] : 412 -> 408
~ -[SAMLResponseElement assertions] : 304 -> 300
~ -[SAMLResponseElement assertionMeetsConditions:] : 380 -> 376
~ -[SAMLResponseElement authnStatement] : 308 -> 304
~ -[XMLWrapperQuery registerXpathNamespacesForCtx:error:] : 460 -> 456
~ -[XMLWrapperQuery executeXpathQuery:query:ctxNode:error:] : 608 -> 600
~ -[SAMLAssertion samlAttributes] : 348 -> 344
~ -[SAMLAssertion authorizations] : 304 -> 300
~ -[SAMLAssertion isValidForRequestor:] : 312 -> 308
~ -[SAMLAssertion authorizationForResource:] : 348 -> 344
~ -[SAMLAttributeQuery addAttribute:values:] : 344 -> 340
~ -[SAMLAttribute values] : 336 -> 332
~ -[SAMLSignedInfo xmlNode:] : 628 -> 620
~ -[SAMLSignedInfo references] : 304 -> 300
~ -[SAMLSubjectConfirmation xmlNode:] : 572 -> 564
~ -[SAMLSubject subjectConfirmations] : 304 -> 300
```
