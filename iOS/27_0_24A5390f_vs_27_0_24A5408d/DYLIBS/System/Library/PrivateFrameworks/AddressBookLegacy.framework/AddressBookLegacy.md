## AddressBookLegacy

> `/System/Library/PrivateFrameworks/AddressBookLegacy.framework/AddressBookLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78440` | `0x78770` | **`+0x330`** |
| `__TEXT.__oslogstring` | `0x2d7f` | `0x2eff` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x1aa0` | `0x1aa8` | **`+0x8`** |

### Other Changes

```diff

-12876.100.1.0.0
+12877.100.1.0.0

-  Functions: 2627
+  Functions: 2633

-  CStrings:  2548
+  CStrings:  2552
CStrings:
+ "Could not create bitmap context. Error: bytesPerPixel × width × height overflows (w=%f h=%f)"
+ "Could not create bitmap context. Error: size is non-finite, negative, or exceeds SIZE_MAX (w=%f h=%f)"
+ "Could not scale image data. Error: bytesPerPixel × width × height overflows (w=%f h=%f)"
+ "Could not scale image data. Error: size is non-finite, negative, or exceeds SIZE_MAX (w=%f h=%f)"
```
