## Diagnostic-9008

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9008.appex/Diagnostic-9008`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb70c` | `0xb9f0` | **`+0x2e4`** |
| `__DATA_CONST.__const` | `0x478` | `0x4f0` | **`+0x78`** |
| `__TEXT.__objc_methname` | `0x22da` | `0x2335` | **`+0x5b`** |
| `__TEXT.__auth_stubs` | `0x820` | `0x840` | **`+0x20`** |
| `__TEXT.__cstring` | `0x85d` | `0x87d` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1ea0` | `0x1ec0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x300` | `0x320` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x8c0` | `0x8d8` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xa08` | `0xa18` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x420` | `0x430` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x982` | `0x991` | **`+0xf`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1307.0.26.502.1
+1307.0.46.0.0

-  Functions: 295
-  Symbols:   191
-  CStrings:  657
+  Functions: 301
+  Symbols:   193
+  CStrings:  661
Symbols:
+ _objc_retainBlock
+ _objc_retain_x5
CStrings:
+ "_showAlertWithTitle:message:actionTitle:completion:"
+ "showUnknownErrorAlertWithCode:completion:"
+ "showUserAuthErrorAlertWithCompletion:"
+ "v16@?0@\"UIAlertAction\"8"
+ "v32@0:8q16@?24"
- "_showAlertWithTitle:message:actionTitle:"
```
