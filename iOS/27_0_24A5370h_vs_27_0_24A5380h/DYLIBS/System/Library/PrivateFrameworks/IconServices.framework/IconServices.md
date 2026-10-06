## IconServices

> `/System/Library/PrivateFrameworks/IconServices.framework/IconServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x676b0` | `0x670e4` | **`-0x5cc`** |
| `__AUTH_CONST.__objc_const` | `0x143a8` | `0x13f98` | **`-0x410`** |
| `__TEXT.__oslogstring` | `0x40fc` | `0x406a` | **`-0x92`** |
| `__TEXT.__cstring` | `0x454f` | `0x44f1` | **`-0x5e`** |
| `__DATA.__data` | `0x1d4c` | `0x1cf0` | **`-0x5c`** |
| `__DATA_CONST.__got` | `0x650` | `0x6a8` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x69bc` | `0x6964` | **`-0x58`** |
| `__AUTH.__objc_data` | `0x820` | `0x870` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x2bc0` | `0x2b70` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0x48e0` | `0x48a0` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x31b0` | `0x3180` | **`-0x30`** |
| `__DATA_CONST.__const` | `0xa10` | `0xa38` | **`+0x28`** |
| `__DATA.__bss` | `0x688` | `0x698` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1d0` | `0x1c0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x19d8` | `0x19c8` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x118` | `0x110` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x30` | `0x28` | **`-0x8`** |

### Other Changes

```diff

-779.0.0.0.0
+785.0.100.0.0

-  Functions: 2609
-  Symbols:   4971
-  CStrings:  1085
+  Functions: 2606
+  Symbols:   4963
+  CStrings:  1079
Symbols:
+ -[ISGenericRecipe isDebugModeEnabled]
+ -[ISGenericRecipe setDebugModeEnabled:]
+ _ISIsTransparent
+ _OBJC_IVAR_$_ISGenericRecipe._debugModeEnabled
+ ___78-[ICRFinalizedIcon(IconServicesAdditions) _IS_imageWithCompositingDescriptor:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48s_e15_^{CGImage=}8?0ls32l8s40l8s48l8
- -[ISCompositingDescriptor cacheFinalizedIconOnGeneratedImage]
- -[ISCompositingDescriptor setCacheFinalizedIconOnGeneratedImage:]
- -[ISDefaults isCalistogaEnabled]
- -[ISDynamicIconStackResource layerDataForSize:scale:]
- -[ISICRCompositor layerDataForCompositingDescriptor:]
- -[ISIconStackAssetCatalogResource layerDataForSize:scale:]
- -[ISIconStackCompositeResource layerDataForSize:scale:]
- _OBJC_IVAR_$_ISCompositingDescriptor._cacheFinalizedIconOnGeneratedImage
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_ISLayerScalableCompositorResource
- __OBJC_$_PROTOCOL_METHOD_TYPES_ISLayerScalableCompositorResource
- __OBJC_$_PROTOCOL_REFS_ISLayerScalableCompositorResource
- __OBJC_LABEL_PROTOCOL_$_ISLayerScalableCompositorResource
- __OBJC_PROTOCOL_$_ISLayerScalableCompositorResource
- __OBJC_PROTOCOL_REFERENCE_$_ISLayerScalableCompositorResource
CStrings:
+ "12:43:35"
+ "Central pixel is still transparent even with retry."
+ "Flattened representation is seemingly a fully transparent image: %@"
+ "^{CGImage=}8@?0"
+ "debug layer"
+ "figure.skating"
- "%d"
- ".calistoga"
- "00:30:55"
- "Calistoga"
- "CalistogaIconServicesOnly"
- "Failed to serialize finalized composite icon for size: (%f,%f) scale:(%lf). Error:%@"
- "Failed to serialize finalized icon for icon stack %@ with descriptor: %@"
- "Failed to serialize finalized icon for named: %@ for size: (%f,%f) scale:(%lf). Error:%@"
- "Remapping %@ -> %@"
- "SwiftUI"
- "com.apple.application-icon.calendar.base"
- "com.apple.application-icon.clock.base"
```
