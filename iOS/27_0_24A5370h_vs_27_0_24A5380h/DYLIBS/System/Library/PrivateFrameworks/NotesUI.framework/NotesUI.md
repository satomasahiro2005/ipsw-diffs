## NotesUI

> `/System/Library/PrivateFrameworks/NotesUI.framework/NotesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b4058` | `0x2b5914` | **`+0x18bc`** |
| `__DATA.__bss` | `0x4500` | `0x3f50` | **`-0x5b0`** |
| `__DATA_DIRTY.__bss` | `0x3fb0` | `0x4550` | **`+0x5a0`** |
| `__DATA_DIRTY.__data` | `0x2460` | `0x2600` | **`+0x1a0`** |
| `__DATA.__data` | `0x578c` | `0x561c` | **`-0x170`** |
| `__TEXT.__oslogstring` | `0xa002` | `0xa152` | **`+0x150`** |
| `__AUTH.__objc_data` | `0x40a8` | `0x4008` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x4028` | `0x40c8` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x24840` | `0x24898` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x10110` | `0x10168` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x48f0` | `0x4944` | **`+0x54`** |
| `__DATA_CONST.__const` | `0x6488` | `0x64d8` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xc400` | `0xc3c0` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0x4730` | `0x46f0` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x173e8` | `0x17428` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x9b90` | `0x9bd0` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x31a0` | `0x31d0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x2e90` | `0x2ea0` | **`+0x10`** |
| `__TEXT.__const` | `0x9d64` | `0x9d54` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x1248` | `0x124c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2991.0.0.0.0
+2996.0.0.0.0

-  Functions: 14839
-  Symbols:   15986
-  CStrings:  3249
+  Functions: 14844
+  Symbols:   15995
+  CStrings:  3252
Symbols:
+ -[ICReindexEverythingBackgroundTask isRunningFullReindex]
+ -[ICReindexEverythingBackgroundTask rescheduleAndCallCompletion:error:]
+ -[ICReindexEverythingBackgroundTask runFullReindexResettingEverything:attachments:completion:]
+ -[ICReindexEverythingBackgroundTask setIsRunningFullReindex:]
+ _ICUseCoreDataCoreSpotlightIntegration
+ _OBJC_CLASS_$_ICReindexer
+ _OBJC_IVAR_$_ICReindexEverythingBackgroundTask._isRunningFullReindex
+ __OBJC_$_INSTANCE_VARIABLES_ICReindexEverythingBackgroundTask
+ ___74-[ICThumbnailGeneratorNote generateThumbnailWithConfiguration:completion:]_block_invoke_3
+ ___94-[ICReindexEverythingBackgroundTask runFullReindexResettingEverything:attachments:completion:]_block_invoke
+ ___block_descriptor_48_e8_32bs40w_e20_v20?0B8"NSError"12lw40l8s32l8
+ ___block_descriptor_50_e8_32bs40w_e17_v16?0"NSError"8lw40l8s32l8
+ ___swift_mutable_project_boxed_opaque_existential_1
+ _kICReindexAttachmentsOnLaunchKey
+ _swift_makeBoxUnique
- +[ICDeviceSupport(UI) shouldShowWritingToolsButton]
- -[ICTodoButton(PlatformSpecificResponsibility) setHighlighted:]
- _OBJC_CLASS_$_WTAvailability
- ___51+[ICDeviceSupport(UI) shouldShowWritingToolsButton]_block_invoke
- _shouldShowWritingToolsButton.onceToken
- _shouldShowWritingToolsButton.shouldShowExplicitWritingToolsButton
CStrings:
+ "Reindex BG task: CoreData/CoreSpotlight integration enabled; nothing to do"
+ "Reindex BG task: client state indicates a stale index; running full reindex"
+ "Reindex BG task: indexed pending items"
+ "Reindex BG task: indexing pending items failed, will retry on next wake. error: %@"
+ "Reindex BG task: no pending reindex, index is current, no pending items; rescheduling and exiting"
+ "Reindex BG task: running full reindex (everything: %@, attachments: %@)"
+ "Renamed linked section heading"
- "Reindex BG task: no pending reindex; rescheduling and exiting"
- "Reindex BG task: running deferred reindex"
- "completed: %@"
- "incomplete: %@"
```
