## pcsstatus

> `/usr/libexec/pcsstatus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x9f0` | `0xa00` | **`+0x10`** |
| `__TEXT.__text` | `0xeaa4` | `0xeab4` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x508` | `0x510` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1303.0.6.0.0
+1303.40.9.0.0

-  Symbols:   266
+  Symbols:   267
Symbols:
+ _SOSCCIsSOSTrustAndSyncingEnabledCachedValue
Functions:
~ sub_1000039a0 : 640 -> 656
```
