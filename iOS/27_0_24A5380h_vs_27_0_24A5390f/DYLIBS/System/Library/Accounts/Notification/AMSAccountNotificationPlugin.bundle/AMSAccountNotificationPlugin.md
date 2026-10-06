## AMSAccountNotificationPlugin

> `/System/Library/Accounts/Notification/AMSAccountNotificationPlugin.bundle/AMSAccountNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10c34` | `0x10f9c` | **`+0x368`** |
| `__TEXT.__oslogstring` | `0x2bf5` | `0x2d46` | **`+0x151`** |
| `__AUTH_CONST.__const` | `0x1a8` | `0x1c8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x470` | `0x490` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x9b0` | `0x9c0` | **`+0x10`** |
| `__TEXT.__cstring` | `0xab5` | `0xac5` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x624` | `0x634` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x388` | `0x390` | **`+0x8`** |

### Other Changes

```diff

-10.0.50.0.0
+10.0.54.0.0

-  Functions: 221
+  Functions: 223

-  CStrings:  239
+  CStrings:  243
CStrings:
+ "%{public}@: [%{public}@] Failed to update sponsor with new profileIdentifiers. sponsor = %{public}@ error = %{public}@"
+ "%{public}@: [%{public}@] Recomputed profileIdentifiers on sponsor for changed profile = %{public}@."
+ "%{public}@: [%{public}@] Simple profile has no parent. Skipping profileIdentifiers cache update. profile = %{public}@"
+ "@16@?0@\"ACAccount\"8"
```
