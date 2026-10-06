## AskToViewExtension

> `/System/Library/ExtensionKit/Extensions/AskToViewExtension.appex/AskToViewExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19ca0` | `0x18860` | **`-0x1440`** |
| `__TEXT.__auth_stubs` | `0x10e0` | `0xf90` | **`-0x150`** |
| `__DATA_CONST.__auth_got` | `0x878` | `0x7d0` | **`-0xa8`** |
| `__DATA_CONST.__const` | `0xc48` | `0xba8` | **`-0xa0`** |
| `__TEXT.__const` | `0xa58` | `0xa08` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x58f` | `0x53f` | **`-0x50`** |
| `__TEXT.__swift5_capture` | `0x4f4` | `0x4a4` | **`-0x50`** |
| `__TEXT.__cstring` | `0x487` | `0x447` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0x8a2` | `0x86a` | **`-0x38`** |
| `__DATA.__data` | `0x6f0` | `0x6d0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x2e8` | `0x2c8` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x4a1` | `0x481` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x220` | `0x200` | **`-0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x2f0` | `0x2d8` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x540` | `0x530` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x148` | `0x140` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-96.0.0.0.0
+97.125.4.0.0

-  Functions: 357
-  Symbols:   173
-  CStrings:  135
+  Functions: 347
+  Symbols:   167
+  CStrings:  131
Symbols:
+ _swift_dynamicCast
- _OBJC_CLASS_$_NSJSONSerialization
- __swiftEmptyDictionarySingleton
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_initStackObject
- _swift_setDeallocating
- _swift_willThrow
CStrings:
+ "%s Could not build Messages launch URL: %@"
- "%s Could not construct URL to launch Messages"
- "%s Could not create url from payload"
- "%s JSON string was nil"
- "com.apple.AskToMessagesHost.AskToMessagesExtension"
- "dataWithJSONObject:options:error:"
```
