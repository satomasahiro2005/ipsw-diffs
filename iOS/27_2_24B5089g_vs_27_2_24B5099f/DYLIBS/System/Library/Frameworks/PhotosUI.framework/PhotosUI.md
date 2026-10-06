## PhotosUI

> `/System/Library/Frameworks/PhotosUI.framework/PhotosUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45040` | `0x46b90` | **`+0x1b50`** |
| `__AUTH_CONST.__objc_const` | `0x7008` | `0x7368` | **`+0x360`** |
| `__TEXT.__oslogstring` | `0x120c` | `0x1449` | **`+0x23d`** |
| `__AUTH.__objc_data` | `0x1fc8` | `0x2110` | **`+0x148`** |
| `__TEXT.__objc_methlist` | `0x3ed4` | `0x401c` | **`+0x148`** |
| `__DATA.__data` | `0x1c48` | `0x1d68` | **`+0x120`** |
| `__AUTH_CONST.__auth_got` | `0xac0` | `0xb98` | **`+0xd8`** |
| `__AUTH.__data` | `0x738` | `0x808` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x2298` | `0x2358` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2198` | `0x2248` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x2240` | `0x22e0` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0xd8c` | `0xe04` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0x528` | `0x5a0` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0xc58` | `0xcc0` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x1a08` | `0x1a58` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0xcd0` | `0xd1a` | **`+0x4a`** |
| `__TEXT.__const` | `0x3088` | `0x30c8` | **`+0x40`** |
| `__TEXT.__cstring` | `0x4d24` | `0x4d63` | **`+0x3f`** |
| `__TEXT.__eh_frame` | `0x884` | `0x8b4` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x31c` | `0x33c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x668` | `0x688` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xbc1` | `0xbe1` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x238` | `0x250` | **`+0x18`** |
| `__DATA.__bss` | `0x3220` | `0x3230` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x228` | `0x238` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x100` | `0x108` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xf8` | `0x100` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x120` | `0x128` | **`+0x8`** |

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

+  - /System/Library/Frameworks/IOSurface.framework/IOSurface

-  Functions: 3045
-  Symbols:   2955
-  CStrings:  560
+  Functions: 3096
+  Symbols:   3042
+  CStrings:  574
Symbols:
+ +[PVSAdjustedImageSurface supportsBSXPCSecureCoding]
+ -[PVSAdjustedImageSurface .cxx_destruct]
+ -[PVSAdjustedImageSurface allocationSize]
+ -[PVSAdjustedImageSurface createImage]
+ -[PVSAdjustedImageSurface dealloc]
+ -[PVSAdjustedImageSurface encodeWithBSXPCCoder:]
+ -[PVSAdjustedImageSurface height]
+ -[PVSAdjustedImageSurface holdSurfaceInUse]
+ -[PVSAdjustedImageSurface initWithBSXPCCoder:]
+ -[PVSAdjustedImageSurface initWithImage:]
+ -[PVSAdjustedImageSurface initWithSurface:width:height:bitsPerComponent:bitsPerPixel:bitmapInfo:colorSpaceData:]
+ -[PVSAdjustedImageSurface width]
+ GCC_except_table368
+ GCC_except_table399
+ GCC_except_table404
+ GCC_except_table408
+ GCC_except_table412
+ GCC_except_table430
+ GCC_except_table500
+ GCC_except_table523
+ GCC_except_table880
+ GCC_except_table890
+ GCC_except_table893
+ GCC_except_table895
+ GCC_except_table974
+ _CGColorSpaceCopyPropertyList
+ _CGColorSpaceCreateWithPropertyList
+ _CGColorSpaceRelease
+ _CGContextRelease
+ _CGIOSurfaceContextCreate
+ _CGIOSurfaceContextCreateImageReference
+ _CGImageGetBitmapInfo
+ _CGImageGetBitsPerComponent
+ _CGImageGetBitsPerPixel
+ _CGImageGetColorSpace
+ _CGImageGetHeight
+ _CGImageGetImageProvider
+ _CGImageGetProperty
+ _CGImageGetWidth
+ _CGImageProviderCopyIOSurface
+ _IOSurfaceCreateXPCObject
+ _IOSurfaceGetAllocSize
+ _IOSurfaceGetBytesPerElement
+ _IOSurfaceGetHeight
+ _IOSurfaceGetPlaneCount
+ _IOSurfaceGetWidth
+ _IOSurfaceLookupFromXPCObject
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _OBJC_CLASS_$_PVSAdjustedImageSurface
+ _OBJC_IVAR_$_PVSAdjustedImageSurface._bitmapInfo
+ _OBJC_IVAR_$_PVSAdjustedImageSurface._bitsPerComponent
+ _OBJC_IVAR_$_PVSAdjustedImageSurface._bitsPerPixel
+ _OBJC_IVAR_$_PVSAdjustedImageSurface._colorSpaceData
+ _OBJC_IVAR_$_PVSAdjustedImageSurface._height
+ _OBJC_IVAR_$_PVSAdjustedImageSurface._holdsUseCount
+ _OBJC_IVAR_$_PVSAdjustedImageSurface._surface
+ _OBJC_IVAR_$_PVSAdjustedImageSurface._width
+ _OBJC_METACLASS_$_PVSAdjustedImageSurface
+ _OBJC_METACLASS_$__TtC8PhotosUIP33_86A8A7AFB2E6C51099EC2C34AF71B0F629SceneHostingDelegateForwarder
+ _PVSAdjustedImageSurfaceLog
+ _PVSAdjustedImageSurfaceLog.log
+ _PVSAdjustedImageSurfaceLog.onceToken
+ __DATA__TtC8PhotosUIP33_86A8A7AFB2E6C51099EC2C34AF71B0F629SceneHostingDelegateForwarder
+ __INSTANCE_METHODS__TtC8PhotosUIP33_86A8A7AFB2E6C51099EC2C34AF71B0F629SceneHostingDelegateForwarder
+ __IVARS__TtC8PhotosUIP33_86A8A7AFB2E6C51099EC2C34AF71B0F629SceneHostingDelegateForwarder
+ __METACLASS_DATA__TtC8PhotosUIP33_86A8A7AFB2E6C51099EC2C34AF71B0F629SceneHostingDelegateForwarder
+ __OBJC_$_CLASS_METHODS_PVSAdjustedImageSurface
+ __OBJC_$_INSTANCE_METHODS_PVSAdjustedImageSurface
+ __OBJC_$_INSTANCE_VARIABLES_PVSAdjustedImageSurface
+ __OBJC_$_PROP_LIST_PVSAdjustedImageSurface
+ __OBJC_$_PROTOCOL_CLASS_METHODS_BSXPCSecureCoding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BSXPCSecureCoding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT__UISceneHostingControllerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BSXPCSecureCoding
+ __OBJC_$_PROTOCOL_METHOD_TYPES__UISceneHostingControllerDelegate
+ __OBJC_$_PROTOCOL_REFS_BSXPCSecureCoding
+ __OBJC_$_PROTOCOL_REFS__UISceneHostingControllerDelegate
+ __OBJC_CLASS_PROTOCOLS_$_PVSAdjustedImageSurface
+ __OBJC_CLASS_RO_$_PVSAdjustedImageSurface
+ __OBJC_LABEL_PROTOCOL_$_BSXPCSecureCoding
+ __OBJC_LABEL_PROTOCOL_$__UISceneHostingControllerDelegate
+ __OBJC_METACLASS_RO_$_PVSAdjustedImageSurface
+ __OBJC_PROTOCOL_$_BSXPCSecureCoding
+ __OBJC_PROTOCOL_$__UISceneHostingControllerDelegate
+ __PROTOCOLS__TtC8PhotosUIP33_86A8A7AFB2E6C51099EC2C34AF71B0F629SceneHostingDelegateForwarder
+ ___PVSAdjustedImageSurfaceLog_block_invoke
+ ___swift_closure_destructor.9Tm
+ __os_log_debug_impl
+ __xpc_type_mach_send
+ _kCGImagePropertyIOSurface
+ _os_log_create
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_storeEnumTagSinglePayloadGeneric
+ _symbolic Ieg_Sg
+ _symbolic _____ 8PhotosUI22PVSAlbumConcreteClientC8AckState33_B69548FE8D3ECA73A31C3AFCE4B16FC0LLV
+ _symbolic _____ 8PhotosUI29SceneHostingDelegateForwarder33_86A8A7AFB2E6C51099EC2C34AF71B0F6LLC
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic _____Sg 8PhotosUI17PVSConcreteClientC
+ _symbolic _____SgXw 8PhotosUI17PVSConcreteClientC
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 8PhotosUI22PVSAlbumConcreteClientC8AckState33_B69548FE8D3ECA73A31C3AFCE4B16FC0LLV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 8PhotosUI22PVSAlbumConcreteClientC8AckState33_B69548FE8D3ECA73A31C3AFCE4B16FC0LLV So16os_unfair_lock_sV
- GCC_except_table354
- GCC_except_table385
- GCC_except_table390
- GCC_except_table394
- GCC_except_table398
- GCC_except_table416
- GCC_except_table486
- GCC_except_table509
- GCC_except_table866
- GCC_except_table876
- GCC_except_table879
- GCC_except_table881
- GCC_except_table960
- _symbolic Sd
CStrings:
+ "Adjusted image has no IOSurface behind it."
+ "Adjusted image has no color space that can be flattened for transport."
+ "Adjusted image is %ld bits per pixel but its surface is %zu bytes per element."
+ "Adjusted image is %ldx%ld but its surface is %zux%zu."
+ "Adjusted image reports %ld bits per component and %ld per pixel."
+ "Adjusted image's color space didn't survive transport."
+ "Adjusted image's surface has %zu planes."
+ "CoreGraphics won't read a %ldx%ld surface as %ld bits per pixel with bitmap info %u."
+ "Ignoring completion for already-dismissed album view content: %s."
+ "bitmapInfo"
+ "bitsPerComponent"
+ "bitsPerPixel"
+ "colorSpace"
+ "surface"
```
