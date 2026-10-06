## libCoreFSCache.dylib

> `/System/Library/Frameworks/OpenGLES.framework/libCoreFSCache.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a78` | `0x5ce8` | **`+0x270`** |
| `__TEXT.__oslogstring` | `0xb9a` | `0xcbd` | **`+0x123`** |
| `__TEXT.__const` | `0xb0` | `0xc0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x140` | `0x130` | **`-0x10`** |
| `__TEXT.__cstring` | `0x29a` | `0x29c` | **`+0x2`** |

### Other Changes

```diff

-404.0.0.0.0
+404.1.1.0.0

-  Functions: 118
+  Functions: 122

-  CStrings:  83
+  CStrings:  88
CStrings:
+ "Unexpected: in-memory page-aligned size: %zu is larger than read-only on-disk file size: %zu by more than a page. Page size is %zu."
+ "fopen for resetting cache not permitted on read-only cache file."
+ "r"
+ "read-only cache is invalid or missing; not reinitializing"
+ "refusing to reset a read-only cache"
```
