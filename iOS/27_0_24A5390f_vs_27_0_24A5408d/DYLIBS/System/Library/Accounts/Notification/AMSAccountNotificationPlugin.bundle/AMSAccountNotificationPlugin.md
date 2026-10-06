## AMSAccountNotificationPlugin

> `/System/Library/Accounts/Notification/AMSAccountNotificationPlugin.bundle/AMSAccountNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10f9c` | `0x11f68` | **`+0xfcc`** |
| `__TEXT.__oslogstring` | `0x2d46` | `0x2f28` | **`+0x1e2`** |
| `__DATA_CONST.__const` | `0x490` | `0x4c0` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x9c0` | `0x9e8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x1c8` | `0x1a8` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x634` | `0x64c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x390` | `0x398` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-10.0.54.0.0
+10.0.60.2.2

-  Functions: 223
+  Functions: 226

-  CStrings:  243
+  CStrings:  250
CStrings:
+ "%{public}@Applied delta to sponsor profileIdentifiers. profile = %{public}@ | isDeletion = %{public}@"
+ "%{public}@Deselected simple profile: %{public}@."
+ "%{public}@Error staging deselected simple profile: %{public}@. error = %{public}@"
+ "%{public}@Failed to persist deselected simple profile: %{public}@. error = %{public}@"
+ "%{public}@Failed to remove simple profile: %{public}@. error = %{public}@"
+ "%{public}@Failed to update sponsor with new profileIdentifiers. sponsor = %{public}@ error = %{public}@"
+ "%{public}@Removed simple profile: %{public}@."
+ "%{public}@Removing simple profile on sponsor sign-out: %{public}@."
+ "%{public}@Simple profile has no identifier. Skipping profileIdentifiers cache update. profile = %{public}@"
+ "%{public}@Simple profile has no parent. Skipping profileIdentifiers cache update. profile = %{public}@"
+ "%{public}@The account was added already active. account = %{public}@"
+ "v24@?0@\"NSURL\"8@\"NSError\"16"
- "%{public}@: [%{public}@] Failed to update sponsor with new profileIdentifiers. sponsor = %{public}@ error = %{public}@"
- "%{public}@: [%{public}@] Recomputed profileIdentifiers on sponsor for changed profile = %{public}@."
- "%{public}@: [%{public}@] Simple profile has no parent. Skipping profileIdentifiers cache update. profile = %{public}@"
- "%{public}@The account was added already active. account = %{public}@."
- "@16@?0@\"ACAccount\"8"
```
