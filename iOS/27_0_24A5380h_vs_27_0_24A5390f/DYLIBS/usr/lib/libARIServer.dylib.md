## libARIServer.dylib

> `/usr/lib/libARIServer.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3617` | `0x363f` | **`+0x28`** |
| `__TEXT.__text` | `0x28b20` | `0x28b30` | **`+0x10`** |

### Other Changes

```diff

-1636.0.0.0.0
+1638.0.0.0.0

-  CStrings:  529
+  CStrings:  530
Functions:
~ __ZN3Ari22AriXpcServerConnectionC2EP17_xpc_connection_sNSt3__18functionIFvNS3_10shared_ptrIS0_EEEEE : 208 -> 224
CStrings:
+ "AriHostRtIPC connection queue (multiple instances)"
+ "AriHostRtIPC listen queue"
- "ConnectionQueue (multiple instances)"
```
