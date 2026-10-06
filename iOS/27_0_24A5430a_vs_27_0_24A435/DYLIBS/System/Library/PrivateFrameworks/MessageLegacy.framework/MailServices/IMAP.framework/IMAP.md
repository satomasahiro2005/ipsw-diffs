## IMAP

> `/System/Library/PrivateFrameworks/MessageLegacy.framework/MailServices/IMAP.framework/IMAP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c4d4` | `0x3c498` | **`-0x3c`** |

### Other Changes

```text
Functions:
~ _OUTLINED_FUNCTION_1 -> _OUTLINED_FUNCTION_3 : 12 -> 20
~ -[MFIMAPCommandPipeline failureResponsesFromSendingCommandsWithConnection:] : 1376 -> 1324
~ _OUTLINED_FUNCTION_2 -> _OUTLINED_FUNCTION_1 : 20 -> 12
~ -[CastleIMAPAccount authTokenWithError:].cold.1 : 152 -> 156
~ -[CastleIMAPAccount handleOverQuotaResponse:].cold.1 : 72 -> 64
~ -[CastleIMAPAccount _updateEmailAddressAndAliases].cold.2 : 100 -> 104
~ -[CastleIMAPAccount _updateEmailAddressAndAliases].cold.3 : 84 -> 76
```
