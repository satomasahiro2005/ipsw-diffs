## MobileMulticastTransfer

> `/System/Library/PrivateFrameworks/MobileMulticastTransfer.framework/MobileMulticastTransfer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37f54` | `0x383e0` | **`+0x48c`** |
| `__TEXT.__oslogstring` | `0x510f` | `0x5199` | **`+0x8a`** |
| `__AUTH_CONST.__const` | `0x3120` | `0x3180` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x5018` | `0x5048` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xf90` | `0xf98` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1860` | `0x1868` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2bc` | `0x2c0` | **`+0x4`** |
| `__TEXT.__cstring` | `0x1091` | `0x108f` | **`-0x2`** |

### Other Changes

```diff

-274.2.2.0.0
+274.40.15.0.0

-  Functions: 1594
+  Functions: 1601

-  CStrings:  569
+  CStrings:  571
Symbols:
+ -[SKRaptorQDecoder workFolder]
+ GCC_except_table17
+ GCC_except_table23
+ _OBJC_IVAR_$_SKRaptorQDecoder._workFolder
- GCC_except_table16
- GCC_except_table22
- GCC_except_table34
- GCC_except_table9
CStrings:
+ "Failed to purge decoder's work folder: %{public}@"
+ "Failed to purge part output file: %{public}@"
+ "Work folder for NanoRQ decoder: %{public}@"
- "'"
```
