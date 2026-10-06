## AMSAccountSyncNotificationPlugin

> `/System/Library/Accounts/Notification/AMSAccountSyncNotificationPlugin.bundle/AMSAccountSyncNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d30` | `0x1de0` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x676` | `0x6ce` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c8` | `0x2d0` | **`+0x8`** |

### Other Changes

```diff

-10.0.60.2.4
+10.1.11.2.1

-  CStrings:  39
+  CStrings:  40
Functions:
~ sub_242ed4b90 -> sub_24683bb90 : 1632 -> 1808
CStrings:
+ "%{public}@: [%{public}@] Not syncing. Account is a Simple Profile. account = %{public}@"
```
