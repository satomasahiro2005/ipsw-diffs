## StocksCore

> `/System/Library/PrivateFrameworks/StocksCore.framework/StocksCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x254dbc` | `0x25684c` | **`+0x1a90`** |
| `__TEXT.__const` | `0x1d600` | `0x1d560` | **`-0xa0`** |
| `__TEXT.__oslogstring` | `0x33a5` | `0x3405` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x14200` | `0x14230` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x17c30` | `0x17c58` | **`+0x28`** |
| `__TEXT.__cstring` | `0xffa0` | `0xffc0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x6bc4` | `0x6be4` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x81ed` | `0x820d` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x99f4` | `0x9a0c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x9638` | `0x9650` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3720` | `0x3730` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0xd0b4` | `0xd0a4` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x2334` | `0x2344` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2470` | `0x2478` | **`+0x8`** |

### Other Changes

```diff

-2016.0.0.0.0
+2018.0.0.0.0

-  Functions: 13759
+  Functions: 13763

-  CStrings:  1882
+  CStrings:  1884
CStrings:
+ "Discarding stale quote for %{public}s: server timestamp %{public}s precedes cached %{public}s"
+ "clientRefreshedAt"
+ "widgetSparklineFetchTimeout"
- "dateLastRefreshed"
```
