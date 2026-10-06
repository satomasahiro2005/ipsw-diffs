## BarcodeSupport

> `/System/Library/PrivateFrameworks/BarcodeSupport.framework/BarcodeSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3487c` | `0x3484c` | **`-0x30`** |

### Other Changes

```text
Functions:
~ ___57-[BCSQRCodeParser parseCodeFromString:completionHandler:]_block_invoke.cold.1 : 64 -> 56
~ ___57-[BCSQRCodeParser parseCodeFromString:completionHandler:]_block_invoke.13.cold.1 : 64 -> 56
~ ___72-[BCSQRCodeParser postNotificationAfterParsingCodeFromImage:completion:]_block_invoke.cold.1 : 64 -> 56
~ ___81-[BCSQRCodeParser startQRCodeParsingSessionWithMetadataObject:completionHandler:]_block_invoke_3.cold.1 : 92 -> 84
~ -[BCSQRCodeParser _parseMetadataObject:reply:completionHandler:].cold.2 : 68 -> 60
~ ___64-[BCSQRCodeParser _parseMetadataObject:reply:completionHandler:]_block_invoke.18.cold.1 : 68 -> 60
```
