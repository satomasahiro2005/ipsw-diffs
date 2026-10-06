## AMSAccountNotificationPlugin

> `/System/Library/Accounts/Notification/AMSAccountNotificationPlugin.bundle/AMSAccountNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1089c` | `0x10c34` | **`+0x398`** |
| `__TEXT.__oslogstring` | `0x2b1d` | `0x2bf5` | **`+0xd8`** |
| `__TEXT.__cstring` | `0xa55` | `0xab5` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x820` | `0x860` | **`+0x40`** |
| `__TEXT.__const` | `0x222` | `0x232` | **`+0x10`** |
| `__DATA.__data` | `0x130` | `0x138` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x440` | `0x448` | **`+0x8`** |

### Other Changes

```diff

-10.0.45.0.0
+10.0.50.0.0

-  Functions: 218
-  Symbols:   198
-  CStrings:  235
+  Functions: 221
+  Symbols:   200
+  CStrings:  239
Symbols:
+ _objc_retain_x28
+ _swift_release_x22
CStrings:
+ "%{public}@: [%{public}@] Reverting storefront for remote-device change. incomingStorefront = %{public}@ | revertingTo = %{public}@"
+ "%{public}@: [%{public}@] The storefront changed. Posting a storefront changed notification. dsid = %{public}@ | mediaType = %{public}@ | usedLocalAccountFallback = %{public}@ | oldStorefront = %{public}@ | newStorefront = %{public}@"
+ "Failed to reset cache. dsid ="
+ "NO"
+ "Skipping engagement sync. createBagForSubProfile returned nil."
+ "Successfully reset cache. dsid ="
+ "YES"
- "%{public}@: [%{public}@] The storefront changed. Posting a storefront changed notification. oldStorefront = %{public}@ | newStorefront = %{public}@"
- "Failed to reset cache "
- "Successfully reset cache"
```
