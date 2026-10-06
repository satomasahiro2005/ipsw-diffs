## FitnessCoachingCore

> `/System/Library/PrivateFrameworks/FitnessCoachingCore.framework/FitnessCoachingCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14a74` | `0x14a10` | **`-0x64`** |

### Other Changes

```diff

-2027.0.9.0.0
+2027.0.11.0.0
Functions:
~ -[FCCNotificationSuppressionStore notificationsSuppressed] : 324 -> 320
~ -[FCCAtypicalDayConfiguration protobuf] : 356 -> 352
~ -[FCCGoalProgressContent transportData] : 352 -> 348
~ -[FCCGoalCompletionContent transportData] : 332 -> 328
~ -[FCCAlmostThereConfiguration protobuf] : 388 -> 384
~ +[FCCDailyGoalLocalizer localizedDescriptionForIncompleteGoalTypes:percentComplete:value:valueRemaining:date:firstName:moveUnit:isWheelchairUser:progressEventIdentifier:minutesToWalkToCompleteRing:hasCurrentMoveStreak:experienceType:isStandalone:] : 2560 -> 2548
~ +[FCCDailyGoalLocalizer localizedDescriptionForGoalsCompleted:singleGoalExceeded:date:firstName:isWheelchairUser:experienceType:isStandalone:] : 1144 -> 1136
~ +[FCCDailyGoalLocalizer _keyForGoalTypes:] : 384 -> 380
~ -[FCCGoalProgressContentProtobuf writeTo:] : 268 -> 264
~ -[FCCCompletionOffTrackConfiguration protobuf] : 520 -> 512
~ -[FCCAlmostThereConfigurationProtobuf dictionaryRepresentation] : 712 -> 708
~ -[FCCAlmostThereConfigurationProtobuf writeTo:] : 468 -> 464
~ -[FCCAlmostThereConfigurationProtobuf copyWithZone:] : 548 -> 544
~ -[FCCAlmostThereConfigurationProtobuf mergeFrom:] : 504 -> 500
~ -[FCCGoalCompletionProtobuf writeTo:] : 220 -> 216
~ -[FCCCompletionOffTrackConfigurationProtobuf dictionaryRepresentation] : 632 -> 628
~ -[FCCCompletionOffTrackConfigurationProtobuf writeTo:] : 460 -> 452
~ -[FCCCompletionOffTrackConfigurationProtobuf copyWithZone:] : 480 -> 476
~ -[FCCCompletionOffTrackConfigurationProtobuf mergeFrom:] : 472 -> 468
~ -[FCCAtypicalDayConfigurationProtobuf writeTo:] : 296 -> 292
```
