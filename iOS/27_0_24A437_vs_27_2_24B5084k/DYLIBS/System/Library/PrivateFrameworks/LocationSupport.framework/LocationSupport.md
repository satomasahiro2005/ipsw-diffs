## LocationSupport

> `/System/Library/PrivateFrameworks/LocationSupport.framework/LocationSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x229ec` | `0x22b30` | **`+0x144`** |
| `__TEXT.__cstring` | `0x1c20` | `0x1c34` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x740` | `0x750` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xc40` | `0xc50` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1208` | `0x1214` | **`+0xc`** |
| `__DATA.__bss` | `0x30` | `0x38` | **`+0x8`** |

### Other Changes

```diff

-3185.0.6.0.3
+3186.0.12.0.0

-  Functions: 732
-  Symbols:   473
-  CStrings:  459
+  Functions: 735
+  Symbols:   478
+  CStrings:  460
Symbols:
+ _CLConnectionClientSetTestRegistrationEndpoint
+ _CLConnectionSharedUsernameCacheForTest
+ _CLConnectionUsernameCacheDestroyForTest
+ _os_variant_allows_internal_security_policies
+ _xpc_connection_create_from_endpoint
CStrings:
+ "com.apple.locationd"
```
