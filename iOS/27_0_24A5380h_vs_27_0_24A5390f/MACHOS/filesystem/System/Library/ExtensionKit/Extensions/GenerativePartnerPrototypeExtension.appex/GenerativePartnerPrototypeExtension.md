## GenerativePartnerPrototypeExtension

> `/System/Library/ExtensionKit/Extensions/GenerativePartnerPrototypeExtension.appex/GenerativePartnerPrototypeExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ddcc` | `0x3c348` | **`-0x1a84`** |
| `__DATA.__bss` | `0x5c10` | `0x5910` | **`-0x300`** |
| `__TEXT.__eh_frame` | `0x19a8` | `0x1ae8` | **`+0x140`** |
| `__TEXT.__const` | `0x3722` | `0x3612` | **`-0x110`** |
| `__TEXT.__auth_stubs` | `0x20f0` | `0x21e0` | **`+0xf0`** |
| `__DATA_CONST.__auth_got` | `0x1080` | `0x10f8` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0xf70` | `0xfb0` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x106a` | `0x102e` | **`-0x3c`** |
| `__TEXT.__oslogstring` | `0xce5` | `0xcb5` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x498` | `0x4c0` | **`+0x28`** |
| `__DATA.__data` | `0x1270` | `0x1250` | **`-0x20`** |
| `__TEXT.__cstring` | `0xd3ed` | `0xd3cd` | **`-0x20`** |
| `__DATA.__common` | `0xd8` | `0xf0` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x2e0` | `0x2c8` | **`-0x18`** |
| `__DATA_CONST.__const` | `0x15e8` | `0x15d8` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0xa8` | `0xb8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x7c4` | `0x7b8` | **`-0xc`** |
| `__TEXT.__swift_as_cont` | `0xe4` | `0xf0` | **`+0xc`** |
| `__TEXT.__constg_swiftt` | `0x700` | `0x6f8` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0xbc` | `0xc4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-287.0.6.0.0
+291.1.0.5.0

-  Functions: 1937
-  Symbols:   183
+  Functions: 1866
+  Symbols:   182
Symbols:
- _swift_getErrorValue
CStrings:
+ "%@"
+ "Streaming assistant output %s, %ld chars"
+ "Streaming generated text %s, %ld chars"
+ "Streaming writing tools output %s, %ld chars"
+ "The requested text generated for the user as preamble, postamble or description of the generated writing tools output."
+ "The requested text generated for the user."
+ "The written or rewritten text generated for the user."
- "Failed to decode WritingTools JSON: "
- "Preamble, postamble, or anything unrelated to generating new text intended for a note, or somewhere that a cursor is active."
- "Received writing tools token %s, %ld chars"
- "Rewritten text such as selected text in a note, or new text to be added to a note."
- "System assistant response: %{public}s)"
- "Unparsed generated content: %{public}s)"
- "Writing Tools response: %{public}s)"
```
