## PhotosFileProvider

> `/System/Library/ExtensionKit/Extensions/PhotosFileProvider.appex/PhotosFileProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29f0` | `0x2b08` | **`+0x118`** |
| `__TEXT.__oslogstring` | `0x64f` | `0x6a1` | **`+0x52`** |
| `__TEXT.__auth_stubs` | `0x340` | `0x350` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x128` | `0x130` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

-  Symbols:   99
-  CStrings:  176
+  Symbols:   101
+  CStrings:  177
Symbols:
+ _PXAsyncShareFileProviderErrorDomain
+ _PXAsyncShareFileProviderErrorIsProvenanceFatal
Functions:
~ sub_1000033d4 : 560 -> 840
CStrings:
+ "[ContentProvenance] Item materialization failed with a fatal provenance error: %@"
```
