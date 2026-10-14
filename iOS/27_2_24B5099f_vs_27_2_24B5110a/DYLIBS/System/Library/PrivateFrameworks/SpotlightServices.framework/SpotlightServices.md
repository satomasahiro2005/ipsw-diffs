## SpotlightServices

> `/System/Library/PrivateFrameworks/SpotlightServices.framework/SpotlightServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x160504` | `0x16096c` | **`+0x468`** |
| `__TEXT.__oslogstring` | `0xbc0b` | `0xbd0b` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0xe648` | `0xe688` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x8dd0` | `0x8df8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x36c60` | `0x36c80` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3498` | `0x34b0` | **`+0x18`** |
| `__TEXT.__const` | `0x2e38` | `0x2e48` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2465.1.7.0.0
+2465.1.9.0.0

-  Functions: 6461
-  Symbols:   11509
-  CStrings:  7943
+  Functions: 6468
+  Symbols:   11513
+  CStrings:  7947
Symbols:
+ +[SPKQuery appScopeBundleIdentifiers]
+ +[SPKQuery isAllowedUnderAppScopeInContext:]
+ -[SPSearchQueryContext appScopeBundleIdentifier]
+ -[SPSearchQueryContext appScopeEntity]
+ -[SPSearchQueryContext isAppScopedSearch]
+ GCC_except_table39
- GCC_except_table22
- GCC_except_table37
CStrings:
+ "(unresolved)"
+ "[qid=%lu][AppScope] %{public}@ is in a multi-producer domain but declares no appScopeBundleIdentifiers — denying under app scope %{public}@ rather than leaking."
+ "[qid=%lu][AppScope] Bundle ID: %{public}@"
+ "[qid=%lu][AppScope] Detected app-scoped search"
```
