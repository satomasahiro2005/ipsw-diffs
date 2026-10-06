## IOAnalytics

> `/System/Library/HIDPlugins/SessionFilters/IOAnalytics.plugin/IOAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14cd4` | `0x14ca8` | **`-0x2c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1
Functions:
~ _createPayloadFromDictionary : 436 -> 432
~ -[IOAnalytics lazyInit] : 1048 -> 1044
~ -[IOAnalytics addedService:withClassName:] : 976 -> 972
~ __44-[IOAnalytics removedService:withClassName:]_block_invoke.95 : 388 -> 384
~ -[CAEvent isValidPayload:] : 1088 -> 1080
~ _convertNSDataToNSString : 260 -> 256
~ _convertNSStringToNSData : 444 -> 440
~ _classImplementsMethodsInProtocol : 304 -> 300
~ _base64EncodeArray : 328 -> 324
~ _base64DecodeArray : 340 -> 336
```
