## IntentsFoundation

> `/System/Library/PrivateFrameworks/IntentsFoundation.framework/IntentsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9428` | `0x93fc` | **`-0x2c`** |

### Other Changes

```diff

-4016.0.41.16.102
+4016.0.42.4.0
Functions:
~ -[NSArray(IntentsFoundation) if_firstObjectPassingTest:] : 312 -> 308
~ -[NSArray(IntentsFoundation) if_flatMap:] : 416 -> 412
~ -[NSArray(IntentsFoundation) if_objectsPassingTest:] : 372 -> 368
~ __IFOrderedSetTransform : 428 -> 424
~ __IFSetTransform : 428 -> 424
~ +[NSString(IntentsFoundation) if_hexStringFromBytes:length:] : 208 -> 216
~ -[NSDictionary(IntentsFoundation) if_compactMap:] : 420 -> 412
~ +[NSDictionary(IntentsFoundation) if_dictionaryWithObjects:forKeys:count:uniquingKeysWith:] : 300 -> 316
~ ____IFAsyncArrayTransform_block_invoke_2 : 260 -> 252
~ -[INFSentence resolvedSentence] : 1464 -> 1448
~ -[INFSentence unresolvedInArray:] : 316 -> 312
~ -[INFSentence concreteToken:in:] : 380 -> 376
~ -[INFSentence filteredPlaceholders] : 424 -> 420
~ -[NSArray(IntentsFoundation) if_enumerateAsynchronouslyOnQueue:block:completionHandler:] : 972 -> 968
```
