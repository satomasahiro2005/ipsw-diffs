## IMAP

> `/System/Library/PrivateFrameworks/MessageLegacy.framework/MailServices/IMAP.framework/IMAP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c4ac` | `0x3c4d4` | **`+0x28`** |

### Other Changes

```text
Functions:
~ -[IMAPAccount setStoreMailboxType:onServer:] : 224 -> 232
~ -[MFIMAPConnection _readDataOfLength:] : 324 -> 320
~ _MFMessageFlagsFromArray : 348 -> 352
~ _status_response : 620 -> 628
~ _fetch_response : 2780 -> 2804
```
