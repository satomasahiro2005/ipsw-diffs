## CoreMedia

> `/System/Library/Frameworks/CoreMedia.framework/CoreMedia`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e08f4` | `0x2e0f2c` | **`+0x638`** |
| `__TEXT.__cstring` | `0x6077a` | `0x6081a` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x331cf` | `0x331fd` | **`+0x2e`** |
| `__DATA_DIRTY.__bss` | `0x1b30` | `0x1b50` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0xced0` | `0xcee0` | **`+0x10`** |
| `__DATA.__bss` | `0xa288` | `0xa278` | **`-0x10`** |
| `__DATA_CONST.__const` | `0xbc00` | `0xbc10` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7910` | `0x7918` | **`+0x8`** |

### Other Changes

```diff

-3385.7.1.0.0
+3385.8.1.11.1

-  Functions: 17301
-  Symbols:   12730
-  CStrings:  15324
+  Functions: 17307
+  Symbols:   12734
+  CStrings:  15329
Symbols:
+ _FigEndpointManagerRemoteXPC_CreateEndpoint
+ _FigEndpointManagerRemoteXPC_DestroyEndpoint
+ _kFigEndpointManagerXPCMsgParam_EndpointInfo
+ _kFigEndpointManagerXPCMsgParam_EndpointObjectID
CStrings:
+ "<< FigEndpointManagerXPCRemote >> %s: (%p) %p"
+ "Could not create adminConnectionMutex"
+ "FigEndpointManagerRemoteXPC_CreateEndpoint"
+ "FigEndpointManagerRemoteXPC_DestroyEndpoint"
+ "eventCountByClass total out of range"
```
