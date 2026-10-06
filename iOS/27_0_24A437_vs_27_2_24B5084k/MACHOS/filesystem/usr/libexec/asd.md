## asd

> `/usr/libexec/asd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x830a38` | `0x96b27c` | **`+0x13a844`** |
| `__TEXT.__const` | `0xd10f0` | `0xb62c0` | **`-0x1ae30`** |
| `__DATA_CONST.__const` | `0x29098` | `0x29858` | **`+0x7c0`** |
| `__DATA.__data` | `0xed30` | `0xedd0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x4818` | `0x4868` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x6e50` | `0x6e98` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0x75e0` | `0x75c0` | **`-0x20`** |
| `__DATA.__common` | `0x244` | `0x22c` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x360c` | `0x35f4` | **`-0x18`** |
| `__DATA.__bss` | `0x7cb0` | `0x7ca0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xe80` | `0xe70` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0xa3f4` | `0xa3e4` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x2298` | `0x2290` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 6373
-  Symbols:   2066
-  CStrings:  2732
+  Functions: 6379
+  Symbols:   2064
+  CStrings:  2731
Symbols:
- _OBJC_CLASS_$_NSThread
- __dispatch_main_q
CStrings:
- "isMainThread"
```
