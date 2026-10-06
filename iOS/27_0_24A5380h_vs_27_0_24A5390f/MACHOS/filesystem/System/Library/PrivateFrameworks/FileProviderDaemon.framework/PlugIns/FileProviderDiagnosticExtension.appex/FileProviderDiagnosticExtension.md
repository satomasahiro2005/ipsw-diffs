## FileProviderDiagnosticExtension

> `/System/Library/PrivateFrameworks/FileProviderDaemon.framework/PlugIns/FileProviderDiagnosticExtension.appex/FileProviderDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d10` | `0x2d7c` | **`+0x6c`** |
| `__TEXT.__objc_stubs` | `0xb00` | `0xb40` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x811` | `0x835` | **`+0x24`** |
| `__TEXT.__objc_methtype` | `0x46` | `0x57` | **`+0x11`** |
| `__DATA.__objc_selrefs` | `0x2c8` | `0x2d8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x3b0` | `0x3a0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1e8` | `0x1e0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xc0` | `0xc8` | **`+0x8`** |
| `__TEXT.__cstring` | `0x3b0` | `0x3ac` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4838.0.70.0.0
+4838.0.93.0.0

-  CStrings:  175
+  CStrings:  178
Symbols:
+ _OBJC_CLASS_$_NSUUID
+ _objc_retain_x26
- _objc_retain_x25
- _objc_retain_x27
Functions:
~ sub_100000f4c : 2300 -> 2316
~ sub_100001bc4 -> sub_100001bd4 : 1080 -> 1084
~ sub_100002cd0 -> sub_100002ce4 : 1188 -> 1276
CStrings:
+ "@32@0:8@16@24"
+ "@48@0:8@16@24@32@40"
+ "FileProviderDiagnosticLogs-%@.log"
+ "FileProviderSystemDatabase-%@.txt"
+ "UUID"
+ "UUIDString"
+ "_fpDumpAttachmentItemWithTempURL:ProviderFilter:displayName:requestID:"
+ "_logAttachmentItemWithTempURL:requestID:"
- "@40@0:8@16@24@32"
- "FileProviderDiagnosticLogs-%llu.log"
- "FileProviderSystemDatabase-%llu.txt"
- "_fpDumpAttachmentItemWithTempURL:ProviderFilter:displayName:"
- "_logAttachmentItemWithTempURL:"
```
