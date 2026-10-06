## analyticsd

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x142538` | `0x1442a8` | **`+0x1d70`** |
| `__TEXT.__const` | `0xa2a4` | `0xa464` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x160d5` | `0x16215` | **`+0x140`** |
| `__TEXT.__gcc_except_tab` | `0x176e4` | `0x17794` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x8568` | `0x8608` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x1af29` | `0x1af99` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x3b0` | `0x398` | **`-0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x50` | `0x48` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-569.0.5.0.0
+577.40.5.0.0

-  Functions: 6354
+  Functions: 6410

-  CStrings:  4131
+  CStrings:  4139
CStrings:
+ "LocationNotAuthorized"
+ "LocationServicesDisabled"
+ "MarketNA"
+ "[CD] Market: Location not authorized"
+ "[CD] Market: Location services disabled"
+ "[CD] Market: Market unknown: %s"
+ "[CD] Market: Reporting market: %{private}s"
+ "bluetoothStatus"
+ "locationAuthorizationStatus"
+ "locationServicesEnabled"
+ "{JsonValue={variant<std::monostate, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>={__impl<std::monostate, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=(__union<std::__variant_detail::_Trait::_Available, 0UL, std::monostate, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<0UL, std::monostate>={monostate=}}(__union<std::__variant_detail::_Trait::_Available, 1UL, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<1UL, JsonObject>={JsonObject={JsonColumnBlock<apple::cow::detail::CowString>={IntrusivePtr<jsonvalue::detail::JsonColumnBlock<apple::cow::detail::CowString>::Node, jsonvalue::detail::JsonColumnBlock<apple::cow::detail::CowString>::NodeTraits>=^{Node}}Q}}}(__union<std::__variant_detail::_Trait::_Available, 2UL, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<2UL, JsonArray>={JsonArray={JsonColumnBlock<void>={IntrusivePtr<jsonvalue::detail::JsonColumnBlock<>::Node, jsonvalue::detail::JsonColumnBlock<>::NodeTraits>=^{Node}}Q}}}(__union<std::__variant_detail::_Trait::_Available, 3UL, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<3UL, apple::cow::detail::CowString>={CowString={CowSequence<char, 23U>=[24C]}}}(__union<std::__variant_detail::_Trait::_Available, 4UL, bool, long long, unsigned long long, double>=c{__alt<4UL, bool>=B}(__union<std::__variant_detail::_Trait::_Available, 5UL, long long, unsigned long long, double>=c{__alt<5UL, long long>=q}(__union<std::__variant_detail::_Trait::_Available, 6UL, unsigned long long, double>=c{__alt<6UL, unsigned long long>=Q}(__union<std::__variant_detail::_Trait::_Available, 7UL, double>=c{__alt<7UL, double>=d}(__union<std::__variant_detail::_Trait::_Available, 8UL>=)))))))))I}}}8@?0"
- "LocationFrameworkNotSupported"
- "[CD] Market: Location framework not supported"
- "{JsonValue={variant<std::monostate, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>={__impl<std::monostate, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=(__union<std::__variant_detail::_Trait::_Available, 0UL, std::monostate, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<0UL, std::monostate>={monostate=}}(__union<std::__variant_detail::_Trait::_Available, 1UL, JsonObject, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<1UL, JsonObject>={JsonObject={IntrusivePtr<apple::cow::detail::EmbeddedArray<JsonObjectPayloadHeader, JsonValue>>=^v}}}(__union<std::__variant_detail::_Trait::_Available, 2UL, JsonArray, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<2UL, JsonArray>={JsonArray={CowVector<JsonValue, 0U>={CowSequence<JsonValue, 0U>=[16C]}}}}(__union<std::__variant_detail::_Trait::_Available, 3UL, apple::cow::detail::CowString, bool, long long, unsigned long long, double>=c{__alt<3UL, apple::cow::detail::CowString>={CowString={CowSequence<char, 0U>=[16C]}}}(__union<std::__variant_detail::_Trait::_Available, 4UL, bool, long long, unsigned long long, double>=c{__alt<4UL, bool>=B}(__union<std::__variant_detail::_Trait::_Available, 5UL, long long, unsigned long long, double>=c{__alt<5UL, long long>=q}(__union<std::__variant_detail::_Trait::_Available, 6UL, unsigned long long, double>=c{__alt<6UL, unsigned long long>=Q}(__union<std::__variant_detail::_Trait::_Available, 7UL, double>=c{__alt<7UL, double>=d}(__union<std::__variant_detail::_Trait::_Available, 8UL>=)))))))))I}}}8@?0"
```
