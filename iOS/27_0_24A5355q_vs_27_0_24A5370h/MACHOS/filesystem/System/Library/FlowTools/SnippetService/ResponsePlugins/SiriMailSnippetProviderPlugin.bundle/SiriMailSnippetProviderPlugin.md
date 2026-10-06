## SiriMailSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/SiriMailSnippetProviderPlugin.bundle/SiriMailSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9b28` | `0xbd84` | **`+0x225c`** |
| `__TEXT.__objc_methname` | `0x3a` | `0x286` | **`+0x24c`** |
| `__DATA.__data` | `0x288` | `0x4c0` | **`+0x238`** |
| `__TEXT.__auth_stubs` | `0x870` | `0xaa0` | **`+0x230`** |
| `__TEXT.__oslogstring` | `0x751` | `0x921` | **`+0x1d0`** |
| `__DATA.__objc_const` | `0xb8` | `0x218` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `—` | `0x154` | **`+0x154`** |
| `__DATA_CONST.__auth_got` | `0x440` | `0x558` | **`+0x118`** |
| `__TEXT.__objc_methtype` | `0x1` | `0x101` | **`+0x100`** |
| `__DATA.__objc_selrefs` | `0x20` | `0x118` | **`+0xf8`** |
| `__TEXT.__objc_stubs` | `0x80` | `0x160` | **`+0xe0`** |
| `__TEXT.__const` | `0x292` | `0x328` | **`+0x96`** |
| `__DATA_CONST.__objc_protolist` | `—` | `0x50` | **`+0x50`** |
| `__DATA_CONST.__got` | `0xe8` | `0x130` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x116` | `0x15c` | **`+0x46`** |
| `__TEXT.__objc_classname` | `0x43` | `0x83` | **`+0x40`** |
| `__DATA_CONST.__objc_protorefs` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x188` | `0x1a8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1c0` | `0x1e0` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x100` | `0x118` | **`+0x18`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.17.4.0.0
+3600.23.4.0.0
+  - /System/Library/Frameworks/Contacts.framework/Contacts

+  - /System/Library/PrivateFrameworks/EmailAddressing.framework/EmailAddressing

-  Functions: 189
-  Symbols:   92
-  CStrings:  32
+  Functions: 204
+  Symbols:   113
+  CStrings:  95
Symbols:
+ _CNContactIdentifierKey
+ _OBJC_CLASS_$_CNContact
+ _OBJC_CLASS_$_CNContactFormatter
+ _OBJC_CLASS_$_CNContactStore
+ _OBJC_CLASS_$_EAEmailAddressParser
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _objc_allocWithZone
+ _objc_release_x25
+ _objc_release_x27
+ _objc_retain_x22
+ _objc_retain_x26
+ _objc_retain_x8
+ _swift_arrayDestroy
+ _swift_bridgeObjectRelease_n
+ _swift_errorRelease
+ _swift_getObjCClassMetadata
+ _swift_initStackObject
+ _swift_release_x25
+ _swift_release_x27
+ _swift_release_x28
+ _swift_setDeallocating
+ _swift_willThrow
- _swift_release_x22
- _swift_release_x23
CStrings:
+ "#16@0:8"
+ "#DraftMailSnippetHandler confirmationRequestedByDeleteTool - toolIdentifiers: %s, isDelete: %{bool}d, isDestructiveAction: %{bool}d"
+ "#DraftMailSnippetHandler supportsAsync - delete/destructive draft confirmation, deferring to default handler for MessageItemView rendering, returning .unsupported"
+ "#DraftMailSnippetHandler supportsAsync - found draft entity with state: %s, isConfirmation: %{bool}d, returning .supported"
+ "#DraftMailSnippetHandler supportsAsync - response type is not .inform or .confirm, returning .unsupported"
+ "#ReadMailSnippetHandler resolvePersonDisplay - could not resolve contact for emailAddress: %s"
+ "#ReadMailSnippetHandler resolvePersonDisplay - person has no contactIdentifier and no handle, it is likely not in Contacts"
+ "#SiriMailSnippetProviderPlugin handle(item:context:) failed to convert DraftMessageEntity to WidgetMessage"
+ "@\"NSString\"16@0:8"
+ "@16@0:8"
+ "@24@0:8:16"
+ "@24@0:8@\"NSCoder\"16"
+ "@24@0:8@16"
+ "@24@0:8^{_NSZone=}16"
+ "@32@0:8:16@24"
+ "@40@0:8:16@24@32"
+ "B16@0:8"
+ "B24@0:8#16"
+ "B24@0:8:16"
+ "B24@0:8@\"Protocol\"16"
+ "B24@0:8@16"
+ "CNKeyDescriptor"
+ "NSCoding"
+ "NSCopying"
+ "NSObject"
+ "NSSecureCoding"
+ "Q16@0:8"
+ "T#,R"
+ "T@\"NSString\",?,R,C"
+ "T@\"NSString\",R,C"
+ "TB,R"
+ "TQ,R"
+ "Vv16@0:8"
+ "^{_NSZone=}16@0:8"
+ "autorelease"
+ "class"
+ "conformsToProtocol:"
+ "copyWithZone:"
+ "debugDescription"
+ "description"
+ "descriptorForRequiredKeysForStyle:"
+ "encodeWithCoder:"
+ "hash"
+ "identifier"
+ "init"
+ "initWithCoder:"
+ "isEqual:"
+ "isKindOfClass:"
+ "isMemberOfClass:"
+ "isProxy"
+ "performSelector:"
+ "performSelector:withObject:"
+ "performSelector:withObject:withObject:"
+ "predicateForContactsMatchingEmailAddress:"
+ "rawAddressFromFullAddress:"
+ "release"
+ "respondsToSelector:"
+ "retain"
+ "retainCount"
+ "self"
+ "stringFromContact:style:"
+ "superclass"
+ "supportsSecureCoding"
+ "unifiedContactsMatchingPredicate:keysToFetch:error:"
+ "v24@0:8@\"NSCoder\"16"
+ "v24@0:8@16"
+ "zone"
- "#DraftMailSnippetHandler supportsAsync - found draft entity with state: %s, returning .supported"
- "#DraftMailSnippetHandler supportsAsync - response type is not .inform, returning .unsupported"
- "#ReadMailSnippetHandler toWidgetMessage - sender did not have a contactIdentifier, it is likely not in Contacts"
- "#SiriMailSnippetProviderPlugin handle(item:context:) failed to convert DraftMessageEntity to _SiriMailMessage"
```
