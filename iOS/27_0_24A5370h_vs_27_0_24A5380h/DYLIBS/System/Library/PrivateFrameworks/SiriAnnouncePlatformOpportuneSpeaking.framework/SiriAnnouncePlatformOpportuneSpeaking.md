## SiriAnnouncePlatformOpportuneSpeaking

> `/System/Library/PrivateFrameworks/SiriAnnouncePlatformOpportuneSpeaking.framework/SiriAnnouncePlatformOpportuneSpeaking`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6478` | `0x983c` | **`+0x33c4`** |
| `__TEXT.__cstring` | `0x1bd` | `0x38d` | **`+0x1d0`** |
| `__TEXT.__eh_frame` | `0x80` | `0x158` | **`+0xd8`** |
| `__AUTH_CONST.__auth_got` | `0x440` | `0x4e0` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x375` | `0x3f9` | **`+0x84`** |
| `__TEXT.__oslogstring` | `0x15e` | `0x1ce` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0xa8` | `0x100` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0x1c4` | `0x214` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x100` | `0x150` | **`+0x50`** |
| `__DATA_CONST.__got` | `0xd0` | `0x118` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x258` | `0x2a0` | **`+0x48`** |
| `__DATA.__data` | `0x270` | `0x290` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1e0` | `0x1f8` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xfc` | `0x114` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__TEXT.__const` | `0x748` | `0x758` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-3600.26.1.0.0
+3600.26.2.0.0

+  - /System/Library/Frameworks/UserNotifications.framework/UserNotifications

-  Functions: 253
-  Symbols:   252
-  CStrings:  18
+  Functions: 269
+  Symbols:   265
+  CStrings:  33
Symbols:
+ _OBJC_CLASS_$_UNNotification
+ ___swift_memcpy41_8
+ __swiftEmptyDictionarySingleton
+ _bzero
+ _objc_release_x25
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x8
+ _swift_dynamicCast
+ _swift_release_x22
+ _swift_retain_x19
+ _symbolic SS______t 7ToolKit10TypedValueO
+ _symbolic Si13notifications_Si6appIDst
+ _symbolic Si5types_Si9bundleIDsSi08instanceC0Si13notificationsSi015notificationAppC0t
+ _symbolic _____ySS_____G s18_DictionaryStorageC 7ToolKit10TypedValueO
- ___swift_memcpy24_8
CStrings:
+ ", notificationAppIDs="
+ ", notifications="
+ "Array lengths must match: notifications="
+ "Encoding %ld UserNotificationEntity values"
+ "Encoding %ld heterogeneous entities with entity values"
+ "InterruptionLevel"
+ "UserNotificationEntity"
+ "UserNotificationEntityPriorityStatus"
+ "UserNotificationEntitySourceFeed"
+ "com.apple.usernotificationsd"
+ "containsOneTimePasscode"
+ "interruptionLevel"
+ "isPreviewRestricted"
+ "notificationCenter"
+ "threadIdentifier"
```
