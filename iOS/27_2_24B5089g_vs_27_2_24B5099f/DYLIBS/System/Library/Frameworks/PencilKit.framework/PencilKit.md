## PencilKit

> `/System/Library/Frameworks/PencilKit.framework/PencilKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3575a4` | `0x356fd0` | **`-0x5d4`** |
| `__AUTH_CONST.__objc_const` | `0x49260` | `0x490c0` | **`-0x1a0`** |
| `__TEXT.__gcc_except_tab` | `0x254f8` | `0x2559c` | **`+0xa4`** |
| `__TEXT.__objc_methlist` | `0x2620c` | `0x26184` | **`-0x88`** |
| `__TEXT.__oslogstring` | `0xee56` | `0xedff` | **`-0x57`** |
| `__AUTH.__objc_data` | `0xa6d0` | `0xa680` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0xe780` | `0xe7c0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x13688` | `0x13648` | **`-0x40`** |
| `__DATA_CONST.__objc_arraydata` | `0x920` | `0x958` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x107e8` | `0x107b0` | **`-0x38`** |
| `__AUTH_CONST.__objc_dictobj` | `0x460` | `0x488` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x7010` | `0x6fe8` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x8648` | `0x8668` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x7c0` | `0x7e0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x2cec` | `0x2cd0` | **`-0x1c`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x6c0` | `0x6d8` | **`+0x18`** |
| `__TEXT.__cstring` | `0xf959` | `0xf96b` | **`+0x12`** |
| `__TEXT.__const` | `0x8f54` | `0x8f64` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1190` | `0x1188` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xdb8` | `0xdb0` | **`-0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x116c` | `0x1170` | **`+0x4`** |

### Other Changes

```diff

-621.0.0.0.0
+622.1.1.0.0

-  Functions: 18501
-  Symbols:   33163
-  CStrings:  3600
+  Functions: 18484
+  Symbols:   33130
+  CStrings:  3599
Symbols:
+ +[PKTextInputLanguageSelectionController _scriptQualifiedLocaleIdentifiers]
+ +[PKTextInputLanguageSelectionController _transliterationInputModeRules]
+ -[PKDrawingPaletteView _contentViewForTesting]
+ -[PKDrawingPaletteView _toolPickerViewForTesting]
+ -[PKMetalRenderer newComputeVertexBufferWithLength:outOffset:commandBuffer:]
+ -[PKMetalResourceHandlerBuffer deallocateReusableBuffers]
+ -[PKMetalResourceHandlerBuffer initWithSize:options:device:purgeable:initialReusableBufferCount:]
+ -[PKPaletteHostView _usesCompactPaletteWidth]
+ -[PKPaletteHostView compactPaletteAvailableWidth]
+ -[PKPaletteToolPickerAndColorPickerView compactPaletteWidth]
+ -[PKPaletteToolPickerAndColorPickerView setCompactPaletteWidth:]
+ -[PKPaletteToolPickerView _ensureFirstToolVisibleForRTLIfNeeded]
+ -[PKPaletteView compactPaletteWidth]
+ -[PKTextInputLanguageSelectionController ensureKeyboardLanguageConsistencyIfNeededWhileWriting:]
+ _OBJC_IVAR_$_PKMetalRenderer._computeVertexBuffer
+ _OBJC_IVAR_$_PKMetalResourceHandlerBuffer._lock
+ _OBJC_IVAR_$_PKPaletteToolPickerAndColorPickerView._compactPaletteWidth
+ ___72+[PKTextInputLanguageSelectionController _transliterationInputModeRules]_block_invoke
+ ___75+[PKTextInputLanguageSelectionController _scriptQualifiedLocaleIdentifiers]_block_invoke
+ ___76-[PKMetalRenderer newComputeVertexBufferWithLength:outOffset:commandBuffer:]_block_invoke
+ ___block_descriptor_48_ea8_32s40s_e28_v16?0"<MTLCommandBuffer>"8ls32l8s40l8
- -[PKMetalResourceHandler deallocateReusableBuffers]
- -[PKMetalResourceHandler newGPUBufferWithLength:outOffset:commandBuffer:]
- -[PKPaletteToolPickerAndColorPickerView didMoveToWindow]
- -[PKPaletteToolPickerAndColorPickerView safeAreaInsetsDidChange]
- -[PKPaletteToolPickerView _ensureCorrectToolSelectionForRTLIfNeeded]
- -[PKPaletteToolReorderController .cxx_destruct]
- -[PKPaletteToolReorderController _allowedCenterRectForVisibleToolsRect:liftedSize:]
- -[PKPaletteToolReorderController _beginDraggingToolView:atLocation:]
- -[PKPaletteToolReorderController _containerLocationOfRecognizer:]
- -[PKPaletteToolReorderController _draggedToolCenter]
- -[PKPaletteToolReorderController _endDragAnimated:]
- -[PKPaletteToolReorderController _endReordering]
- -[PKPaletteToolReorderController _longPressGestureHandler:]
- -[PKPaletteToolReorderController _reorderableToolViewAtLocationOfRecognizer:]
- -[PKPaletteToolReorderController _updateDragAtLocation:]
- -[PKPaletteToolReorderController beginReordering]
- -[PKPaletteToolReorderController delegate]
- -[PKPaletteToolReorderController endReorderingAnimated:]
- -[PKPaletteToolReorderController gestureRecognizer:shouldRecognizeSimultaneouslyWithGestureRecognizer:]
- -[PKPaletteToolReorderController gestureRecognizerShouldBegin:]
- -[PKPaletteToolReorderController initWithDelegate:]
- -[PKPaletteToolReorderController isActive]
- -[PKPaletteToolReorderController isDragging]
- -[PKPaletteToolReorderController longPressGestureRecognizer]
- -[PKTextInputLanguageSelectionController ensureKeyboardLanguageConsistencyIfNeeded]
- _OBJC_CLASS_$_PKPaletteToolReorderController
- _OBJC_IVAR_$_PKMetalResourceHandler._gpuResourceBuffer
- _OBJC_IVAR_$_PKPaletteToolReorderController._active
- _OBJC_IVAR_$_PKPaletteToolReorderController._delegate
- _OBJC_IVAR_$_PKPaletteToolReorderController._dragAllowedCenterRect
- _OBJC_IVAR_$_PKPaletteToolReorderController._dragDesiredCenter
- _OBJC_IVAR_$_PKPaletteToolReorderController._dragLiftedSize
- _OBJC_IVAR_$_PKPaletteToolReorderController._dragTouchOffset
- _OBJC_IVAR_$_PKPaletteToolReorderController._draggedSnapshotView
- _OBJC_IVAR_$_PKPaletteToolReorderController._draggedToolView
- _OBJC_IVAR_$_PKPaletteToolReorderController._longPressGestureRecognizer
- _OBJC_METACLASS_$_PKPaletteToolReorderController
- __OBJC_$_INSTANCE_METHODS_PKPaletteToolReorderController
- __OBJC_$_INSTANCE_VARIABLES_PKPaletteToolReorderController
- __OBJC_$_PROP_LIST_PKPaletteToolReorderController
- __OBJC_CLASS_PROTOCOLS_$_PKPaletteToolReorderController
- __OBJC_CLASS_RO_$_PKPaletteToolReorderController
- __OBJC_METACLASS_RO_$_PKPaletteToolReorderController
- ___51-[PKMetalResourceHandler deallocateReusableBuffers]_block_invoke
- ___51-[PKPaletteToolReorderController _endDragAnimated:]_block_invoke
- ___51-[PKPaletteToolReorderController _endDragAnimated:]_block_invoke_2
- ___51-[PKPaletteToolReorderController _endDragAnimated:]_block_invoke_3
- ___68-[PKPaletteToolPickerView _ensureCorrectToolSelectionForRTLIfNeeded]_block_invoke
- ___68-[PKPaletteToolReorderController _beginDraggingToolView:atLocation:]_block_invoke
- ___73-[PKMetalResourceHandler newGPUBufferWithLength:outOffset:commandBuffer:]_block_invoke
- ___73-[PKMetalResourceHandler newGPUBufferWithLength:outOffset:commandBuffer:]_block_invoke_2
- ___73-[PKMetalResourceHandler newGPUBufferWithLength:outOffset:commandBuffer:]_block_invoke_3
- ___block_descriptor_48_ea8_32s40w_e28_v16?0"<MTLCommandBuffer>"8lw40l8s32l8
- ___block_descriptor_72_ea8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
CStrings:
+ "Campo not supported on phone"
+ "LanguageController: Skipping keyboard language propagation while writing."
+ "mr-Translit"
+ "mr_Latn"
+ "\xf0a"
- "Couldn't snapshot the tool being dragged; falling back to a placeholder."
- "Did begin dragging a tool."
- "Did begin reordering tools."
- "Did end reordering tools."
- "Reordering refused by the delegate."
- "\xf0!"
```
