## nehelper

> `/usr/libexec/nehelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x4ae1` | `0x4a97` | **`-0x4a`** |
| `__TEXT.__text` | `0x25624` | `0x25600` | **`-0x24`** |
| `__DATA_CONST.__cfstring` | `0x5180` | `0x51a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5f37` | `0x5f44` | **`+0xd`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2331.0.0.0.1
+2340.0.0.0.4
Functions:
~ sub_10001199c : 2312 -> 2152
~ sub_100014874 -> sub_1000147d4 : 8276 -> 8376
~ sub_1000202ac -> sub_100020270 : 3164 -> 3192
~ sub_1000221e8 -> sub_1000221c8 : 956 -> 948
~ sub_1000252f0 -> sub_1000252c8 : 100 -> 104
CStrings:
+ "plugin-types"
- "%@: not platform entitled and no application ID is set, permission denied"
```
