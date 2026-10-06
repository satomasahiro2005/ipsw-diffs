## IMTransferAgent

> `/System/Library/PrivateFrameworks/IMTransferServices.framework/IMTransferAgent.app/IMTransferAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2efc` | `0x2f1c` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x550` | `0x560` | **`+0x10`** |
| `__TEXT.__cstring` | `0x5dc` | `0x5e5` | **`+0x9`** |
| `__TEXT.__objc_methname` | `0x392` | `0x39b` | **`+0x9`** |
| `__DATA_CONST.__auth_got` | `0x2b8` | `0x2c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Symbols:   103
-  CStrings:  136
+  Symbols:   104
+  CStrings:  137
Symbols:
+ _xpc_dictionary_get_int64
Functions:
~ sub_10000160c : 5208 -> 5240
CStrings:
+ "priority"
+ "receiveFileTransfer:topic:path:requestURLString:ownerID:senderExemptFromLDM:signature:fileSize:decryptionKey:sourceAppID:priority:progressBlock:completionBlock:"
- "receiveFileTransfer:topic:path:requestURLString:ownerID:senderExemptFromLDM:signature:fileSize:decryptionKey:sourceAppID:progressBlock:completionBlock:"
```
