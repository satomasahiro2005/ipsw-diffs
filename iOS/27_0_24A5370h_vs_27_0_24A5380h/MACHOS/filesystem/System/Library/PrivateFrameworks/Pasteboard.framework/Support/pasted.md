## pasted

> `/System/Library/PrivateFrameworks/Pasteboard.framework/Support/pasted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cd6c` | `0x1c838` | **`-0x534`** |
| `__TEXT.__cstring` | `0x1d38` | `0x1d94` | **`+0x5c`** |
| `__TEXT.__oslogstring` | `0x2151` | `0x21a4` | **`+0x53`** |
| `__TEXT.__objc_stubs` | `0x4560` | `0x4520` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x13d8` | `0x1400` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x5179` | `0x515a` | **`-0x1f`** |
| `__DATA_CONST.__got` | `0x4a0` | `0x4b8` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1378` | `0x1368` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x724` | `0x714` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x718` | `0x708` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-9127.0.71.0.0
+9127.0.75.1.101

-  Functions: 519
+  Functions: 510

-  CStrings:  1366
+  CStrings:  1367
Symbols:
+ _PBProcessArraySerially
- _PBPerformCallback
CStrings:
+ "Resetting changeCount to 0 for pasteboard %@ loaded from a different boot session."
+ "v32@?0@\"NSString\"8@?<v@?>16@?<v@?@\"NSError\">24"
+ "v32@?0@\"PBItem\"8@?<v@?>16@?<v@?@\"NSError\">24"
- "firstObject"
- "subarrayWithRange:"
```
