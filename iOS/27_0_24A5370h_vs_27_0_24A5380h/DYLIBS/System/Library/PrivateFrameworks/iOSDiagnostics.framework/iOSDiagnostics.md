## iOSDiagnostics

> `/System/Library/PrivateFrameworks/iOSDiagnostics.framework/iOSDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5414` | `0x55dc` | **`+0x1c8`** |
| `__TEXT.__oslogstring` | `0x402` | `0x4f5` | **`+0xf3`** |
| `__TEXT.__objc_methlist` | `0x9fc` | `0xa1c` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x1ba0` | `0x1bb8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x700` | `0x718` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xa8` | `0xb8` | **`+0x10`** |

### Other Changes

```diff

-1369.0.0.0.0
+1374.0.5.0.0

-  Functions: 188
-  Symbols:   485
-  CStrings:  89
+  Functions: 191
+  Symbols:   484
+  CStrings:  94
Symbols:
- ___49-[DADiagnosticsRemoteRunner _establishConnection]_block_invoke_3
CStrings:
+ "Connection successfully established to remote runner service"
+ "Establishing connection to remote runner service"
+ "XPC connection to remote runner failed: %@"
+ "XPC connection to remote runner not established"
+ "XPC connection to remote runner timed out"
```
