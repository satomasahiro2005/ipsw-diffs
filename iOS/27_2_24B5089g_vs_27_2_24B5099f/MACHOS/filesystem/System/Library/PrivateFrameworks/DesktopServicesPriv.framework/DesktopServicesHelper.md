## DesktopServicesHelper

> `/System/Library/PrivateFrameworks/DesktopServicesPriv.framework/DesktopServicesHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83068` | `0x844dc` | **`+0x1474`** |
| `__TEXT.__gcc_except_tab` | `0xa7fc` | `0xaa04` | **`+0x208`** |
| `__TEXT.__oslogstring` | `0x397c` | `0x3a11` | **`+0x95`** |
| `__TEXT.__unwind_info` | `0x39c0` | `0x3a50` | **`+0x90`** |
| `__DATA.__data` | `0x519` | `0x5a1` | **`+0x88`** |
| `__TEXT.__objc_stubs` | `0x1ee0` | `0x1f00` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1e29` | `0x1e46` | **`+0x1d`** |
| `__TEXT.__auth_stubs` | `0x1920` | `0x1910` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x9b0` | `0x9b8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xca0` | `0xc98` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1857.1.4.0.0
+1857.1.7.0.0

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 2229
-  Symbols:   580
-  CStrings:  1234
+  Functions: 2253
+  Symbols:   579
+  CStrings:  1237
Symbols:
+ _CFURLIsFileReferenceURL
- __CFURLAttachSecurityScopeToFileURL
- __CFURLCopySecurityScopeFromFileURL
CStrings:
+ "2!0"
+ "Move operation path cache is full, evicting an entry"
+ "_URLByInsertingResolveFlags:"
+ "rename refused a symlinked component on a resolved path\n\t old: `%{public}@`\n\t new: `%{public}@`"
- "2 0"
```
