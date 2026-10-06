## AMSAccountNotificationPlugin

> `/System/Library/Accounts/Notification/AMSAccountNotificationPlugin.bundle/AMSAccountNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11f68` | `0x11970` | **`-0x5f8`** |
| `__TEXT.__oslogstring` | `0x2f28` | `0x2d88` | **`-0x1a0`** |
| `__DATA_CONST.__objc_selrefs` | `0x9e8` | `0x9c8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x398` | `0x3a0` | **`+0x8`** |

### Other Changes

```diff

-10.0.60.2.2
+10.0.60.2.4

-  CStrings:  250
+  CStrings:  246
Functions:
~ sub_24259c568 -> sub_24253d568 : 1532 -> 4
CStrings:
- "%{public}@Applied delta to sponsor profileIdentifiers. profile = %{public}@ | isDeletion = %{public}@"
- "%{public}@Failed to update sponsor with new profileIdentifiers. sponsor = %{public}@ error = %{public}@"
- "%{public}@Simple profile has no identifier. Skipping profileIdentifiers cache update. profile = %{public}@"
- "%{public}@Simple profile has no parent. Skipping profileIdentifiers cache update. profile = %{public}@"
```
