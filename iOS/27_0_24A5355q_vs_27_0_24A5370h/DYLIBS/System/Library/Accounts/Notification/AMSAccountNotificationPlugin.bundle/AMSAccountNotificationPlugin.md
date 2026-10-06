## AMSAccountNotificationPlugin

> `/System/Library/Accounts/Notification/AMSAccountNotificationPlugin.bundle/AMSAccountNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10030` | `0x1089c` | **`+0x86c`** |
| `__TEXT.__oslogstring` | `0x2a7e` | `0x2b1d` | **`+0x9f`** |
| `__DATA_CONST.__objc_selrefs` | `0x970` | `0x9b0` | **`+0x40`** |
| `__TEXT.__cstring` | `0xa15` | `0xa55` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x5f4` | `0x624` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x448` | `0x470` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x800` | `0x820` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1a0` | `0x1b8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x408` | `0x410` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x438` | `0x440` | **`+0x8`** |

### Other Changes

```diff

-10.0.40.4.1
+10.0.45.0.0

-  Functions: 213
-  Symbols:   194
-  CStrings:  230
+  Functions: 218
+  Symbols:   198
+  CStrings:  235
Symbols:
+ _AMSAccountPrivacyAcknowledgementChangedVersionsUserInfoKey
+ _AMSAccountPrivacyAcknowledgementDidChangeNotification
+ _OBJC_CLASS_$_NSDistributedNotificationCenter
+ _objc_retainAutoreleaseReturnValue
CStrings:
+ "%{public}@Error posting notification: %{public}@"
+ "%{public}@Not syncing privacy acknowledgement. Sync is disabled for this account save."
+ "%{public}@Posting a %{public}@ notification."
+ "%{public}@Privacy acknowledgement changed. account = %{public}@ | changedVersions = %{public}@"
+ "%{public}@Syncing privacy acknowledgement. account = %{public}@ | privacyAcknowledgement = %{public}@"
+ "com.apple.private.applemediaservices"
+ "v32@?0@\"NSString\"8@\"NSNumber\"16^B24"
- "%{public}@: [%{public}@] Not syncing privacy acknowledgement. Sync is disabled for this account save."
- "%{public}@: [%{public}@] Syncing privacy acknowledgement. account = %{public}@ | privacyAcknowledgement = %{public}@"
```
