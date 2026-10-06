## HomeNotification

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeNotification.appex/HomeNotification`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e53c` | `0x253b8` | **`+0x6e7c`** |
| `__DATA.__bss` | `0x2e8` | `0x668` | **`+0x380`** |
| `__TEXT.__cstring` | `0x133e` | `0x16ae` | **`+0x370`** |
| `__TEXT.__eh_frame` | `0x4ec` | `0x84c` | **`+0x360`** |
| `__TEXT.__auth_stubs` | `0x1420` | `0x1710` | **`+0x2f0`** |
| `__TEXT.__const` | `0x678` | `0x8b8` | **`+0x240`** |
| `__DATA_CONST.__auth_got` | `0xa20` | `0xb98` | **`+0x178`** |
| `__TEXT.__unwind_info` | `0x6e0` | `0x850` | **`+0x170`** |
| `__DATA.__data` | `0x7e0` | `0x910` | **`+0x130`** |
| `__DATA_CONST.__auth_ptr` | `0x240` | `0x358` | **`+0x118`** |
| `__TEXT.__oslogstring` | `0xa94` | `0xb9d` | **`+0x109`** |
| `__TEXT.__swift5_reflstr` | `0x1b2` | `0x2b2` | **`+0x100`** |
| `__TEXT.__lldbsummaries` | `—` | `0xf7` | **`+0xf7`** |
| `__DATA_CONST.__const` | `0xf90` | `0x1048` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0x168` | `0x218` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x764` | `0x7f4` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x420` | `0x490` | **`+0x70`** |
| `__DATA.__objc_const` | `0x16b0` | `0x1710` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x2d40` | `0x2da0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x3c2b` | `0x3c81` | **`+0x56`** |
| `__TEXT.__constg_swiftt` | `0x224` | `0x270` | **`+0x4c`** |
| `__DATA.__objc_selrefs` | `0xf90` | `0xfb0` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x14` | `0x30` | **`+0x1c`** |
| `__DATA.__objc_data` | `0x528` | `0x540` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x180` | `0x194` | **`+0x14`** |
| `__TEXT.__objc_methlist` | `0xf14` | `0xf24` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x1c` | `0x24` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x2c` | `0x30` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x18` | `0x1c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-1232.3.0.0.0
+1238.0.0.0.0

-  Functions: 547
-  Symbols:   324
-  CStrings:  926
+  Functions: 648
+  Symbols:   333
+  CStrings:  954
Symbols:
+ _HMBulletinReasonDoorbellPressed
+ _HMBulletinReasonKey
+ _UNNotificationDefaultActionIdentifier
+ __swiftImmortalRefCount
+ _memcpy
+ _swift_deallocBox
+ _swift_release_n
+ _swift_retain_n
+ _swift_retain_x1
+ _swift_slowAlloc
+ _swift_slowDealloc
- _swift_projectBox
- _swift_retain_x25
CStrings:
+ ", multiAccessory: "
+ ", tappedThrough: "
+ "Authentication failed – dismissing"
+ "CameraNotificationLongPressEvent(mode: "
+ "No clipID found – will attempt recovery from significant events"
+ "No clipID in bulletin and no significant events to recover from – will use live stream"
+ "NotificationLongPress"
+ "Person detected but eventsResult is nil – no face recognition actions"
+ "Recovered clipID from significant event: %{public}@"
+ "Submitting notification feedback: action=%{public}@ hasSummaryCaption=%{public}@ featureDomain=%{public}@ featureType=%{public}@ subFeature=%{public}@"
+ "[camera refresh analytics] long-press emitted at %s tappedThrough=%{bool}d displayedMode=%s isDoorbell=%{bool}d multipleAccessories=%{bool}d"
+ "[camera refresh analytics] long-press skipped at %s (alreadyEmitted=%{bool}d, eventNil=%{bool}d)"
+ "accessoryProfile"
+ "auth-failed"
+ "clipUUID"
+ "com.apple.Home.CameraViewer"
+ "currentNotificationDisplayMode"
+ "dateOfOccurrence"
+ "defaultActionURL"
+ "didReceive-response"
+ "hasEmittedLongPressEvent"
+ "pendingLongPressEvent"
+ "performCleanup"
+ "representsMultipleAccessories"
+ "tap-through"
+ "tappedThroughToApp"
+ "userInfo keys: %{public}@"
+ "viewWillDisappear"
+ "viewWillDisappear:"
- "No clipID found – continue showing live"
```
