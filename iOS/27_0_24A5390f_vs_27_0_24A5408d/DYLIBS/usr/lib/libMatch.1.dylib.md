## libMatch.1.dylib

> `/usr/lib/libMatch.1.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6868` | `0x6910` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x158` | `0x150` | **`-0x8`** |

### Other Changes

```diff

-49.0.0.0.0
+50.0.1.0.0
Functions:
~ _matchExec : 4184 -> 4104
~ _expandBuffers : 172 -> 284
~ _addNodeToList : 240 -> 376
```
