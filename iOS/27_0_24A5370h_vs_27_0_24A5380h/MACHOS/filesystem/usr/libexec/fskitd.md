## fskitd

> `/usr/libexec/fskitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c4d0` | `0x4c6ec` | **`+0x21c`** |
| `__TEXT.__cstring` | `0x3959` | `0x3900` | **`-0x59`** |
| `__TEXT.__objc_methname` | `0x683b` | `0x67e5` | **`-0x56`** |
| `__DATA_CONST.__const` | `0x2638` | `0x2688` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x22e4` | `0x22b4` | **`-0x30`** |
| `__TEXT.__objc_stubs` | `0x52c0` | `0x52e0` | **`+0x20`** |
| `__DATA.__objc_const` | `0x2300` | `0x22f0` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1920` | `0x1918` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x368` | `0x370` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1158` | `0x1160` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-974.0.1.0.2
+974.0.7.0.0

-  Functions: 1486
+  Functions: 1484

-  CStrings:  2097
+  CStrings:  2096
CStrings:
+ "B16@?0@\"NSDictionary\"8"
+ "addObjectsFromArray:"
+ "lifs_unmount_send_block_invoke_2"
- "-[fskitdXPCServer activateVolume:usingBundle:options:replyHandler:]"
- "-[fskitdXPCServer deactivateVolume:usingBundle:numericOptions:replyHandler:]"
- "activateVolume:usingBundle:options:replyHandler:"
- "deactivateVolume:usingBundle:numericOptions:replyHandler:"
```
