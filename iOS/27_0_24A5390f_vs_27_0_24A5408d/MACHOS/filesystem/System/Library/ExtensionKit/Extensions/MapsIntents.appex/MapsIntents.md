## MapsIntents

> `/System/Library/ExtensionKit/Extensions/MapsIntents.appex/MapsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x560c0` | `0x59924` | **`+0x3864`** |
| `__TEXT.__swift5_typeref` | `0x2a4e` | `0x3852` | **`+0xe04`** |
| `__DATA.__data` | `0x1cc8` | `0x1ef8` | **`+0x230`** |
| `__TEXT.__const` | `0x4eb4` | `0x50d4` | **`+0x220`** |
| `__TEXT.__auth_stubs` | `0x1c40` | `0x1df0` | **`+0x1b0`** |
| `__TEXT.__objc_stubs` | `0x12a0` | `0x1440` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x19ab` | `0x1b39` | **`+0x18e`** |
| `__TEXT.__swift5_fieldmd` | `0xa0c` | `0xb5c` | **`+0x150`** |
| `__TEXT.__swift5_reflstr` | `0x114e` | `0x129e` | **`+0x150`** |
| `__TEXT.__objc_methname` | `0x4abe` | `0x4bf4` | **`+0x136`** |
| `__DATA.__bss` | `0x84b0` | `0x85c0` | **`+0x110`** |
| `__DATA_CONST.__const` | `0x1cf8` | `0x1e08` | **`+0x110`** |
| `__DATA_CONST.__auth_got` | `0xe28` | `0xf08` | **`+0xe0`** |
| `__DATA_CONST.__got` | `0x578` | `0x628` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x1538` | `0x15d8` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0xdc8` | `0xe38` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x6ac` | `0x710` | **`+0x64`** |
| `__TEXT.__cstring` | `0x1d65` | `0x1dc5` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x44` | **`+0x44`** |
| `__DATA.__objc_const` | `0x1e98` | `0x1ed8` | **`+0x40`** |
| `__DATA_CONST.__auth_ptr` | `0xa20` | `0xa60` | **`+0x40`** |
| `__DATA.__common` | `0x128` | `0x158` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x28f8` | `0x2920` | **`+0x28`** |
| `__DATA_CONST.__objc_intobj` | `0x798` | `0x7b0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xffc` | `0x1014` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__TEXT.__objc_methtype` | `0x1000` | `0xff1` | **`-0xf`** |
| `__TEXT.__swift5_types` | `0x94` | `0xa0` | **`+0xc`** |
| `__DATA_CONST.__objc_catlist` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x420` | `0x428` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2972.30.6.12.32
+2972.30.6.12.54

+  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry

+  - /usr/lib/libc++.1.dylib

-  Functions: 1510
-  Symbols:   259
-  CStrings:  1266
+  Functions: 1553
+  Symbols:   280
+  CStrings:  1287
Symbols:
+ _NRDevicePropertyMainScreenHeight
+ _NRDevicePropertyMainScreenWidth
+ _NRDevicePropertyScreenScale
+ _OBJC_CLASS_$_NRPairedDeviceRegistry
+ _OBJC_CLASS_$_UITraitCollection
+ __Unwind_Resume
+ __ZNSt11logic_errorC2EPKc
+ __ZNSt12length_errorD1Ev
+ __ZNSt20bad_array_new_lengthC1Ev
+ __ZNSt20bad_array_new_lengthD1Ev
+ __ZTISt12length_error
+ __ZTISt20bad_array_new_length
+ __ZTVSt12length_error
+ __ZdlPv
+ __ZnwmSt19__type_descriptor_t
+ ___cxa_allocate_exception
+ ___cxa_free_exception
+ ___cxa_throw
+ ___gxx_personality_v0
+ _objc_alloc_init
+ _objc_autoreleaseReturnValue
+ _objc_retain_x25
- _swift_retain_x26
CStrings:
+ "CalculateETAIntent: [favorites] fetch failed after %ld ms. Error=%s"
+ "CalculateETAIntent: [favorites] fetch succeeded in %ld ms (matched: %{bool}d)"
+ "CalculateETAIntent: [favorites] no geoMapItem — skipping favorite lookup, using default style"
+ "CalculateETAIntent: interfaceIdiom=%s"
+ "CalculateETAIntent: paired watch size unavailable; using fallback maxContentWidth=%f mapViewportSize=%s"
+ "CalculateETAIntent: watchScreenPt=%fx%f mapViewportSize=%s"
+ "Contradictory frame constraints specified."
+ "addressMarkerStyleAttributes"
+ "attributeAtIndex:"
+ "countAttrs"
+ "doubleValue"
+ "generateGeodesicDistanceSnapshot(from:to:layout:)"
+ "generateMapSnapshot(for:layout:)"
+ "getActivePairedDevice"
+ "hasAttributes"
+ "replaceAttributes:count:"
+ "setIncludeHistoricTravelTime:"
+ "setTrafficType:"
+ "setTraitCollection:"
+ "sharedInstance"
+ "styleAttributesForMapItemWithAttributes:"
+ "traitCollectionWithUserInterfaceStyle:"
+ "valueForProperty:"
+ "vector"
- "CalculateETAIntent: Failed to fetch favorite item for GEOMapItem: %@. Error=%s."
- "generateGeodesicDistanceSnapshot(from:to:)"
- "generateMapSnapshot(for:)"
```
