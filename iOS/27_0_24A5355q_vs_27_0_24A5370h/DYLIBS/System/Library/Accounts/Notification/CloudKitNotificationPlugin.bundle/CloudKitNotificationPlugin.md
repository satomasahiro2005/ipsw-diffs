## CloudKitNotificationPlugin

> `/System/Library/Accounts/Notification/CloudKitNotificationPlugin.bundle/CloudKitNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x40` | `0x60` | **`+0x20`** |
| `__TEXT.__cstring` | `0x18` | `0x37` | **`+0x1f`** |
| `__TEXT.__text` | `0x12cc` | `0x12c8` | **`-0x4`** |

### Other Changes

```diff

-2710.108.20.0.0
+2710.112.0.0.0

-  CStrings:  15
+  CStrings:  16
Functions:
~ sub_23bf01d6c -> sub_23d076d6c : 1616 -> 1608
~ sub_23bf02834 -> sub_23d07782c : 1604 -> 1600
~ sub_23bf02e78 -> sub_23d077e6c : 436 -> 444
CStrings:
+ "dataclassesDisabledForCellular"
```
