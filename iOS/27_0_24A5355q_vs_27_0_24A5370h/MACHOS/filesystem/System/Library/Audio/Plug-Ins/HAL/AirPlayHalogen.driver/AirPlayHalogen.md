## AirPlayHalogen

> `/System/Library/Audio/Plug-Ins/HAL/AirPlayHalogen.driver/AirPlayHalogen`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xec6c` | `0xeccc` | **`+0x60`** |
| `__TEXT.__cstring` | `0x3450` | `0x3468` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x318` | `0x320` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-980.58.1.11.1
+980.63.2.0.0

-  Functions: 319
+  Functions: 320

-  CStrings:  265
+  CStrings:  266
CStrings:
+ "[%{ptr}] StartIO begin\n"
```
