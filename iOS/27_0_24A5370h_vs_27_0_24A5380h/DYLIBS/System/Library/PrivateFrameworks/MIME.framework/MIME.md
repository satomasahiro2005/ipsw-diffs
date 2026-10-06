## MIME

> `/System/Library/PrivateFrameworks/MIME.framework/MIME`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x343fc` | `0x34424` | **`+0x28`** |
| `__DATA_DIRTY.__bss` | `0x101` | `0xf9` | **`-0x8`** |

### Other Changes

```diff

-3893.100.7.0.0
+3895.100.17.2.1
Functions:
~ _MFCreateStringWithBytes : 1104 -> 1096
~ +[NSDate(MFDateUtils) mf_copyDateInCommonFormatsWithString:] : 2504 -> 2516
~ _copyMutablePlainTextFromPoint : 4040 -> 4056
~ -[MFBase64Encoder appendData:] : 1052 -> 1088
~ -[NSMutableData(RFC2231Support) mf_appendRFC2231CompliantValue:forKey:] : 1436 -> 1432
~ -[MFDataMessageStore bodyDataForMessage:isComplete:isPartial:downloadIfNecessary:] : 372 -> 364
~ __ZN12DecodeBuffer11parseHeaderEv : 240 -> 236
```
