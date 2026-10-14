## assistivetouchd

> `/System/Library/CoreServices/AssistiveTouch.app/assistivetouchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x168408` | `0x169510` | **`+0x1108`** |
| `__TEXT.__objc_methname` | `0x38800` | `0x38a70` | **`+0x270`** |
| `__TEXT.__oslogstring` | `0x6fac` | `0x71c3` | **`+0x217`** |
| `__TEXT.__objc_stubs` | `0x2c220` | `0x2c400` | **`+0x1e0`** |
| `__TEXT.__objc_methlist` | `0x158f4` | `0x159bc` | **`+0xc8`** |
| `__DATA_CONST.__const` | `0x6f40` | `0x6ff8` | **`+0xb8`** |
| `__DATA.__objc_const` | `0x1c848` | `0x1c8c0` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0xc5c8` | `0xc640` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x2a3c` | `0x2a90` | **`+0x54`** |
| `__TEXT.__objc_methtype` | `0x7814` | `0x785d` | **`+0x49`** |
| `__TEXT.__unwind_info` | `0x6248` | `0x6290` | **`+0x48`** |
| `__DATA_CONST.__cfstring` | `0x9fc0` | `0xa000` | **`+0x40`** |
| `__TEXT.__cstring` | `0xe22e` | `0xe25d` | **`+0x2f`** |
| `__DATA.__data` | `0x4330` | `0x4340` | **`+0x10`** |
| `__TEXT.__const` | `0x4b40` | `0x4b50` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x12f0` | `0x12f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1510.4.3.0.0
+1510.4.4.0.0

-  Functions: 9411
+  Functions: 9430

-  CStrings:  12058
+  CStrings:  12091
Symbols:
+ _$s7SwiftUI9EmptyViewVAA0D0AAMc
- _$s7SwiftUI9EmptyViewVAA0D0AAWP
CStrings:
+ "@\"AXElement\"28@0:8i16@\"AXElement\"20"
+ "B24@0:8^{CGPoint=dd}16"
+ "B24@0:8i16B20"
+ "B24@?0@\"AXElement\"8Q16"
+ "B8@?0"
+ "Element %{public}@ cannot scroll %i; app scroll view %{public}@: %{public}@"
+ "Ignoring scanning mode change while the scanner is unloaded."
+ "Neither element %{public}@ nor its fallback scroll ancestors could perform scroll action %i."
+ "No scanned element has a scroll ancestor for action %i. Falling back to %lu app scroll view(s)."
+ "Scroll action %i on element %{public}@: %{public}@"
+ "Snap to Item: performing custom gesture at snapped element point (%.1f, %.1f)"
+ "T@\"NSArray\",&,N,V_cachedAppScrollViews"
+ "T{CGPoint=dd},N,V_snappedBubbleModeElementGesturePoint"
+ "Using app scroll view %{public}@ as the fallback scroll ancestor for action %i."
+ "_appScrollAncestorForScrollAction:nearestToElement:"
+ "_appScrollViews"
+ "_bubbleModeSnappedElementGesturePoint:"
+ "_cachedAppScrollViews"
+ "_enumerateScannedElementsUsingBlock:"
+ "_isBubbleModeFocusedInMenuOnDisplay:"
+ "_snappedBubbleModeElementGesturePoint"
+ "_updateFallbackScrollAncestorsForElement:allowingAppScrollViews:"
+ "appScrollViewForAction:nearestToElement:"
+ "appScrollViewsForAction:"
+ "cachedAppScrollViews"
+ "isAssistiveTouchMenuElementWithPid:menuVisible:"
+ "performed"
+ "rectWithAXAttribute:"
+ "refused"
+ "scannedElementsReachAnyScrollView"
+ "setCachedAppScrollViews:"
+ "setSnappedBubbleModeElementGesturePoint:"
+ "snappedBubbleModeElementGesturePoint"
```
