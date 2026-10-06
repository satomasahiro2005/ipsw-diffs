## libusd_ms.dylib

> `/usr/lib/usd/libusd_ms.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x274ad2c` | `0x274dfe4` | **`+0x32b8`** |
| `__TEXT.__unwind_info` | `0x1129e8` | `0x111790` | **`-0x1258`** |
| `__DATA.__bss` | `0x26e500` | `0x26d6f0` | **`-0xe10`** |
| `__TEXT.__const` | `0x62ca50` | `0x62bfd0` | **`-0xa80`** |
| `__TEXT.__gcc_except_tab` | `0x25c520` | `0x25cf5c` | **`+0xa3c`** |
| `__TEXT.__cstring` | `0x2b190c` | `0x2b1dfc` | **`+0x4f0`** |
| `__TEXT.__swift5_assocty` | `0x5b28` | `0x5738` | **`-0x3f0`** |
| `__TEXT.__swift5_typeref` | `0x5f0e` | `0x5c72` | **`-0x29c`** |
| `__DATA.__data` | `0x550b8` | `0x54e38` | **`-0x280`** |
| `__AUTH_CONST.__const` | `0x1304f0` | `0x1306d0` | **`+0x1e0`** |
| `__TEXT.__swift5_proto` | `0x25d0` | `0x2558` | **`-0x78`** |
| `__TEXT.__oslogstring` | `0x1ef33` | `0x1ef9a` | **`+0x67`** |
| `__TEXT.__swift5_reflstr` | `0x4ac9` | `0x4a79` | **`-0x50`** |
| `__DATA_CONST.__const` | `0xd958` | `0xd988` | **`+0x30`** |
| `__AUTH.__tf_func` | `0x3990` | `0x39a8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1b68` | `0x1b50` | **`-0x18`** |
| `__DATA.__common` | `0x5ff0` | `0x5ff8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x8c8` | `0x8c0` | **`-0x8`** |

### Other Changes

```diff

-24.1.24.0.0
+24.1.26.0.0

-  Functions: 200947
-  Symbols:   54408
-  CStrings:  31322
+  Functions: 200816
+  Symbols:   54411
+  CStrings:  31344
Symbols:
+ _$sSlsE19underestimatedCountSivg
+ __ZN32pxrInternal__aapl__pxrReserved__18UsdImagingDelegate28_HandleMaterialBindingChangeERKNS_7SdfPathERKNS_9TfHashMapIS1_NSt3__16vectorIS1_NS5_9allocatorIS1_EEEENS1_4HashENS5_8equal_toIS1_EENS7_INS5_4pairIS2_S9_EEEEEEPNS_20UsdImagingIndexProxyE
+ __ZN32pxrInternal__aapl__pxrReserved__18UsdImagingDelegate34_HandlePointInstancerBindingChangeERKNS_7SdfPathEPNS_20UsdImagingIndexProxyE
+ __ZN32pxrInternal__aapl__pxrReserved__20HdStResourceRegistry34MarkTextureGarbageCollectionNeededEv
+ __ZN32pxrInternal__aapl__pxrReserved__20UsdImagingIndexProxy13AddDependencyERKNS_7SdfPathES3_
+ __ZN32pxrInternal__aapl__pxrReserved__20UsdImagingIndexProxy16SetBoundMaterialERKNS_7SdfPathES3_b
+ __ZN32pxrInternal__aapl__pxrReserved__20UsdImagingIndexProxy17_RemoveDependencyERKNS_7SdfPathES3_
+ __ZN32pxrInternal__aapl__pxrReserved__26HdSt_TextureHandleRegistry27MarkGarbageCollectionNeededEv
+ __ZN32pxrInternal__aapl__pxrReserved__54USDIMAGING_ENABLE_SPARSE_MATERIAL_BINDING_INVALIDATIONE
+ __ZN32pxrInternal__aapl__pxrReserved__60USDIMAGING_ENABLE_SPARSE_MATERIAL_BINDING_INVALIDATION_valueE
+ __ZNK32pxrInternal__aapl__pxrReserved__21UsdImagingPrimAdapter27ManagesDescendantPopulationEv
+ __ZNK32pxrInternal__aapl__pxrReserved__29UsdSkelImagingSkelRootAdapter27ManagesDescendantPopulationEv
+ __ZNK32pxrInternal__aapl__pxrReserved__31UsdImagingPointInstancerAdapter18GetProtoRprimPathsERKNS_7SdfPathE
+ __ZNK32pxrInternal__aapl__pxrReserved__31UsdImagingPointInstancerAdapter24HasInstancerProtoAdapterERKNS_7SdfPathE
- _$s17BorrowingIterators0A8SequencePTl
- _$s7Elements17BorrowingSequencePTl
- _$sSPyxGs8_PointersMc
- _$sSTss17BorrowingSequenceRzrlE19underestimatedCountSivg
- _$sSTss17BorrowingSequenceRzrlE31_customContainsEquatableElementySbSg0F0STQzF
- _$sSlss17BorrowingSequenceRzrlE19underestimatedCountSivg
- _$sSlss17BorrowingSequenceRzrlE31_customContainsEquatableElementySbSg0F0STQzF
- _$ss17BorrowingSequenceP04makeA8Iterator0aD0QzyFTq
- _$ss17BorrowingSequenceP0A8IteratorAB_s0aC8ProtocolTn
- _$ss17BorrowingSequenceP19underestimatedCountSivgTq
- _$ss17BorrowingSequenceP31_customContainsEquatableElementySbSg0F0QzFTq
CStrings:
+ "00:37:45)"
+ "Enable sparse invalidation for direct material:binding edits in the legacy UsdImagingDelegate."
+ "File not found (timeSample): "
+ "GLTF mesh '%s' has face indices that are out of range for its %zu points; dropping primitive geometry\n"
+ "Jul 11 2026"
+ "USDIMAGING_ENABLE_SPARSE_MATERIAL_BINDING_INVALIDATION"
+ "_HandleMaterialBindingChange"
+ "_HandlePointInstancerBindingChange"
+ "_RemoveDependency"
+ "bool pxrInternal__aapl__pxrReserved__::UsdImagingDelegate::_HandleMaterialBindingChange(const SdfPath &, const _FlattenedDependenciesCacheMap &, UsdImagingIndexProxy *)"
+ "bool pxrInternal__aapl__pxrReserved__::UsdImagingDelegate::_HandlePointInstancerBindingChange(const SdfPath &, UsdImagingIndexProxy *)"
+ "decode: cannot find indices buffer with id "
+ "decode: cannot find length buffer with id "
+ "decode: cannot find sharpness buffer with id "
+ "decode: cannot get scope for sharpness buffer with id "
+ "encode: Cannot create indices buffer for Corner"
+ "encode: GCLBufferListAppendNew for Corner sharpness"
+ "encode: GCLBufferListAppendNew for accelerations"
+ "encode: GCLBufferListAppendNew for velocities"
+ "encodePMCFromRawData: Cannot create indices buffer for Corner"
+ "encodePMCFromRawData: GCLBufferListAppendNew accelerations"
+ "encodePMCFromRawData: GCLBufferListAppendNew for Corner sharpness"
+ "encodePMCFromRawData: GCLBufferListAppendNew velocities"
+ "userProperties:"
+ "void pxrInternal__aapl__pxrReserved__::UsdImagingIndexProxy::AddDependency(const SdfPath &, const SdfPath &)"
+ "void pxrInternal__aapl__pxrReserved__::UsdImagingIndexProxy::_RemoveDependency(const SdfPath &, const SdfPath &)"
- "22:39:43)"
- "Jun 23 2026"
- "decode: Unable to decode creases, missing sharpness"
- "void pxrInternal__aapl__pxrReserved__::UsdImagingIndexProxy::AddDependency(const SdfPath &, const UsdPrim &)"
```
