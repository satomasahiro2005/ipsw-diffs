## HybridQueryProcessing

> `/System/Library/PrivateFrameworks/HybridQueryProcessing.framework/HybridQueryProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd6af0` | `0xd8c90` | **`+0x21a0`** |
| `__TEXT.__unwind_info` | `0x1760` | `0x18a0` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x4022` | `0x40b2` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x2514` | `0x2494` | **`-0x80`** |
| `__AUTH_CONST.__auth_got` | `0x1138` | `0x1150` | **`+0x18`** |
| `__TEXT.__const` | `0x399c` | `0x398c` | **`-0x10`** |
| `__TEXT.__cstring` | `0x2153` | `0x2143` | **`-0x10`** |

### Other Changes

```diff

-62.1.0.0.0
+67.0.0.0.0

-  Functions: 3647
+  Functions: 3678
CStrings:
+ "HQP 1P: %s.FilterableAttribute missing filterDate — skipping default date ordering"
+ "Safety Block: skipping semantic search and disabling prefix/variant matching — QueryParser flagged the query as OVS (kQPSafetyStatus=BlockedByDenylist); falling back to plain keyword-only search"
- "ARG_MAIL_CATEGORY"
- "Safety Block: skipping semantic search — QueryParser flagged the query as OVS (kQPSafetyStatus=BlockedByDenylist); falling back to keyword-only"
```
