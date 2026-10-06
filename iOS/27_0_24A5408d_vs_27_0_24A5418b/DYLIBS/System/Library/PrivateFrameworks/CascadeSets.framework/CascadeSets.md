## CascadeSets

> `/System/Library/PrivateFrameworks/CascadeSets.framework/CascadeSets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa9f90` | `0xaa010` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x5400` | `0x5410` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3270` | `0x3278` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x669c` | `0x66a4` | **`+0x8`** |

### Other Changes

```diff

-250.0.0.1.0
+250.0.0.3.0

-  Functions: 4613
-  Symbols:   5129
+  Functions: 4614
+  Symbols:   5130
Symbols:
+ -[CCItemFieldPredicate copyWithFieldType:value:]
Functions:
+ -[CCItemFieldPredicate copyWithFieldType:value:]
~ ___44-[CCSetChangeXPCNotifier notifyChangeToSet:]_block_invoke : 596 -> 628
~ +[CCCachedDocumentUtilities documentCachePredicateFromAssociatedSetPredicate:documentCacheSet:error:] : 796 -> 784
~ +[CCCachedDocumentUtilities _documentCachePredicateFromAssociatedSetKeyPrefixedIdentifier:documentCacheSet:error:] : 508 -> 516
CStrings:
+ "%@ firing xpc_event for set: %@ to %lu listener(s)"
- "%@ firing xpc_event for set: %@"
```
