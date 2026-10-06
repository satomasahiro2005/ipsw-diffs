## UserNotificationsCore

> `/System/Library/PrivateFrameworks/UserNotificationsCore.framework/UserNotificationsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0xfba0` | `0xf480` | **`-0x720`** |
| `__DATA_DIRTY.__data` | `0x6c50` | `0x72f0` | **`+0x6a0`** |
| `__DATA_DIRTY.__bss` | `0x7390` | `0x7930` | **`+0x5a0`** |
| `__DATA.__data` | `0x44e8` | `0x4098` | **`-0x450`** |
| `__AUTH_CONST.__objc_const` | `0x23400` | `0x23810` | **`+0x410`** |
| `__AUTH.__data` | `0x37a0` | `0x34c8` | **`-0x2d8`** |
| `__AUTH_CONST.__const` | `0xdb08` | `0xd9b8` | **`-0x150`** |
| `__TEXT.__const` | `0x13788` | `0x1363c` | **`-0x14c`** |
| `__AUTH.__objc_data` | `0x11f0` | `0x1108` | **`-0xe8`** |
| `__DATA_DIRTY.__objc_data` | `0x2720` | `0x2808` | **`+0xe8`** |
| `__TEXT.__swift5_typeref` | `0x7848` | `0x77d7` | **`-0x71`** |
| `__TEXT.__swift5_fieldmd` | `0x51b0` | `0x5164` | **`-0x4c`** |
| `__TEXT.__text` | `0x231960` | `0x231938` | **`-0x28`** |
| `__TEXT.__swift5_reflstr` | `0x4767` | `0x474a` | **`-0x1d`** |
| `__TEXT.__constg_swiftt` | `0x797c` | `0x7960` | **`-0x1c`** |
| `__TEXT.__eh_frame` | `0x82b8` | `0x82d4` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x720` | `0x708` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x64d8` | `0x64c0` | **`-0x18`** |
| `__TEXT.__swift5_capture` | `0x210c` | `0x20f8` | **`-0x14`** |
| `__TEXT.__oslogstring` | `0x115f7` | `0x1160a` | **`+0x13`** |
| `__TEXT.__cstring` | `0x90e3` | `0x90d1` | **`-0x12`** |
| `__TEXT.__objc_methlist` | `0x5f64` | `0x5f74` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xd84` | `0xd78` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x1728` | `0x1720` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3e08` | `0x3e10` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x700` | `0x704` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x5e4` | `0x5e0` | **`-0x4`** |

### Other Changes

```diff

-708.0.0.0.0
+713.0.0.0.0

-  Functions: 9489
-  Symbols:   6452
-  CStrings:  2197
+  Functions: 9466
+  Symbols:   6439
+  CStrings:  2194
Symbols:
+ -[UNCNotificationRecordMapper _categoriesByIdentifier]
+ _OBJC_IVAR_$_UNCNotificationRecordMapper._cachedCategoriesByIdentifier
+ __OBJC_$_CATEGORY_NSArray_$_UserNotificationsCore
+ __OBJC_$_CLASS_METHODS_UNCNotificationSourceDescription(Testing|Factory)
+ __OBJC_$_INSTANCE_METHODS_NSArray(UserNotificationsCore|UNSNotificationRecord)
+ __OBJC_$_INSTANCE_METHODS_UNCNotificationSourceDescription(Testing|Factory)
+ ___swift_closure_destructor.19Tm
+ ___swift_memcpy160_8
+ ___swift_project_boxed_opaque_existential_2Tm
+ ___unnamed_23
+ _symbolic _____SgXw 21UserNotificationsCore22AlertCoordinatorClientC
- __OBJC_$_CATEGORY_NSArray_$_UNSNotificationRecord
- __OBJC_$_CLASS_METHODS_UNCNotificationSourceDescription(Factory|Testing)
- __OBJC_$_INSTANCE_METHODS_NSArray(UNSNotificationRecord|UserNotificationsCore)
- __OBJC_$_INSTANCE_METHODS_UNCNotificationSourceDescription(Factory|Testing)
- ___swift_closure_destructor.23Tm
- ___swift_closure_destructor.5Tm
- ___swift_memcpy176_8
- ___unnamed_25
- _associated conformance 21UserNotificationsCore0A36NotificationEntityShowPreviewSettingOSHAASQ
- _get_type_metadata 15Synchronization5MutexVy21UserNotificationsCore16AccessoryMonitorC20InitialDataLoadState33_97C91B3C99055C0D500B893AACCA76D3LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy21UserNotificationsCore34SummarizationChinSuggestionManagerC06RecordI033_573D11D1E7C5C2A041ED647150EBC13BLLCG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy10Foundation4UUIDVSo29UNCAppleWatchSettingsAccessorCGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy10Foundation4UUIDVSo9PDRDeviceCGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySS22AccessoryNotifications0D20ForwardingConnectionCGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySSSDy22AccessoryNotifications0C12NotificationV10IdentifierVAFGGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySSSo18DAExtensionSessionCGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySSSo8DADeviceCGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySay21UserNotificationsCore23AccessorySettingsRecordVGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySay21UserNotificationsCore26AppleWatchForwardingRecord33_C9A03BC249DD699D896BC7E941311696LLVGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySayy21UserNotificationsCore16AccessoryMonitorC5EventOYbcGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySbG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic So28UNNotificationSourceSettingsCSg
- _symbolic _____ 21UserNotificationsCore0A36NotificationEntityShowPreviewSettingO
CStrings:
- "always"
- "never"
- "whenAuthenticated"
```
