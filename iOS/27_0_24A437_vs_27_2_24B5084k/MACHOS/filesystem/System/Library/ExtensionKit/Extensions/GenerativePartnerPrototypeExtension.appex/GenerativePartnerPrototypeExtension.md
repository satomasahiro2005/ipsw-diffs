## GenerativePartnerPrototypeExtension

> `/System/Library/ExtensionKit/Extensions/GenerativePartnerPrototypeExtension.appex/GenerativePartnerPrototypeExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e200` | `0x3bd7c` | **`-0x2484`** |
| `__DATA_CONST.__const` | `0x15d8` | `0x1810` | **`+0x238`** |
| `__TEXT.__const` | `0x3632` | `0x3762` | **`+0x130`** |
| `__TEXT.__swift5_fieldmd` | `0x7b8` | `0x8dc` | **`+0x124`** |
| `__TEXT.__swift5_reflstr` | `0x6b7` | `0x7d7` | **`+0x120`** |
| `__TEXT.__eh_frame` | `0x1ae8` | `0x19e8` | **`-0x100`** |
| `__TEXT.__oslogstring` | `0xcb5` | `0xbf5` | **`-0xc0`** |
| `__DATA.__data` | `0x1288` | `0x1330` | **`+0xa8`** |
| `__TEXT.__constg_swiftt` | `0x6f8` | `0x784` | **`+0x8c`** |
| `__DATA.__bss` | `0x5a10` | `0x5a90` | **`+0x80`** |
| `__TEXT.__cstring` | `0xd3cd` | `0xd3fd` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x228` | `0x258` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xfe0` | `0x1008` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x103e` | `0x1064` | **`+0x26`** |
| `__TEXT.__auth_stubs` | `0x23b0` | `0x23d0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x11e0` | `0x11f0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xa8` | `0xb8` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x900` | `0x8f8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x568` | `0x560` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0xc4` | `0xcc` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xb8` | `0xc0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2d0` | `0x2d4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-291.6.0.5.102
+297.6.0.5.0

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Functions: 1877
-  Symbols:   181
-  CStrings:  195
+  Functions: 1843
+  Symbols:   183
+  CStrings:  192
Symbols:
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ _swift_cvw_enumFn_getEnumTag
CStrings:
+ "Completed image to JPEG conversion: %{public}s"
+ "Skipping contentReference (%{public}ld chars); an attachment was already streamed"
+ "com.apple.Shortcuts.AskAFMAction.Entities"
- " ---- Candidate %{public}ld, Segment %{public}ld ----"
- "Completed HEIC to JPEG conversion: %{public}s"
- "Completed streaming entities and attachments"
- "Ignoring text content which was already streamed: %s, %{public}ld characters"
- "Text streaming completed, gathering images & file segments"
- "Unhandled segment content type: %{public}s)"
```
