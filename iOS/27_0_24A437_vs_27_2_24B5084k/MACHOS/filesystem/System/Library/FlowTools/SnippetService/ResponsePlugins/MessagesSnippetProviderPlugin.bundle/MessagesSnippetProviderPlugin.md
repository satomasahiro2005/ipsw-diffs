## MessagesSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/MessagesSnippetProviderPlugin.bundle/MessagesSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c844` | `0x2c368` | **`-0x4dc`** |
| `__TEXT.__auth_stubs` | `0x2090` | `0x2100` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x13f0` | `0x1390` | **`-0x60`** |
| `__TEXT.__oslogstring` | `0x16f7` | `0x1737` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x1050` | `0x1088` | **`+0x38`** |
| `__TEXT.__const` | `0xd18` | `0xd08` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x790` | `0x788` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0xcc` | `0xc8` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0xb8` | `0xb4` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0xc4` | `0xc0` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-3600.47.22.11.2
+3605.15.1.0.0

-  Functions: 823
-  Symbols:   152
-  CStrings:  125
+  Functions: 817
+  Symbols:   151
+  CStrings:  126
Symbols:
- _swift_release_x12
CStrings:
+ "#MessagesSendSnippetHandler %s Unsupported: Idiom is empty."
+ "#MessagesSendSnippetHandler %s Unsupported: Skip for current idiom: %s"
- "#MessagesSendSnippetHandler %s Unsupported: Skip for current idiom"
```
