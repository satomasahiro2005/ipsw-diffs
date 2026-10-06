## sysdiagnosed

> `/usr/libexec/sysdiagnosed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x610c0` | `0x60f60` | **`-0x160`** |
| `__DATA_CONST.__cfstring` | `0x115e0` | `0x11540` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x10c32` | `0x10bd5` | **`-0x5d`** |
| `__TEXT.__objc_methname` | `0xa5c5` | `0xa602` | **`+0x3d`** |
| `__DATA_CONST.__const` | `0x1408` | `0x13e8` | **`-0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0xea8` | `0xe90` | **`-0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0x1410` | `0x13f8` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x3f04` | `0x3f1c` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x29b8` | `0x29c8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xd9c` | `0xdac` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1587.0.0.0.0
+1593.0.0.0.0

-  CStrings:  4842
+  CStrings:  4839
CStrings:
+ "NOT SELF CONTAINS '.vrdump'"
+ "setInternalDirectoryForTesting:"
+ "setSharedInstanceForTesting:"
- "/usr/local/bin/amstool"
- "AMSToolCookieExports"
- "NOT SELF ENDSWITH[c] '.vrdump'"
- "amstool_cookies_list.txt"
- "cookies"
- "logs/AMSTool"
```
