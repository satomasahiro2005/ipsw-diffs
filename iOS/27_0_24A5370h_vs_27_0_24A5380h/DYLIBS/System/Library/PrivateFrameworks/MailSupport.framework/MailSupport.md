## MailSupport

> `/System/Library/PrivateFrameworks/MailSupport.framework/MailSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x260` | `0x120` | **`-0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x10d8` | `0x1218` | **`+0x140`** |
| `__DATA.__data` | `0xbb8` | `0xb78` | **`-0x40`** |
| `__TEXT.__text` | `0x225c4` | `0x225f8` | **`+0x34`** |
| `__AUTH_CONST.__objc_const` | `0x44b8` | `0x4488` | **`-0x30`** |
| `__DATA_DIRTY.__data` | `0x430` | `0x458` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x19c0` | `0x19b0` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x6a0` | `0x6a8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1560` | `0x1568` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1678` | `0x1670` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1c0` | `0x1bc` | **`-0x4`** |

### Other Changes

```diff

-3893.100.7.0.0
+3895.100.17.2.1

+  - /usr/lib/swift/libswiftCompression.dylib

-  Symbols:   2032
+  Symbols:   2033
Symbols:
+ +[MSParsecSearchIndexState indexStateForMessagesIndexed:messageBodiesIndexed:indexableMessages:attachmentsIndexed:indexableAttachments:]
+ -[MSParsecSearchIndexState initWithPercentMessagesIndexed:percentMessageBodiesIndexed:percentAttachmentsIndexed:totalMessageCount:indexedMessageCount:indexType:]
+ GCC_except_table51
+ GCC_except_table57
+ GCC_except_table60
+ _EMIsEnhancedSiriAvailable
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_MailSupport
- +[MSParsecSearchIndexState indexStateForMessagesIndexed:messageBodiesIndexed:indexableMessages:percentUnindexedBodiesInFrecent:attachmentsIndexed:indexableAttachments:]
- -[MSParsecSearchIndexState initWithPercentMessagesIndexed:percentMessageBodiesIndexed:percentUnindexedBodiesInFrecent:percentAttachmentsIndexed:totalMessageCount:indexedMessageCount:indexType:]
- -[MSParsecSearchIndexState percentUnindexedBodiesInFrecent]
- GCC_except_table52
- GCC_except_table59
- GCC_except_table61
- _OBJC_IVAR_$_MSParsecSearchIndexState._percentUnindexedBodiesInFrecent
```
