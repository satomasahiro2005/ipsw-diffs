## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/iMessage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x116a80` | `0x116c2c` | **`+0x1ac`** |
| `__TEXT.__objc_methname` | `0x1603e` | `0x160be` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x5618` | `0x5640` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x43f0` | `0x43f8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x348c` | `0x3494` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2d28` | `0x2d30` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
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
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1491.200.73.0.0
+1491.200.95.0.0

-  Functions: 2553
+  Functions: 2555

-  CStrings:  5501
+  CStrings:  5502
CStrings:
+ "receiveFileTransfer:transferGUID:topic:path:requestURLString:ownerID:signature:decryptionKey:fileSize:balloonBundleID:senderContext:senderID:priority:replaceExistingPreview:progressBlock:completionBlock:"
+ "resolveBalloonPluginAttachmentPayload:forMessageGUID:balloonBundleID:fromIdentifier:isFromMe:senderToken:completion:"
- "receiveFileTransfer:transferGUID:topic:path:requestURLString:ownerID:signature:decryptionKey:fileSize:balloonBundleID:senderContext:senderID:priority:progressBlock:completionBlock:"
```
