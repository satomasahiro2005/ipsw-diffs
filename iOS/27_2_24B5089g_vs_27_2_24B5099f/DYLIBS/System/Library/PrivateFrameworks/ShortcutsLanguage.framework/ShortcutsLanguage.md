## ShortcutsLanguage

> `/System/Library/PrivateFrameworks/ShortcutsLanguage.framework/ShortcutsLanguage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x170b00` | `0x170cc0` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x86c6` | `0x8672` | **`-0x54`** |
| `__AUTH_CONST.__auth_got` | `0x1388` | `0x1380` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x9d0` | `0x9c8` | **`-0x8`** |

### Other Changes

```diff

-5111.0.2.0.0
+5113.0.1.1.1

-  Functions: 7507
-  Symbols:   1956
-  CStrings:  1037
+  Functions: 7506
+  Symbols:   1953
+  CStrings:  1035
Symbols:
+ _ts_subtree_array_delete
+ _ts_tree_new
- ___stderrp
- _abort
- _ts_calloc_default
- _ts_malloc_default
- _ts_realloc_default
CStrings:
- "tree-sitter failed to allocate %zu bytes"
- "tree-sitter failed to reallocate %zu bytes"
```
