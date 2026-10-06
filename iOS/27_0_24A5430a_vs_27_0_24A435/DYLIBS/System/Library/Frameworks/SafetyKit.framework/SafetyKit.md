## SafetyKit

> `/System/Library/Frameworks/SafetyKit.framework/SafetyKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfd28` | `0xfd20` | **`-0x8`** |

### Other Changes

```text
Functions:
~ -[SALocationManager notifyLocation:].cold.1 : 84 -> 88
~ -[SALocationManager stopMonitoringLocation].cold.1 : 84 -> 88
~ -[SALocationManager locationManager:didUpdateLocations:].cold.1 : 124 -> 116
~ -[SALocationManager locationManager:didFailWithError:].cold.1 : 92 -> 84
```
