## AVCPlugin

> `/System/Library/ExtensionKit/Extensions/AVCPlugin.appex/AVCPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x1190` | `0x1180` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x8d0` | `0x8c8` | **`-0x8`** |
| `__TEXT.__text` | `0x1572c` | `0x15734` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-46.0.0.0.0
+47.0.0.0.0

-  Symbols:   150
+  Symbols:   149
Symbols:
- _swift_retain_x22
Functions:
~ sub_100014d90 : 644 -> 640
~ sub_100015ddc -> sub_100015dd8 : 276 -> 288
```
