## AMSAccountNotificationPlugin

> `/System/Library/Accounts/Notification/AMSAccountNotificationPlugin.bundle/AMSAccountNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x125cc` | `0x129d4` | **`+0x408`** |
| `__TEXT.__oslogstring` | `0x30ce` | `0x316f` | **`+0xa1`** |
| `__DATA_CONST.__objc_selrefs` | `0xa08` | `0xa30` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x65c` | `0x66c` | **`+0x10`** |

### Other Changes

```diff

-10.1.11.2.1
+10.1.13.2.1

-  Functions: 231
+  Functions: 232

-  CStrings:  254
+  CStrings:  256
CStrings:
+ "%{public}@: [%{public}@] Someone cleared the account's first name. Restoring it."
+ "%{public}@: [%{public}@] Someone cleared the account's last name. Restoring it."
```
