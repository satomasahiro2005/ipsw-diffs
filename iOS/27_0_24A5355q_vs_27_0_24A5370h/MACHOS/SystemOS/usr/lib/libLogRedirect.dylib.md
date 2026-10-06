## libLogRedirect.dylib

> `/usr/lib/libLogRedirect.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24b8` | `0x24ac` | **`-0xc`** |

### Same-size Content Changes

- `__AUTH_CONST.__interpose`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-64578.47.1.0.0
+64578.53.1.0.0
Functions:
~ _resetDyldInsertLibraries : 436 -> 424
~ _HookWrite : 376 -> 372
~ _HookBufferAppendEscapedString : 560 -> 548
~ _ParsePathList : 352 -> 344
~ _LogPredicate_Evaluate : 632 -> 640
~ _GetIsSystemFramework : 144 -> 160
```
