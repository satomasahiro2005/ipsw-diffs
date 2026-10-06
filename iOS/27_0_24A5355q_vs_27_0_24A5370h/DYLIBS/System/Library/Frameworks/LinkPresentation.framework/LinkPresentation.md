## LinkPresentation

> `/System/Library/Frameworks/LinkPresentation.framework/LinkPresentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10ba88` | `0x10bbd0` | **`+0x148`** |
| `__TEXT.__gcc_except_tab` | `0x234dc` | `0x23408` | **`-0xd4`** |
| `__TEXT.__const` | `0x22f4` | `0x2334` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0xdbe0` | `0xdc00` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1113c` | `0x11154` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x1630` | `0x1640` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x7b28` | `0x7b38` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x81a0` | `0x81b0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xe08` | `0xe10` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`
- `__TEXT.__ustring`

### Other Changes

```diff

-308.1.0.0.0
+310.0.0.0.0

-  Functions: 6852
+  Functions: 6854

-  CStrings:  2318
+  CStrings:  2319
Symbols:
+ -[LPFileMetadata(Transformers) sharedObjectOverridePresentationPropertiesTransformer:]
+ -[LPMetadataProvider _generateSpecializationIfPossibleForCompleteMetadata:MIMEType:completionHandler:]
+ -[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:MIMEType:completionHandler:]
+ -[LPThemeBuilder createShadowForApplicationBadge]
+ -[LPiCloudSharingMetadata(Transformer) _effectiveImageForTransformer:]
+ -[LPiCloudSharingMetadata(Transformer) _shouldUsePhotosSharedCollectionPresentationForTransformer:]
+ -[LPiCloudSharingMetadata(Transformer) sharedObjectOverridePresentationPropertiesTransformer:]
+ GCC_except_table128
+ GCC_except_table189
+ _UIFontTextStyleTitle2
+ ___102-[LPMetadataProvider _generateSpecializationIfPossibleForCompleteMetadata:MIMEType:completionHandler:]_block_invoke
+ ___102-[LPMetadataProvider _generateSpecializationIfPossibleForCompleteMetadata:MIMEType:completionHandler:]_block_invoke_2
+ ___95-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:MIMEType:completionHandler:]_block_invoke
+ ___95-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:MIMEType:completionHandler:]_block_invoke_10
+ ___95-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:MIMEType:completionHandler:]_block_invoke_11
+ ___95-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:MIMEType:completionHandler:]_block_invoke_2
+ ___95-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:MIMEType:completionHandler:]_block_invoke_3
+ ___95-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:MIMEType:completionHandler:]_block_invoke_4
+ ___95-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:MIMEType:completionHandler:]_block_invoke_5
+ ___95-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:MIMEType:completionHandler:]_block_invoke_6
+ ___95-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:MIMEType:completionHandler:]_block_invoke_7
+ ___95-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:MIMEType:completionHandler:]_block_invoke_8
+ ___95-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:MIMEType:completionHandler:]_block_invoke_9
- -[LPFileMetadata(Transformers) sharedObjectIconPropertiesForTransformer:]
- -[LPMetadataProvider _generateSpecializationIfPossibleForCompleteMetadata:completionHandler:]
- -[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:completionHandler:]
- -[LPiCloudSharingMetadata(Transformer) computeIconPropertiesWithURL:]
- -[LPiCloudSharingMetadata(Transformer) sharedObjectIconPropertiesForTransformer:]
- GCC_except_table129
- GCC_except_table164
- GCC_except_table181
- GCC_except_table187
- ___86-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:completionHandler:]_block_invoke
- ___86-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:completionHandler:]_block_invoke_10
- ___86-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:completionHandler:]_block_invoke_11
- ___86-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:completionHandler:]_block_invoke_2
- ___86-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:completionHandler:]_block_invoke_3
- ___86-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:completionHandler:]_block_invoke_4
- ___86-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:completionHandler:]_block_invoke_5
- ___86-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:completionHandler:]_block_invoke_6
- ___86-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:completionHandler:]_block_invoke_7
- ___86-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:completionHandler:]_block_invoke_8
- ___86-[LPMetadataProvider _internalPostProcessResolvedMetadataWithEvent:completionHandler:]_block_invoke_9
- ___93-[LPMetadataProvider _generateSpecializationIfPossibleForCompleteMetadata:completionHandler:]_block_invoke
- ___93-[LPMetadataProvider _generateSpecializationIfPossibleForCompleteMetadata:completionHandler:]_block_invoke_2
- _photosIconOuterMargin.visionSize
CStrings:
+ "Freeform-Folder"
+ "rectangle.stack.and.person"
- "rectangle.stack.badge.person.crop.fill"
```
