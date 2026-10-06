## CoreDAV

> `/System/Library/PrivateFrameworks/CoreDAV.framework/CoreDAV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51eb0` | `0x51ebc` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x27a8` | `0x27b0` | **`+0x8`** |

### Other Changes

```diff

-1248.0.0.0.0
+1248.1.2.0.0
Symbols:
+ -[CoreDAVMultiGetWithFallbackTaskGroup _fatalMultiGetError]
- -[CoreDAVMultiGetWithFallbackTaskGroup error]
Functions:
~ ___53-[CoreDAVMultiGetWithFallbackTaskGroup _fetchOneItem]_block_invoke : 536 -> 552
~ ___54-[CoreDAVMultiGetWithFallbackTaskGroup startTaskGroup]_block_invoke : 312 -> 308
```
