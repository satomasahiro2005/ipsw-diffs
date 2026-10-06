## ckdiscretionaryd

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/Support/ckdiscretionaryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c88` | `0x6908` | **`-0x380`** |
| `__TEXT.__cstring` | `0x3f3` | `0x361` | **`-0x92`** |
| `__DATA_CONST.__cfstring` | `0x240` | `0x1e0` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x430` | `0x3d0` | **`-0x60`** |
| `__TEXT.__dlopen_cstrs` | `0x50` | `—` | **`-0x50`** |
| `__TEXT.__objc_methname` | `0x1a46` | `0x1a02` | **`-0x44`** |
| `__TEXT.__auth_stubs` | `0x600` | `0x5c0` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0x1500` | `0x14c0` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0x310` | `0x2f0` | **`-0x20`** |
| `__DATA.__bss` | `0x30` | `0x20` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x718` | `0x708` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x394` | `0x384` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2c8` | `0x2b8` | **`-0x10`** |
| `__TEXT.__const` | `0x90` | `0x88` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0x762` | `0x763` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2710.108.20.0.0
+2710.112.0.0.0

+  - /System/Library/PrivateFrameworks/CloudDocs.framework/CloudDocs

-  - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking

-  Functions: 205
-  Symbols:   148
-  CStrings:  466
+  Functions: 202
+  Symbols:   144
+  CStrings:  457
Symbols:
+ _OBJC_CLASS_$_BRContainersMonitor
- _OBJC_CLASS_$_NSAssertionHandler
- __sl_dlopen
- _objc_getClass
- _objc_retain_x3
- _objc_retain_x9
CStrings:
+ "Missing critical attribute for initialization of CKDiscretionaryTask. serialQueue:%p, connection:%p, operationID:%p, options:%p, scheduler:%p, startHandler:%p, suspendHandler:%p, transaction:%p, bundleID:%p"
- "%s"
- "BRContainersMonitor"
- "Class getBRContainersMonitorClass(void)_block_invoke"
- "Missing critical attribute for initilization of CKDiscretionaryTask. serialQueue:%p, connection:%p, operationID:%p, options:%p, scheduler:%p, startHandler:%p, suspendHandler:%p, transaction:%p, bundleID:%p"
- "NDApplication.m"
- "Unable to find class %s"
- "currentHandler"
- "handleFailureInFunction:file:lineNumber:description:"
- "softlink:r:path:/System/Library/PrivateFrameworks/CloudDocs.framework/CloudDocs"
- "void *CloudDocsLibrary(void)"
```
