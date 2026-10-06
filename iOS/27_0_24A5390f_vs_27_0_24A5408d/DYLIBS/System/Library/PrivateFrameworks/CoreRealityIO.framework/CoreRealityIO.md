## CoreRealityIO

> `/System/Library/PrivateFrameworks/CoreRealityIO.framework/CoreRealityIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c4f6c` | `0x2c4e54` | **`-0x118`** |
| `__TEXT.__cstring` | `0x114fb` | `0x113fb` | **`-0x100`** |
| `__AUTH_CONST.__const` | `0x1b898` | `0x1b950` | **`+0xb8`** |
| `__TEXT.__const` | `0x213f0` | `0x213b0` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x3f37` | `0x3f76` | **`+0x3f`** |
| `__AUTH_CONST.__auth_got` | `0x34a0` | `0x3478` | **`-0x28`** |
| `__TEXT.__gcc_except_tab` | `0x36128` | `0x3614c` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x408` | `0x418` | **`+0x10`** |
| `__AUTH_CONST.__weak_auth_got` | `0x440` | `0x438` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x530` | `0x538` | **`+0x8`** |
| `__DATA_CONST.__weak_got` | `0x30` | `0x28` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x108f8` | `0x10900` | **`+0x8`** |

### Other Changes

```diff

-235.0.4.0.0
+235.0.6.0.0

-  Symbols:   21053
-  CStrings:  2179
+  Symbols:   21049
+  CStrings:  2181
Symbols:
+ GCC_except_table246
+ GCC_except_table257
+ _OBJC_CLASS_$_SGNodeDefStore
+ __ZN32pxrInternal__aapl__pxrReserved__7VtValue5_InitIA8_cE4InitEPS0_RA8_Kc
+ __ZN9realityio4mtlx17MtlxActionPayloadC2ERNS0_14NeoShadeShaderEP14SGNodeDefStore
+ __ZZN32pxrInternal__aapl__pxrReserved__7VtValue5_InitIA8_cE12_GetTypeInfoEvE2ti
- __ZN32pxrInternal__aapl__pxrReserved__11TfSingletonINS_14TraceCollectorEE15_CreateInstanceERNSt3__16atomicIPS1_EE
- __ZN32pxrInternal__aapl__pxrReserved__11TfSingletonINS_14TraceCollectorEE9_instanceE
- __ZN32pxrInternal__aapl__pxrReserved__13TraceReporter16UpdateTraceTreesEv
- __ZN32pxrInternal__aapl__pxrReserved__13TraceReporter17GetGlobalReporterEv
- __ZN32pxrInternal__aapl__pxrReserved__14TraceCollector10SetEnabledEb
- __ZN32pxrInternal__aapl__pxrReserved__14TraceCollector5ClearEv
- __ZN9realityio4mtlx17MtlxActionPayloadC2ERNS0_14NeoShadeShaderE
- __ZNK32pxrInternal__aapl__pxrReserved__13TraceReporter11GetCountersEv
- __ZNK32pxrInternal__aapl__pxrReserved__15TfWeakPtrFacadeINS_9TfWeakPtrENS_13TraceReporterEEptEv
- __ZTSN32pxrInternal__aapl__pxrReserved__9TfWeakPtrINS_13TraceReporterEEE
CStrings:
+ "Failed to create SGNodeDefStore for MaterialX version '%s': %@"
+ "Release"
+ "importSession:BuildConfig"
- "DataType *pxrInternal__aapl__pxrReserved__::TfWeakPtrFacade<pxrInternal__aapl__pxrReserved__::TfWeakPtr, pxrInternal__aapl__pxrReserved__::TraceReporter>::operator->() const [PtrTemplate = pxrInternal__aapl__pxrReserved__::TfWeakPtr, Type = pxrInternal__aapl__pxrReserved__::TraceReporter]"
```
