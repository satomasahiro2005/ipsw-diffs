## AMSAccountSyncNotificationPlugin

> `/System/Library/Accounts/Notification/AMSAccountSyncNotificationPlugin.bundle/AMSAccountSyncNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c34` | `0x1d30` | **`+0xfc`** |
| `__TEXT.__oslogstring` | `0x610` | `0x676` | **`+0x66`** |

### Other Changes

```diff

-10.0.45.0.0
+10.0.50.0.0

-  CStrings:  38
+  CStrings:  39
Functions:
~ sub_23d068b90 -> sub_241aedb90 : 1380 -> 1632
CStrings:
+ "%{public}@: [%{public}@] Not syncing. Account was inactive and remains inactive. account = %{public}@"
```
