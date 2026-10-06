## libCoreKE.dylib

> `/usr/lib/libCoreKE.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x1d678` | `0x17b68` | **`-0x5b10`** |
| `__TEXT.__text` | `0x15a5e7c` | `0x15a413c` | **`-0x1d40`** |
| `__DATA.__data` | `0x5348` | `0x5d20` | **`+0x9d8`** |
| `__DATA.__common` | `0xc40` | `0x270` | **`-0x9d0`** |
| `__TEXT.__const` | `0xdf004` | `0xdeaf4` | **`-0x510`** |
| `__TEXT.__cstring` | `0x25ca` | `0x2639` | **`+0x6f`** |
| `__TEXT.__unwind_info` | `0xc10` | `0xc20` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-  Functions: 820
+  Functions: 821

-  CStrings:  375
+  CStrings:  377
Symbols:
+ _objc_claimAutoreleasedReturnValue
+ _objc_retain_x22
+ _objc_retain_x8
+ _objc_storeStrong
- _objc_retainAutoreleasedReturnValue
- _objc_retain_x1
- _objc_retain_x19
- _objc_retain_x23
CStrings:
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s cccurve25519 failed: small-order point used%s\n"
+ "generate_wrapping_key_curve25519"
```
