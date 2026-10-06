## BackBoardHIDTouchEventProcessor

> `/System/Library/PrivateFrameworks/BackBoardHIDTouchEventProcessor.framework/BackBoardHIDTouchEventProcessor`

### Other Changes

```diff

-873.100.0.0.0
+877.0.0.0.0
Functions:
~ -[BKHIDDirectTouchEventProcessor initWithHitTestDispatcher:displayRenderSpace:deliveryManager:senderCache:serviceMatcherDataProvider:] -> -[BKHIDDirectTouchEventProcessor _initWithHitTestDispatcher:persistentPropertyController:deliveryManagerProvider:displayRenderSpace:orientationProvider:senderCache:touchServiceClientManager:touchPadManager:serviceMatcherDataProvider:] : 348 -> 2136
~ -[BKHIDDirectTouchEventProcessor _initWithHitTestDispatcher:persistentPropertyController:deliveryManagerProvider:displayRenderSpace:orientationProvider:senderCache:touchServiceClientManager:touchPadManager:serviceMatcherDataProvider:] -> -[BKHIDDirectTouchEventProcessor initWithHitTestDispatcher:displayRenderSpace:deliveryManager:senderCache:serviceMatcherDataProvider:] : 2136 -> 348
```
