## NotebookSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/NotebookSnippetProviderPlugin.bundle/NotebookSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e788` | `0x23d5c` | **`+0x55d4`** |
| `__DATA_CONST.__const` | `0x2b0` | `0x490` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x7a7` | `0x963` | **`+0x1bc`** |
| `__TEXT.__auth_stubs` | `0xe60` | `0xfc0` | **`+0x160`** |
| `__TEXT.__eh_frame` | `0xbfc` | `0xabc` | **`-0x140`** |
| `__TEXT.__swift5_capture` | `—` | `0xc0` | **`+0xc0`** |
| `__DATA_CONST.__auth_got` | `0x738` | `0x7e8` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x2bf` | `0x30c` | **`+0x4d`** |
| `__TEXT.__unwind_info` | `0x4e8` | `0x4a0` | **`-0x48`** |
| `__TEXT.__const` | `0x9f0` | `0xa20` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1f8` | `0x220` | **`+0x28`** |
| `__DATA.__data` | `0x2e0` | `0x300` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x84` | `0x64` | **`-0x20`** |
| `__TEXT.__swift_as_ret` | `0xa8` | `0x94` | **`-0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x1f8` | `0x208` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x104` | `0xf4` | **`-0x10`** |
| `__DATA.__common` | `0xb0` | `0xb8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3600.28.3.0.0
+3600.28.10.0.0

+  - /System/Library/PrivateFrameworks/IntelligenceFlowShared.framework/IntelligenceFlowShared

-  Functions: 500
-  Symbols:   104
-  CStrings:  53
+  Functions: 561
+  Symbols:   119
+  CStrings:  57
Symbols:
+ _swift_arrayDestroy
+ _swift_bridgeObjectRetain_n
+ _swift_deallocObject
+ _swift_release_n
+ _swift_release_x25
+ _swift_release_x26
+ _swift_release_x27
+ _swift_retain_n
+ _swift_retain_x21
+ _swift_retain_x23
+ _swift_retain_x24
+ _swift_retain_x26
+ _swift_retain_x27
+ _swift_retain_x28
+ _swift_setDeallocating
CStrings:
+ "[NotebookSnippetProvider] Handling ReadableReminders container with %ld children via per-item path"
+ "[ReminderCreateUpdateSnippetHandler] Response has archiveView — deferring to DefaultHandler for ShowsSnippetView"
+ "[ReminderSearchResultSnippetHandler] After hydration: %ld reminders, %ld subtasks"
+ "[ReminderSearchResultSnippetHandler] Unwrapped %ld ReadableReminders containers into %ld child entities"
```
