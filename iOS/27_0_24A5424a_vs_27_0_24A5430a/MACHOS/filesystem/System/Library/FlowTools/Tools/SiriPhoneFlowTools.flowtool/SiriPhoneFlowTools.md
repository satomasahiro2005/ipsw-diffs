## SiriPhoneFlowTools

> `/System/Library/FlowTools/Tools/SiriPhoneFlowTools.flowtool/SiriPhoneFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb4238` | `0xb4488` | **`+0x250`** |
| `__TEXT.__oslogstring` | `0x537e` | `0x53ee` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x12a0` | `0x12c0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1167` | `0x1177` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x558` | `0x560` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.38.22.11.1
+3600.38.22.11.2

-  Functions: 5442
-  Symbols:   11596
-  CStrings:  800
+  Functions: 5446
+  Symbols:   11597
+  CStrings:  802
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/SiriPhone/install/Symbols/BuiltProducts/libSiriPhoneFlowToolsImplementation.a(SPHCallCenter-783cc41c59834007beeb874ad6e38984.o)
+ _objc_msgSend$setAlternatives:
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/SiriPhone/install/Symbols/BuiltProducts/libSiriPhoneFlowToolsImplementation.a(SPHCallCenter-bd3bb0a6ed5d5935258fc6779c1fb87f.o)
CStrings:
+ "Found applicationDefined identifier -- returning stripped contact"
+ "IntentPerson -> INPerson (no contactIdentifier, forwarded as-is): %s"
+ "IntentPerson -> INPerson name-only skeleton + siriMatches: %s"
+ "setAlternatives:"
- "Found applicationDefined identifier -- returning skeleton contact"
- "IntentPerson -> INPerson: %s"
```
