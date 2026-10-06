## GeneralSettingsIntents

> `/System/Library/ExtensionKit/Extensions/GeneralSettingsIntents.appex/GeneralSettingsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdeec` | `0xb460` | **`-0x2a8c`** |
| `__TEXT.__auth_stubs` | `0xb10` | `0x7d0` | **`-0x340`** |
| `__TEXT.__objc_methname` | `0x276` | `0x47` | **`-0x22f`** |
| `__DATA.__objc_const` | `0x278` | `0x90` | **`-0x1e8`** |
| `__TEXT.__cstring` | `0x2e91` | `0x2cd1` | **`-0x1c0`** |
| `__DATA_CONST.__auth_got` | `0x590` | `0x3f0` | **`-0x1a0`** |
| `__DATA.__data` | `0x598` | `0x408` | **`-0x190`** |
| `__TEXT.__objc_methlist` | `0x184` | `—` | **`-0x184`** |
| `__DATA.__objc_selrefs` | `0x120` | `0x28` | **`-0xf8`** |
| `__TEXT.__objc_methtype` | `0xd3` | `—` | **`-0xd3`** |
| `__DATA.__objc_data` | `0xc0` | `—` | **`-0xc0`** |
| `__TEXT.__eh_frame` | `0x5e0` | `0x530` | **`-0xb0`** |
| `__TEXT.__objc_classname` | `0x105` | `0x64` | **`-0xa1`** |
| `__TEXT.__objc_stubs` | `0x140` | `0xa0` | **`-0xa0`** |
| `__TEXT.__swift5_typeref` | `0x743` | `0x6bd` | **`-0x86`** |
| `__TEXT.__unwind_info` | `0x4b0` | `0x448` | **`-0x68`** |
| `__DATA_CONST.__got` | `0x1a0` | `0x168` | **`-0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x2ec` | `0x2b8` | **`-0x34`** |
| `__DATA_CONST.__objc_protolist` | `0x30` | `—` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x4c0` | `0x490` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x244` | `0x218` | **`-0x2c`** |
| `__TEXT.__const` | `0x1368` | `0x1348` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x730` | `0x718` | **`-0x18`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `—` | **`-0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x628` | `0x618` | **`-0x10`** |
| `__DATA.__common` | `0xa8` | `0xa0` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x8` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x6c` | `0x74` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x4c` | `0x54` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x34` | `0x30` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-2027.0.2.0.0
+2027.0.4.0.0

-  - /System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices

-  Functions: 351
-  Symbols:   122
-  CStrings:  234
+  Functions: 320
+  Symbols:   82
+  CStrings:  169
Symbols:
- _OBJC_CLASS_$_BKSMousePointerDevice
- _OBJC_CLASS_$_BKSMousePointerService
- _OBJC_CLASS_$_NSObject
- _OBJC_CLASS_$_NSPredicate
- _OBJC_METACLASS_$_NSObject
- __swiftEmptySetSingleton
- _bzero
- _objc_msgSendSuper2
- _objc_release_x22
- _objc_release_x23
- _objc_release_x25
- _objc_release_x26
- _objc_release_x27
- _objc_release_x28
- _objc_release_x8
- _objc_retain_x19
- _objc_retain_x20
- _objc_retain_x21
- _objc_retain_x23
- _objc_retain_x27
- _objc_retain_x28
- _objc_retain_x8
- _objc_retain_x9
- _swift_beginAccess
- _swift_bridgeObjectRetain_n
- _swift_dynamicCast
- _swift_endAccess
- _swift_getObjCClassMetadata
- _swift_getObjectType
- _swift_release
- _swift_release_x21
- _swift_release_x22
- _swift_release_x23
- _swift_retain_x20
- _swift_retain_x21
- _swift_retain_x22
- _swift_retain_x23
- _swift_slowDealloc
- _swift_unknownObjectRelease
- _swift_unknownObjectRetain
CStrings:
- "#16@0:8"
- ".cxx_destruct"
- "@\"NSString\"16@0:8"
- "@16@0:8"
- "@24@0:8:16"
- "@32@0:8:16@24"
- "@40@0:8:16@24@32"
- "B16@0:8"
- "B24@0:8#16"
- "B24@0:8:16"
- "B24@0:8@\"Protocol\"16"
- "B24@0:8@16"
- "BKSMousePointerDeviceObserver"
- "BSInvalidatable"
- "GeneralSettingsIntents"
- "NOT (productName CONTAINS[c] %@)"
- "NSObject"
- "POINTERS"
- "Q16@0:8"
- "T#,R"
- "T@\"NSString\",?,R,C"
- "T@\"NSString\",R,C"
- "TQ,R"
- "The “Trackpad & Mouse” setting is in the iOS Settings app under the “General” pane. This setting allows users to change trackpad and mouse settings."
- "The “Trackpad” setting is in the iOS Settings app under the “General” pane. This setting allows users to change trackpad settings."
- "Trackpad & Mouse"
- "Vv16@0:8"
- "^{_NSZone=}16@0:8"
- "_TtC22GeneralSettingsIntents35GeneralSettingsPointerDeviceManager"
- "addPointerDeviceObserver:"
- "autorelease"
- "class"
- "com.apple.graphic-icon.trackpad-and-mouse"
- "conformsToProtocol:"
- "dealloc"
- "debugDescription"
- "description"
- "evaluateWithObject:"
- "hardwareType"
- "hash"
- "invalidate"
- "isEqual:"
- "isKindOfClass:"
- "isMemberOfClass:"
- "isProxy"
- "mousePointerDevicesDidChange:"
- "mousePointerDevicesDidConnect:"
- "mousePointerDevicesDidDisconnect:"
- "performSelector:"
- "performSelector:withObject:"
- "performSelector:withObject:withObject:"
- "pointerDevices"
- "release"
- "respondsToSelector:"
- "retain"
- "retainCount"
- "self"
- "senderDescriptor"
- "sharedInstance"
- "superclass"
- "token"
- "v16@0:8"
- "v24@0:8@\"NSSet\"16"
- "v24@0:8@16"
- "zone"
```
