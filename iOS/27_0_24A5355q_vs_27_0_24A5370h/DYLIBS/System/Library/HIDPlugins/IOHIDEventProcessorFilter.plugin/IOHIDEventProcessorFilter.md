## IOHIDEventProcessorFilter

> `/System/Library/HIDPlugins/IOHIDEventProcessorFilter.plugin/IOHIDEventProcessorFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3738` | `0x3734` | **`-0x4`** |

### Other Changes

```diff

-2353.0.0.0.1
+2360.0.2.0.0
Functions:
~ __ZN19IOHIDEventProcessor6filterEP12__IOHIDEvent : 872 -> 864
~ __ZN19IOHIDEventProcessor4openEPvP14__IOHIDServicej -> __ZN5Timer4initEP16dispatch_queue_s : 4 -> 284
~ __ZN19IOHIDEventProcessor4openEP14__IOHIDServicej -> __ZN19IOHIDEventProcessor4openEPvP14__IOHIDServicej : 128 -> 4
~ __ZN19IOHIDEventProcessor25scheduleWithDispatchQueueEPvP16dispatch_queue_s -> __ZN19IOHIDEventProcessor4openEP14__IOHIDServicej : 12 -> 136
~ __ZN5Timer4initEP16dispatch_queue_s -> __ZN19IOHIDEventProcessor25scheduleWithDispatchQueueEPvP16dispatch_queue_s : 284 -> 12
~ __ZN11ButtonEvent7LPEnterEP12__IOHIDEvent : 552 -> 548
```
