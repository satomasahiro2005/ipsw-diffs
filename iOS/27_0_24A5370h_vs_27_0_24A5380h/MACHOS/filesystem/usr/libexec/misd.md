## misd

> `/usr/libexec/misd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21c28` | `0x21d24` | **`+0xfc`** |
| `__TEXT.__cstring` | `0xb5f4` | `0xb6ba` | **`+0xc6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-396.0.0.0.0
+398.0.0.0.0

-  Functions: 455
+  Functions: 456

-  CStrings:  1750
+  CStrings:  1754
CStrings:
+ "%s proxy prefixes (ND6_IFF_PROXY_PREFIXES) on %s"
+ "%s: %s is not prefix sharing; not enabling proxy prefixes"
+ "%s: mis_ext_if_set_proxy_prefixes, err %d"
+ "%s: mis_ext_if_set_proxy_prefixes, network %s, err %d"
+ "mis_ext_if_set_proxy_prefixes"
- "%s: mis_set_proxy_prefixes, err %d"
```
