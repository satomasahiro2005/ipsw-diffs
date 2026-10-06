## Notes

> `/System/Library/PrivateFrameworks/Notes.framework/Notes`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13e54` | `0x13fc8` | **`+0x174`** |
| `__TEXT.__oslogstring` | `0xd8e` | `0xe41` | **`+0xb3`** |
| `__TEXT.__cstring` | `0x149b` | `0x14df` | **`+0x44`** |
| `__DATA_CONST.__objc_selrefs` | `0x14c8` | `0x14d0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5d8` | `0x5e0` | **`+0x8`** |

### Other Changes

```diff

-2998.0.0.0.0
+3001.2.1.0.0

-  Functions: 534
-  Symbols:   996
-  CStrings:  272
+  Functions: 536
+  Symbols:   997
+  CStrings:  275
Symbols:
+ _dlerror
CStrings:
+ "/System/Library/PrivateFrameworks/NotesShared.framework/NotesShared"
+ "Could not load NotesShared in %@; HTML notes will be indexed without an App Intents entity association: %s"
+ "Loaded NotesShared but the entity-association category did not register"
```
