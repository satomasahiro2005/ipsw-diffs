## Cards

> `/System/Library/PrivateFrameworks/Cards.framework/Cards`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9b14` | `0x9ab8` | **`-0x5c`** |

### Other Changes

```text
Functions:
~ -[CRInvocationChain _forwardInvocation:] : 620 -> 616
~ -[CRInvocationChain _respondsToSelector:] : 336 -> 332
~ -[CRInvocationChain _methodSignatureForSelector:] : 348 -> 344
~ -[CRInvocationChain _enumerateChainedObjectsUsingBlock:] : 308 -> 304
~ -[SFCardSection(CRCardSection) parametersForInteraction:] : 720 -> 716
~ -[SFCardSection(CRCardSection) actionCommands] : 548 -> 544
~ -[SFCollectionCardSection(CRCardSection) resolvedCardSections] : 472 -> 468
~ -[CRBundleManager _getBundlesOnCurrentQueueWithCompletion:] : 1480 -> 1476
~ +[CRCardMocks mockCardsDeserialized] : 408 -> 404
~ +[CRCardMocks movieCard] : 3936 -> 3932
~ +[CRCardMocks responseCard] : 680 -> 676
~ +[CRCardMocks mockAsyncCardWithCard:] : 376 -> 372
~ +[CRCardMocks formattedTextsForStringsAndImages:] : 436 -> 432
~ -[CRProtocolRestrictedInvocationChain _selector:isPartOfProtocol:] : 336 -> 324
~ -[CRJSObject _backingObjectForJSValue:] : 604 -> 600
~ -[SFCard(CRCard) resolvedCardSections] : 472 -> 468
~ -[NSArray(DeepCopy) _deepCopy] : 372 -> 368
~ -[NSSet(DeepCopy) _deepCopy] : 372 -> 368
~ -[CRJSContext _cardWithTitle:cardSections:interaction:error:] : 1392 -> 1380
```
