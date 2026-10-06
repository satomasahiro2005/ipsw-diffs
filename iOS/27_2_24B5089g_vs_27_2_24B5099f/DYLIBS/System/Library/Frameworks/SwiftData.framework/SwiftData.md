## SwiftData

> `/System/Library/Frameworks/SwiftData.framework/SwiftData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17cc74` | `0x181180` | **`+0x450c`** |
| `__TEXT.__cstring` | `0x6e2d` | `0x708d` | **`+0x260`** |
| `__DATA.__bss` | `0xa730` | `0xa8b0` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0x938c` | `0x94ac` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x14c7` | `0x1587` | **`+0xc0`** |
| `__TEXT.__const` | `0xbcf8` | `0xbda8` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x5ff8` | `0x60a4` | **`+0xac`** |
| `__AUTH_CONST.__objc_const` | `0x4800` | `0x4880` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x299c` | `0x29fc` | **`+0x60`** |
| `__DATA_DIRTY.__data` | `0x5c80` | `0x5cd8` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x2f84` | `0x2fdc` | **`+0x58`** |
| `__DATA.__data` | `0x1e70` | `0x1ea8` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x4440` | `0x4470` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x6820` | `0x6848` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x4c58` | `0x4c78` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1a18` | `0x1a30` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xe88` | `0xea0` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x79c` | `0x7a8` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x918` | `0x920` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x300` | `0x304` | **`+0x4`** |

### Other Changes

```diff

-184.0.0.0.0
+187.0.0.0.0

+  - /System/Library/PrivateFrameworks/CollectionsInternal.framework/CollectionsInternal

-  Functions: 6953
-  Symbols:   1903
-  CStrings:  650
+  Functions: 6983
+  Symbols:   1909
+  CStrings:  661
Symbols:
+ ___swift_closure_destructor.55Tm
+ ___swift_closure_destructor.73Tm
+ ___swift_closure_destructor.87Tm
+ ___unnamed_43
+ ___unnamed_47
+ ___unnamed_50
+ ___unnamed_53
+ ___unnamed_55
+ ___unnamed_58
+ _associated conformance 9SwiftData12DefaultStoreC10FutureTypeO28UnfetchedAttributeCodingKeys33_F9CED4885FEE8F99E760C5D693B1DDB5LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 9SwiftData12DefaultStoreC10FutureTypeO28UnfetchedAttributeCodingKeys33_F9CED4885FEE8F99E760C5D693B1DDB5LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _symbolic _____ 19CollectionsInternal6BitSetV
+ _symbolic _____ 9SwiftData12DefaultStoreC10FutureTypeO28UnfetchedAttributeCodingKeys33_F9CED4885FEE8F99E760C5D693B1DDB5LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SwiftData12DefaultStoreC10FutureTypeO28UnfetchedAttributeCodingKeys33_F9CED4885FEE8F99E760C5D693B1DDB5LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SwiftData12DefaultStoreC10FutureTypeO28UnfetchedAttributeCodingKeys33_F9CED4885FEE8F99E760C5D693B1DDB5LLO
- ___swift_closure_destructor.47Tm
- ___swift_closure_destructor.65Tm
- ___swift_closure_destructor.86Tm
- ___unnamed_42
- ___unnamed_46
- ___unnamed_48
- ___unnamed_52
- ___unnamed_54
- ___unnamed_56
CStrings:
+ " while materializing a keypath for "
+ ". Please file a bug report with your desired use case and a test."
+ "Failed to append "
+ "Failed to append the keypath for "
+ "Illegal attempt to save a partially fetched model that was never fully hydrated: "
+ "Unexpected backing data after promoting an excluded relationship: "
+ "Unreachable: .unfetchedAttribute is resolved by promoting the whole backing data, never fulfillFromCache."
+ "XCTestConfigurationFilePath"
+ "com.apple.GenerativeFunctions.agentstored"
+ "propertiesToFetch: ignoring to-many relationship '%s' on %s — DefaultStore does not support narrowing to-many relationships via propertiesToFetch, it will be fetched normally when accessed"
+ "unfetchedAttribute"
```
