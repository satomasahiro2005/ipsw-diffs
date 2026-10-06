## AddressBook

> `/System/Library/Frameworks/AddressBook.framework/AddressBook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a698` | `0x1a940` | **`+0x2a8`** |
| `__TEXT.__oslogstring` | `0x3db` | `0x55b` | **`+0x180`** |
| `__TEXT.__const` | `0xd4` | `0xdc` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 682
+  Functions: 688

-  CStrings:  268
+  CStrings:  272
CStrings:
+ "Could not create bitmap context. Error: bytesPerPixel × width × height overflows (w=%f h=%f)"
+ "Could not create bitmap context. Error: size is non-finite, negative, or exceeds SIZE_MAX (w=%f h=%f)"
+ "Could not scale image data. Error: bytesPerPixel × width × height overflows (w=%f h=%f)"
+ "Could not scale image data. Error: size is non-finite, negative, or exceeds SIZE_MAX (w=%f h=%f)"
```
