## SiriPhoneSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/SiriPhoneSnippetProviderPlugin.bundle/SiriPhoneSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf8fc4` | `0xf923c` | **`+0x278`** |
| `__TEXT.__oslogstring` | `0x790e` | `0x797e` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x16e0` | `0x1700` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x13b6` | `0x13c6` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x668` | `0x670` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
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

-  Functions: 7071
-  Symbols:   15265
-  CStrings:  1017
+  Functions: 7077
+  Symbols:   15266
+  CStrings:  1019
Symbols:
+ _objc_msgSend$setAlternatives:
CStrings:
+ "Found applicationDefined identifier -- returning stripped contact"
+ "IntentPerson -> INPerson (no contactIdentifier, forwarded as-is): %s"
+ "IntentPerson -> INPerson name-only skeleton + siriMatches: %s"
+ "setAlternatives:"
- "Found applicationDefined identifier -- returning skeleton contact"
- "IntentPerson -> INPerson: %s"
```
