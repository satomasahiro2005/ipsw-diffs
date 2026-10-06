## GPUToolsPlayback

> `/System/Library/PrivateFrameworks/GPUToolsPlayback.framework/GPUToolsPlayback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x638d4` | `0x63838` | **`-0x9c`** |
| `__AUTH_CONST.__objc_const` | `0x5488` | `0x54c0` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x30fc` | `0x311c` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a68` | `0x2a80` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x21e8` | `0x21e0` | **`-0x8`** |

### Other Changes

```diff

-  Functions: 1403
-  Symbols:   2879
+  Functions: 1402
+  Symbols:   2880
Symbols:
+ GCC_except_table111
Functions:
~ __ZNSt3__16vectorINS_4pairIyU8__strongP11objc_objectEENS_9allocatorIS5_EEE24__emplace_back_slow_pathIJS5_EEEPS5_DpOT_ : 220 -> 212
~ -[DYMTLIndirectArgumentBufferManager resolveIABDecodingOperations] : 1452 -> 1456
~ __ZNSt3__110__function6__funcINS_6__bindIMN14ShaderDebugger8Metadata20MDSerializerLLVM3XXXEFvPNS5_17TracepointContextEEJPS5_RKNS_12placeholders4__phILi1EEEEEEFvS7_EEclEOS7_ : 44 -> 48
~ __ZNSt3__110__function6__funcINS_6__bindIMN14ShaderDebugger8Metadata20MDSerializerLLVM3XXXEFvPNS5_17TracepointContextENS4_20MDWaypointTracePoint22TracePointWaypointTypeEEJPS5_RKNS_12placeholders4__phILi1EEES9_EEEFvS7_EEclEOS7_ : 52 -> 56
~ __ZNSt3__16vectorINS_5tupleIJyyyyyyEEENS_9allocatorIS2_EEE6resizeEm : 372 -> 376
~ ___63-[DYMTLCommonDebugFunctionPlayer setupProfilingForCounterLists]_block_invoke : 1344 -> 1352
~ __ZNSt3__16vectorIyNS_9allocatorIyEEE6resizeEm : 284 -> 288
~ ___63-[DYMTLCommonDebugFunctionPlayer setupProfilingForCounterLists]_block_invoke_2 : 1720 -> 1728
~ __ZNSt3__16vectorIbNS_9allocatorIbEEE6resizeEmb : 128 -> 132
~ __ZNSt3__16vectorI14MTLScissorRectNS_9allocatorIS1_EEE6assignEmRKS1_ : 260 -> 256
- __ZNSt3__16vectorI33MTLVertexAmplificationViewMappingNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_
~ __ZNSt3__15dequeIU8__strongU13block_pointerFvvENS_9allocatorIS3_EEED2B9fqe220106Ev : 312 -> 316
~ __ZNSt3__114__split_bufferIPU8__strongU13block_pointerFvvENS_9allocatorIS4_EEE12emplace_backIJS4_EEEvDpOT_ : 264 -> 268
~ __ZNSt3__114__split_bufferIPU8__strongU13block_pointerFvvERNS_9allocatorIS4_EEE12emplace_backIJS4_EEEvDpOT_ : 264 -> 268
```
