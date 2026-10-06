## GameControllerFoundation

> `/System/Library/PrivateFrameworks/GameControllerFoundation.framework/GameControllerFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6fc24` | `0x7010c` | **`+0x4e8`** |
| `__AUTH.__objc_data` | `0x2940` | `0x27b0` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `0x320` | `0x4b0` | **`+0x190`** |
| `__AUTH_CONST.__cfstring` | `0x6f80` | `0x6fa0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x6b84` | `0x6ba4` | **`+0x20`** |
| `__TEXT.__cstring` | `0x71ba` | `0x71d9` | **`+0x1f`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e30` | `0x1e48` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2110` | `0x2120` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa58` | `0xa60` | **`+0x8`** |

### Other Changes

```diff

-14.0.19.0.0
+14.0.21.0.0

-  Functions: 2957
-  Symbols:   5367
-  CStrings:  1336
+  Functions: 2962
+  Symbols:   5372
+  CStrings:  1337
Symbols:
+ +[GCIOIterator iterate:handler:]
+ -[GCIOIterator nextObject:]
+ -[GCIORegistryEntry enumerateChildrenInPlane:handler:error:]
+ -[GCIORegistryEntry firstChildInPlane:objectClass:matching:error:]
+ _IORegistryEntryGetChildIterator
CStrings:
+ "Error creating child iterator."
```
