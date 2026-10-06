## NFRestoreService

> `/System/Library/PrivateFrameworks/NearFieldPrivateServices.framework/XPCServices/NFRestoreService.xpc/NFRestoreService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbd0` | `0xc48` | **`+0x78`** |
| `__DATA_CONST.__cfstring` | `0x120` | `0x160` | **`+0x40`** |
| `__TEXT.__cstring` | `0x267` | `0x28a` | **`+0x23`** |
| `__TEXT.__auth_stubs` | `0x2b0` | `0x2d0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x160` | `0x170` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x70` | `0x78` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   64
-  CStrings:  97
+  Symbols:   67
+  CStrings:  99
Symbols:
+ _OBJC_CLASS_$_NSString
+ _objc_release_x26
+ _objc_release_x28
+ _objc_retain_x24
- _objc_release_x27
Functions:
~ sub_1000013b8 : 1092 -> 1212
CStrings:
+ "InvalidBStateSettingsPolicy"
+ "ignore"
```
