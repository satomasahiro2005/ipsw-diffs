## CoreServicesInternal

> `/System/Library/PrivateFrameworks/CoreServicesInternal.framework/CoreServicesInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e0dc` | `0x2e154` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x20c1` | `0x20d1` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xab0` | `0xaa8` | **`-0x8`** |

### Other Changes

```diff

-606.0.0.0.0
+608.0.0.0.0

-  Functions: 654
+  Functions: 652
Functions:
~ _OUTLINED_FUNCTION_7 : 12 -> 20
- _OUTLINED_FUNCTION_7
~ __ZL36CFURLCreateByResolvingDataInBookmarkPK13__CFAllocatorR12BookmarkDatajmPK9__CFArrayPhPP9__CFErrorPPK7__CFURL : 11212 -> 11284
~ __ZL12fileIDsMatchR12BookmarkDatajPK7__CFURL : 340 -> 480
- __ZL36CFURLCreateByResolvingDataInBookmarkPK13__CFAllocatorR12BookmarkDatajmPK9__CFArrayPhPP9__CFErrorPPK7__CFURL.cold.32
~ __ZL18matchURLToBookmarkR12BookmarkDatajPK7__CFURLPh.cold.1 : 64 -> 68
~ __ZL18matchURLToBookmarkR12BookmarkDatajPK7__CFURLPh.cold.2 : 64 -> 68
~ __ZL18matchURLToBookmarkR12BookmarkDatajPK7__CFURLPh.cold.3 : 64 -> 68
CStrings:
+ "COMPLETED RESOLUTION of a bookmark to a filesystem item, depth=%u item=<%p: %@>, stale=%{bool}d"
- "COMPLETED RESOLUTION of a bookmark to a filesystem item, depth=%u item=<%p: %@>"
```
