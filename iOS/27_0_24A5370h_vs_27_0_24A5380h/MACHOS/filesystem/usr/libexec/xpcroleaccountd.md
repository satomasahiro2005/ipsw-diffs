## xpcroleaccountd

> `/usr/libexec/xpcroleaccountd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21a4` | `0x2238` | **`+0x94`** |
| `__TEXT.__auth_stubs` | `0x630` | `0x640` | **`+0x10`** |
| `__TEXT.__cstring` | `0x40a` | `0x417` | **`+0xd`** |
| `__DATA_CONST.__auth_got` | `0x328` | `0x330` | **`+0x8`** |
| `__TEXT.__const` | `0xa0` | `0x98` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3298.0.4.502.1
+3298.0.10.0.0

-  Functions: 19
-  Symbols:   120
-  CStrings:  76
+  Functions: 20
+  Symbols:   121
+  CStrings:  77
Symbols:
+ _fgetxattr
CStrings:
+ "@(#)VERSION:Darwin Role Account Bootstrapper Version 1.0.0: Sat Jun 27 00:45:36 PDT 2026; root:libxpc_executables-3298.0.10~15/xpcroleaccountd/RELEASE_ARM64E"
+ "Darwin Role Account Bootstrapper Version 1.0.0: Sat Jun 27 00:45:36 PDT 2026; root:libxpc_executables-3298.0.10~15/xpcroleaccountd/RELEASE_ARM64E"
+ "com.apple.quarantine"
- "@(#)VERSION:Darwin Role Account Bootstrapper Version 1.0.0: Wed Jun 17 22:26:57 PDT 2026; root:libxpc_executables-3298.0.4.502.1~2/xpcroleaccountd/RELEASE_ARM64E"
- "Darwin Role Account Bootstrapper Version 1.0.0: Wed Jun 17 22:26:57 PDT 2026; root:libxpc_executables-3298.0.4.502.1~2/xpcroleaccountd/RELEASE_ARM64E"
```
