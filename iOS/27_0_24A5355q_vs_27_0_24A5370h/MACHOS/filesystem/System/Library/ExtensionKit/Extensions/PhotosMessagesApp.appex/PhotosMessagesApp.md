## PhotosMessagesApp

> `/System/Library/ExtensionKit/Extensions/PhotosMessagesApp.appex/PhotosMessagesApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5244` | `0x52e0` | **`+0x9c`** |
| `__TEXT.__cstring` | `0x3ef` | `0x418` | **`+0x29`** |
| `__DATA_CONST.__const` | `0x5a8` | `0x5d0` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x1da4` | `0x1dca` | **`+0x26`** |
| `__TEXT.__objc_stubs` | `0x1cc0` | `0x1ce0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x490` | `0x4a0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x8d0` | `0x8d8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x258` | `0x260` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x6b3` | `0x6b5` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 95
-  Symbols:   138
-  CStrings:  447
+  Functions: 96
+  Symbols:   139
+  CStrings:  449
Symbols:
+ _objc_retain_x25
CStrings:
+ "Picker is already presented - updating received search text"
+ "attributedStringFromSearchText:photoLibrary:"
+ "setReceivedSearchText:"
+ "v16@?0@\"<PUMutablePickerConfiguration>\"8"
- "Picker is already presented - adding decorated query data"
- "searchWithDecoratedQueryData:"
```
