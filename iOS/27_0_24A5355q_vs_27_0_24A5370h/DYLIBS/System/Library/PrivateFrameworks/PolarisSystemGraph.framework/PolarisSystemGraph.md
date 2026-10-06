## PolarisSystemGraph

> `/System/Library/PrivateFrameworks/PolarisSystemGraph.framework/PolarisSystemGraph`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa9f8` | `0xa9b8` | **`-0x40`** |

### Other Changes

```diff

-256.0.0.502.2
+256.0.2.500.1
Functions:
~ -[PSSGClient requestResourcesWithStrides:failedReason:] : 964 -> 960
~ -[PSSGClient handleResourceRequestWithStridesCompletedMessage:] : 480 -> 476
~ -[PSSGMessageBase initWithRawMessage:] : 452 -> 444
~ -[PSSGMessageBase serialize] : 788 -> 780
~ +[PSSGMessagePublishResourceKeysAndStrides messageWithKeysAndStrides:sender:] : 880 -> 876
~ -[PSSGMessagePublishResourceKeysAndStrides resourceOptions] : 604 -> 616
~ +[PSSGMessageSetResourceAvailability messageWithKeysAndResourceAvailability:sender:] : 464 -> 460
~ -[PSSGMessageRequestResourcesBase initWithRawMessage:] : 700 -> 696
~ -[PSSGMessageRequestResourcesBase serialize] : 1232 -> 1196
~ -[PSSysHealthClient updateSystemHealthWithProfile:missesAllowed:poll_interval_secs:] : 400 -> 396
```
