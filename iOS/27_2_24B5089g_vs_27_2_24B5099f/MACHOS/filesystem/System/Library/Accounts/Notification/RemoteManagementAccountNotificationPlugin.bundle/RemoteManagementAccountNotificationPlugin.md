## RemoteManagementAccountNotificationPlugin

> `/System/Library/Accounts/Notification/RemoteManagementAccountNotificationPlugin.bundle/RemoteManagementAccountNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23b8` | `0x23e8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x309` | `0x32e` | **`+0x25`** |
| `__DATA_CONST.__cfstring` | `0x1c0` | `0x1e0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1b0` | `0x1b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-624.40.13.0.0
+624.40.15.0.0

+  - /System/Library/PrivateFrameworks/ExchangeSync.framework/Frameworks/DAEAS.framework/DAEAS

-  Symbols:   114
-  CStrings:  183
+  Symbols:   115
+  CStrings:  184
Symbols:
+ _AccountPropertyRemoteManagementExchangeProtocolType
Functions:
~ sub_18d8 -> sub_1950 : 680 -> 728
CStrings:
+ "RemoteManagementExchangeProtocolType"
```
