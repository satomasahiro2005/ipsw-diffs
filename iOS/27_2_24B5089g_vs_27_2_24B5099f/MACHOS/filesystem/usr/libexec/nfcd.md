## nfcd

> `/usr/libexec/nfcd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1eeb98` | `0x1eec18` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x9ae0` | `0x9b48` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x20d8b` | `0x20d64` | **`-0x27`** |
| `__DATA_CONST.__cfstring` | `0x11920` | `0x11900` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x4e7a` | `0x4e6c` | **`-0xe`** |
| `__TEXT.__cstring` | `0x23254` | `0x2325c` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x9fcc` | `0x9fc4` | **`-0x8`** |
| `__TEXT.__objc_methname` | `0x1600c` | `0x1600b` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-371.7.0.0.0
+371.8.0.0.0

-  Functions: 4350
+  Functions: 4351

-  CStrings:  11591
+  CStrings:  11589
CStrings:
+ "%@/Library/Logs/nfcd_lpcd_false-detect-v2.plist"
+ "NFCD built from (B&I) Stockholm_Base-371.8"
+ "q24@?0@\"NSString\"8@\"NSString\"16"
+ "removeItemAtPath:error:"
+ "sortUsingComparator:"
+ "v32@?0@8Q16^B24"
- "%{public}s:%i Invoking TTR for %d 0x%x"
- "-[_NFSeshatSession maybeTTR:appletResult:]"
- "NFCD built from (B&I) Stockholm_Base-371.7"
- "Result: %d Applet Result: %d"
- "Seshat Failure!"
- "descriptionWithLocale:"
- "maybeTTR:appletResult:"
- "v24@0:8I16S20"
```
