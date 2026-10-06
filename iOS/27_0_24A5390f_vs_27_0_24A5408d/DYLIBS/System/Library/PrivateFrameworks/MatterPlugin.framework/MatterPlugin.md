## MatterPlugin

> `/System/Library/PrivateFrameworks/MatterPlugin.framework/MatterPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a8bc` | `0x4abc0` | **`+0x304`** |
| `__AUTH_CONST.__objc_const` | `0x6c08` | `0x6c98` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0x1ab0` | `0x1b18` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x5e5b` | `0x5eb8` | **`+0x5d`** |
| `__DATA_CONST.__const` | `0xa08` | `0xa58` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x49ec` | `0x4a3c` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1240` | `0x1288` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d88` | `0x1dc8` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x3ac` | `0x3b8` | **`+0xc`** |

### Other Changes

```diff

-86.0.0.0.0
+86.1.1.0.0

-  Functions: 1713
-  Symbols:   2762
-  CStrings:  625
+  Functions: 1721
+  Symbols:   2775
+  CStrings:  626
Symbols:
+ -[MTRPluginClientXPCProxy callRemoteProxyObject:applyBackpressureCap:]
+ -[MTRPluginClientXPCProxy inFlightPossiblyCappedSendCount]
+ -[MTRPluginClientXPCProxy lastDropLogNSec]
+ -[MTRPluginClientXPCProxy setInFlightPossiblyCappedSendCount:]
+ -[MTRPluginClientXPCProxy setLastDropLogNSec:]
+ -[MTRPluginClientXPCProxy setSuppressedDropCount:]
+ -[MTRPluginClientXPCProxy suppressedDropCount]
+ _OBJC_IVAR_$_MTRPluginClientXPCProxy._inFlightPossiblyCappedSendCount
+ _OBJC_IVAR_$_MTRPluginClientXPCProxy._lastDropLogNSec
+ _OBJC_IVAR_$_MTRPluginClientXPCProxy._suppressedDropCount
+ ___70-[MTRPluginClientXPCProxy callRemoteProxyObject:applyBackpressureCap:]_block_invoke
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_57_e8_32s40bs48w_e5_v8?0ls32l8s40l8w48l8
+ _clock_gettime_nsec_np
- ___49-[MTRPluginClientXPCProxy callRemoteProxyObject:]_block_invoke
CStrings:
+ "%@ dropping XPC send to client - in-flight count %lu >= cap %lu (%lu drop(s) since last log)"
```
