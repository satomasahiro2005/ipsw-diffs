## ADFollowUpExtension

> `/System/Library/ExtensionKit/Extensions/ADFollowUpExtension.appex/ADFollowUpExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19790` | `0x1a42c` | **`+0xc9c`** |
| `__TEXT.__auth_stubs` | `0x14f0` | `0x1580` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0xa9d` | `0xb2d` | **`+0x90`** |
| `__TEXT.__cstring` | `0x5cb` | `0x64b` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x698` | `0x718` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x1851` | `0x18b1` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x12c0` | `0x1320` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x678` | `0x6c8` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0xa88` | `0xad0` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x4f8` | `0x520` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x2d0` | `0x2f0` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x7f1` | `0x811` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x670` | `0x688` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x15c` | `0x174` | **`+0x18`** |
| `__DATA.__objc_data` | `0x758` | `0x768` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x4a0` | `0x4b0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x4f0` | `0x4fc` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4.0.30.0.0
+4.0.33.0.0

-  Functions: 352
-  Symbols:   243
-  CStrings:  391
+  Functions: 363
+  Symbols:   249
+  CStrings:  399
Symbols:
+ _OBJC_CLASS_$_UIAlertAction
+ _OBJC_CLASS_$_UIAlertController
+ _swift_isEscapingClosureAtFileLocation
+ _swift_release_x9
+ _swift_retain_x26
+ _swift_task_getMainExecutor
+ _swift_task_isCurrentExecutor
- _swift_retain_x23
CStrings:
+ "ADFollowUpExtension/ConfirmationSheetViewController.swift"
+ "Incorrect actor executor assumption; Expected same executor as "
+ "[%s] Alternative distribution is unsupported in a virtual machine"
+ "[%s] Install reported a failure; dismissing confirmation sheet"
+ "actionWithTitle:style:handler:"
+ "addAction:"
+ "alertControllerWithTitle:message:preferredStyle:"
+ "v16@?0@\"UIAlertAction\"8"
```
