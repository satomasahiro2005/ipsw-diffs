## BTLEServer

> `/usr/sbin/BTLEServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f744` | `0x7f8e4` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0xd852` | `0xd8d6` | **`+0x84`** |
| `__DATA_CONST.__got` | `0x9b8` | `0x9b0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2700.38.0.0.0
+2700.39.0.0.0

-  Functions: 3165
+  Functions: 3167

-  CStrings:  5255
+  CStrings:  5257
CStrings:
+ "DoAP codec list read length (%lu) exceeded data length (%lu)"
+ "DoAP stream client header read length (%lu) exceeded data length (%lu)"
```
