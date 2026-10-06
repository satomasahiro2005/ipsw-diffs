## IOHIDEventSystemStatistics

> `/System/Library/HIDPlugins/IOHIDEventSystemStatistics.plugin/IOHIDEventSystemStatistics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x168` | `0x160` | **`-0x8`** |
| `__TEXT.__text` | `0x24d8` | `0x24d4` | **`-0x4`** |

### Other Changes

```diff

-2353.0.0.0.1
+2360.0.2.0.0
Functions:
~ __ZN26IOHIDEventSystemStatistics15collectKeyStatsEP14__IOHIDServiceP12__IOHIDEvent : 624 -> 620
~ __ZN26IOHIDEventSystemStatistics25registerMultiPressServiceEP14__IOHIDService -> __ZN26IOHIDEventSystemStatistics21registerButtonServiceEP14__IOHIDService : 336 -> 96
~ __ZN26IOHIDEventSystemStatistics20registerCrownServiceEP14__IOHIDService -> __ZN26IOHIDEventSystemStatistics25registerMultiPressServiceEP14__IOHIDService : 180 -> 336
~ __ZN26IOHIDEventSystemStatistics21registerButtonServiceEP14__IOHIDService -> __ZN26IOHIDEventSystemStatistics20registerCrownServiceEP14__IOHIDService : 96 -> 180
```
