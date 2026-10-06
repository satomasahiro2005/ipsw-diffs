## PencilKit

> `/System/Library/Frameworks/PencilKit.framework/PencilKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x355d24` | `0x3575a4` | **`+0x1880`** |
| `__AUTH_CONST.__objc_const` | `0x48df0` | `0x49260` | **`+0x470`** |
| `__TEXT.__objc_methlist` | `0x26074` | `0x2620c` | **`+0x198`** |
| `__TEXT.__oslogstring` | `0xed2f` | `0xee56` | **`+0x127`** |
| `__DATA_CONST.__objc_selrefs` | `0x135b0` | `0x13688` | **`+0xd8`** |
| `__AUTH.__objc_data` | `0xa698` | `0xa738` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x85d0` | `0x8648` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x10770` | `0x107e8` | **`+0x78`** |
| `__TEXT.__const` | `0x8ef4` | `0x8f54` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x254b8` | `0x254f8` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x2cb8` | `0x2cec` | **`+0x34`** |
| `__TEXT.__swift5_capture` | `0xa9c` | `0xacc` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x1180` | `0x1190` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xda8` | `0xdb8` | **`+0x10`** |
| `__DATA_DIRTY.__objc_ivar` | `0x115c` | `0x116c` | **`+0x10`** |
| `__TEXT.__cstring` | `0xf962` | `0xf959` | **`-0x9`** |
| `__AUTH_CONST.__auth_got` | `0x1e28` | `0x1e30` | **`+0x8`** |

### Other Changes

```diff

-616.100.0.0.0
+621.0.0.0.0

-  Functions: 18461
-  Symbols:   33099
-  CStrings:  3595
+  Functions: 18501
+  Symbols:   33163
+  CStrings:  3600
Symbols:
+ +[PKInkingTool _convertColorFromLight:toAppearance:]
+ +[PKInkingTool _isPureBlackOrWhite:]
+ -[PKColorMatrixView colorAppearance]
+ -[PKColorMatrixView setColorAppearance:]
+ -[PKColorPicker colorUserInterfaceStyleOnlyConvertsBlackAndWhite]
+ -[PKColorPicker setColorUserInterfaceStyleOnlyConvertsBlackAndWhite:]
+ -[PKDeviceLockStateObserver dealloc]
+ -[PKDrawingPaletteView colorUserInterfaceStyleOnlyConvertsBlackAndWhite]
+ -[PKDrawingPaletteView setColorUserInterfaceStyleOnlyConvertsBlackAndWhite:]
+ -[PKInkAttributesPicker colorAppearance]
+ -[PKInkAttributesPicker setColorAppearance:]
+ -[PKPaletteBaseColorPickerController colorAppearance]
+ -[PKPaletteBaseColorPickerController setColorAppearance:]
+ -[PKPaletteColorPickerView colorAppearance]
+ -[PKPaletteColorPickerView setColorAppearance:]
+ -[PKPaletteColorSwatch setColorAppearance:]
+ -[PKPaletteHostView _updateContextMenuAvoidanceRect]
+ -[PKPaletteStandardColorPickerController colorAppearance]
+ -[PKPaletteSystemColorPickerController _shouldConvertColorPickerColorFromDarkToLight:]
+ -[PKPaletteSystemColorPickerController colorAppearance]
+ -[PKPaletteSystemColorPickerController setColorAppearance:]
+ -[PKPaletteToolPickerView _isAllToolsColorAppearanceEqualsTo:]
+ -[PKPaletteToolPickerView colorAppearance]
+ -[PKPaletteToolPickerView setColorAppearance:]
+ -[PKPaletteToolPreview colorAppearance]
+ -[PKPaletteToolPreview setColorAppearance:]
+ -[PKPaletteToolReorderController .cxx_destruct]
+ -[PKPaletteToolReorderController _allowedCenterRectForVisibleToolsRect:liftedSize:]
+ -[PKPaletteToolReorderController _beginDraggingToolView:atLocation:]
+ -[PKPaletteToolReorderController _containerLocationOfRecognizer:]
+ -[PKPaletteToolReorderController _draggedToolCenter]
+ -[PKPaletteToolReorderController _endDragAnimated:]
+ -[PKPaletteToolReorderController _endReordering]
+ -[PKPaletteToolReorderController _longPressGestureHandler:]
+ -[PKPaletteToolReorderController _reorderableToolViewAtLocationOfRecognizer:]
+ -[PKPaletteToolReorderController _updateDragAtLocation:]
+ -[PKPaletteToolReorderController beginReordering]
+ -[PKPaletteToolReorderController delegate]
+ -[PKPaletteToolReorderController endReorderingAnimated:]
+ -[PKPaletteToolReorderController gestureRecognizer:shouldRecognizeSimultaneouslyWithGestureRecognizer:]
+ -[PKPaletteToolReorderController gestureRecognizerShouldBegin:]
+ -[PKPaletteToolReorderController initWithDelegate:]
+ -[PKPaletteToolReorderController isActive]
+ -[PKPaletteToolReorderController isDragging]
+ -[PKPaletteToolReorderController longPressGestureRecognizer]
+ -[PKPaletteToolView colorAppearance]
+ -[PKPaletteToolView setColorAppearance:]
+ -[PKSqueezePaletteView setColorAppearance:]
+ -[PKSqueezePaletteViewExpandedColorsLayout colorAppearanceDidChange]
+ -[PKSqueezePaletteViewExpandedInkingToolLayout colorAppearanceDidChange]
+ -[PKSqueezePaletteViewExpandedToolsLayout colorAppearanceDidChange]
+ -[PKSqueezePaletteViewMiniPaletteLayout colorAppearanceDidChange]
+ -[PKToolPicker _colorUserInterfaceStyleOnlyConvertsBlackAndWhite]
+ -[PKToolPicker _setColorUserInterfaceStyleOnlyConvertsBlackAndWhite:]
+ -[_PKColorAlphaSliderIOS colorUserInterfaceStyleOnlyConvertsBlackAndWhite]
+ -[_PKColorAlphaSliderIOS setColorUserInterfaceStyleOnlyConvertsBlackAndWhite:]
+ -[_PKInkAttributesPickerView colorAppearance]
+ -[_PKInkAttributesPickerView setColorAppearance:]
+ OBJC_IVAR_$_PKPaletteSystemColorPickerController._onlyConvertsBlackAndWhiteInDark
+ _$s9PencilKit33PKSqueezeVisualIntelligenceButton33_37F59D7289F7B321309FA7D662ED2685LLC22updateInteractionStateyyF
+ _$s9PencilKit33PKSqueezeVisualIntelligenceButton33_37F59D7289F7B321309FA7D662ED2685LLC22updateInteractionStateyyFyyXEfU_
+ _$s9PencilKit33PKSqueezeVisualIntelligenceButton33_37F59D7289F7B321309FA7D662ED2685LLC22updateInteractionStateyyFyyXEfU_TA
+ _$sIg_Ieg_TR
+ _OBJC_CLASS_$_PKDeviceLockStateObserver
+ _OBJC_CLASS_$_PKPaletteToolReorderController
+ _OBJC_IVAR_$_PKColorMatrixView._colorAppearance
+ _OBJC_IVAR_$_PKDeviceLockStateObserver._notifyToken
+ _OBJC_IVAR_$_PKMetalRendererController._updateCycleRendererReadySemaphore
+ _OBJC_IVAR_$_PKPaletteBaseColorPickerController._colorAppearance
+ _OBJC_IVAR_$_PKPaletteColorPickerView._colorAppearance
+ _OBJC_IVAR_$_PKPaletteColorSwatch._colorAppearance
+ _OBJC_IVAR_$_PKPaletteToolPickerView._colorAppearance
+ _OBJC_IVAR_$_PKPaletteToolPreview._colorAppearance
+ _OBJC_IVAR_$_PKPaletteToolReorderController._active
+ _OBJC_IVAR_$_PKPaletteToolReorderController._delegate
+ _OBJC_IVAR_$_PKPaletteToolReorderController._dragAllowedCenterRect
+ _OBJC_IVAR_$_PKPaletteToolReorderController._dragDesiredCenter
+ _OBJC_IVAR_$_PKPaletteToolReorderController._dragLiftedSize
+ _OBJC_IVAR_$_PKPaletteToolReorderController._dragTouchOffset
+ _OBJC_IVAR_$_PKPaletteToolReorderController._draggedSnapshotView
+ _OBJC_IVAR_$_PKPaletteToolReorderController._draggedToolView
+ _OBJC_IVAR_$_PKPaletteToolReorderController._longPressGestureRecognizer
+ _OBJC_IVAR_$_PKPaletteToolView._colorAppearance
+ _OBJC_IVAR_$_PKSqueezePaletteColorSwatchButton._colorAppearance
+ _OBJC_IVAR_$_PKSqueezePaletteDrawingTool._colorAppearance
+ _OBJC_IVAR_$_PKSqueezePaletteMulticolorSwatchButton._colorAppearance
+ _OBJC_IVAR_$_PKSqueezePaletteView._colorAppearance
+ _OBJC_IVAR_$_PKToolPicker.__colorUserInterfaceStyleOnlyConvertsBlackAndWhite
+ _OBJC_METACLASS_$_PKDeviceLockStateObserver
+ _OBJC_METACLASS_$_PKPaletteToolReorderController
+ __OBJC_$_INSTANCE_METHODS_PKDeviceLockStateObserver
+ __OBJC_$_INSTANCE_METHODS_PKPaletteToolReorderController
+ __OBJC_$_INSTANCE_VARIABLES_PKDeviceLockStateObserver
+ __OBJC_$_INSTANCE_VARIABLES_PKPaletteToolReorderController
+ __OBJC_$_PROP_LIST_PKPaletteToolReorderController
+ __OBJC_CLASS_PROTOCOLS_$_PKPaletteToolReorderController
+ __OBJC_CLASS_RO_$_PKDeviceLockStateObserver
+ __OBJC_CLASS_RO_$_PKPaletteToolReorderController
+ __OBJC_METACLASS_RO_$_PKDeviceLockStateObserver
+ __OBJC_METACLASS_RO_$_PKPaletteToolReorderController
+ ___51-[PKPaletteToolReorderController _endDragAnimated:]_block_invoke
+ ___51-[PKPaletteToolReorderController _endDragAnimated:]_block_invoke_2
+ ___51-[PKPaletteToolReorderController _endDragAnimated:]_block_invoke_3
+ ___62-[PKMetalRendererController updateCyclePreCACommit:isDrawing:]_block_invoke_5
+ ___68-[PKPaletteToolReorderController _beginDraggingToolView:atLocation:]_block_invoke
+ _notify_cancel
- -[PKColorMatrixView _uiColorUserInterfaceStyle]
- -[PKColorMatrixView colorUserInterfaceStyle]
- -[PKColorMatrixView setColorUserInterfaceStyle:]
- -[PKInkAttributesPicker colorUserInterfaceStyle]
- -[PKInkAttributesPicker setColorUserInterfaceStyle:]
- -[PKPaletteBaseColorPickerController colorUserInterfaceStyle]
- -[PKPaletteBaseColorPickerController setColorUserInterfaceStyle:]
- -[PKPaletteColorPickerView colorUserInterfaceStyle]
- -[PKPaletteColorPickerView setColorUserInterfaceStyle:]
- -[PKPaletteColorSwatch setColorUserInterfaceStyle:]
- -[PKPaletteInkingToolView _uiColorUserInterfaceStyle]
- -[PKPaletteStandardColorPickerController colorUserInterfaceStyle]
- -[PKPaletteSystemColorPickerController colorUserInterfaceStyle]
- -[PKPaletteSystemColorPickerController setColorUserInterfaceStyle:]
- -[PKPaletteToolPickerView _isAllToolsColorUserInterfaceStyleEqualsTo:]
- -[PKPaletteToolPickerView colorUserInterfaceStyle]
- -[PKPaletteToolPickerView setColorUserInterfaceStyle:]
- -[PKPaletteToolPreview colorUserInterfaceStyle]
- -[PKPaletteToolPreview setColorUserInterfaceStyle:]
- -[PKPaletteToolView colorUserInterfaceStyle]
- -[PKPaletteToolView setColorUserInterfaceStyle:]
- -[PKSqueezePaletteView setColorUserInterfaceStyle:]
- -[PKSqueezePaletteViewExpandedColorsLayout colorUserInterfaceStyleDidChange]
- -[PKSqueezePaletteViewExpandedInkingToolLayout colorUserInterfaceStyleDidChange]
- -[PKSqueezePaletteViewExpandedToolsLayout colorUserInterfaceStyleDidChange]
- -[PKSqueezePaletteViewMiniPaletteLayout colorUserInterfaceStyleDidChange]
- -[_PKInkAttributesPickerView colorUserInterfaceStyle]
- -[_PKInkAttributesPickerView setColorUserInterfaceStyle:]
- _$s9PencilKit33PKSqueezeVisualIntelligenceButton33_37F59D7289F7B321309FA7D662ED2685LLC13isHighlightedSbvs
- _$s9PencilKit33PKSqueezeVisualIntelligenceButton33_37F59D7289F7B321309FA7D662ED2685LLC22updateInteractionStateyyFyycfU_
- _$s9PencilKit33PKSqueezeVisualIntelligenceButton33_37F59D7289F7B321309FA7D662ED2685LLC22updateInteractionStateyyFyycfU_TA
- _OBJC_IVAR_$_PKColorMatrixView._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKPaletteBaseColorPickerController._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKPaletteColorPickerView._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKPaletteColorSwatch._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKPaletteToolPickerView._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKPaletteToolPreview._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKPaletteToolView._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKSqueezePaletteColorSwatchButton._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKSqueezePaletteDrawingTool._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKSqueezePaletteMulticolorSwatchButton._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKSqueezePaletteView._colorUserInterfaceStyle
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:293: libc++ Hardening assertion __k != __leftmost failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:603: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:615: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:633: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:638: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:669: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:682: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:692: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:697: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__utility/is_pointer_in_range.h:38: libc++ Hardening assertion std::__is_valid_range(__begin, __end) failed: [__begin, __end) is not a valid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1171: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:434: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:446: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:509: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/list:1500: libc++ Hardening assertion this != std::addressof(__c) failed: list::splice(iterator, list) called with this == &list\n"
+ "Couldn't snapshot the tool being dragged; falling back to a placeholder."
+ "Did begin dragging a tool."
+ "Did begin reordering tools."
+ "Did end reordering tools."
+ "Reordering refused by the delegate."
+ "Skip updating opacity label constraints, vertical offset: %{private}.2f, scaling factor: %{private}.2f"
+ "Update palette UI style: %{private}ld, color appearance: %{private}ld"
+ "\xf0!"
+ "\xf0\xf0\xf0\xf0\x81\x92"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:293: libc++ Hardening assertion __k != __leftmost failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:603: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:615: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:633: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:638: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:669: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:682: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:692: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:697: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__utility/is_pointer_in_range.h:38: libc++ Hardening assertion std::__is_valid_range(__begin, __end) failed: [__begin, __end) is not a valid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1171: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:434: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:446: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:509: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/list:1500: libc++ Hardening assertion this != std::addressof(__c) failed: list::splice(iterator, list) called with this == &list\n"
- "Graphing"
- "Notes"
- "Update palette UI style: %{private}ld, color UI style: %{private}ld"
- "\xf0\xf0\xf0\xf0q\x92"
```
