## RemoteInjectionAgent

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/RemoteInjectionAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2290` | `0x23e4` | **`+0x154`** |
| `__DATA_CONST.__const` | `0x1a0` | `0x1c8` | **`+0x28`** |
| `__TEXT.__cstring` | `0x1f6` | `0x212` | **`+0x1c`** |
| `__TEXT.__auth_stubs` | `0x4f0` | `0x500` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x288` | `0x290` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd8` | `0xe0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-64578.160.1.0.0
+64578.209.1.0.0

-  Functions: 23
-  Symbols:   108
-  CStrings:  102
+  Functions: 24
+  Symbols:   109
+  CStrings:  103
Symbols:
+ _objc_retain
Functions:
~ sub_100001628 : 592 -> 908
+ sub_100001a98
CStrings:
+ "v56@?0I8I12I16{?=[8I]}20i52"
```
