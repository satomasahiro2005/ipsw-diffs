## FitnessCoachingHealthServices

> `/System/Library/PrivateFrameworks/FitnessCoachingHealthServices.framework/FitnessCoachingHealthServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb458` | `0xb444` | **`-0x14`** |

### Other Changes

```diff

-2027.0.9.0.0
+2027.0.11.0.0
Functions:
~ _FCEventCoalescedWithRules : 544 -> 540
~ +[FCGoalProgressEvaluator nextScheduledDatesByEventIdentifiersForEvents:model:evaluationDelegate:] : 420 -> 416
~ +[FCGoalProgressEvaluator evaluateEvents:withModel:evaluationDelegate:] : 388 -> 384
~ -[FCGoalProgressCoordinator dealloc] : 348 -> 344
~ -[FCGoalProgressCoordinator _onqueue_unscheduleEventIdentifiers:] : 364 -> 360
```
