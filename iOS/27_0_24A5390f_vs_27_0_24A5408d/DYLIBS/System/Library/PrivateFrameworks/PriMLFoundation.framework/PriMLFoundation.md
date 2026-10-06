## PriMLFoundation

> `/System/Library/PrivateFrameworks/PriMLFoundation.framework/PriMLFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70aa4` | `0x7571c` | **`+0x4c78`** |
| `__TEXT.__eh_frame` | `0x35e8` | `0x3a20` | **`+0x438`** |
| `__TEXT.__oslogstring` | `0x1abd` | `0x1ccd` | **`+0x210`** |
| `__AUTH_CONST.__const` | `0x2730` | `0x28f8` | **`+0x1c8`** |
| `__TEXT.__const` | `0x3d28` | `0x3ea8` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x18b8` | `0x19f0` | **`+0x138`** |
| `__AUTH_CONST.__objc_const` | `0x2350` | `0x2468` | **`+0x118`** |
| `__AUTH.__data` | `0x11b0` | `0x1258` | **`+0xa8`** |
| `__TEXT.__swift5_fieldmd` | `0x1418` | `0x14b4` | **`+0x9c`** |
| `__TEXT.__constg_swiftt` | `0x1254` | `0x12d8` | **`+0x84`** |
| `__TEXT.__swift5_reflstr` | `0x1161` | `0x11e1` | **`+0x80`** |
| `__TEXT.__cstring` | `0x806` | `0x882` | **`+0x7c`** |
| `__AUTH_CONST.__auth_got` | `0xc88` | `0xce8` | **`+0x60`** |
| `__DATA.__data` | `0x910` | `0x968` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0xfa8` | `0xfde` | **`+0x36`** |
| `__TEXT.__swift_as_cont` | `0x260` | `0x294` | **`+0x34`** |
| `__TEXT.__swift5_capture` | `0x25c` | `0x27c` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x124` | `0x140` | **`+0x1c`** |
| `__DATA_DIRTY.__data` | `0xcb0` | `0xcc8` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x114` | `0x12c` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x13c` | `0x148` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x110` | `0x118` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x270` | `0x278` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x240` | `0x248` | **`+0x8`** |

### Other Changes

```diff

-38.0.0.0.0
+42.0.0.0.0

-  Functions: 1953
-  Symbols:   686
-  CStrings:  188
+  Functions: 2025
+  Symbols:   699
+  CStrings:  199
Symbols:
+ __DATA__TtC15PriMLFoundation14LocalStoreSink
+ __IVARS__TtC15PriMLFoundation14LocalStoreSink
+ __METACLASS_DATA__TtC15PriMLFoundation14LocalStoreSink
+ _swift_deallocPartialClassInstance
+ _swift_release_x9
+ _swift_retain_x26
+ _swift_task_localValueGet
+ _symbolic SaySJG
+ _symbolic _____ 15PriMLFoundation14LocalStoreSinkC
+ _symbolic _____ 15PriMLFoundation16FailedTaskResultV
+ _symbolic _____ 15PriMLFoundation20TaskExecutionContextO
+ _symbolic _____ySJG s23_ContiguousArrayStorageC
+ _symbolic _____y______pSgG s9TaskLocalC 15PriMLFoundation0A10DownloaderP
+ _type_layout_string 15PriMLFoundation16FailedTaskResultV
- _swift_release_x10
CStrings:
+ "Recipe collectionIdPrefix '%s' is not prefixed by plugin '%s'"
+ "Recipe for PFL/ETL task %s is missing `collectionIdPrefix`; falling back to plugin[:useCase]."
+ "Recipe for fedStats task %s is missing `clientIdentifier`; falling back to plugin[:useCase]."
+ "[LocalStoreSink] Failed to store task result at %s: %@"
+ "[LocalStoreSink] Stored task result under %s"
+ "[PriMLPlugin] Skipping failure sink fan-out: task.taskId '%s' is not a parseable TaskId"
+ "[PriMLPlugin] handleFailure for task %s itself failed: %@."
+ "error_description"
+ "failureSubmission"
+ "skip_crash_record_check"
+ "task_result_store_path"
```
