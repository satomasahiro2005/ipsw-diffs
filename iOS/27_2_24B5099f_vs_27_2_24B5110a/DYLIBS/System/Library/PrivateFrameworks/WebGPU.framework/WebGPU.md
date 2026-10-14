## WebGPU

> `/System/Library/PrivateFrameworks/WebGPU.framework/WebGPU`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x658` | `0xc50` | **`+0x5f8`** |
| `__TEXT.__text` | `0x24573c` | `0x245bb4` | **`+0x478`** |
| `__TEXT.__objc_methlist` | `0x200` | `0x614` | **`+0x414`** |
| `__DATA.__data` | `0x150` | `0x330` | **`+0x1e0`** |
| `__DATA_CONST.__objc_selrefs` | `0xb08` | `0xcb0` | **`+0x1a8`** |
| `__TEXT.__gcc_except_tab` | `0xa9b8` | `0xaa4c` | **`+0x94`** |
| `__DATA_CONST.__objc_protolist` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__cstring` | `0x3e44c` | `0x3e46c` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4420` | `0x4430` | **`+0x10`** |

### Other Changes

```diff

-625.2.7.1.0
+625.2.8.10.4

-  Functions: 3649
-  Symbols:   4108
+  Functions: 3651
+  Symbols:   4140
Symbols:
+ GCC_except_table115
+ GCC_except_table127
+ GCC_except_table98
+ __OBJC_$_PROP_LIST_MTLAllocation
+ __OBJC_$_PROP_LIST_MTLBuffer
+ __OBJC_$_PROP_LIST_MTLResource
+ __OBJC_$_PROP_LIST_MTLTexture
+ __OBJC_$_PROP_LIST_NSObject
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLAllocation
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLBuffer
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLResource
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLTexture
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSObject
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSObject
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLAllocation
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLBuffer
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLResource
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLTexture
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSObject
+ __OBJC_$_PROTOCOL_REFS_MTLAllocation
+ __OBJC_$_PROTOCOL_REFS_MTLBuffer
+ __OBJC_$_PROTOCOL_REFS_MTLResource
+ __OBJC_$_PROTOCOL_REFS_MTLTexture
+ __OBJC_LABEL_PROTOCOL_$_MTLAllocation
+ __OBJC_LABEL_PROTOCOL_$_MTLBuffer
+ __OBJC_LABEL_PROTOCOL_$_MTLResource
+ __OBJC_LABEL_PROTOCOL_$_MTLTexture
+ __OBJC_LABEL_PROTOCOL_$_NSObject
+ __OBJC_PROTOCOL_$_MTLAllocation
+ __OBJC_PROTOCOL_$_MTLBuffer
+ __OBJC_PROTOCOL_$_MTLResource
+ __OBJC_PROTOCOL_$_MTLTexture
+ __OBJC_PROTOCOL_$_NSObject
+ __OBJC_PROTOCOL_REFERENCE_$_MTLBuffer
+ __OBJC_PROTOCOL_REFERENCE_$_MTLTexture
+ __ZN3WTF6VectorIN6WebGPU5Queue23ProvisionalTextureClearELm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEED1Ev
+ __ZN6WebGPU14CommandEncoder19addResidentResourceEPU22objcproto11MTLResource11objc_object
+ __ZN6WebGPU14CommandEncoder20clearTextureIfNeededERK20WGPUImageCopyTexturemRKNS_6DeviceEPU32objcproto21MTLBlitCommandEncoder11objc_objectPKS0_
+ __ZN6WebGPU14CommandEncoder20clearTextureIfNeededERNS_7TextureEmmRKNS_6DeviceEPU32objcproto21MTLBlitCommandEncoder11objc_objectPKS0_
- GCC_except_table101
- GCC_except_table126
- GCC_except_table130
- GCC_except_table134
- GCC_except_table46
- __ZN6WebGPU14CommandEncoder20clearTextureIfNeededERK20WGPUImageCopyTexturemRKNS_6DeviceEPU32objcproto21MTLBlitCommandEncoder11objc_object
- __ZN6WebGPU14CommandEncoder20clearTextureIfNeededERNS_7TextureEmmRKNS_6DeviceEPU32objcproto21MTLBlitCommandEncoder11objc_object
CStrings:
+ "21.0.0 (clang-2100.3.34.1) [+internal-os]"
+ "static void WebGPU::CommandEncoder::clearTextureIfNeeded(Texture &, NSUInteger, NSUInteger, const Device &, __strong id<MTLBlitCommandEncoder>, const CommandEncoder * _Nullable)"
- "21.0.0 (clang-2100.4.1.1) [+internal-os]"
- "static void WebGPU::CommandEncoder::clearTextureIfNeeded(Texture &, NSUInteger, NSUInteger, const Device &, __strong id<MTLBlitCommandEncoder>)"
```
