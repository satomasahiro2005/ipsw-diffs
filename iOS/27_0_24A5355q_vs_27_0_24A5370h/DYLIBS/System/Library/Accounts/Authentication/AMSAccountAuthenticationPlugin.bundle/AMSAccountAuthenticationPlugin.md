## AMSAccountAuthenticationPlugin

> `/System/Library/Accounts/Authentication/AMSAccountAuthenticationPlugin.bundle/AMSAccountAuthenticationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x97c8` | `0xa410` | **`+0xc48`** |
| `__TEXT.__oslogstring` | `0x18bc` | `0x1aa0` | **`+0x1e4`** |
| `__DATA_CONST.__const` | `0x468` | `0x4e0` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x948` | `0x980` | **`+0x38`** |
| `__TEXT.__cstring` | `0x971` | `0x98d` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x198` | `0x1b0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x5bc` | `0x5c4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x188` | `0x190` | **`+0x8`** |

### Other Changes

```diff

-10.0.40.4.1
+10.0.45.0.0

-  Functions: 97
-  Symbols:   151
-  CStrings:  175
+  Functions: 101
+  Symbols:   154
+  CStrings:  183
Symbols:
+ _OBJC_CLASS_$_AMSAccountCachedServerData
+ _OBJC_CLASS_$_AMSMutableBinaryPromise
+ _OBJC_CLASS_$_AMSMutablePromise
CStrings:
+ "%{public}@Account data fetch completed. account = %{public}@"
+ "%{public}@Account data fetch failed. error = %{public}@"
+ "%{public}@Account save completed. account = %{public}@"
+ "%{public}@Performing cached data fetch. account = %{public}@"
+ "%{public}@Skipping data fetch, account save failed. error = %{public}@"
+ "%{public}@Starting cached data fetch. credentialSource = %lu | accountBecameActive = %{public}@ | account = %{public}@"
+ "%{public}@Triggering cached data fetch. account = %{public}@"
+ "v24@?0@\"NSURL\"8@\"NSError\"16"
```
