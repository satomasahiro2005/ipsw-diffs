## AACloudServiceOwner

> `/System/Library/Accounts/ServiceOwners/AACloudServiceOwner.bundle/AACloudServiceOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1294` | `0x1350` | **`+0xbc`** |
| `__TEXT.__objc_stubs` | `0x3c0` | `0x400` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0xd6` | `0x109` | **`+0x33`** |
| `__TEXT.__auth_stubs` | `0x1f0` | `0x210` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1d8` | `0x1e8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x108` | `0x118` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x4b4` | `0x4c0` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc8` | `0xd0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1063.1.0.0.0
+1064.0.0.0.0

-  Functions: 36
-  Symbols:   49
-  CStrings:  110
+  Functions: 37
+  Symbols:   52
+  CStrings:  113
Symbols:
+ _ACErrorDomain
+ __os_log_error_impl
+ _objc_release_x9
Functions:
~ sub_18d0 : 124 -> 248
CStrings:
+ "Sign-out completed with dataclass plugin error: %@"
+ "code"
+ "domain"
```
