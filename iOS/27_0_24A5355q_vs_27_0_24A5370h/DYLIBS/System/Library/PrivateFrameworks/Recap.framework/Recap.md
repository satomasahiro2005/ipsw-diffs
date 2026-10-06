## Recap

> `/System/Library/PrivateFrameworks/Recap.framework/Recap`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2207c` | `0x21fc8` | **`-0xb4`** |
| `__TEXT.__unwind_info` | `0x9d0` | `0x9d8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-195.0.0.0.0
+197.0.0.0.0
Functions:
~ -[RCPPlayer playEventStream:withOptions:] : 1468 -> 1464
~ -[RCPVirtualHIDService propertyForKey:forService:] : 108 -> 104
~ -[CLTOption lefthandHelp] : 804 -> 796
~ -[CLTOptionParser usageString] : 824 -> 816
~ -[CLTOptionParser parse] : 1400 -> 1392
~ -[RCPEventDeliveryServicePool tearDown] : 452 -> 444
~ -[RCPPlayer prewarmForEventStream:withError:] : 448 -> 444
~ __RCPHIDEventMatchingPredicateCore : 332 -> 328
~ +[RCPEventSenderProperties supplyMissingStandardProperties:senderID:] : 1544 -> 1540
~ +[RCPEventSenderProperties senderFromIOHIDService:] : 428 -> 424
~ +[RCPEventSenderProperties _isMouseSender:] : 392 -> 388
~ -[RCPEventSenderProperties _hexifiedObject:] : 460 -> 456
~ +[RCPEventStream eventStreamWithData:error:] : 1328 -> 1324
~ +[RCPEventStream eventStreamWithStudyLogFileURL:error:] : 1132 -> 1128
~ -[RCPEventStream transformDigitizerEventLocationsWithTransform:] : 268 -> 264
~ -[RCPMovie trimmedFrom:to:] : 452 -> 448
~ -[RCPMovie encodeToXPC] : 848 -> 840
~ -[RCPMovie initWithContentsOfURL:] : 860 -> 856
~ -[RCPEventStreamRecorder _finalizePointerEvents] : 480 -> 476
~ +[RCPRecorder unregisterEventStreamRecorder:] : 376 -> 372
~ -[RCPRecorder _registerIOHIDClient] : 884 -> 880
~ ____ioHIDEventCallback_block_invoke : 588 -> 576
~ -[RCPScreenRecorder snapshot] : 532 -> 536
~ -[RCPSyntheticEventStream _findScreenForDisplayUUID:] : 372 -> 368
~ -[RCPSyntheticEventStream _createIOHIDWithEventType:] : 1372 -> 1356
~ -[RCPSyntheticEventStream _finalizePointerButtonMasks] : 492 -> 488
~ -[RCPSyntheticEventStream _updateTouchPoints:count:] : 228 -> 232
~ -[RCPSyntheticEventStream _touchDownAtPoints:touchCount:pressure:radius:edgeMaskOptions:] : 368 -> 384
~ -[RCPSyntheticEventStream touchDown:touchCount:pressure:radius:] : 184 -> 188
~ -[RCPSyntheticEventStream liftUpActivePointsByIndex:] : 504 -> 512
~ -[RCPSyntheticEventStream liftUpAtAllActivePointsWithEventType:] : 160 -> 156
~ -[RCPSyntheticEventStream liftUpAtAllActivePoints] : 156 -> 144
~ -[RCPSyntheticEventStream liftUp:touchCount:] : 148 -> 152
~ -[RCPSyntheticEventStream _moveLastTouchPoint:eventMask:] : 172 -> 184
~ -[RCPSyntheticEventStream moveToPoints:touchCount:pressure:duration:radius:] : 532 -> 512
~ -[RCPSyntheticEventStream pressButtons:duration:] : 512 -> 504
~ -[RCPSyntheticEventStream rotate:withRadius:rotation:duration:touchCount:] : 456 -> 440
~ -[RCPSyntheticEventStream pointerDiscreteGesture:duration:frequency:] : 872 -> 868
~ -[RCPSyntheticEventStream _hoverAtPoints:touchCount:pressure:radius:edgeMaskOptions:withEventType:withZPosition:withAzimuthAngle:withRollAngle:withAltitudeAngle:] : 476 -> 492
~ _parseMultitouchCommandFromArgumentString : 1864 -> 1828
~ -[RCPTimelineView drawRect:] : 1408 -> 1404
~ -[RCPTraceLayer drawInContext:] : 2096 -> 2092
CStrings:
+ "01:26:14"
+ "Jun 11 2026"
- "10:08:28"
- "May 21 2026"
```
