## libMetalMetricsInterpose.dylib

> `/usr/lib/libMetalMetricsInterpose.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x141a4` | `0x1409c` | **`-0x108`** |
| `__TEXT.__gcc_except_tab` | `0x12dc` | `0x12b8` | **`-0x24`** |
| `__TEXT.__auth_stubs` | `0x800` | `0x820` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xd6d` | `0xd58` | **`-0x15`** |
| `__DATA_CONST.__auth_got` | `0x410` | `0x420` | **`+0x10`** |
| `__DATA.__data` | `0x1` | `0x10` | **`+0xf`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__thread_vars`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5.0.19.0.0
+5.0.22.0.0

-  Symbols:   967
+  Symbols:   970
Symbols:
+ __ZL24_EncoderCounterOffsetKey
+ _objc_getAssociatedObject
+ _objc_msgSend$numberWithUnsignedLong:
+ _objc_setAssociatedObject
- _objc_msgSend$metalGetEncoderCounterOffset:encoderTraceId:
Functions:
~ __Z30_MTMResolveEncoderGPUTimestampyym23FPMTLMetricsEncoderTypebPy : 404 -> 452
~ __ZL60MTL4CommandBuffer_renderCommandEncoderWithDescriptor_optionsPFvvEP11objc_objectP13objc_selectorP24MTL4RenderPassDescriptorm : 900 -> 1012
~ __ZL39MTL4CommandBuffer_computeCommandEncoderPFvvEP11objc_objectP13objc_selector : 536 -> 656
~ __ZL36MTL4RenderCommandEncoder_EndEncodingPFvvEP11objc_objectP13objc_selector : 916 -> 684
~ __ZL37MTL4ComputeCommandEncoder_EndEncodingPFvvEP11objc_objectP13objc_selector : 880 -> 652
~ __ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE25__parse_equivalence_classIPKcEET_S7_S7_PNS_20__bracket_expressionIcS2_EE : 532 -> 508
~ __ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE23__parse_character_classIPKcEET_S7_S7_PNS_20__bracket_expressionIcS2_EE : 176 -> 152
~ __ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE24__parse_collating_symbolIPKcEET_S7_S7_RNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE : 228 -> 204
~ __ZNSt3__15dequeINS_7__stateIcEENS_9allocatorIS2_EEE19__add_back_capacityEv : 484 -> 472
CStrings:
+ "numberWithUnsignedLong:"
- "metalGetEncoderCounterOffset:encoderTraceId:"
```
