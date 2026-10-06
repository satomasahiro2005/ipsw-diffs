## SiriNotificationsFlowTools

> `/System/Library/FlowTools/Tools/SiriNotificationsFlowTools.flowtool/SiriNotificationsFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x194e0` | `0x20494` | **`+0x6fb4`** |
| `__TEXT.__eh_frame` | `0x910` | `0xd98` | **`+0x488`** |
| `__TEXT.__auth_stubs` | `0xd30` | `0x10b0` | **`+0x380`** |
| `__TEXT.__cstring` | `0x4bb` | `0x6db` | **`+0x220`** |
| `__DATA_CONST.__auth_got` | `0x6a0` | `0x860` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0x66f` | `0x7ef` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x698` | `0x7e0` | **`+0x148`** |
| `__TEXT.__const` | `0x1710` | `0x1830` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0x1a0` | `0x2c0` | **`+0x120`** |
| `__DATA.__data` | `0x910` | `0x9b8` | **`+0xa8`** |
| `__DATA_CONST.__const` | `0x980` | `0xa28` | **`+0xa8`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x270` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x14a` | `0x1c3` | **`+0x79`** |
| `__DATA_CONST.__auth_ptr` | `0x7d0` | `0x848` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0x74c` | `0x7bc` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x240` | `0x29c` | **`+0x5c`** |
| `__DATA.__objc_const` | `0x118` | `0x160` | **`+0x48`** |
| `__DATA.__objc_data` | `—` | `0x48` | **`+0x48`** |
| `__DATA.__objc_selrefs` | `0x68` | `0xb0` | **`+0x48`** |
| `__TEXT.__objc_classname` | `0x3b` | `0x7b` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x28` | `0x60` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0xd0` | `0x100` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x30` | `0x50` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x2c` | `0x40` | **`+0x14`** |
| `__DATA.__common` | `0xc0` | `0xd0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x548` | `0x558` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x3c` | `0x40` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-3605.2.1.0.0
+3605.2.1.1.1

+  - /System/Library/Frameworks/UIKit.framework/UIKit

+  - /System/Library/PrivateFrameworks/DialogEngine.framework/DialogEngine

+  - /System/Library/PrivateFrameworks/SiriDialogEngine.framework/SiriDialogEngine

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftCoreImage.dylib

+  - /usr/lib/swift/libswiftMLCompute.dylib

+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

+  - /usr/lib/swift/libswiftSpatial.dylib

-  Functions: 616
-  Symbols:   137
-  CStrings:  88
+  Functions: 748
+  Symbols:   153
+  CStrings:  116
Symbols:
+ _OBJC_CLASS_$_DialogElement
+ _OBJC_CLASS_$_NSPersonNameComponentsFormatter
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftMLCompute
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftUIKit
+ _objc_release_x25
+ _objc_release_x27
+ _objc_release_x28
+ _objc_retain_x21
+ _swift_allocError
+ _swift_getErrorValue
+ _swift_initClassMetadata2
+ _swift_release_x9
+ _swift_retain_x9
- __swift_stdlib_bridgeErrorToNSError
CStrings:
+ "%s.%s %{private}s contains unspeakable content: %{bool}d"
+ "%s.%s %{private}s is a critical alert, returning false"
+ "%s.%s %{private}s is long notification: %{bool}d"
+ "%s.%s %{public}s rendered no dialog"
+ "%s.%s CAT render failed: %{public}s"
+ "%s.%s app bundle id: %{private}s"
+ "%s.%s conversion error: %{public}s"
+ "%s.%s error: %{public}s"
+ "%s.%s isReadLatest: %{bool}d, isCatchMeUp: %{bool}d, app: %{private}s"
+ "%s.%s not a single-notification announce, deferring to the planner"
+ "%s.%s notification count: %ld"
+ "%s.%s notification id: %{private}s contains a one time passcode"
+ "%s.%s notification id: %{private}s is missing a date, returning nil"
+ "%s.%s number of apps with notifications: %ld"
+ "%s.%s priority or passcode notification, deferring to the planner"
+ "%s.%s returning announce CAT follow-up"
+ "%s.%s sorted and grouped into %ld apps, %ld threads"
+ "%s.%s unspeakable range count: %ld"
+ "/System/Library/PrivateFrameworks/SiriNotificationsIntents.framework"
+ "AnnounceNotificationCATDialog"
+ "ReadNotifications#AnnounceNotificationPrompt"
+ "ReadNotifications#ReadFullNotification"
+ "ReadNotifications#ReadSummarizedNotification"
+ "_TtC26SiriNotificationsFlowTools24AnnounceNotificationCATs"
+ "announceableNotification(in:)"
+ "catId"
+ "code"
+ "currentSummaryType"
+ "dialog"
+ "domain"
+ "excessiveNotification"
+ "followUpAction(for:context:)"
+ "fullPrint"
+ "fullSpeak"
+ "hand_control_to_user"
+ "isSameAppOrThread"
+ "localizedStringFromPersonNameComponents:style:options:"
+ "numberOfTimesPrompted"
+ "previousSummaryType"
+ "printOnly"
+ "spokenOnly"
+ "unreadableNotification"
- "%s.%s %s contains unspeakable content: %{bool}d"
- "%s.%s %s is a critical alert, returning false"
- "%s.%s %s is long notification: %{bool}d"
- "%s.%s app bundle id: %s"
- "%s.%s conversion error: %s"
- "%s.%s error: %@"
- "%s.%s executing PrepareNotificationsTool - isReadLatest: %{bool}d, isCatchMeUp: %{bool}d, app: %s"
- "%s.%s notification id: %s contains a one time passcode"
- "%s.%s notification id: %s is missing a date, returning nil"
- "%s.%s notifications: %s"
- "%s.%s number of apps with notifications: %s"
- "%s.%s returning result: %s"
- "%s.%s sorted and grouped notifications: %s"
- "%s.%s unspeakable ranges: %s"
```
