## TextUnderstandingRuntime

> `/System/Library/PrivateFrameworks/TextUnderstandingRuntime.framework/TextUnderstandingRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2377dc` | `0x236b7c` | **`-0xc60`** |
| `__TEXT.__eh_frame` | `0x158a4` | `0x15674` | **`-0x230`** |
| `__AUTH.__data` | `0xf78` | `0x1008` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x97ca` | `0x974a` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0x7768` | `0x7710` | **`-0x58`** |
| `__TEXT.__cstring` | `0x50d2` | `0x5082` | **`-0x50`** |
| `__TEXT.__swift_as_cont` | `0xd48` | `0xd00` | **`-0x48`** |
| `__DATA.__data` | `0x2f80` | `0x2fc0` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x1d5c` | `0x1d9c` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xed0` | `0xf08` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x2f6c` | `0x2f3c` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x41e8` | `0x4208` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0xeac8` | `0xead8` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x3538` | `0x3528` | **`-0x10`** |
| `__TEXT.__const` | `0x12b88` | `0x12b98` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3f78` | `0x3f6c` | **`-0xc`** |
| `__TEXT.__swift_as_entry` | `0x58c` | `0x580` | **`-0xc`** |
| `__TEXT.__swift_as_ret` | `0x774` | `0x76c` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x374c` | `0x3748` | **`-0x4`** |
| `__TEXT.__swift5_typeref` | `0x4d3d` | `0x4d3b` | **`-0x2`** |

### Other Changes

```diff

-176.3.0.0.0
+176.3.0.1.0

-  Functions: 12182
-  Symbols:   591
-  CStrings:  1001
+  Functions: 12172
+  Symbols:   575
+  CStrings:  998
Symbols:
+ _swift_getFunctionTypeMetadata0
- _MDItemAccountHandles
- _MDItemAccountIdentifier
- _MDItemAccountType
- _MDItemAdditionalRecipientEmailAddresses
- _MDItemAuthorEmailAddresses
- _MDItemContentType
- _MDItemHiddenAdditionalRecipientEmailAddresses
- _MDItemMailCategories
- _MDItemPrimaryRecipientEmailAddresses
- _MDItemProviderDataTypes
- _MDItemRecipientEmailAddresses
- _MDItemRecipients
- _MDItemSubject
- _MDMailMessageHeader
- _MDMailMessageID
- _swift_deallocUninitializedObject
- _swift_release_x6
CStrings:
+ "MailSmartRepliesProfileProcessor: Fetched %ld emails from Mail"
- "MailSmartRepliesProfileProcessor: Fetched %ld emails from Spotlight, %ld from Mail"
- "MailSmartRepliesProfileProcessor: Fetched %ld items from Spotlight, converting to emails"
- "kMDItemAuthorEmailAddresses=='"
- "kMDItemPrimaryRecipientEmailAddresses=='"
```
