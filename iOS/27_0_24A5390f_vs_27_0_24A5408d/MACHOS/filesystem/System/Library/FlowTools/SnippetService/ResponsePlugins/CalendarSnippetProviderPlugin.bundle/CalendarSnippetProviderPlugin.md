## CalendarSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/CalendarSnippetProviderPlugin.bundle/CalendarSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14350` | `0x1a820` | **`+0x64d0`** |
| `__TEXT.__oslogstring` | `0x5b5` | `0x9c5` | **`+0x410`** |
| `__TEXT.__eh_frame` | `0x9c8` | `0xb78` | **`+0x1b0`** |
| `__DATA.__data` | `0x480` | `0x618` | **`+0x198`** |
| `__TEXT.__auth_stubs` | `0xc40` | `0xdb0` | **`+0x170`** |
| `__TEXT.__const` | `0x850` | `0x9c0` | **`+0x170`** |
| `__DATA.__bss` | `0x400` | `0x500` | **`+0x100`** |
| `__DATA_CONST.__auth_got` | `0x628` | `0x6e0` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x410` | `0x4b0` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x140` | `0x1b8` | **`+0x78`** |
| `__TEXT.__constg_swiftt` | `0x1a8` | `0x214` | **`+0x6c`** |
| `__DATA_CONST.__const` | `0x4c0` | `0x528` | **`+0x68`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x238` | **`+0x68`** |
| `__DATA_CONST.__auth_ptr` | `0x1b0` | `0x210` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x316` | `0x36c` | **`+0x56`** |
| `__TEXT.__swift5_reflstr` | `0x8d` | `0xbd` | **`+0x30`** |
| `__DATA.__common` | `0x70` | `0x88` | **`+0x18`** |
| `__TEXT.__cstring` | `0xeb` | `0xfb` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xc0` | `0xb0` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x2c` | `0x38` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x74` | `0x78` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-3600.18.5.0.0
+3600.18.9.1.1

-  Functions: 342
-  Symbols:   122
-  CStrings:  39
+  Functions: 401
+  Symbols:   130
+  CStrings:  51
Symbols:
+ _objc_release_x27
+ _objc_release_x28
+ _objc_release_x9
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_getEnumCaseMultiPayload
+ _swift_release_x22
+ _swift_storeEnumTagMultiPayload
- _objc_release_x22
CStrings:
+ "DeleteEventIntent"
+ "[CalendarSnippetProvider] Building event from entity on the synchronous per-item path — no hydration, so eventModel and punch-out are unavailable (idiom=%{public}s)"
+ "[CreateEventSnippetHandler] Extracted %ld created events from response"
+ "[CreateEventSnippetHandler] Failed to hydrate any events from %ld entities"
+ "[EventConfirmationHandler] Calendar event `.confirm` from an unhandled tool — schemaId=%{public}s, toolId=%{public}s"
+ "[EventConfirmationHandler] Calendar event `.confirm` without an actionConfirmation context (kind=%{public}s)"
+ "[EventConfirmationHandler] EventEntity not found in the typedValue passed to handle (operation=%{public}s): %s"
+ "[Snippet.Event] CalendarEntity color is not a symbolic palette color"
+ "[Snippet.Event] CalendarEntity missing color parameter"
+ "[Snippet.Event] EntityValue location parameter in an unhandled shape"
+ "[Snippet.Event] EntityValue missing title parameter"
+ "[Snippet.Event] Unknown symbolic calendar color"
+ "[Snippet.Event] hydrate(): EKEphemeralCacheEventStoreProvider returned a nil store; rendering placeholder data"
+ "parameterConfirmation"
- "[DeleteEventConfirmationHandler] EventEntity not found in the typedValue passed to handle: %s"
- "com.apple.mobilecal.DeleteEventIntent"
```
