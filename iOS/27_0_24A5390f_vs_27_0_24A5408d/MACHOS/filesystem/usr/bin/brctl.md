## brctl

> `/usr/bin/brctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x140bc` | `0x13d54` | **`-0x368`** |
| `__DATA_CONST.__const` | `0x1010` | `0xfa0` | **`-0x70`** |
| `__TEXT.__cstring` | `0x457d` | `0x451e` | **`-0x5f`** |
| `__TEXT.__objc_methname` | `0x2ba4` | `0x2b53` | **`-0x51`** |
| `__TEXT.__gcc_except_tab` | `0x9bc` | `0x96c` | **`-0x50`** |
| `__TEXT.__objc_stubs` | `0x3240` | `0x3200` | **`-0x40`** |
| `__DATA.__objc_selrefs` | `0xde8` | `0xdd8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x3d0` | `0x3c0` | **`-0x10`** |
| `__TEXT.__const` | `0xf8` | `0xf0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-5168.0.5.0.2
+5168.0.55.0.0

-  Functions: 259
+  Functions: 256

-  CStrings:  1305
+  CStrings:  1298
CStrings:
- "client"
- "cs"
- "delete"
- "deleteAllContentsOfContainerID:onClient:onServer:wait:reply:"
- "deleting container %s on client:%s and on server:%s\n"
- "deletion failed with %s\n"
- "setObjResult:error:"
```
