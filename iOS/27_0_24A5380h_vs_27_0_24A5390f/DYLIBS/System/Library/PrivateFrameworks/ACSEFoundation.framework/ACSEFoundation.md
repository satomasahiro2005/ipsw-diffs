## ACSEFoundation

> `/System/Library/PrivateFrameworks/ACSEFoundation.framework/ACSEFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22e98` | `0x24700` | **`+0x1868`** |
| `__TEXT.__oslogstring` | `0x882` | `0x9c2` | **`+0x140`** |
| `__TEXT.__eh_frame` | `0x1798` | `0x18c8` | **`+0x130`** |
| `__DATA.__bss` | `0x1590` | `0x1510` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x80` | `0x100` | **`+0x80`** |
| `__DATA_DIRTY.__data` | `0xf0` | `0x160` | **`+0x70`** |
| `__DATA.__data` | `0x460` | `0x3f8` | **`-0x68`** |
| `__TEXT.__unwind_info` | `0xa08` | `0xa48` | **`+0x40`** |
| `__TEXT.__cstring` | `0x924` | `0x944` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x250` | `0x260` | **`+0x10`** |
| `__TEXT.__const` | `0x14e8` | `0x14f8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x190` | `0x19c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x928` | `0x930` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x210` | `0x218` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x94` | `0x9c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x9c` | `0xa0` | **`+0x4`** |

### Other Changes

```diff

-301.24.0.9.0
+301.24.0.11.0

-  Functions: 740
+  Functions: 749

-  CStrings:  131
+  CStrings:  137
CStrings:
+ "Built anonymous request %s for url: %s"
+ "Failed to create base URL from key: %s, baseURL: %s"
+ "Failed to fetch anonymous response for request: %@"
+ "Failed to resolve path against base URL from key: %s, baseURL: %s, path: %s"
+ "Successfully fetched anonymous response for request: %@"
+ "X-Apple-Request-UUID"
```
