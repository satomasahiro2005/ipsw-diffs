## SystemStatus

> `/System/Library/PrivateFrameworks/SystemStatus.framework/SystemStatus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5970c` | `0x59774` | **`+0x68`** |
| `__AUTH_CONST.__cfstring` | `0x4860` | `0x4880` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0xf578` | `0xf598` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3f34` | `0x3f47` | **`+0x13`** |
| `__DATA_CONST.__const` | `0x19f8` | `0x1a00` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fb8` | `0x1fc0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x84f0` | `0x84f8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2238` | `0x2230` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x5d4` | `0x5d8` | **`+0x4`** |

### Other Changes

```diff

-284.1.0.0.0
+286.101.0.0.0

-  Functions: 3176
-  Symbols:   5618
-  CStrings:  768
+  Functions: 3177
+  Symbols:   5620
+  CStrings:  769
Symbols:
+ -[STDynamicActivityAttributionXPCClientHandle invalidateConnection]
+ _OBJC_IVAR_$_STDynamicActivityAttributionXPCClientHandle._connectionLock
Functions:
~ -[STDynamicActivityAttributionXPCClientHandle currentAttributionsDidChange:] : 96 -> 140
~ -[STDynamicActivityAttributionXPCClientHandle initWithXPCConnection:serverHandle:] : 688 -> 692
~ ___82-[STDynamicActivityAttributionXPCClientHandle initWithXPCConnection:serverHandle:]_block_invoke : 128 -> 104
~ ___82-[STDynamicActivityAttributionXPCClientHandle initWithXPCConnection:serverHandle:]_block_invoke_2 : 128 -> 104
+ -[STDynamicActivityAttributionXPCClientHandle invalidateConnection]
CStrings:
+ "a"
+ "chargingImpossible"
- "A"
```
