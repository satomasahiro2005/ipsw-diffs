## Logging

> `/System/Library/Trace/Providers/Logging.bundle/Logging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa928` | `0xaeb4` | **`+0x58c`** |
| `__TEXT.__cstring` | `0x19ea` | `0x1c75` | **`+0x28b`** |
| `__DATA.__objc_data` | `0x890` | `0x950` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x920` | `0x9b0` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x5c8` | `0x618` | **`+0x50`** |
| `__TEXT.__const` | `0x912` | `0x95e` | **`+0x4c`** |
| `__TEXT.__constg_swiftt` | `0x358` | `0x394` | **`+0x3c`** |
| `__DATA.__data` | `0x4b8` | `0x4e8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x590` | `0x5c0` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x236` | `0x25b` | **`+0x25`** |
| `__TEXT.__unwind_info` | `0x3e0` | `0x400` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x2e0` | `0x2fc` | **`+0x1c`** |
| `__TEXT.__auth_stubs` | `0xa70` | `0xa80` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x540` | `0x548` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x332` | `0x338` | **`+0x6`** |
| `__TEXT.__swift5_proto` | `0x60` | `0x64` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x3c` | `0x40` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-196.0.0.0.0
+202.0.0.0.0

-  Functions: 371
-  Symbols:   128
-  CStrings:  199
+  Functions: 388
+  Symbols:   129
+  CStrings:  209
Symbols:
+ _objc_retain_x24
CStrings:
+ "(subsystem == \"com.apple.FoundationModels\" AND (category == \"Instrument\" OR category == \"session\" OR category == \"InstrumentSignpost\")) OR (subsystem == \"com.apple.modelmanager\" AND category == \"OSSignPoster\")"
+ "Foundation Models instrumentation"
+ "FoundationModels"
+ "InstrumentSignpost"
+ "Logging.FoundationModelsDataCategory"
+ "The 'FoundationModels' data category contains `os_signpost` instrumentation describing\nFoundation Models session, inference, tool call, and model loading events."
+ "_TtC7Logging28FoundationModelsDataCategory"
+ "com.apple.FoundationModels"
+ "com.apple.modelmanager"
+ "foundation-models"
```
