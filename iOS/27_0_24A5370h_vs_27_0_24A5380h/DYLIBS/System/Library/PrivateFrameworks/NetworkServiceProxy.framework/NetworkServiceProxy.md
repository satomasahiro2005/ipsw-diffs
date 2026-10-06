## NetworkServiceProxy

> `/System/Library/PrivateFrameworks/NetworkServiceProxy.framework/NetworkServiceProxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x60604` | `0x60d7c` | **`+0x778`** |
| `__TEXT.__oslogstring` | `0x3058` | `0x310f` | **`+0xb7`** |
| `__TEXT.__cstring` | `0x5997` | `0x5a00` | **`+0x69`** |
| `__AUTH.__objc_data` | `0x1360` | `0x13b0` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x140` | `0xf0` | **`-0x50`** |
| `__TEXT.__objc_methlist` | `0x5da4` | `0x5dcc` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x11a8` | `0x11c8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2888` | `0x2898` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x6c8` | `0x6c0` | **`-0x8`** |
| `__AUTH_CONST.__objc_const` | `0x7ce0` | `0x7ce8` | **`+0x8`** |

### Other Changes

```diff

-974.0.0.0.0
+976.0.0.0.0

-  Functions: 2074
-  Symbols:   3226
-  CStrings:  1193
+  Functions: 2079
+  Symbols:   3229
+  CStrings:  1199
Symbols:
+ -[NSPPrivateAccessTokenFetcher checkCurrentQuotaStatusWithQueue:completionHandler:]
+ -[NSPServerClient checkCurrentQuotaStatusWithFetcher:allowRetry:completionHandler:]
+ ___83-[NSPPrivateAccessTokenFetcher checkCurrentQuotaStatusWithQueue:completionHandler:]_block_invoke
+ ___83-[NSPServerClient checkCurrentQuotaStatusWithFetcher:allowRetry:completionHandler:]_block_invoke
- _os_variant_has_internal_content
CStrings:
+ "-[NSPPrivateAccessTokenFetcher checkCurrentQuotaStatusWithQueue:completionHandler:]"
+ "Check current quota status got invalid connection, retrying"
+ "Failed to fetch current quota status: %@"
+ "Fetch device quota got invalid connection, retrying"
+ "Fetching current quota status"
+ "NSPServerQuotaStatus"
```
