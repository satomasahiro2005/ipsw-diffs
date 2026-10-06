## CarbonCore

> `/System/Library/PrivateFrameworks/CarbonCore.framework/CarbonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34288` | `0x33d8c` | **`-0x4fc`** |
| `__TEXT.__cstring` | `0x20126` | `0x2008b` | **`-0x9b`** |
| `__AUTH_CONST.__cfstring` | `0xba0` | `0xb20` | **`-0x80`** |
| `__TEXT.__oslogstring` | `0x4801` | `0x4794` | **`-0x6d`** |
| `__AUTH_CONST.__const` | `0x1630` | `0x1610` | **`-0x20`** |
| `__DATA_CONST.__const` | `0xf0d8` | `0xf0c8` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa38` | `0xa30` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x230` | `0x228` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xd08` | `0xd00` | **`-0x8`** |

### Other Changes

```diff

-1405.0.0.0.0
+1406.0.0.0.0

-  Functions: 1099
-  Symbols:   1606
-  CStrings:  4670
+  Functions: 1093
+  Symbols:   1599
+  CStrings:  4662
Symbols:
- __XCacheableSetWithStringKey
- __ZN11SCCacheable16SetWithStringKeyEjPKcmj
- __ZN11SCCacheable16SetWithStringKeyEjPKcmj13audit_token_t
- __ZN15RemoteCacheable16SetWithStringKeyEjPKcmj
- __scsclient_CacheableSetWithStringKey
- __scsserver_CacheableSetWithStringKey
- _sandbox_check_by_audit_token
CStrings:
- "    %d: %s"
- " - int value %d (0x%x)\n"
- " - str value '%s'\n"
- "%s: NAMEDDATA: deallocating passed in data, %p/%d, because the client %d is sandboxed or no cacheable exists"
- "CacheableSetWithStringKey"
- "Has prefs: %d slots\n"
- "SetWithStringKey"
- "_scsserver_CacheableSetWithStringKey"
```
