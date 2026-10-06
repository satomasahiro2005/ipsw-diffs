## DesktopServicesHelper

> `/System/Library/PrivateFrameworks/DesktopServicesPriv.framework/DesktopServicesHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8157c` | `0x81aac` | **`+0x530`** |
| `__TEXT.__oslogstring` | `0x3655` | `0x37af` | **`+0x15a`** |
| `__TEXT.__gcc_except_tab` | `0xa3bc` | `0xa4dc` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x38c0` | `0x3938` | **`+0x78`** |
| `__TEXT.__objc_stubs` | `0x1e80` | `0x1ec0` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x1dcf` | `0x1e0a` | **`+0x3b`** |
| `__DATA.__bss` | `0x900` | `0x910` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x990` | `0x9a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x500` | `0x510` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1910` | `0x1920` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x904` | `0x914` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x1448` | `0x1456` | **`+0xe`** |
| `__DATA_CONST.__auth_got` | `0xc98` | `0xca0` | **`+0x8`** |
| `__TEXT.__cstring` | `0x2787` | `0x2784` | **`-0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-1850.0.0.0.0
+1852.0.0.0.0

-  Functions: 2214
-  Symbols:   578
-  CStrings:  1211
+  Functions: 2222
+  Symbols:   579
+  CStrings:  1221
Symbols:
+ _os_variant_has_internal_diagnostics
CStrings:
+ "@32@0:8@16@24"
+ "Begin: %{public}s"
+ "TCFURLInfo::TranslateCFError -- status: %{public}s\n\t CFError: %{public}@\n\t URL: %{public}@\n\t Backtrace:\n%{public}@"
+ "[Signpost:%llu] CopyReader: Begin: %{public}s"
+ "[Signpost:%llu] CopyReader: End"
+ "[Signpost:%llu] CopyReader_Drain: Begin: %{public}s"
+ "[Signpost:%llu] CopyReader_Drain: End"
+ "[Signpost:%llu] CopyWriter: Begin: %{public}s"
+ "[Signpost:%llu] CopyWriter: End"
+ "[Signpost:%llu] CopyWriter_Drain: Begin: %{public}s"
+ "[Signpost:%llu] CopyWriter_Drain: End"
+ "initWithEventName:initialDictionary:"
+ "setFileOperationKind:"
- ": "
- "Begin%{public}s%{public}s"
- "TCFURLInfo::TranslateCFError -- status: %{public}s\n\t CFError: %{public}@\n\t Backtrace:\n%{public}@"
```
