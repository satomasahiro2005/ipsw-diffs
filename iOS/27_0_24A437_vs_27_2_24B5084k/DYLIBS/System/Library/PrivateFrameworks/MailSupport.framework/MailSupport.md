## MailSupport

> `/System/Library/PrivateFrameworks/MailSupport.framework/MailSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22de0` | `0x22e94` | **`+0xb4`** |
| `__TEXT.__gcc_except_tab` | `0x280c` | `0x283c` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x628` | `0x608` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x4488` | `0x4468` | **`-0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x168` | `0x180` | **`+0x18`** |
| `__DATA.__data` | `0xbe8` | `0xbd0` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1678` | `0x1688` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1a0` | `0x190` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x458` | `0x468` | **`+0x10`** |
| `__TEXT.__cstring` | `0x4ddb` | `0x4dcb` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x19b0` | `0x19c0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x10c8` | `0x10d8` | **`+0x10`** |
| `__DATA.__bss` | `0x348` | `0x350` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x558` | `0x560` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x108` | `0x110` | **`+0x8`** |

### Other Changes

```diff

-3901.100.1.2.14
+3901.200.34.0.0

-  Functions: 978
+  Functions: 975

-  CStrings:  726
+  CStrings:  727
Symbols:
+ +[MSCustomProtocolURLSchemeHandler handlerForURLScheme:]
+ -[MSCustomProtocolURLSchemeHandler .cxx_destruct]
+ -[MSCustomProtocolURLSchemeHandler initWithAllowedScheme:]
+ -[MSParsecSearchIndexState initWithPercentMessagesIndexed:percentMessageBodiesIndexed:percentAttachmentsIndexed:totalMessageCount:indexedMessageCount:]
+ GCC_except_table50
+ GCC_except_table56
+ GCC_except_table59
+ _NSURLErrorDomain
+ _OBJC_CLASS_$_NSError
+ _OBJC_IVAR_$_MSCustomProtocolURLSchemeHandler._allowedScheme
+ __OBJC_$_INSTANCE_VARIABLES_MSCustomProtocolURLSchemeHandler
- +[MSCustomProtocolURLSchemeHandler sharedHandler]
- -[MSParsecSearchIndexState indexType]
- -[MSParsecSearchIndexState initWithPercentMessagesIndexed:percentMessageBodiesIndexed:percentAttachmentsIndexed:totalMessageCount:indexedMessageCount:indexType:]
- GCC_except_table51
- GCC_except_table58
- GCC_except_table60
- _OBJC_IVAR_$_MSParsecSearchIndexState._indexType
- __OBJC_$_CLASS_PROP_LIST_MSCustomProtocolURLSchemeHandler
- ___49+[MSCustomProtocolURLSchemeHandler sharedHandler]_block_invoke
- _sharedHandler.handler
- _sharedHandler.onceToken
CStrings:
+ "i"
+ "percentMessagesIndexed: %ld percentMessageBodiesIndexed: %ld percentAttachmentsIndexed: %ld totalMessageCount: %ld indexedMessageCount: %ld "
- "indexType: %ld percentMessagesIndexed: %ld percentMessageBodiesIndexed: %ld percentAttachmentsIndexed: %ld totalMessageCount: %ld indexedMessageCount: %ld "
```
