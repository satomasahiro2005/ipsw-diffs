## MTLAssetUpgraderD

> `/usr/libexec/MTLAssetUpgraderD`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18418` | `0x18600` | **`+0x1e8`** |
| `__TEXT.__objc_stubs` | `0x7c0` | `0x840` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0xfb0` | `0xfe8` | **`+0x38`** |
| `__TEXT.__objc_methname` | `0x534` | `0x568` | **`+0x34`** |
| `__TEXT.__oslogstring` | `0xb14` | `0xb41` | **`+0x2d`** |
| `__DATA.__objc_selrefs` | `0x1f0` | `0x210` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x1e0` | `0x200` | **`+0x20`** |
| `__TEXT.__cstring` | `0x92f` | `0x945` | **`+0x16`** |
| `__DATA_CONST.__got` | `0x100` | `0x108` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5c0` | `0x5c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`

### Other Changes

```diff

-382.5.0.0.0
+382.5.3.0.0

-  Functions: 348
-  Symbols:   633
-  CStrings:  206
+  Functions: 350
+  Symbols:   641
+  CStrings:  212
Symbols:
+ GCC_except_table41
+ GCC_except_table44
+ GCC_except_table50
+ _NSCocoaErrorDomain
+ _ZN17MTLAssetUpgraderD24cleanupCompilerArtifactsEv
+ __ZN17MTLAssetUpgraderD24cleanupCompilerArtifactsEv
+ _objc_msgSend$code
+ _objc_msgSend$domain
+ _objc_msgSend$isEqualToString:
+ _objc_msgSend$removeItemAtURL:error:
- GCC_except_table42
- GCC_except_table49
CStrings:
+ "Failed to remove compiler artifacts '%@': %@"
+ "code"
+ "com.apple.gpuarchiver"
+ "domain"
+ "isEqualToString:"
+ "removeItemAtURL:error:"
```
