## NotesAppMigrationExtension

> `/private/var/staged_system_apps/MobileNotes.app/Extensions/NotesAppMigrationExtension.appex/NotesAppMigrationExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ef78` | `0x8320c` | **`+0x4294`** |
| `__TEXT.__eh_frame` | `0x2ff8` | `0x3568` | **`+0x570`** |
| `__TEXT.__auth_stubs` | `0x2020` | `0x2260` | **`+0x240`** |
| `__TEXT.__const` | `0x56c4` | `0x58d4` | **`+0x210`** |
| `__DATA_CONST.__auth_got` | `0x1018` | `0x1138` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0xf06` | `0x1026` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x19c0` | `0x1ad0` | **`+0x110`** |
| `__DATA_CONST.__got` | `0x650` | `0x748` | **`+0xf8`** |
| `__DATA_CONST.__auth_ptr` | `0x650` | `0x738` | **`+0xe8`** |
| `__DATA_CONST.__const` | `0x3eb8` | `0x3fa0` | **`+0xe8`** |
| `__TEXT.__swift5_typeref` | `0x18eb` | `0x19a9` | **`+0xbe`** |
| `__TEXT.__objc_methname` | `0x1fcc` | `0x2086` | **`+0xba`** |
| `__DATA.__bss` | `0xa080` | `0xa110` | **`+0x90`** |
| `__DATA.__data` | `0x2320` | `0x2390` | **`+0x70`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x78` | **`+0x54`** |
| `__TEXT.__swift_as_ret` | `0x20` | `0x6c` | **`+0x4c`** |
| `__TEXT.__swift5_capture` | `0x55c` | `0x5a4` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0x2e20` | `0x2e60` | **`+0x40`** |
| `__TEXT.__cstring` | `0xb34` | `0xb64` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1062` | `0x1092` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0xd8c` | `0xdb0` | **`+0x24`** |
| `__TEXT.__swift_as_cont` | `0x1c` | `0x40` | **`+0x24`** |
| `__DATA.__objc_const` | `0x5a0` | `0x5c0` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x29b` | `0x2bb` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1ab8` | `0x1ad4` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0xbe8` | `0xbf8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x524` | `0x528` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x160` | `0x164` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-2985.0.0.202.2
+2991.0.0.0.0

+  - /System/Library/PrivateFrameworks/ToolKit.framework/ToolKit

-  Functions: 2109
-  Symbols:   278
-  CStrings:  609
+  Functions: 2166
+  Symbols:   281
+  CStrings:  619
Symbols:
+ _ICAttachmentUTTypeGallery
+ _ICAttachmentUTTypePaperDocumentPDF
+ _ICAttachmentUTTypePaperDocumentScan
+ _ICAttachmentUTTypeSystemPaper
- _swift_retain_x27
CStrings:
+ "GenerateFallbackPDF tool not found in ToolDatabase; skipping %ld attachments"
+ "com.apple.mobilenotes.GenerateFallbackPDF"
+ "enumerateAttachmentsInContext:batchSize:visibleOnly:saveAfterBatch:usingBlock:"
+ "failed to generate fallback PDF for %s: %@"
+ "failed to start ToolKit session: %@; skipping %ld attachments"
+ "fallbackPDFGenerationFailures"
+ "no attachments need fallback PDF generation"
+ "requesting host to generate %ld fallback PDFs"
+ "transcriptAsPlainTextWithoutSpeakerLabels"
+ "v24@?0@\"ICAttachment\"8^B16"
```
