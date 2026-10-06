## CalendarSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/CalendarSnippetProviderPlugin.bundle/CalendarSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a848` | `0x1e5c0` | **`+0x3d78`** |
| `__TEXT.__eh_frame` | `0xb78` | `0xd18` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x9c5` | `0xad5` | **`+0x110`** |
| `__TEXT.__auth_stubs` | `0xdb0` | `0xe80` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x528` | `0x480` | **`-0xa8`** |
| `__TEXT.__const` | `0x9c0` | `0x938` | **`-0x88`** |
| `__DATA.__bss` | `0x500` | `0x480` | **`-0x80`** |
| `__TEXT.__objc_stubs` | `0xe0` | `0x160` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x4a8` | `0x520` | **`+0x78`** |
| `__DATA.__data` | `0x618` | `0x680` | **`+0x68`** |
| `__DATA_CONST.__auth_got` | `0x6e0` | `0x748` | **`+0x68`** |
| `__TEXT.__objc_methname` | `0x97` | `0xda` | **`+0x43`** |
| `__TEXT.__swift5_typeref` | `0x36c` | `0x3ac` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x1b8` | `0x190` | **`-0x28`** |
| `__DATA.__objc_selrefs` | `0x38` | `0x58` | **`+0x20`** |
| `__TEXT.__cstring` | `0xfb` | `0xdb` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x214` | `0x1f8` | **`-0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0x210` | `0x228` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x238` | `0x250` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0xb0` | `0xa0` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0xbd` | `0xae` | **`-0xf`** |
| `__TEXT.__swift_as_cont` | `0x58` | `0x64` | **`+0xc`** |
| `__DATA.__common` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x28` | `0x24` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x38` | `0x34` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x98` | `0x9c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x78` | `0x7c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-3600.18.9.11.1
+3605.6.1.0.0

-  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 401
-  Symbols:   130
-  CStrings:  51
+  Functions: 456
+  Symbols:   135
+  CStrings:  57
Symbols:
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$_NSDateIntervalFormatter
+ _objc_release_x22
+ _objc_release_x23
+ _objc_release_x25
+ _swift_deletedAsyncMethodErrorTu
- _objc_release_x9
CStrings:
+ "[CalendarSnippetProvider] Building the accessory card on the per-item path"
+ "[CreateEventSnippetHandler] Rendering the accessory card"
+ "[EventConfirmationHandler] Rendering the accessory card"
+ "[EventDisambiguationHandler] Rendering the accessory card"
+ "[EventListSnippetHandler] Rendering the accessory card"
+ "[UpdateEventSnippetHandler] Rendering the accessory card"
+ "setDateStyle:"
+ "setTimeStyle:"
+ "stringFromDate:"
+ "stringFromDate:toDate:"
- "IntelligenceFlow"
- "SiriCompanion"
- "[Snippet.Event] CalendarEntity color is not a symbolic palette color"
- "[Snippet.Event] Unknown symbolic calendar color"
```
