## AVCHalogen

> `/System/Library/Audio/Plug-Ins/AVC/AVCHalogen.driver/AVCHalogen`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xac60` | `0xaccc` | **`+0x6c`** |
| `__TEXT.__cstring` | `0x2a52` | `0x2a6a` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x228` | `0x230` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-980.58.1.11.1
+980.63.2.0.0

-  Functions: 220
+  Functions: 221

-  CStrings:  218
+  CStrings:  219
CStrings:
+ "[%{ptr}] StartIO begin\n"
```
