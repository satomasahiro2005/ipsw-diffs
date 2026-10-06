## libusd_ms.dylib

> `/usr/lib/usd/libusd_ms.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x275608c` | `0x27576d4` | **`+0x1648`** |
| `__TEXT.__cstring` | `0x2b1e9c` | `0x2b244c` | **`+0x5b0`** |
| `__TEXT.__oslogstring` | `0x1efba` | `0x1f402` | **`+0x448`** |
| `__AUTH_CONST.__const` | `0x1307e0` | `0x130770` | **`-0x70`** |
| `__TEXT.__unwind_info` | `0x112b20` | `0x112b80` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x25d488` | `0x25d4e4` | **`+0x5c`** |
| `__TEXT.__eh_frame` | `0x3cb38` | `0x3caf8` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1b48` | `0x1b28` | **`-0x20`** |
| `__AUTH_CONST.__weak_auth_got` | `0xb228` | `0xb248` | **`+0x20`** |
| `__DATA.__data` | `0x550f8` | `0x55118` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xd988` | `0xd9a8` | **`+0x20`** |
| `__TEXT.__const` | `0x62cd80` | `0x62cda0` | **`+0x20`** |
| `__AUTH.__tf_func` | `0x39a8` | `0x39c0` | **`+0x18`** |
| `__DATA.__bss` | `0x26e4f0` | `0x26e500` | **`+0x10`** |
| `__DATA.__common` | `0x5ff8` | `0x6000` | **`+0x8`** |

### Other Changes

```diff

-24.1.31.0.0
+24.1.32.0.0

-  Functions: 201004
-  Symbols:   54423
-  CStrings:  31349
+  Functions: 201009
+  Symbols:   54424
+  CStrings:  31375
Symbols:
+ __Z57__retain__ZN32pxrInternal__aapl__pxrReserved__9SdfBufferEPN32pxrInternal__aapl__pxrReserved__9SdfBufferE
+ __Z58__release__ZN32pxrInternal__aapl__pxrReserved__9SdfBufferEPN32pxrInternal__aapl__pxrReserved__9SdfBufferE
+ __ZN32pxrInternal__aapl__pxrReserved__22Tf_RetainReleaseHelper6retainINS_9SdfBufferEEEvPT_
+ __ZN32pxrInternal__aapl__pxrReserved__22Tf_RetainReleaseHelper7releaseINS_9SdfBufferEEEvPT_
+ __ZN32pxrInternal__aapl__pxrReserved__38SDF_TEXT_FILE_FORMAT_MAX_NESTING_DEPTHE
+ __ZN32pxrInternal__aapl__pxrReserved__44SDF_TEXT_FILE_FORMAT_MAX_NESTING_DEPTH_valueE
+ __ZN32pxrInternal__aapl__pxrReserved__8TfRefPtrINS_9SdfBufferEE13_AddRefStaticEPNS_9TfRefBaseE
+ __ZN32pxrInternal__aapl__pxrReserved__8TfRefPtrINS_9SdfBufferEE16_RemoveRefStaticEPKNS_9TfRefBaseE
+ _dispatch_apply
- _$sSb8swiftUsdEySbSo019pxrInternal__aapl__C10Reserved__O0B13APISchemaBaseVcfC
- __ZN32pxrInternal__aapl__pxrReserved__9SdfBuffer88__synthesized_lifetimeAccessor___retain__ZN32pxrInternal__aapl__pxrReserved__9TfRefBaseEEv
- __ZN32pxrInternal__aapl__pxrReserved__9SdfBuffer89__synthesized_lifetimeAccessor___release__ZN32pxrInternal__aapl__pxrReserved__9TfRefBaseEEv
- _dispatch_group_async
- _dispatch_release
- _dispatch_semaphore_create
- _dispatch_semaphore_signal
- _dispatch_semaphore_wait
CStrings:
+ "20:46:43)"
+ "Failed to allocate destination images (%d x %d) for specular-glossiness to metallic-roughness conversion; aborting conversion"
+ "Generate"
+ "GetOrLoadEntryData"
+ "Image::allocate: image dimensions (%d x %d x %d) are invalid or too large; refusing to allocate to avoid integer overflow"
+ "Image::read: decoded image dimensions (%d x %d x %d) are invalid or too large; refusing to allocate to avoid integer overflow"
+ "Maximum nesting depth for container values (lists, tuples, and dictionaries) in the USDA text file format. Input nested more deeply than this is rejected as a parse error to prevent a thread-stack overflow. Values less than 1 are treated as 1."
+ "Ptex face %d has an out-of-range resolution log2 (%d, %d); skipping to avoid an out-of-bounds write."
+ "Ptex face %d tile (%d x %d) does not fit in the texture page (%d x %d); skipping to avoid an out-of-bounds write."
+ "Ptex face resolution log2 (%d x %d) exceeds the maximum packable size (%d); rejecting face by treating it as 1x1."
+ "SDF_TEXT_FILE_FORMAT_MAX_NESTING_DEPTH"
+ "Sep 13 2026"
+ "Unable to open private inspection stage for variant enumeration; skipping cross-layer GeomSubset check for non-default variants."
+ "Value nesting too deep (exceeds maximum depth of %zu). Increase SDF_TEXT_FILE_FORMAT_MAX_NESTING_DEPTH if this input is trusted."
+ "[SdfZipFile] asset (size=%zu) is not readable via the no-mmap fallback path"
+ "[SdfZipFile] pread fallback read %zu of %u bytes at file offset %u (fd=%d) — returning zero-filled buffer to preserve non-null GetFile() contract"
+ "_markMeshesWithCrossLayerSubsets-session.usda"
+ "allocate"
+ "bool adobe::usd::Image::allocate(int, int, int)"
+ "bool adobe::usd::Image::read(const ImageAsset &, int)"
+ "bool adobe::usd::processAnisotropyPixels(const Image &, const tinygltf::Image *, float, bool, const AnisotropyData &, Image &, Image &)"
+ "bool adobe::usd::processAnisotropyPixelsFromRoughness(const AnisotropyData &, const tinygltf::Image *, bool, Image &)"
+ "const char *pxrInternal__aapl__pxrReserved__::SdfZipFile::_Impl::GetOrLoadEntryData(uint32_t, uint32_t) const"
+ "nanoexr error: invalid or too-large image dimensions\n"
+ "processAnisotropyPixels"
+ "processAnisotropyPixels: failed to allocate %d x %d anisotropy level/angle images; skipping anisotropy conversion"
+ "processAnisotropyPixelsFromRoughness"
+ "processAnisotropyPixelsFromRoughness: failed to allocate %d x %d anisotropy level image; skipping anisotropy conversion"
+ "read"
+ "std::pair<size_t, bool> pxrInternal__aapl__pxrReserved__::_CountTriangles(const SdfPath &, const VtIntArray &, const VtIntArray &)"
+ "v16@?0Q8"
+ "void pxrInternal__aapl__pxrReserved__::HdStPtexMipmapTextureLoader::Block::Generate(HdStPtexMipmapTextureLoader *, PtexTexture *, unsigned char *, int, int, int)"
+ "void pxrInternal__aapl__pxrReserved__::HdStPtexMipmapTextureLoader::Block::SetSize(unsigned char, unsigned char, bool)"
- " path="
- "01:18:52)"
- "Could not allocate asset buffer"
- "Could not read asset into buffer"
- "Sep  1 2026"
- "[diag] _processTexture skipped: res="
- "std::pair<int, bool> pxrInternal__aapl__pxrReserved__::_CountTriangles(const SdfPath &, const VtIntArray &, const VtIntArray &)"
```
