## IntentsServices

> `/System/Library/PrivateFrameworks/IntentsServices.framework/IntentsServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa0d4` | `0xa0c0` | **`-0x14`** |

### Other Changes

```diff

-4016.0.41.16.102
+4016.0.42.4.0
Functions:
~ ___55-[INSAnalytics logEventWithType:context:contextNoCopy:]_block_invoke : 260 -> 256
~ ___138-[SAIntentGroupProcessIntent(INSExtensionService) _resolveIntentSlotsWithExtensionProxy:onQueue:processIntentCompleted:completionHandler:]_block_invoke.5 : 1176 -> 1168
~ -[SAIntentGroupGetIntentDefinitions(INSExtensionService) ins_getIntentDefinitionsWithCompletionHandler:] : 720 -> 716
~ -[SAIntentGroupGetIntentDefinitions(INSExtensionService) _matchesIntentDefinition:] : 1408 -> 1404
```
