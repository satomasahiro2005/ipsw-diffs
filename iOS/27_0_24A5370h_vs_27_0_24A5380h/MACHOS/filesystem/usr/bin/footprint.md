## footprint

> `/usr/bin/footprint`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fa48` | `0x1fae0` | **`+0x98`** |
| `__TEXT.__cstring` | `0x2ceb` | `0x2d73` | **`+0x88`** |
| `__DATA_CONST.__got` | `0x210` | `0x248` | **`+0x38`** |
| `__DATA_CONST.__cfstring` | `0x10e0` | `0x1100` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-358.0.0.0.0
+360.0.0.0.0

-  CStrings:  1068
+  CStrings:  1069
Functions:
~ +[FPSystemMem getBootCarveoutSize] : 268 -> 276
~ +[FPProcess _nameForBsdInfo:] : 424 -> 440
~ _main : 8472 -> 8600
CStrings:
+ "--forkCorpse is not compatible with --sample because a corpse's memory state is frozen at fork time and will not change between samples"
```
