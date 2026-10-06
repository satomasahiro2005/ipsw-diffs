## HybridQueryProcessing

> `/System/Library/PrivateFrameworks/HybridQueryProcessing.framework/HybridQueryProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xde748` | `0xd6af0` | **`-0x7c58`** |
| `__TEXT.__oslogstring` | `0x40a2` | `0x4022` | **`-0x80`** |
| `__DATA.__data` | `0xc20` | `0xba8` | **`-0x78`** |
| `__TEXT.__eh_frame` | `0x2584` | `0x2514` | **`-0x70`** |
| `__TEXT.__swift5_typeref` | `0x17d4` | `0x176e` | **`-0x66`** |
| `__TEXT.__const` | `0x39dc` | `0x399c` | **`-0x40`** |
| `__TEXT.__cstring` | `0x2113` | `0x2153` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1790` | `0x1760` | **`-0x30`** |
| `__DATA_DIRTY.__data` | `0x1028` | `0x1008` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1208` | `0x1220` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0xcab` | `0xcbb` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x6970` | `0x6978` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x150` | `0x14c` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x90` | `0x94` | **`+0x4`** |

### Other Changes

```diff

-59.0.1.0.0
+62.1.0.0.0

-  Functions: 3698
+  Functions: 3647
CStrings:
+ "(?i)(.*[/.])?sent$"
+ "(^|\\s)\\.([A-Za-z][A-Za-z0-9]{0,9})(?=\\s|$)"
+ "HQP Planner [%s]: ordering phrase %s detected — L1 query unchanged, hint will drive L2 date sort"
+ "filterOnly(skipRankingWhenFilterOnly=true, direction="
- "HQP Planner [%s]: time ordering %s applied to %ld queries"
- "HQP Planner: %ld person phrases share argLabel=%s and at least one is ungrounded; per-phrase AND-chain will collide with FTS slot overwrite and likely return empty results"
- "filterOnly(skipRankingWhenFilterOnly=true)"
- "plannerRequestedTimeOrdering("
```
