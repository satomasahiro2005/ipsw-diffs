## MFAAuthentication

> `/System/Library/PrivateFrameworks/MFAAuthentication.framework/MFAAuthentication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42d48` | `0x435b8` | **`+0x870`** |
| `__TEXT.__oslogstring` | `0x4eea` | `0x5041` | **`+0x157`** |
| `__TEXT.__cstring` | `0x1bba` | `0x1cb1` | **`+0xf7`** |
| `__DATA_CONST.__objc_selrefs` | `0x4e8` | `0x520` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x4a4` | `0x4dc` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x1c80` | `0x1ca0` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0xa8` | `0xc0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x7d0` | `0x7d8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x7f0` | `0x7f8` | **`+0x8`** |

### Other Changes

```diff

-1219.40.7.0.0
+1219.40.10.502.1

-  Functions: 861
-  Symbols:   1891
-  CStrings:  735
+  Functions: 871
+  Symbols:   1900
+  CStrings:  749
Symbols:
+ -[MFAACertificateManager verifyComponentType:forModuleMFi3Certificate:forAuthFlags:]
+ -[MFAACertificateManager verifyComponentType:forModuleMFi4Certificate:]
+ -[MFAACertificateManager verifyIndex:forModuleMFi4Certificate:forModule:]
+ -[MFAACertificateManager verifyModuleCertificate:forModule:forAuthFlags:forIndex:]
+ -[MFAACertificateManager verifyPartNumber:forModuleMFi4Certificate:forModule:]
+ GCC_except_table45
+ _OUTLINED_FUNCTION_52
+ _OUTLINED_FUNCTION_53
+ _OUTLINED_FUNCTION_54
+ _SecCertificateCopyComponentAttributes
- GCC_except_table35
CStrings:
+ "%s: !certRef"
+ "%s: !componentAttributes"
+ "%s: !retrievedIndex"
+ "%s: (moduleType=%d) found certPartNumber:%@"
+ "%s: (moduleType=%d) found index:%@"
+ "%s: (moduleType=%d) index:%@"
+ "%s: (moduleType=%d) productTypeString:%@"
+ "(moduleType=%d) Error: missing index"
+ "(moduleType=%d) Failure: cannot find part number"
+ "(moduleType=%d) Failure: part number is too short"
+ "-[MFAACertificateManager verifyIndex:forModuleMFi4Certificate:forModule:]"
+ "-[MFAACertificateManager verifyModuleCertificate:forModule:forAuthFlags:forIndex:]"
+ "-[MFAACertificateManager verifyPartNumber:forModuleMFi4Certificate:forModule:]"
+ "iPhone19,4"
```
