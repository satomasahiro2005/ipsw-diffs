## PersonalizedSensing

> `/System/Library/PrivateFrameworks/PersonalizedSensing.framework/PersonalizedSensing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10480` | `0x10454` | **`-0x2c`** |

### Other Changes

```text
Functions:
~ ___39-[MOConnection onConnectionInterrupted]_block_invoke : 1132 -> 1124
~ ___85-[MOPersonalizedSensingServiceManager fetchPersonalizedContextWithOptions:withReply:]_block_invoke_2 : 672 -> 668
~ ___100-[MOPersonalizedSensingServiceManager fetchContextWithOptions:predicates:authorizedTypes:withReply:]_block_invoke_2 : 408 -> 404
~ -[MODefaultsManager clearRefreshStateDefaults] : 432 -> 428
~ +[MOContextPredicateBuilder inspectExpression:] : 740 -> 732
~ +[MOContextPredicateBuilder disassemblePredicate:] : 672 -> 668
~ +[MOContextPredicateBuilder extractFirstValueForKeyPath:fromPredicates:] : 624 -> 612
```
