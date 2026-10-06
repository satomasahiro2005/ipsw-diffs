## analyticsd

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x140398` | `0x141b38` | **`+0x17a0`** |
| `__TEXT.__gcc_except_tab` | `0x17448` | `0x17648` | **`+0x200`** |
| `__TEXT.__const` | `0xa1ac` | `0xa2a4` | **`+0xf8`** |
| `__DATA_CONST.__const` | `0xad18` | `0xad98` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x84c8` | `0x8540` | **`+0x78`** |
| `__TEXT.__cstring` | `0x16079` | `0x16075` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-564.0.0.0.0
+569.0.5.0.0

-  Functions: 6331
+  Functions: 6348

-  CStrings:  4113
+  CStrings:  4115
CStrings:
+ "development"
+ "viewName"
+ "{JsonValue={variant<std::monostate, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>={__impl<std::monostate, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=(__union<std::__variant_detail::_Trait::_Available, 0UL, std::monostate, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<0UL, std::monostate>={monostate=}}(__union<std::__variant_detail::_Trait::_Available, 1UL, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<1UL, JsonObject>={JsonObject={IntrusivePtr<apple::cow::detail::EmbeddedArray<JsonObjectPayloadHeader, JsonValue>>=^v}}}(__union<std::__variant_detail::_Trait::_Available, 2UL, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<2UL, JsonArray>={JsonArray={CowVector<JsonValue, 0U>={CowSequence<JsonValue, 0U>=[16C]}}}}(__union<std::__variant_detail::_Trait::_Available, 3UL, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<3UL, apple::cow::detail::CowString>={CowString={CowSequence<char, 0U>=[16C]}}}(__union<std::__variant_detail::_Trait::_Available, 4UL, bool, long long, unsigned long long, double>=c{__alt<4UL, bool>=B}(__union<std::__variant_detail::_Trait::_Available, 5UL, long long, unsigned long long, double>=c{__alt<5UL, long long>=q}(__union<std::__variant_detail::_Trait::_Available, 6UL, unsigned long long, double>=c{__alt<6UL, unsigned long long>=Q}(__union<std::__variant_detail::_Trait::_Available, 7UL, double>=c{__alt<7UL, double>=d}(__union<std::__variant_detail::_Trait::_Available, 8UL>=)))))))))I}}}8@?0"
- "{JsonValue={variant<std::monostate, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>={__impl<std::monostate, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=(__union<std::__variant_detail::_Trait::_Available, 0UL, std::monostate, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<0UL, std::monostate>={monostate=}}(__union<std::__variant_detail::_Trait::_Available, 1UL, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<1UL, JsonObject>={JsonObject={IntrusivePtr<apple::cow::detail::EmbeddedArray<JsonObjectPayloadHeader, JsonValue>>=^v}}}(__union<std::__variant_detail::_Trait::_Available, 2UL, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<2UL, JsonArray>={JsonArray={CowVector<JsonValue, 0U>={CowSequence<JsonValue, 0U>=(?=^{JsonValue}^v)[0C]Q}}}}(__union<std::__variant_detail::_Trait::_Available, 3UL, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<3UL, apple::cow::detail::CowString>={CowString={CowSequence<char, 0U>=(?=*^v)[0C]Q}}}(__union<std::__variant_detail::_Trait::_Available, 4UL, bool, long long, unsigned long long, double>=c{__alt<4UL, bool>=B}(__union<std::__variant_detail::_Trait::_Available, 5UL, long long, unsigned long long, double>=c{__alt<5UL, long long>=q}(__union<std::__variant_detail::_Trait::_Available, 6UL, unsigned long long, double>=c{__alt<6UL, unsigned long long>=Q}(__union<std::__variant_detail::_Trait::_Available, 7UL, double>=c{__alt<7UL, double>=d}(__union<std::__variant_detail::_Trait::_Available, 8UL>=)))))))))I}}}8@?0"
```
