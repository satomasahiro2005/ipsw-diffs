## AuthenticationServicesAgent

> `/usr/libexec/AuthenticationServicesAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21b08` | `0x21b44` | **`+0x3c`** |
| `__TEXT.__objc_methname` | `0x39d9` | `0x39f9` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1040` | `0x1028` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x500` | `0x508` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x760` | `0x758` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-7625.1.18.10.4
+7625.1.20.10.3

+  - /System/Library/PrivateFrameworks/SafariShared.framework/SafariShared

-  - /usr/lib/swift/libswiftAVFoundation.dylib

-  - /usr/lib/swift/libswiftMLCompute.dylib

-  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Symbols:   620
+  Symbols:   618
Symbols:
+ _OBJC_CLASS_$_WBSBiomeDonationManager
- __swift_FORCE_LOAD_$_swiftAVFoundation
- __swift_FORCE_LOAD_$_swiftMLCompute
- __swift_FORCE_LOAD_$_swiftNaturalLanguage
CStrings:
+ "initRegisteringActivityHandler:pccLimitChecker:securityRecommendationsBiomeDonor:"
- "initRegisteringActivityHandler:pccLimitChecker:"
```
