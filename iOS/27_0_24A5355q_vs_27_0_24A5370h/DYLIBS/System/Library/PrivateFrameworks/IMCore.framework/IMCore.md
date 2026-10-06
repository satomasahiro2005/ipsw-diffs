## IMCore

> `/System/Library/PrivateFrameworks/IMCore.framework/IMCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fdab0` | `0x2fe320` | **`+0x870`** |
| `__TEXT.__unwind_info` | `0xc130` | `0xc470` | **`+0x340`** |
| `__TEXT.__oslogstring` | `0x23f4b` | `0x240fb` | **`+0x1b0`** |
| `__DATA.__bss` | `0x1e950` | `0x1eae0` | **`+0x190`** |
| `__AUTH.__objc_data` | `0x4430` | `0x4318` | **`-0x118`** |
| `__AUTH_CONST.__const` | `0xc328` | `0xc3f8` | **`+0xd0`** |
| `__AUTH.__data` | `0x2ee8` | `0x2e40` | **`-0xa8`** |
| `__TEXT.__const` | `0x11660` | `0x116e0` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0x22190` | `0x22128` | **`-0x68`** |
| `__TEXT.__swift5_reflstr` | `0x3806` | `0x3866` | **`+0x60`** |
| `__DATA.__data` | `0x64c8` | `0x6520` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x12034` | `0x12080` | **`+0x4c`** |
| `__TEXT.__cstring` | `0x134c5` | `0x13505` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x324c` | `0x3218` | **`-0x34`** |
| `__TEXT.__objc_methlist` | `0x18d04` | `0x18cd4` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0xba40` | `0xba60` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xea50` | `0xea70` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0xae0` | `0xaf8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x21b8` | `0x21a8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x2868` | `0x2878` | **`+0x10`** |
| `__DATA_CONST.__objc_catlist` | `0xe0` | `0xf0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x918` | `0x908` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x568` | `0x578` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x39bc` | `0x39ae` | **`-0xe`** |
| `__TEXT.__swift5_proto` | `0xfd0` | `0xfdc` | **`+0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x5c0` | `0x5b8` | **`-0x8`** |
| `__TEXT.__swift5_fieldmd` | `0x4198` | `0x41a0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x3f0` | `0x3ec` | **`-0x4`** |

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

+  - /usr/lib/swift/libswiftRegexBuilder.dylib

-  Functions: 15201
-  Symbols:   2686
-  CStrings:  5046
+  Functions: 15202
+  Symbols:   2690
+  CStrings:  5052
Symbols:
+ _IMBalloonPluginIdentifierCanRenderReplyPreview
+ _IMBalloonPluginIdentifierReplyPreviewFallbackText
+ _IMBalloonPluginIdentifierReplyPreviewSymbolName
+ _IMBalloonPluginIdentifierVendsOwnReplyPreviewContent
+ _IMFileTransferPreviewGenerationStateCanAggregate
+ _IMIsRunningInMessagesExtension
+ _IMSetUserAccountActionIntent
+ _OBJC_CLASS_$_IMChatForkingInfo
+ _OBJC_CLASS_$_IMChatForkingRequest
- _IMSetUserRegistrationFailureIntent
- _OBJC_CLASS_$_IMCoreHelloWorldClass
- _OBJC_CLASS_$_IMCoreHelloWorldClass_Impl
- _OBJC_METACLASS_$_IMCoreHelloWorldClass
- _OBJC_METACLASS_$_IMCoreHelloWorldClass_Impl
CStrings:
+ "ChatBot Logo - Generated fresh transferGuid %@ after relay-GUID collision"
+ "ChatBot Logo - Refusing to reuse transferGuid %@ from relay; collides with existing IMFileTransfer. Generating a fresh transferGuid instead."
+ "Failed to find cached chat for guid: %@. Properties were not updated"
+ "Ignoring nil Communication Safety Sensitivity for transfer %@. Depending on intent, set analysis to Not Sensitive instead."
+ "Mark chat item %@ for CommSafety with %lu per-transfer analyses"
+ "ThreadServiceChange"
+ "_fileTransferUpdated:CanAggregateChanged"
+ "chat: %@  propertiesUpdated"
+ "chat: %{public}@ property %{public}@ changed: %{public}@ -> %{public}@"
- "Failed to find cached chat for guid: %@. Properties were not updated: %@"
- "Mark chat item %@ for CommSafety: %d"
- "chat: %@  propertiesUpdated: %@"
```
