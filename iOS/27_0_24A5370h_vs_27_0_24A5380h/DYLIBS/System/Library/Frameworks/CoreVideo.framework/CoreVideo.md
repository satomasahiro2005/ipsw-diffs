## CoreVideo

> `/System/Library/Frameworks/CoreVideo.framework/CoreVideo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xba6c` | `0xc53c` | **`+0xad0`** |
| `__TEXT.__text` | `0x6e464` | `0x6eeb8` | **`+0xa54`** |
| `__TEXT.__unwind_info` | `0x1d18` | `0x1d70` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0xea0` | `0xeb0` | **`+0x10`** |

### Other Changes

```diff

-758.23.0.0.0
+758.25.0.0.0

-  Functions: 3621
-  Symbols:   8138
-  CStrings:  1026
+  Functions: 3631
+  Symbols:   8150
+  CStrings:  1061
Symbols:
+ _CFAllocatorGetTypeID
+ _CFSetApplyFunction
+ _CVArrayAppendSInt64Value
+ __ZL24allArrayElementsHaveTypePK9__CFArraym
+ __ZL28isCFNumberOrArrayOfCFNumbersPKv
+ __ZL29checkRequiredCompatibilityKeyPKvPv
+ __ZL30resolveKeyUsingLCMIntegerValuePK9__CFArrayP14__CFDictionaryPK10__CFString
+ __ZL30resolveKeyUsingMaxIntegerValuePK9__CFArrayP14__CFDictionaryPK10__CFString
+ __ZL33resolveKeyRequiringValueConsensusPK9__CFArrayP14__CFDictionaryPK10__CFStringmPKc
+ __ZL33setRequiredCompatibilityKeyToTruePKvPv
+ __ZL36resolveKeyUsingMergedDictionaryValuePK9__CFArrayP14__CFDictionaryPK10__CFString
+ __ZL36resolveKeyUsingORAcrossBooleanValuesPK9__CFArrayP14__CFDictionaryPK10__CFString
+ __ZL48addBooleanCompatibilityKeyToRequiredSetIfPresentPK14__CFDictionaryPK10__CFStringP7__CFSet
- __ZL19mergeCFDictionariesPKvS0_Pv
CStrings:
+ "CVPixelBufferCreateResolvedAttributesDictionary: conflict merging dictionary: key %@, values %@ and %@"
+ "Returning err %d because attributes is NULL"
+ "Returning err %d because attributes is not a CFArray"
+ "Returning err %d because bitsPerBlockRef is not a CFNumber"
+ "Returning err %d because could not allocate filteredPixelFormatTypesRef"
+ "Returning err %d because could not allocate oldIOSurfaceProperties"
+ "Returning err %d because could not allocate realTimeCacheModeArray"
+ "Returning err %d because could not allocate requiredCompatibility"
+ "Returning err %d because could not allocate result"
+ "Returning err %d because element is NULL"
+ "Returning err %d because element is not a CFDictionary"
+ "Returning err %d because key is not a CFString"
+ "Returning err %d because pixelFormatDescription is not a CFDictionary"
+ "Returning err %d because planeRef is not a CFDictionary"
+ "Returning err %d because resolvedDictionaryOut is NULL"
+ "Returning err %d because result is not a CFDictionary"
+ "Returning err %d because the resolved value for %@ is not a CFNumber"
+ "Returning err %d because the resolved value for kCVPixelBufferBytesPerRowAlignmentKey is not a CFNumber"
+ "Returning err %d because the value for %@ is not a CFBoolean"
+ "Returning err %d because the value for %@ is not a CFDictionary"
+ "Returning err %d because the value for %@ is not a CFNumber"
+ "Returning err %d because the value for %@ is not of the expected CFType"
+ "Returning err %d because the value for kCVPixelBufferBytesPerRowAlignmentKey is not a CFNumber"
+ "Returning err %d because the value for kCVPixelBufferCacheModeKey contains a non-CFNumber element"
+ "Returning err %d because the value for kCVPixelBufferCacheModeKey is not a CFArray"
+ "Returning err %d because the value for kCVPixelBufferExactBytesPerRowKey contains a non-CFNumber element"
+ "Returning err %d because the value for kCVPixelBufferExactBytesPerRowKey is not a CFNumber or a CFArray of CFNumbers"
+ "Returning err %d because the value for kCVPixelBufferIOSurfacePropertiesKey is not a CFDictionary"
+ "Returning err %d because the value for kCVPixelBufferPixelFormatTypeKey contains a non-CFNumber element"
+ "Returning err %d because the value for kCVPixelBufferPixelFormatTypeKey is not a CFArray"
+ "Returning err %d because the value for kCVPixelBufferPixelFormatTypeKey is not a CFNumber or a CFArray of CFNumbers"
+ "Returning err %d because the value for kCVPixelBufferPreferRealTimeCacheModeIfEveryoneDoesKey is not a CFBoolean"
+ "Returning err %d because the value for kIOSurfaceCacheMode is not a CFNumber"
+ "bytes per row alignment vs exact bytes per row mismatch"
+ "checkIOOrEXSurfaceAndCreatePixelBufferBacking returning err %d because planeHeight[planeIndex %u] %u is not equal to %u required by image height %u and verticalSubsampling %u"
+ "checkIOOrEXSurfaceAndCreatePixelBufferBacking returning err %d because planeWidth[planeIndex %u] %u is not equal to %u required by image width %u and horizontalSubsampling %u"
+ "exact height does not match supplied height"
+ "planar bytes per row alignment vs exact bytes per row mismatch"
+ "unmergeable attachment dictionary"
- "CVPixelBufferCreateResolvedAttributesDictionary: conflict merging IOSurfaceProperties: key %@, values %@ and %@"
- "bytes per row alignemnt vs exact bytes per row mismatch"
- "custom layout size mismatch"
- "planar bytes per row alignemnt vs exact bytes per row mismatch"
```
