## libMainThreadChecker.dylib

> `/usr/lib/libMainThreadChecker.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41f90` | `0x41f7c` | **`-0x14`** |
| `__TEXT.__unwind_info` | `0xe8` | `0xe0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-64578.47.1.0.0
+64578.53.1.0.0
Functions:
~ _resetDyldInsertLibraries : 436 -> 424
~ ___library_initializer : 2352 -> 2348
~ _SwizzleClasses : 1400 -> 1392
~ _DetectAppKitNSDocumentAsynchronousSaving : 308 -> 312
```
