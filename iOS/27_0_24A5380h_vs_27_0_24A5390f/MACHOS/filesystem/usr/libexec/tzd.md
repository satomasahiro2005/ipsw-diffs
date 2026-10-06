## tzd

> `/usr/libexec/tzd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15c58` | `0x15d18` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x968` | `0x9f8` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0xc40` | `0xca0` | **`+0x60`** |
| `__DATA.__objc_data` | `0x2b0` | `0x300` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x139f` | `0x13df` | **`+0x40`** |
| `__TEXT.__cstring` | `0x17a4` | `0x17c4` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x4f8` | `0x510` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x44c` | `0x464` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xf50` | `0xf60` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x103` | `0x113` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xb9a` | `0xb8a` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x7b0` | `0x7b8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x278` | `0x280` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x458` | `0x460` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-89.0.0.0.0
+90.0.0.0.0

-  Functions: 424
-  Symbols:   403
-  CStrings:  384
+  Functions: 425
+  Symbols:   405
+  CStrings:  389
Symbols:
+ _OBJC_CLASS_$_UNNotificationIcon
+ _objc_retain_x3
CStrings:
+ "TZNotificationIcon"
+ "com.apple.Preferences"
+ "iconForApplicationIdentifier:"
+ "setIcon:"
+ "setIconForApplicationIdentifier:onContent:"
```
