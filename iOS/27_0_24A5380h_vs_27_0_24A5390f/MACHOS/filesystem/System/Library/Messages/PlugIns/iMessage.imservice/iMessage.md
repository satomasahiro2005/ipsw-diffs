## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/iMessage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x109a88` | `0x10a50c` | **`+0xa84`** |
| `__TEXT.__oslogstring` | `0x1c40b` | `0x1c51b` | **`+0x110`** |
| `__TEXT.__objc_methname` | `0x14de2` | `0x14e7e` | **`+0x9c`** |
| `__DATA_CONST.__const` | `0x53e0` | `0x5458` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x9a40` | `0x9a84` | **`+0x44`** |
| `__TEXT.__objc_stubs` | `0xeae0` | `0xeb20` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3e4d` | `0x3e7d` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2bb8` | `0x2bd8` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x4178` | `0x4188` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3064` | `0x3074` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1358` | `0x1360` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x9b4` | `0x9b8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1486.100.5.2.1
+1487.100.6.2.2

-  Functions: 2406
+  Functions: 2417

-  CStrings:  5297
+  CStrings:  5302
CStrings:
+ "Comm-safety analysis returned no result for transfer %@, proceeding with send. error: %@. %@"
+ "Not sending gradient for message %@, comm-safety blocked the send. %@"
+ "Send failure for collaboration message guid %@ to %@ after already completing the send (reason: %u)."
+ "_analyzeAcquiredAttachmentsForSensitiveContentForMessage:chatIdentifier:completion:"
+ "_generateAndAttachGradientsForMessage:completion:"
+ "analyzeContent:ofType:isFromMe:completionHandler:"
+ "analyzeContent:withIdentifier:chatID:isFromMe:completionHandler:"
+ "checkExistingAttachmentSensitivityIfNeededFor:attachmentURL:isFromMe:completion:"
+ "decisioningMetadata"
+ "updateSpamModelMetadataWith:wasJunk:isJunk:"
- "_generateGradientsForMessage:completion:"
- "analyzeContent:ofType:completionHandler:"
- "analyzeContent:withIdentifier:chatID:completionHandler:"
- "checkExistingAttachmentSensitivityIfNeededFor:attachmentURL:isFromMe:"
- "setSpamModelMetadata:"
```
