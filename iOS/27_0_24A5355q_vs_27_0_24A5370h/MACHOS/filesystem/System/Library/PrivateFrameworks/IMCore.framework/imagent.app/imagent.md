## imagent

> `/System/Library/PrivateFrameworks/IMCore.framework/imagent.app/imagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5efb4` | `0x5fd88` | **`+0xdd4`** |
| `__DATA.__objc_data` | `0xfd8` | `0x1098` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x1770` | `0x1828` | **`+0xb8`** |
| `__DATA.__data` | `0x1708` | `0x17a8` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x3208` | `0x32a8` | **`+0xa0`** |
| `__TEXT.__const` | `0x1960` | `0x1a00` | **`+0xa0`** |
| `__DATA.__bss` | `0x1260` | `0x12e0` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x23c0` | `0x2440` | **`+0x80`** |
| `__TEXT.__objc_classname` | `0x995` | `0x9f5` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x6adb` | `0x6b3b` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x748` | `0x7a8` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1cd8` | `0x1d38` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x3280` | `0x32d8` | **`+0x58`** |
| `__TEXT.__objc_methname` | `0xc749` | `0xc799` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x8a8` | `0x8f4` | **`+0x4c`** |
| `__TEXT.__auth_stubs` | `0x1a70` | `0x1aa0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xad8` | `0xaf8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x17cc` | `0x17ec` | **`+0x20`** |
| `__DATA.__common` | `0xf0` | `0x108` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xd48` | `0xd60` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x100` | `0x114` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0xe8` | `0xfc` | **`+0x14`** |
| `__TEXT.__swift5_typeref` | `0x914` | `0x926` | **`+0x12`** |
| `__DATA.__objc_selrefs` | `0x2b88` | `0x2b98` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x308` | `0x318` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x1f8` | `0x208` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x3375` | `0x3385` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3ac` | `0x3bc` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x138` | `0x140` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xf8` | `0x100` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x10c` | `0x114` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x100` | `0x104` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x74` | `0x78` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

-  Functions: 1480
-  Symbols:   617
-  CStrings:  2535
+  Functions: 1505
+  Symbols:   620
+  CStrings:  2543
Symbols:
+ _IMDFileTransferExplicitDownloadCompletedGUIDKey
+ _OBJC_CLASS_$_IMChatForkingReport
+ _OBJC_CLASS_$_IMChatForkingRequest
CStrings:
+ "22:45:02"
+ "Auto-enrolling in SMS relay"
+ "IMDaemonDiagnosticTasksProtocol"
+ "Jun 18 2026"
+ "MiC is disabled, so no need to enroll device for SMS relay."
+ "SMS Relay Enrollment"
+ "_TtC7imagent29DiagnosticTasksRequestHandler"
+ "generateChatForkingReportsFromRequests:completionHandler:"
+ "imagent1"
+ "storeRecoverableMessagePartWithBody:forMessageWithGUID:deleteDate:fromSync:"
+ "updateChatWithMessageItem:"
- "21:34:40"
- "May 29 2026"
- "storeRecoverableMessagePartWithBody:forMessageWithGUID:deleteDate:"
```
