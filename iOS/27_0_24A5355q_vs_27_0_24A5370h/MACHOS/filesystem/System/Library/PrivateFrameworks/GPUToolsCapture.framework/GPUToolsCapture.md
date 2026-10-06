## GPUToolsCapture

> `/System/Library/PrivateFrameworks/GPUToolsCapture.framework/GPUToolsCapture`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29225c` | `0x291f90` | **`-0x2cc`** |
| `__DATA.__objc_const` | `0x1b1e0` | `0x1b4a8` | **`+0x2c8`** |
| `__TEXT.__objc_methlist` | `0x13454` | `0x1358c` | **`+0x138`** |
| `__TEXT.__objc_methname` | `0x1b7c2` | `0x1b8ac` | **`+0xea`** |
| `__TEXT.__objc_stubs` | `0x18320` | `0x183e0` | **`+0xc0`** |
| `__DATA.__data` | `0x34d0` | `0x3530` | **`+0x60`** |
| `__DATA.__objc_data` | `0x2120` | `0x2170` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x15a3` | `0x15da` | **`+0x37`** |
| `__DATA.__objc_selrefs` | `0x6fe0` | `0x7010` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x4c00` | `0x4c20` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0xaf91` | `0xafae` | **`+0x1d`** |
| `__DATA.__objc_ivar` | `0xb90` | `0xba4` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x350` | `0x358` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x428` | `0x430` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x328` | `0x330` | **`+0x8`** |

### Same-size Content Changes

- `__AUTH_CONST.__interpose`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-2027.0.28.0.0
+2027.0.31.0.0

-  Functions: 9780
-  Symbols:   16172
-  CStrings:  9397
+  Functions: 9799
+  Symbols:   16216
+  CStrings:  9407
Symbols:
+ -[CaptureMTLTensor initWithBaseObject:captureBuffer:captureAuxiliaryPlanes:]
+ -[CaptureMTLTensorAuxiliaryPlane .cxx_destruct]
+ -[CaptureMTLTensorAuxiliaryPlane baseObject]
+ -[CaptureMTLTensorAuxiliaryPlane blockFactors]
+ -[CaptureMTLTensorAuxiliaryPlane bufferOffset]
+ -[CaptureMTLTensorAuxiliaryPlane buffer]
+ -[CaptureMTLTensorAuxiliaryPlane conformsToProtocol:]
+ -[CaptureMTLTensorAuxiliaryPlane dataType]
+ -[CaptureMTLTensorAuxiliaryPlane dealloc]
+ -[CaptureMTLTensorAuxiliaryPlane description]
+ -[CaptureMTLTensorAuxiliaryPlane forwardingTargetForSelector:]
+ -[CaptureMTLTensorAuxiliaryPlane initWithBaseObject:captureContext:captureMTLBuffer:]
+ -[CaptureMTLTensorAuxiliaryPlane originalObject]
+ -[CaptureMTLTensorAuxiliaryPlane planeType]
+ -[CaptureMTLTensorAuxiliaryPlane respondsToSelector:]
+ -[CaptureMTLTensorAuxiliaryPlane streamReference]
+ -[CaptureMTLTensorAuxiliaryPlane touch]
+ -[CaptureMTLTensorAuxiliaryPlane traceContext]
+ -[CaptureMTLTensorAuxiliaryPlane traceStream]
+ GCC_except_table3598
+ GCC_except_table4224
+ GCC_except_table4399
+ GCC_except_table4400
+ GCC_except_table4401
+ GCC_except_table4402
+ GCC_except_table4403
+ GCC_except_table4405
+ GCC_except_table4407
+ GCC_except_table4409
+ GCC_except_table4411
+ GCC_except_table4412
+ GCC_except_table4413
+ GCC_except_table4414
+ GCC_except_table4415
+ GCC_except_table4586
+ GCC_except_table4587
+ GCC_except_table4588
+ GCC_except_table4589
+ GCC_except_table4590
+ GCC_except_table4591
+ GCC_except_table4862
+ OBJC_IVAR_$_CaptureMTLTensor._captureAuxiliaryPlanes
+ OBJC_IVAR_$_CaptureMTLTensorAuxiliaryPlane._baseObject
+ OBJC_IVAR_$_CaptureMTLTensorAuxiliaryPlane._captureBuffer
+ OBJC_IVAR_$_CaptureMTLTensorAuxiliaryPlane._traceContext
+ OBJC_IVAR_$_CaptureMTLTensorAuxiliaryPlane._traceStream
+ _OBJC_CLASS_$_CaptureMTLTensorAuxiliaryPlane
+ _OBJC_METACLASS_$_CaptureMTLTensorAuxiliaryPlane
+ __OBJC_$_INSTANCE_METHODS_CaptureMTLTensorAuxiliaryPlane
+ __OBJC_$_INSTANCE_VARIABLES_CaptureMTLTensorAuxiliaryPlane
+ __OBJC_$_PROP_LIST_CaptureMTLTensorAuxiliaryPlane
+ __OBJC_$_PROP_LIST_MTLTensorAuxiliaryPlane
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLTensorAuxiliaryPlane
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLTensorAuxiliaryPlane
+ __OBJC_$_PROTOCOL_REFS_MTLTensorAuxiliaryPlane
+ __OBJC_CLASS_PROTOCOLS_$_CaptureMTLTensorAuxiliaryPlane
+ __OBJC_CLASS_RO_$_CaptureMTLTensorAuxiliaryPlane
+ __OBJC_LABEL_PROTOCOL_$_MTLTensorAuxiliaryPlane
+ __OBJC_METACLASS_RO_$_CaptureMTLTensorAuxiliaryPlane
+ __OBJC_PROTOCOL_$_MTLTensorAuxiliaryPlane
+ __ZNSt3__16vectorI16GTTelemetryLayerNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorI16GTTelemetryQueueNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorI17GTTelemetryDeviceNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqn220106v
+ _objc_msgSend$bufferForPlane:
+ _objc_msgSend$initWithBaseObject:captureBuffer:captureAuxiliaryPlanes:
+ _objc_msgSend$initWithBaseObject:captureContext:captureMTLBuffer:
+ _objc_msgSend$offsetForPlane:
+ _objc_msgSend$planeType
+ _objc_msgSend$setBuffer:offset:forPlane:
- GCC_except_table3579
- GCC_except_table4205
- GCC_except_table4380
- GCC_except_table4381
- GCC_except_table4382
- GCC_except_table4383
- GCC_except_table4384
- GCC_except_table4386
- GCC_except_table4388
- GCC_except_table4390
- GCC_except_table4392
- GCC_except_table4393
- GCC_except_table4394
- GCC_except_table4395
- GCC_except_table4396
- GCC_except_table4567
- GCC_except_table4568
- GCC_except_table4569
- GCC_except_table4570
- GCC_except_table4571
- GCC_except_table4572
- GCC_except_table4843
- __ZNSt3__16vectorI16GTTelemetryLayerNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorI16GTTelemetryQueueNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorI17GTTelemetryDeviceNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqn220100v
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/download/memwatch/GTChunkTable.c:134"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/download/memwatch/GTChunkTable.c:142"
+ "@\"<MTLTensorAuxiliaryPlane>\""
+ "CaptureMTLTensorAuxiliaryPlane"
+ "T@\"<MTLTensorAuxiliaryPlane>\",R"
+ "_captureAuxiliaryPlanes"
+ "bufferForPlane:"
+ "initWithBaseObject:captureBuffer:captureAuxiliaryPlanes:"
+ "initWithBaseObject:captureContext:captureMTLBuffer:"
+ "offsetForPlane:"
+ "planeType"
+ "setBuffer:offset:forPlane:"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/download/memwatch/GTChunkTable.c:133"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/download/memwatch/GTChunkTable.c:141"
```
