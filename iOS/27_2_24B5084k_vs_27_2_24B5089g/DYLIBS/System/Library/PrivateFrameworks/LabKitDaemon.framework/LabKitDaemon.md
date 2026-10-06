## LabKitDaemon

> `/System/Library/PrivateFrameworks/LabKitDaemon.framework/LabKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x57e90` | `0x5b01c` | **`+0x318c`** |
| `__TEXT.__oslogstring` | `0x16e8` | `0x1888` | **`+0x1a0`** |
| `__DATA.__data` | `0xac0` | `0xba8` | **`+0xe8`** |
| `__TEXT.__eh_frame` | `0x2720` | `0x27e8` | **`+0xc8`** |
| `__AUTH_CONST.__objc_const` | `0xf28` | `0xfb0` | **`+0x88`** |
| `__TEXT.__swift5_reflstr` | `0x4b4` | `0x514` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x752` | `0x7aa` | **`+0x58`** |
| `__TEXT.__cstring` | `0x1e86` | `0x1ed6` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1090` | `0x10d0` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x2f80` | `0x2fa8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x938` | `0x960` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x558` | `0x57c` | **`+0x24`** |
| `__TEXT.__objc_methlist` | `0xb0c` | `0xb2c` | **`+0x20`** |
| `__AUTH.__objc_data` | `0x540` | `0x558` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0xa94` | `0xaac` | **`+0x18`** |
| `__AUTH.__data` | `0x258` | `0x268` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xd88` | `0xd98` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x400` | `0x410` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0xf0` | `0x100` | **`+0x10`** |
| `__TEXT.__const` | `0x1074` | `0x1084` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x1f0` | `0x1fc` | **`+0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xb0` | `0xb4` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x7c` | `0x80` | **`+0x4`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 1287
-  Symbols:   612
-  CStrings:  210
+  Functions: 1320
+  Symbols:   624
+  CStrings:  219
Symbols:
+ _HKStringFromProfileType
+ _OBJC_CLASS_$_HDPrimaryProfile
+ _OBJC_CLASS_$_HDProtectedDataOperation
+ __OBJC_$_INSTANCE_METHODS__TtC12LabKitDaemon23LabNotificationsManager(LabKitDaemon|LabKitDaemon1|LabKitDaemon2|LabKitDaemon3)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HDProtectedDataOperationDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HDProtectedDataOperationDelegate
+ __OBJC_$_PROTOCOL_REFS_HDProtectedDataOperationDelegate
+ __OBJC_CLASS_PROTOCOLS_$__TtC12LabKitDaemon23LabNotificationsManager(LabKitDaemon|LabKitDaemon1|LabKitDaemon2|LabKitDaemon3)
+ __OBJC_LABEL_PROTOCOL_$_HDProtectedDataOperationDelegate
+ __OBJC_PROTOCOL_$_HDProtectedDataOperationDelegate
+ _symbolic Iegh_
+ _symbolic IeyBh_
+ _symbolic SDy_____y_____SSGSiG 15HealthUtilities15TypedIdentifierV 0A14RecordServices15LaboratoryOrderV
+ _symbolic So24HDProtectedDataOperationC
+ _symbolic _____ySDy_____y_____SSGSiGG 2os21OSAllocatedUnfairLockV 15HealthUtilities15TypedIdentifierV 0E14RecordServices15LaboratoryOrderV
- __OBJC_$_INSTANCE_METHODS__TtC12LabKitDaemon23LabNotificationsManager(LabKitDaemon|LabKitDaemon1|LabKitDaemon2)
- __OBJC_CLASS_PROTOCOLS_$__TtC12LabKitDaemon23LabNotificationsManager(LabKitDaemon|LabKitDaemon1|LabKitDaemon2)
- _symbolic _____ 6LabKit0A24OrderNotificationPayloadV
CStrings:
+ "LabDeviceTokenReconcile"
+ "LabOrderUpdateFromPush"
+ "[%s]: Asked to perform work for unrecognized operation %{public}s"
+ "[%s]: Failed to request work for %{public}s: %@"
+ "[%s]: Giving up on the push for order `%s` after %ld attempts"
+ "[%s]: received a message with no userInfo, ignoring"
+ "[%s]: received a nil public token, ignoring"
+ "[%s]: received a nil topic token, ignoring"
+ "[%{public}s] no profile extension for %{public}s profile"
```
