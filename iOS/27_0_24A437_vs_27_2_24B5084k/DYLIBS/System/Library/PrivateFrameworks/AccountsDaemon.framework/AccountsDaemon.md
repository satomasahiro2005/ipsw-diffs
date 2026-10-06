## AccountsDaemon

> `/System/Library/PrivateFrameworks/AccountsDaemon.framework/AccountsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8377c` | `0x84020` | **`+0x8a4`** |
| `__TEXT.__oslogstring` | `0x90ca` | `0x916a` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x3dc3` | `0x3e03` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1f10` | `0x1f40` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1750` | `0x1778` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x3300` | `0x3320` | **`+0x20`** |

### Other Changes

```diff

-1123.0.0.0.0
+1125.0.0.0.0

-  Functions: 2423
-  Symbols:   3212
-  CStrings:  1187
+  Functions: 2428
+  Symbols:   3215
+  CStrings:  1190
Symbols:
+ ___76-[ACDAccountStoreFilter enabledDataclassesForAccountWithIdentifier:handler:]_block_invoke
+ ___80-[ACDAccountStoreFilter provisionedDataclassesForAccountWithIdentifier:handler:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48bs_e31_v24?0"ACAccount"8"NSError"16ls32l8s40l8s48l8
CStrings:
+ "\"Client %@ is not allowed to access enabled dataclasses for account %@.\""
+ "\"Client %@ is not allowed to access provisioned dataclasses for account %@.\""
+ "\"Posting ACDAccountStoreDidChangeNotification: %{public}@ %{public}@ account: %{private}@ [%{private}@], notifying:%{bool}d\""
+ "You are not allowed to read the authorization model."
- "Posting ACDAccountStoreDidChangeNotification: %{public}@ %{public}@ account: %{private}@ [%{private}@], notifying:%{bool}d"
```
