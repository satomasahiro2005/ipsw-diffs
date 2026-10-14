## MessagesSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/MessagesSnippetProviderPlugin.bundle/MessagesSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2dfe8` | `0x34c7c` | **`+0x6c94`** |
| `__TEXT.__oslogstring` | `0x1747` | `0x1ac7` | **`+0x380`** |
| `__TEXT.__const` | `0xd48` | `0xf48` | **`+0x200`** |
| `__TEXT.__auth_stubs` | `0x21c0` | `0x2390` | **`+0x1d0`** |
| `__TEXT.__eh_frame` | `0x17d0` | `0x1928` | **`+0x158`** |
| `__DATA_CONST.__const` | `0x7d8` | `0x900` | **`+0x128`** |
| `__DATA.__bss` | `0x5d0` | `0x6d0` | **`+0x100`** |
| `__DATA_CONST.__auth_got` | `0x10e8` | `0x11d0` | **`+0xe8`** |
| `__DATA.__data` | `0x4f8` | `0x5d8` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x850` | `0x900` | **`+0xb0`** |
| `__DATA_CONST.__got` | `0x3b8` | `0x438` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x1c0` | `0x240` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x3f9` | `0x473` | **`+0x7a`** |
| `__TEXT.__cstring` | `0x271` | `0x2e1` | **`+0x70`** |
| `__DATA_CONST.__auth_ptr` | `0x408` | `0x468` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x164` | `0x19c` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0x90` | `0xc0` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0xc4` | `0xf4` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x420` | `0x440` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0xdc` | `0xfc` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x118` | `0x12c` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0xb5` | `0xa5` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x1a7` | `0x1b4` | **`+0xd`** |
| `__DATA.__objc_selrefs` | `0x108` | `0x110` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2c` | `0x34` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x104` | `0x10c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`

### Other Changes

```diff

-3605.20.1.0.0
+3605.21.1.11.2

+  - /System/Library/PrivateFrameworks/AppIntentsServices.framework/AppIntentsServices

-  Functions: 868
-  Symbols:   151
-  CStrings:  126
+  Functions: 950
+  Symbols:   153
+  CStrings:  145
Symbols:
+ ___stack_chk_fail
+ ___stack_chk_guard
CStrings:
+ "#%s %s MessageEntity has neither author nor body; skipping row"
+ "#%s %s Unsupported: Skip for current idiom: %s."
+ "#%s %s a display item is not a MobileSMS MessageEntity; leaving this response to the default pipeline"
+ "#%s %s context is nil."
+ "#%s %s no draft entities found."
+ "#%s %s no renderable MessageEntity in handle"
+ "#%s %s not on Apple TV"
+ "#%s %s responseType is not an inform"
+ "#%s %s responseType is not ask or confirm."
+ "#%s deviceIdiom is empty."
+ "#HomeDraftSnippetHandler built draft snippet model - contactName: %s, hasContent: %{bool}d"
+ "#HomeDraftSnippetHandler handling response"
+ "#HomeDraftSnippetHandler no draft value found in response items"
+ "#MessagesReadingSnippetHandler homeAccessory OpenConversationIntent failed: %@"
+ "#MessagesReadingSnippetHandler homeAccessory first-party reading, executing OpenConversationIntent"
+ "com.apple.MobileSMS"
+ "messageEntities(in:)"
+ "simpleItem(for:isSentMessageEntityResponse:)"
+ "spokenPhrase"
```
