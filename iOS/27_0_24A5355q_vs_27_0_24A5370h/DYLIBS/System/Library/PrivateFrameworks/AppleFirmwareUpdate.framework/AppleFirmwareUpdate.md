## AppleFirmwareUpdate

> `/System/Library/PrivateFrameworks/AppleFirmwareUpdate.framework/AppleFirmwareUpdate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa158` | `0xa13c` | **`-0x1c`** |
| `__DATA_CONST.__const` | `0xdd8` | `0xde8` | **`+0x10`** |
| `__TEXT.__const` | `0xd710` | `0xd718` | **`+0x8`** |

### Other Changes

```diff

-1576.0.0.0.0
+1587.0.3.0.3

-  Symbols:   1033
+  Symbols:   1035
Symbols:
+ __oidSmtpUTF8Mailbox
+ _oidSmtpUTF8Mailbox
Functions:
~ -[AppleFirmwareUpdateController registerForPendingEarlyBootAccessoriesInternal] : 552 -> 548
~ -[AppleFirmwareUpdateController findFWAssetFromTag:tag:size:] : 1456 -> 1452
~ -[AppleFirmwareUpdateController sendFDRData:] : 908 -> 888
~ _verify_chain_img4_v1 : 720 -> 724
~ _verify_chain_img4_ec_v1 : 432 -> 436
~ _parse_ec_chain : 592 -> 588
~ -[AppleFirmwareUpdateController createFWAssetInfoInternal] : 1468 -> 1464
```
