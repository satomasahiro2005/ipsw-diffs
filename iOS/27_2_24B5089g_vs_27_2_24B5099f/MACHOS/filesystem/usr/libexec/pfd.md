## pfd

> `/usr/libexec/pfd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x73d0` | `0x7408` | **`+0x38`** |
| `__TEXT.__cstring` | `0x1625` | `0x1634` | **`+0xf`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-120.0.0.0.0
+120.40.2.0.0

-  CStrings:  307
+  CStrings:  308
Functions:
~ sub_100000f30 : 1072 -> 1128
CStrings:
+ "%s: %s: %m"
+ "%s: DIOCGETLIMIT index %d: %m"
- "%s: DIOCGETLIMIT index %d"
```
