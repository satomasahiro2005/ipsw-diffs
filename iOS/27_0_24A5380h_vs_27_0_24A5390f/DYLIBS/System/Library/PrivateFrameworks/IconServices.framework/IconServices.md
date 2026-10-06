## IconServices

> `/System/Library/PrivateFrameworks/IconServices.framework/IconServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x670e4` | `0x66840` | **`-0x8a4`** |
| `__TEXT.__oslogstring` | `0x406a` | `0x3cb3` | **`-0x3b7`** |
| `__AUTH_CONST.__cfstring` | `0x48a0` | `0x49c0` | **`+0x120`** |
| `__TEXT.__cstring` | `0x44f1` | `0x45c3` | **`+0xd2`** |
| `__AUTH_CONST.__objc_intobj` | `0x570` | `0x528` | **`-0x48`** |
| `__TEXT.__gcc_except_tab` | `0x610` | `0x650` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x6964` | `0x6934` | **`-0x30`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x120` | `0x108` | **`-0x18`** |
| `__DATA_CONST.__const` | `0xa38` | `0xa50` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0xc8` | `0xb0` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x19c8` | `0x19d8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3180` | `0x3178` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x400` | `0x408` | **`+0x8`** |

### Other Changes

```diff

-785.0.100.0.0
+788.0.0.0.0

-  Functions: 2606
-  Symbols:   4963
-  CStrings:  1079
+  Functions: 2599
+  Symbols:   4960
+  CStrings:  1076
Symbols:
+ -[ICRFinalizedIcon(IconServicesAdditions) _IS_imageWithCompositingDescriptor:debugResourceVariant:]
+ -[ISICRCompositor _fallbackImageForSize:scale:debugResourceVariant:]
+ -[ISICRCompositor _finalizedIconForCompositingDescriptor:producedStack:]
+ -[ISICRCompositor assetDescription]
+ -[ISICRCompositor initWithIconStackBlock:assetDescription:]
+ -[ISIconStackAssetCatalogResource _assetDescription]
+ -[ISIconStackAssetCatalogResource icrCompositor]
+ -[ISIconStackAssetCatalogResource setIcrCompositor:]
+ -[ISIconStackCompositeResource icrCompositor]
+ -[ISIconStackCompositeResource setIcrCompositor:]
+ -[ISMultisizedAppAssetCatalogResource _assetDescription]
+ GCC_except_table54
+ _OBJC_IVAR_$_ISICRCompositor._assetDescription
+ _OBJC_IVAR_$_ISIconStackAssetCatalogResource._icrCompositor
+ _OBJC_IVAR_$_ISIconStackCompositeResource._icrCompositor
+ ___58-[ISIconStackCompositeResource initWithResource:platform:]_block_invoke
+ ___70-[ISIconStackAssetCatalogResource initWithCatalog:imageName:platform:]_block_invoke
+ ___99-[ICRFinalizedIcon(IconServicesAdditions) _IS_imageWithCompositingDescriptor:debugResourceVariant:]_block_invoke
+ __typeForSiriMode
- -[CUINamedIconLayerStack(IconServicesAdditions) _IS_imageWithCompositingDescriptor:]
- -[ICRFinalizedIcon(IconServicesAdditions) _IS_imageWithCompositingDescriptor:]
- -[ISICRCompositor _fallbackImageForSize:scale:]
- -[ISICRCompositor _finalizedIconForCompositingDescriptor:]
- -[ISICRCompositor compositingDescriptor]
- -[ISICRCompositor initWithIconStackBlock:]
- -[ISICRCompositor setCompositingDescriptor:]
- -[ISIconStackAssetCatalogResource _fallbackImageForSize:scale:]
- -[ISIconStackAssetCatalogResource _finalizedIconForSize:scale:]
- -[ISIconStackAssetCatalogResource _keyForSize:scale:]
- -[ISIconStackAssetCatalogResource finalizedIcons]
- -[ISIconStackCompositeResource _fallbackImageForSize:scale:]
- -[ISIconStackCompositeResource _finalizedIconForSize:scale:]
- -[ISIconStackCompositeResource _keyForSize:scale:]
- -[ISIconStackCompositeResource finalizedIcons]
- GCC_except_table53
- _OBJC_IVAR_$_ISICRCompositor._compositingDescriptor
- _OBJC_IVAR_$_ISIconStackAssetCatalogResource._finalizedIcons
- _OBJC_IVAR_$_ISIconStackCompositeResource._finalizedIcons
- _OUTLINED_FUNCTION_7
- _OUTLINED_FUNCTION_8
- ___78-[ICRFinalizedIcon(IconServicesAdditions) _IS_imageWithCompositingDescriptor:]_block_invoke
CStrings:
+ "20:59:25"
+ "CompositeStack"
+ "DynamicStack"
+ "Failed to generate flatten representation for icon stack %@ with descriptor: %@ for asset type: %@"
+ "GenericAppIcon_iOS_Debug_IR_Finalization_Failure"
+ "GenericAppIcon_iOS_Debug_IR_Render_Failure"
+ "GenericAppIcon_iOS_Debug_Transparent"
+ "IR_FinalizationFailed"
+ "IR_RenderFailed"
+ "IR_TransparentRender"
+ "MultisizeImageCompositeStack"
+ "NaturalStack"
+ "Siri availability reported desiredOrchestrationModeIfEnabled: %@ (%lu)"
- "%.1f-%.1f@%d"
- "12:43:35"
- "After interpretation, final Siri mode is %@ (%lu), creating icon from that"
- "Default case, requesting ISAliasedTypeIcon with type com.apple.application-icon.siri-gen1"
- "EnhancedGlass"
- "Failed to find icon stack for with named: %@ for size: (%f,%f) scale:(%lf)"
- "Failed to generate flatten representation for composite icon stack size: (%f,%f) scale:(%lf)"
- "Failed to generate flatten representation for icon stack %@ with descriptor: %@"
- "Failed to generate flatten representation for icon stack with named: %@ for size: (%f,%f) scale:(%lf)"
- "Failed to generate flatten representation for multisized image with named: %@ for size: (%f,%f) scale:(%lf)"
- "Failed to generate icon stack for composite resource for size: (%f,%f) scale:(%lf)"
- "SOSiriOrchestrationModeLinwood, requesting ISAliasedTypeIcon with type com.apple.application-icon.siri-gen2"
- "SOSiriOrchestrationModeSiriClassic, requesting ISAliasedTypeIcon with type com.apple.application-icon.siri-gen1"
- "SOSiriOrchestrationModeSystemAssistantExperience, requesting ISAliasedTypeIcon with type com.apple.application-icon.siri-intelligence"
- "Siri availability reported desiredOrchestrationMode %@ (%lu)"
- "SolariumCornerRadius"
```
