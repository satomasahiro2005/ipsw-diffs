## MediaAnalysis

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/MediaAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x46a81c` | `0x46a89c` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x1d4a0` | `0x1d4e0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1fd53` | `0x1fd93` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x6476c` | `0x64788` | **`+0x1c`** |
| `__TEXT.__unwind_info` | `0x133b0` | `0x133c0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xf040` | `0xf048` | **`+0x8`** |

### Other Changes

```diff

-435.79.1.4.0
+435.79.1.5.0

-  CStrings:  8322
+  CStrings:  8324
Functions:
~ +[MADUserSafetyQRCodeDetector enabled] : 8 -> 148
~ __ZNKSt3__114default_deleteIN13sentencepiece4util6Status3RepEEclB9fqe220106EPS4_ : 104 -> 92
CStrings:
+ "SensitiveContentAnalysisTestMode"
+ "com.apple.sensitivecontentanalysis.testing"
```
