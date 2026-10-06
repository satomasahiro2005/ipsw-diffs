## usermanagerd

> `/usr/libexec/usermanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xae070` | `0xadff0` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0x15d0` | `0x1560` | **`-0x70`** |
| `__TEXT.__cstring` | `0x7653` | `0x765b` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-488.0.0.0.0
+490.0.0.0.0

-  Functions: 2403
+  Functions: 2400
CStrings:
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s cccurve25519 failed: small-order point used%s\n"
+ "generate_wrapping_key_curve25519"
- "ACMCredential - ACMCredentialDataPKITokenValidated"
- "ACMCredential - ACMCredentialDataPKITokenValidated2"
```
