## AMSAccountNotificationPlugin

> `/System/Library/Accounts/Notification/AMSAccountNotificationPlugin.bundle/AMSAccountNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1196c` | `0x125cc` | **`+0xc60`** |
| `__TEXT.__oslogstring` | `0x2d88` | `0x30ce` | **`+0x346`** |
| `__DATA_CONST.__const` | `0x4c0` | `0x530` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x9c8` | `0xa08` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x860` | `0x840` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0x1a8` | `0x1c8` | **`+0x20`** |
| `__TEXT.__cstring` | `0xac5` | `0xae5` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1b8` | `0x1c8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x64c` | `0x65c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3a8` | `0x3b0` | **`+0x8`** |

### Other Changes

```diff

-10.0.60.2.4
+10.1.11.2.1

-  Functions: 226
-  Symbols:   200
-  CStrings:  246
+  Functions: 231
+  Symbols:   202
+  CStrings:  254
Symbols:
+ _ACErrorDomain
+ _AMSPrivateEntitlementName
CStrings:
+ "%{public}@Failed to fetch simple profiles for sponsor. Leaving profileIdentifiers unchanged. sponsor = %{public}@ error = %{public}@"
+ "%{public}@Failed to save sponsor with recomputed profileIdentifiers. The cache stays stale until the next sponsor save. sponsor = %{public}@ error = %{public}@"
+ "%{public}@No simple profile is selected while the sponsor is active. Marking sponsor selected. sponsor = %{public}@"
+ "%{public}@Recomputed sponsor profileIdentifiers. sponsor = %{public}@ | count = %lu"
+ "%{public}@Sponsor has no identifier. Skipping profileIdentifiers cache update. sponsor = %{public}@"
+ "%{public}@Sponsor no longer exists. Skipping profileIdentifiers cache update. sponsor = %{public}@"
+ "%{public}@Sponsor profileIdentifiers already up to date. Skipping save. sponsor = %{public}@"
+ "%{public}@The account was already active and so were %lu other account(s). Reconciled to a single active account. account = %{public}@"
+ "@\"NSString\"16@?0@\"ACAccount\"8"
+ "v24@?0@\"NSArray\"8@\"NSError\"16"
- "%{public}@Error staging deselected simple profile: %{public}@. error = %{public}@"
- "com.apple.private.applemediaservices"
```
