## lskdd

> `/usr/libexec/lskdd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10a13e0` | `0x10b9900` | **`+0x18520`** |
| `__DATA_CONST.__const` | `0x4fb98` | `0x50de8` | **`+0x1250`** |
| `__TEXT.__const` | `0x3d37c0` | `0x3d3bc0` | **`+0x400`** |
| `__DATA.__data` | `0x2858` | `0x2a38` | **`+0x1e0`** |
| `__TEXT.__unwind_info` | `0xa80` | `0xb40` | **`+0xc0`** |
| `__TEXT.__objc_methtype` | `0xff` | `0x18b` | **`+0x8c`** |
| `__TEXT.__objc_methname` | `0x54c` | `0x5b4` | **`+0x68`** |
| `__TEXT.__gcc_except_tab` | `0x98` | `0xf0` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x240` | `0x270` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xdc` | `0x100` | **`+0x24`** |
| `__DATA_CONST.__cfstring` | `0x100` | `0x120` | **`+0x20`** |
| `__TEXT.__cstring` | `0x161` | `0x17a` | **`+0x19`** |
| `__DATA.__common` | `0x941a4` | `0x941bc` | **`+0x18`** |
| `__DATA.__objc_const` | `0x148` | `0x160` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x130` | `0x148` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1b0` | `0x1c0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x80` | `0x88` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-  Functions: 417
-  Symbols:   203
-  CStrings:  97
+  Functions: 436
+  Symbols:   205
+  CStrings:  105
Symbols:
+ _objc_release_x22
+ _objc_release_x8
CStrings:
+ "com.apple.lskdd.vgkijxyk"
+ "fetchAssetFromBundle:assetType:assetID:reply:"
+ "forceRefreshForBundle:reply:"
+ "getCurrentBundleVersionForBundle:reply:"
+ "v32@0:8q16@?24"
+ "v32@0:8q16@?<v@?@\"NSError\">24"
+ "v32@0:8q16@?<v@?I>24"
+ "v44@0:8q16I24@\"NSData\"28@?<v@?@\"NSData\"@\"NSError\">36"
+ "v44@0:8q16I24@28@?36"
- "invalidate"
```
