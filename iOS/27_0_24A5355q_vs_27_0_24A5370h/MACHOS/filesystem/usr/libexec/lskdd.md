## lskdd

> `/usr/libexec/lskdd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x108e12c` | `0x10a7998` | **`+0x1986c`** |
| `__DATA.__common` | `0x9218c` | `0x94184` | **`+0x1ff8`** |
| `__DATA_CONST.__const` | `0x4f778` | `0x50c68` | **`+0x14f0`** |
| `__DATA.__data` | `0x2678` | `0x28a8` | **`+0x230`** |
| `__TEXT.__objc_stubs` | `0x420` | `0x600` | **`+0x1e0`** |
| `__TEXT.__objc_methname` | `0x410` | `0x54c` | **`+0x13c`** |
| `__TEXT.__const` | `0x3d4850` | `0x3d47c0` | **`-0x90`** |
| `__DATA.__objc_selrefs` | `0x128` | `0x1b0` | **`+0x88`** |
| `__TEXT.__objc_methtype` | `0x97` | `0xff` | **`+0x68`** |
| `__TEXT.__cstring` | `0x118` | `0x161` | **`+0x49`** |
| `__TEXT.__gcc_except_tab` | `0x58` | `0x98` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xb0` | `0xdc` | **`+0x2c`** |
| `__DATA_CONST.__cfstring` | `0xe0` | `0x100` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x60` | `0x80` | **`+0x20`** |
| `__DATA.__bss` | `0x40` | `0x58` | **`+0x18`** |
| `__DATA.__objc_const` | `0x130` | `0x148` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xac8` | `0xae0` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x1a` | `0x31` | **`+0x17`** |
| `__TEXT.__auth_stubs` | `0x230` | `0x240` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x128` | `0x130` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-  Functions: 412
-  Symbols:   199
-  CStrings:  72
+  Functions: 426
+  Symbols:   203
+  CStrings:  97
Symbols:
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSLock
+ _OBJC_CLASS_$_NSXPCConnection
+ _OBJC_CLASS_$_NSXPCInterface
CStrings:
+ "FPAssetServiceProtocol"
+ "bytes"
+ "com.apple.fpassetmanagerd"
+ "copy"
+ "dataWithBytes:length:"
+ "fetchAssetWithID:reply:"
+ "forceRefreshWithReply:"
+ "getCurrentBundleVersionWithReply:"
+ "initWithMachServiceName:options:"
+ "interfaceWithProtocol:"
+ "invalidate"
+ "length"
+ "lock"
+ "remoteObjectProxyWithErrorHandler:"
+ "resume"
+ "setInterruptionHandler:"
+ "setInvalidationHandler:"
+ "setRemoteObjectInterface:"
+ "unlock"
+ "v16@?0@\"NSError\"8"
+ "v24@0:8@?16"
+ "v24@0:8@?<v@?@\"NSError\">16"
+ "v24@0:8@?<v@?I>16"
+ "v24@?0@\"NSData\"8@\"NSError\"16"
+ "v32@0:8@\"NSData\"16@?<v@?@\"NSData\"@\"NSError\">24"
```
