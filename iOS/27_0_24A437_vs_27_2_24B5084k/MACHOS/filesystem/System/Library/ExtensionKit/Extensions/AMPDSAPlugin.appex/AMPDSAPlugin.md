## AMPDSAPlugin

> `/System/Library/ExtensionKit/Extensions/AMPDSAPlugin.appex/AMPDSAPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa8cc` | `0x9584` | **`-0x1348`** |
| `__TEXT.__oslogstring` | `0x4b5` | `0x3e5` | **`-0xd0`** |
| `__TEXT.__auth_stubs` | `0xaf0` | `0xa40` | **`-0xb0`** |
| `__DATA_CONST.__auth_got` | `0x580` | `0x528` | **`-0x58`** |
| `__TEXT.__eh_frame` | `0x598` | `0x560` | **`-0x38`** |
| `__TEXT.__swift5_typeref` | `0x200` | `0x1ca` | **`-0x36`** |
| `__TEXT.__objc_methname` | `0x37` | `0x15` | **`-0x22`** |
| `__DATA.__data` | `0x228` | `0x208` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x150` | `0x130` | **`-0x20`** |
| `__TEXT.__const` | `0x778` | `0x758` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x40` | `0x20` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x2e0` | `0x2d0` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x10` | `0x8` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x218` | `0x210` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x520` | `0x518` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-42.0.0.0.0
+44.0.0.0.0

-  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Functions: 189
-  Symbols:   119
-  CStrings:  50
+  Functions: 185
+  Symbols:   112
+  CStrings:  42
Symbols:
- _OBJC_CLASS_$_NSJSONSerialization
- ___stack_chk_fail
- ___stack_chk_guard
- __swift_FORCE_LOAD_$_swiftAppleArchive
- __swift_stdlib_bridgeErrorToNSError
- _swift_errorRelease
- _swift_errorRetain
CStrings:
- "Context: %s"
- "Couldn't form AMPDSA Hyper Params: %@"
- "Data corrupted"
- "Missing key '%s' in recipe"
- "Type mismatch for type '%s'"
- "Unknown decoding error: %@"
- "Value not found for type '%s'"
- "dataWithJSONObject:options:error:"
```
