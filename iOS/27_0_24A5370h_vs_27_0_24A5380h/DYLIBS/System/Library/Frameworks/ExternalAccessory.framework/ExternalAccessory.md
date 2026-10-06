## ExternalAccessory

> `/System/Library/Frameworks/ExternalAccessory.framework/ExternalAccessory`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `—` | `0x320` | **`+0x320`** |
| `__DATA_DIRTY.__objc_data` | `0x370` | `0x50` | **`-0x320`** |

### Other Changes

```diff

-461.0.0.0.0
+462.0.0.0.0
Functions:
~ -[EAAccessoryManager stopLocationForConnectedAccessories] -> -[EAAccessoryManager unregisterForLocalNotifications] : 320 -> 252
~ -[EAAccessoryManager unregisterForLocalNotifications] -> -[EAAccessoryManager stopLocationForConnectedAccessories] : 252 -> 320
```
