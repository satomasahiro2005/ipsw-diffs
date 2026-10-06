## Silex

> `/System/Library/PrivateFrameworks/Silex.framework/Silex`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x118e50` | `0x118264` | **`-0xbec`** |
| `__AUTH_CONST.__objc_const` | `0x51de8` | `0x51c78` | **`-0x170`** |
| `__TEXT.__objc_methlist` | `0x1e6cc` | `0x1e63c` | **`-0x90`** |
| `__DATA.__data` | `0x9fb8` | `0x9f58` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x3c80` | `0x3c30` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xf118` | `0xf0c8` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x4f30` | `0x4ef8` | **`-0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0xb848` | `0xb818` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x3ca0` | `0x3c80` | **`-0x20`** |
| `__TEXT.__cstring` | `0xa0ba` | `0xa09c` | **`-0x1e`** |
| `__TEXT.__gcc_except_tab` | `0x2444` | `0x2430` | **`-0x14`** |
| `__AUTH_CONST.__auth_got` | `0x7d8` | `0x7c8` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x1e8` | `0x1d8` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x1fb4` | `0x1fac` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x2568` | `0x2560` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1cf0` | `0x1ce8` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xd38` | `0xd30` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1040` | `0x1038` | **`-0x8`** |

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

-  Functions: 8574
-  Symbols:   20689
-  CStrings:  1845
+  Functions: 8559
+  Symbols:   20654
+  CStrings:  1844
Symbols:
+ -[SXVideoProvider playbackSkippedFromTime:toTime:]
- +[SXDocumentTextContentProvider sharedQueue]
- -[SXContext textContentProvider]
- -[SXDocumentTextContentProvider .cxx_destruct]
- -[SXDocumentTextContentProvider classification:isValidForType:]
- -[SXDocumentTextContentProvider contentRelevance:isValidForType:]
- -[SXDocumentTextContentProvider document]
- -[SXDocumentTextContentProvider initWithDocument:]
- -[SXDocumentTextContentProvider textContentForComponent:withType:]
- -[SXDocumentTextContentProvider textContentForComponents:withType:]
- -[SXDocumentTextContentProvider textContentForType:onCompletion:]
- _OBJC_CLASS_$_SXDocumentTextContentProvider
- _OBJC_IVAR_$_SXContext._textContentProvider
- _OBJC_IVAR_$_SXDocumentTextContentProvider._document
- _OBJC_METACLASS_$_SXDocumentTextContentProvider
- __OBJC_$_CLASS_METHODS_SXDocumentTextContentProvider
- __OBJC_$_INSTANCE_METHODS_SXDocumentTextContentProvider
- __OBJC_$_INSTANCE_VARIABLES_SXDocumentTextContentProvider
- __OBJC_$_PROP_LIST_SXDocumentTextContentProvider
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_SXTextContentProvider
- __OBJC_$_PROTOCOL_METHOD_TYPES_SXTextContentProvider
- __OBJC_$_PROTOCOL_REFS_SXTextContentProvider
- __OBJC_CLASS_PROTOCOLS_$_SXDocumentTextContentProvider
- __OBJC_CLASS_RO_$_SXDocumentTextContentProvider
- __OBJC_LABEL_PROTOCOL_$_SXTextContentProvider
- __OBJC_METACLASS_RO_$_SXDocumentTextContentProvider
- __OBJC_PROTOCOL_$_SXTextContentProvider
- ___44+[SXDocumentTextContentProvider sharedQueue]_block_invoke
- ___65-[SXDocumentTextContentProvider textContentForType:onCompletion:]_block_invoke
- ___65-[SXDocumentTextContentProvider textContentForType:onCompletion:]_block_invoke_2
- ___65-[SXDocumentTextContentProvider textContentForType:onCompletion:]_block_invoke_3
- ___block_descriptor_40_e8_32bs_e5_v8?0ls32l8
- ___block_descriptor_56_e8_32bs40w_e5_v8?0lw40l8s32l8
- _dispatch_queue_attr_make_with_qos_class
- _dispatch_queue_create
- _sharedQueue.onceToken
- _sharedQueue.sharedQueue
CStrings:
- "com.apple.news.text-providing"
```
