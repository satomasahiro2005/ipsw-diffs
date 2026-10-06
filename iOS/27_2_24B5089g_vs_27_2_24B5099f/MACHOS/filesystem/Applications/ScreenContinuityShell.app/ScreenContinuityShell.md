## ScreenContinuityShell

> `/Applications/ScreenContinuityShell.app/ScreenContinuityShell`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11ce0` | `0x11ecc` | **`+0x1ec`** |
| `__TEXT.__auth_stubs` | `0x1450` | `0x14b0` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x610` | `0x658` | **`+0x48`** |
| `__TEXT.__objc_methname` | `0x16cd` | `0x170d` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0xa30` | `0xa60` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x500` | `0x520` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x220` | `0x230` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x578` | `0x588` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x488` | `0x490` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-126.8.0.0.0
+126.11.0.0.0

+  - /System/Library/PrivateFrameworks/IconServices.framework/IconServices

-  Symbols:   559
-  CStrings:  365
+  Symbols:   567
+  CStrings:  366
Symbols:
+ _$s10Foundation22_convertNSErrorToErrorys0E0_pSo0C0CSgF
+ _$s22UniformTypeIdentifiers6UTTypeV10identifierSSvg
+ _$s22UniformTypeIdentifiers6UTTypeV14_currentDeviceACvgZ
+ _$s22UniformTypeIdentifiers6UTTypeVMa
+ _OBJC_CLASS_$_ISSymbol
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _objc_retain_x28
CStrings:
+ "symbolForTypeIdentifier:withResolutionStrategy:variantOptions:error:"
```
