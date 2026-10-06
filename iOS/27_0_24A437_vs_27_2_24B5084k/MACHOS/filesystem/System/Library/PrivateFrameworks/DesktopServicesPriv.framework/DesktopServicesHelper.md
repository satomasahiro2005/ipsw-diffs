## DesktopServicesHelper

> `/System/Library/PrivateFrameworks/DesktopServicesPriv.framework/DesktopServicesHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x82db0` | `0x83068` | **`+0x2b8`** |
| `__TEXT.__gcc_except_tab` | `0xa77c` | `0xa7fc` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x3903` | `0x397c` | **`+0x79`** |
| `__TEXT.__objc_stubs` | `0x1ea0` | `0x1ee0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1910` | `0x1920` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x1e19` | `0x1e29` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x39b0` | `0x39c0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x9a8` | `0x9b0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xc98` | `0xca0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x510` | `0x518` | **`+0x8`** |

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
- `__TEXT.__cstring`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1857.0.0.0.0
+1857.1.4.0.0

-  Functions: 2228
-  Symbols:   578
-  CStrings:  1231
+  Functions: 2229
+  Symbols:   580
+  CStrings:  1234
Symbols:
+ _NSFileProviderInternalErrorDomain
+ _objc_autorelease
CStrings:
+ "Lookup of '%{public}@' needed FP's cache, but nothing is monitoring the provider list"
+ "Unwinding after error - %{public}@"
+ "lowercaseString"
```
