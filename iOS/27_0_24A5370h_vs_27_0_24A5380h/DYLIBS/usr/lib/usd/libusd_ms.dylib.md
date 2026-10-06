## libusd_ms.dylib

> `/usr/lib/usd/libusd_ms.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2743a60` | `0x274ad2c` | **`+0x72cc`** |
| `__TEXT.__gcc_except_tab` | `0x25a9c4` | `0x25c520` | **`+0x1b5c`** |
| `__TEXT.__cstring` | `0x2b0a0c` | `0x2b190c` | **`+0xf00`** |
| `__TEXT.__unwind_info` | `0x112730` | `0x1129e8` | **`+0x2b8`** |
| `__TEXT.__const` | `0x62c8c0` | `0x62ca50` | **`+0x190`** |
| `__DATA.__bss` | `0x26e3a0` | `0x26e500` | **`+0x160`** |
| `__TEXT.__eh_frame` | `0x3cc08` | `0x3cb28` | **`-0xe0`** |
| `__AUTH_CONST.__const` | `0x130460` | `0x1304f0` | **`+0x90`** |
| `__DATA.__data` | `0x55078` | `0x550b8` | **`+0x40`** |
| `__DATA_CONST.__const` | `0xd940` | `0xd958` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x8d8` | `0x8c8` | **`-0x10`** |
| `__AUTH_CONST.__weak_auth_got` | `0xb220` | `0xb228` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x5f14` | `0x5f0e` | **`-0x6`** |

### Other Changes

```diff

-24.1.23.0.0
+24.1.24.0.0

-  Functions: 200865
-  Symbols:   54406
-  CStrings:  31230
+  Functions: 200947
+  Symbols:   54408
+  CStrings:  31322
Symbols:
+ __ZN32pxrInternal__aapl__pxrReserved__15aaplUsdGclCodec12compressMeshERKNS0_14GclMeshRawDataERKNS_12VtDictionaryERS4_
+ __ZN32pxrInternal__aapl__pxrReserved__15aaplUsdGclCodec17kResultStatsEntryE
+ __ZN32pxrInternal__aapl__pxrReserved__15aaplUsdGclCodec18kOptionOutputStatsE
+ __ZN32pxrInternal__aapl__pxrReserved__15aaplUsdGclCodec28kResultStatsMeshTrackerEntryE
- _$sytN
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ " (code "
+ " [variantSets="
+ " connArcs="
+ " connTarget="
+ " corners="
+ " in layer "
+ " out of range [0, "
+ " path="
+ " validVariants="
+ " | Vertices: "
+ " — attributes are connection targets from other prims (Gap D)"
+ "\":["
+ "\"}}"
+ "' has multiple time samples): "
+ "' — aborting mesh compression"
+ "**SKIPPING** Cannot compress variant mesh at "
+ "22:39:43)"
+ "COMPRESS"
+ "COMPRESS_VARIANTS"
+ "Empty mesh, skipping: "
+ "Empty variant mesh, skipping: "
+ "GclCodecErrorCode::LESS_EFFICIENT_TO_COMPRESS_IMAGE"
+ "GclCodecErrorCode::PRIM_SPEC_NOT_FOUND"
+ "Jun 23 2026"
+ "Mesh compression failed for "
+ "Mesh compression: animated mesh skipped (attribute '"
+ "OutputStats"
+ "Prim spec not found in target layer for mesh write-back"
+ "Processing mesh (layer path): "
+ "Processing variant mesh (layer path): "
+ "REJECTED"
+ "Skipping mesh (not eligible for compression): "
+ "Variant sets: "
+ "[diag] _processTexture skipped: res="
+ "_compressMeshFromTracker: animated mesh skipped (attribute '"
+ "_compressMeshFromTracker: invalid geometry for "
+ "_compressMeshFromTracker: prim spec not found for "
+ "_compressMeshFromTracker: skipping "
+ "_compressMeshFromTracker: unexpected topology types for "
+ "_compressVariantsFromTracker: animated variant skipped (attribute '"
+ "_compressVariantsFromTracker: inner prim not found for "
+ "_compressVariantsFromTracker: outer prim not found for "
+ "_compressVariantsFromTracker: unexpected topology types for "
+ "_processMesh(node): no tracker for "
+ "_processMesh(node): not eligible: "
+ "bool pxrInternal__aapl__pxrReserved__::SdfListProxy<pxrInternal__aapl__pxrReserved__::SdfPathKeyPolicy>::_Iterator<pxrInternal__aapl__pxrReserved__::SdfListProxy<pxrInternal__aapl__pxrReserved__::SdfPathKeyPolicy> *, pxrInternal__aapl__pxrReserved__::SdfListProxy<pxrInternal__aapl__pxrReserved__::SdfPathKeyPolicy>::_GetHelper>::equal(const This &) const [_TypePolicy = pxrInternal__aapl__pxrReserved__::SdfPathKeyPolicy, Owner = pxrInternal__aapl__pxrReserved__::SdfListProxy<pxrInternal__aapl__pxrReserved__::SdfPathKeyPolicy> *, GetItem = pxrInternal__aapl__pxrReserved__::SdfListProxy<pxrInternal__aapl__pxrReserved__::SdfPathKeyPolicy>::_GetHelper]"
+ "checkAttributeCompatibility: unsupported data type "
+ "compressMesh(raw): Invalid compression level"
+ "compressMesh(raw): cannot set codec"
+ "compressMesh(raw): empty geometry, skipping"
+ "compressMesh(raw): exception"
+ "compressMesh(raw): wrong extension"
+ "compressRaw(pmesh): empty geometry, skipping"
+ "compressRaw: unsupported codec"
+ "compressVariants"
+ "const T &pxrInternal__aapl__pxrReserved__::VtDictionaryGet(const VtDictionary &, const char *) [T = pxrInternal__aapl__pxrReserved__::VtArray<std::string>]"
+ "coveragePercent"
+ "crossLayer"
+ "encodePMCFromRawData: GCLBufferListAppendNew crease indices"
+ "encodePMCFromRawData: GCLBufferListAppendNew crease lengths"
+ "encodePMCFromRawData: GCLBufferListAppendNew crease sharpness"
+ "encodePMCFromRawData: GCLBufferListAppendNew for subset indices"
+ "encodePMCFromRawData: GCLBufferListAppendNew for subset lengths"
+ "encodePMCFromRawData: GCLBufferListAppendNew fvc"
+ "encodePMCFromRawData: GCLBufferListAppendNew fvi"
+ "encodePMCFromRawData: GCLBufferListAppendNew holes"
+ "encodePMCFromRawData: GCLBufferListAppendNew points"
+ "encodePMCFromRawData: GCLBufferListNew"
+ "encodePMCFromRawData: GCLEncodeMeshFromBufferList"
+ "encodePMCFromRawData: GCLOptionsNew"
+ "encodePMCFromRawData: GCLOptionsSet codec"
+ "encodePMCFromRawData: GCLOptionsSet compression level"
+ "encodePMCFromRawData: cannot create buffer for "
+ "encodePMCFromRawData: cannot create indices buffer"
+ "encodePMCFromRawData: empty topology, skipping"
+ "encodePMCFromRawData: failed to extract data for primvar '"
+ "encodePMCFromRawData: incompatible interpolation for "
+ "encodePMCFromRawData: invalid topology"
+ "fromRawData: Invalid topology"
+ "fromRawData: skipping attribute "
+ "fromRawData: skipping unsupported attribute type for "
+ "fromRawData: subset index "
+ "hasCorners"
+ "hasCrossLayerAttrs"
+ "hasOverrideGeometries"
+ "hasPartialVariants"
+ "hasSelfContainedVariants"
+ "hasVariantsAny"
+ "invalidMainGeometry"
+ "mesh.gcl"
+ "mesh.pmc"
+ "meshTracker"
+ "overrides"
+ "processedAttributes"
+ "safeToCompress"
+ "stats"
+ "{\"usd\":{\"tn\":\""
- "00:07:05)"
- "Compressing mesh: "
- "GclCodecErrorCode::LESS_EFFICIENT_TO_COMRPESS_IMAGE"
- "Jun 12 2026"
- "Total unique meshes to compress: "
```
