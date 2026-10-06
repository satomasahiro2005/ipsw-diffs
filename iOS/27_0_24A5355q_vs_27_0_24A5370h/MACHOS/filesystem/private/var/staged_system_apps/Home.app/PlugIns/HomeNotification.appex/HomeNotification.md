## HomeNotification

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeNotification.appex/HomeNotification`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dc3c` | `0x1e590` | **`+0x954`** |
| `__TEXT.__cstring` | `0x11ee` | `0x133e` | **`+0x150`** |
| `__DATA.__data` | `0x7b0` | `0x7e0` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x514` | `0x4ec` | **`-0x28`** |
| `__TEXT.__auth_stubs` | `0x1430` | `0x1410` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x2d60` | `0x2d40` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x745` | `0x764` | **`+0x1f`** |
| `__DATA_CONST.__auth_got` | `0xa28` | `0xa18` | **`-0x10`** |
| `__TEXT.__const` | `0x668` | `0x678` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x3c3b` | `0x3c2b` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0xf98` | `0xf90` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x418` | `0x420` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6e0` | `0x6e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1216.4.0.1.11
+1227.0.0.0.1

-  Functions: 554
-  Symbols:   330
-  CStrings:  921
+  Functions: 553
+  Symbols:   325
+  CStrings:  926
Symbols:
+ _swift_release_x28
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
- _objc_getAssociatedObject
- _objc_setAssociatedObject
- _objc_sync_enter
- _objc_sync_exit
- _swift_allocError
- _swift_continuation_throwingResume
- _swift_continuation_throwingResumeWithError
- _swift_retain_n
CStrings:
+ "HomeNotification/HomeNotificationTableViewController.swift"
+ "HomeNotification/NotificationContent.swift"
+ "HomeNotification/NotificationNearbyAccessoriesView.swift"
+ "HomeNotification/NotificationRouter.swift"
+ "HomeNotification/NotificationViewController.swift"
+ "_createCheckedThrowingContinuation(_:)"
- "notificationActions"
```
