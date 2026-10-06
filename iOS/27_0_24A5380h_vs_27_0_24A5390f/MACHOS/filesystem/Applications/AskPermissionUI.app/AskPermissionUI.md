## AskPermissionUI

> `/Applications/AskPermissionUI.app/AskPermissionUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdd3c` | `0xded8` | **`+0x19c`** |
| `__DATA.__objc_const` | `0x2570` | `0x2658` | **`+0xe8`** |
| `__TEXT.__objc_methname` | `0x400f` | `0x40a1` | **`+0x92`** |
| `__DATA.__objc_data` | `0x500` | `0x550` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x13c8` | `0x1418` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0xea8` | `0xec8` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x1440` | `0x1460` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2400` | `0x2420` | **`+0x20`** |
| `__TEXT.__cstring` | `0xa41` | `0xa58` | **`+0x17`** |
| `__TEXT.__objc_methtype` | `0x18d0` | `0x18df` | **`+0xf`** |
| `__TEXT.__objc_classname` | `0x25d` | `0x26a` | **`+0xd`** |
| `__DATA.__objc_ivar` | `0x164` | `0x16c` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2e8` | `0x2f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`

### Other Changes

```diff

-130.0.23.0.0
+130.0.25.0.0

-  Functions: 257
+  Functions: 263

-  CStrings:  1006
+  CStrings:  1016
CStrings:
+ "@24@0:8@?16"
+ "@?"
+ "DeallocGuard"
+ "TB,N,V_originatedOnThisDevice"
+ "_block"
+ "_originatedOnThisDevice"
+ "dealloc"
+ "initWithDeallocGuardBlock:"
+ "originatedOnThisDevice"
+ "setOriginatedOnThisDevice:"
```
