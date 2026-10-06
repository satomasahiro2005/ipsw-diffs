## SiriMailFlowTools

> `/System/Library/FlowTools/Tools/SiriMailFlowTools.flowtool/SiriMailFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49f58` | `0x4b4e0` | **`+0x1588`** |
| `__TEXT.__objc_methname` | `0x411` | `0x62a` | **`+0x219`** |
| `__DATA.__data` | `0xa90` | `0xc88` | **`+0x1f8`** |
| `__DATA.__objc_const` | `0xad8` | `0xc38` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `—` | `0x154` | **`+0x154`** |
| `__TEXT.__objc_methtype` | `0x1` | `0x101` | **`+0x100`** |
| `__DATA.__objc_selrefs` | `0x118` | `0x200` | **`+0xe8`** |
| `__TEXT.__oslogstring` | `0x13da` | `0x14aa` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x460` | `0x500` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x1480` | `0x1500` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x3d98` | `0x3e00` | **`+0x68`** |
| `__DATA_CONST.__objc_protolist` | `—` | `0x50` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0xa48` | `0xa88` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0xed` | `0x12d` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1420` | `0x1450` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x6b8` | `0x6e2` | **`+0x2a`** |
| `__DATA_CONST.__got` | `0x378` | `0x3a0` | **`+0x28`** |
| `__DATA_CONST.__objc_protorefs` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__const` | `0x16c0` | `0x16d0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x3c8` | `0x3d0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x218` | `0x21c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-3600.23.14.0.0
+3600.23.24.0.0

+  - /System/Library/Frameworks/Contacts.framework/Contacts

-  Functions: 1557
-  Symbols:   157
-  CStrings:  132
+  Functions: 1575
+  Symbols:   165
+  CStrings:  192
Symbols:
+ _CNContactIdentifierKey
+ _OBJC_CLASS_$_CNContact
+ _OBJC_CLASS_$_CNContactFormatter
+ _OBJC_CLASS_$_CNContactStore
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _objc_retain_x20
+ _objc_retain_x25
CStrings:
+ "#16@0:8"
+ "#MailFlowTool foregrounded app %s differs from executing app %s, but composing/sending with attachments in display mode — letting AppIntent execute in foreground so the user can see the attachment in the full UI"
+ "#SendDraftMailTool registering draft snippet for send confirmation (foregroundApp=%s, sendingApp=%s)"
+ "#UpdateDraftMailTool Parameter `target` not found for tool definition %s"
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
+ "initWithCoder:"
+ "isEqual:"
+ "isKindOfClass:"
+ "isMemberOfClass:"
+ "isProxy"
+ "performSelector:"
+ "performSelector:withObject:"
+ "performSelector:withObject:withObject:"
+ "predicateForContactsMatchingEmailAddress:"
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
- "#MailFlowTool foregrounded app %s differs from executing app %s, but composing with attachments in display mode — letting AppIntent execute in foreground so the user can see the attachment in the full UI"
```
