## OfficeImport

> `/System/Library/PrivateFrameworks/OfficeImport.framework/OfficeImport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41f52c` | `0x41f7c0` | **`+0x294`** |
| `__TEXT.__oslogstring` | `—` | `0x35` | **`+0x35`** |
| `__AUTH_CONST.__objc_const` | `0x627f8` | `0x62828` | **`+0x30`** |
| `__TEXT.__cstring` | `0x27232` | `0x27206` | **`-0x2c`** |
| `__AUTH_CONST.__cfstring` | `0x29b60` | `0x29b40` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x51f8c` | `0x51f70` | **`-0x1c`** |
| `__DATA_CONST.__const` | `0x81e0` | `0x81f0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3741c` | `0x3742c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1cfc8` | `0x1cfb8` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1688` | `0x1690` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1560` | `0x1568` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x15e50` | `0x15e58` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x44b4` | `0x44b8` | **`+0x4`** |

### Other Changes

```diff

-322.0.0.0.0
+322.1.1.0.0

-  Functions: 29672
-  Symbols:   47767
-  CStrings:  7971
+  Functions: 29671
+  Symbols:   47770
+  CStrings:  7972
Symbols:
+ -[WXReadState noteNestingDepth]
+ -[WXReadState setNoteNestingDepth:]
+ _HUPropNmLeft
+ _HUPropNmTop
+ _OBJC_IVAR_$_WXReadState.mNoteNestingDepth
+ __ZN5XlPtg11addDataItemEt
+ __os_log_error_impl
+ _os_log_type_enabled
- -[EDBuildableFormula replaceStringInStringTokenAtIndex:content:]
- _CFShow
- __Z24copyStringToExtendedDataPKtPhs
- __ZN5XlPtg11addDataItemEj
- __ZN5XlPtg5clearEv
CStrings:
+ ":%.0f%%;"
```
