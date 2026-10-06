## POP

> `/System/Library/PrivateFrameworks/Message.framework/MailServices/POP.framework/POP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8bd0` | `0x8b94` | **`-0x3c`** |
| `__TEXT.__gcc_except_tab` | `0x13e4` | `0x13dc` | **`-0x8`** |

### Other Changes

```diff

-3891.100.17.2.4
+3893.100.7.0.0
Functions:
~ -[MFLibraryPOPStore messagesWereDeleted:] : 436 -> 432
~ -[MFLibraryPOPStore _handleFlagsChangedForMessages:flags:oldFlagsByMessage:] : 560 -> 556
~ -[MFPOPDownloadQueue handleItems:] : 872 -> 868
~ -[MFPOP3Connection authenticationMechanisms] : 552 -> 548
~ -[MFPOP3Connection _getStatusFromReply] : 1236 -> 1180
~ -[MFPOP3Connection _apopWithUsername:password:] : 628 -> 640
```
