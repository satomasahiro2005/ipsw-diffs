## BlueTool

> `/usr/sbin/BlueTool`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4dde8` | `0x4dee8` | **`+0x100`** |
| `__TEXT.__const` | `0x47c5a0` | `0x47c600` | **`+0x60`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ sub_10000445c : 10112 -> 10368
CStrings:
+ "16:03:24"
- "18:54:38"
```
