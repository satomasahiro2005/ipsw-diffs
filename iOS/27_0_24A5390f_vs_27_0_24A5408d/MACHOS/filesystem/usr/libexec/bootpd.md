## bootpd

> `/usr/libexec/bootpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x110f4` | `0x11288` | **`+0x194`** |
| `__TEXT.__oslogstring` | `0x11a2` | `0x11c4` | **`+0x22`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-555.0.0.0.0
+557.0.0.0.0

-  CStrings:  651
+  CStrings:  652
Functions:
~ sub_1000019bc : 6864 -> 6872
~ sub_100003ac4 -> sub_100003acc : 832 -> 836
~ sub_1000110e8 -> sub_1000110f4 : 1020 -> 1412
CStrings:
+ "frame_length %zu > sendbuf_len %u"
```
