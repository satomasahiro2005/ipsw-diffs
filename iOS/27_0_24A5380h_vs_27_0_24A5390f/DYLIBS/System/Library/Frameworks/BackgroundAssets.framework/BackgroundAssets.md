## BackgroundAssets

> `/System/Library/Frameworks/BackgroundAssets.framework/BackgroundAssets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91238` | `0x9b700` | **`+0xa4c8`** |
| `__TEXT.__oslogstring` | `0x4738` | `0x5228` | **`+0xaf0`** |
| `__DATA_DIRTY.__data` | `—` | `0xa00` | **`+0xa00`** |
| `__AUTH.__data` | `0xb70` | `0x310` | **`-0x860`** |
| `__DATA_DIRTY.__objc_data` | `0x280` | `0x970` | **`+0x6f0`** |
| `__AUTH.__objc_data` | `0x898` | `0x1b0` | **`-0x6e8`** |
| `__TEXT.__eh_frame` | `0x4168` | `0x47c0` | **`+0x658`** |
| `__AUTH_CONST.__const` | `0x1e60` | `0x2040` | **`+0x1e0`** |
| `__TEXT.__unwind_info` | `0x1ae8` | `0x1c80` | **`+0x198`** |
| `__TEXT.__cstring` | `0x424a` | `0x434a` | **`+0x100`** |
| `__TEXT.__swift5_capture` | `0x720` | `0x804` | **`+0xe4`** |
| `__AUTH_CONST.__auth_got` | `0xfb0` | `0x1070` | **`+0xc0`** |
| `__TEXT.__const` | `0x3018` | `0x30d8` | **`+0xc0`** |
| `__AUTH_CONST.__cfstring` | `0x1140` | `0x11e0` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x120d` | `0x12a5` | **`+0x98`** |
| `__DATA_CONST.__got` | `0x5e8` | `0x678` | **`+0x90`** |
| `__DATA.__data` | `0x1380` | `0x1308` | **`-0x78`** |
| `__AUTH_CONST.__objc_const` | `0x2ac8` | `0x2b28` | **`+0x60`** |
| `__DATA.__common` | `0x50` | `0x8` | **`-0x48`** |
| `__DATA_DIRTY.__common` | `—` | `0x48` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0x8e9` | `0x929` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x244` | `0x284` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0xc60` | `0xc98` | **`+0x38`** |
| `__TEXT.__swift_as_entry` | `0x11c` | `0x148` | **`+0x2c`** |
| `__TEXT.__swift_as_ret` | `0x154` | `0x180` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x578` | `0x590` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x930` | `0x948` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xae0` | `0xae8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x120` | `0x124` | **`+0x4`** |

### Other Changes

```diff

-274.0.0.0.0
+279.0.1.0.0

+  - /System/Library/Frameworks/UIKit.framework/UIKit

+  - /usr/lib/swift/libswiftCoreImage.dylib

+  - /usr/lib/swift/libswiftSpatial.dylib

-  Functions: 1962
-  Symbols:   1509
-  CStrings:  593
+  Functions: 2043
+  Symbols:   1534
+  CStrings:  635
Symbols:
+ -[BADownload wasForegroundDownload]
+ GCC_except_table11
+ _OBJC_CLASS_$_NSNotificationCenter
+ _OBJC_CLASS_$_UIApplication
+ _OBJC_IVAR_$_BADownload._wasForegroundDownload
+ ___swift_closure_destructor.103Tm
+ ___swift_closure_destructor.107Tm
+ ___swift_closure_destructor.266Tm
+ ___swift_closure_destructor.75Tm
+ ___swift_closure_destructor.81Tm
+ ___swift_closure_destructor.98Tm
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreImage_$_BackgroundAssets
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftSpatial_$_BackgroundAssets
+ __swift_FORCE_LOAD_$_swiftUIKit
+ __swift_FORCE_LOAD_$_swiftUIKit_$_BackgroundAssets
+ _swift_bridgeObjectRetain_n
+ _swift_getExtendedFunctionTypeMetadata
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
+ _symbolic SDySSypG
+ _symbolic ScCyx______pG s5ErrorP
+ _symbolic ShySSG
+ _symbolic So17BADownloadManagerCXDXMT
+ _symbolic _____ 10Foundation4DateV
+ _symbolic _____Sg So20NSNotificationCenterC10FoundationE16ObservationTokenV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 29ManagedBackgroundAssetsHelper26DeferredStatusUpdateRecordC20StaticRepresentationV
+ _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE So20NSNotificationCenterC10FoundationE16ObservationTokenV
+ _symbolic _____y_____SgG 15Synchronization5_CellVAARi_zrlE So20NSNotificationCenterC10FoundationE16ObservationTokenV
+ _symbolic _____y______G So20NSNotificationCenterC10FoundationE21BaseMessageIdentifierV So13UIApplicationC5UIKitE015DidBecomeActiveE0V
+ _symbolic x______pIegTrzo_ s5ErrorP
- GCC_except_table21
- GCC_except_table9
- ___swift_closure_destructor.100Tm
- ___swift_closure_destructor.104Tm
- ___swift_closure_destructor.67Tm
- ___swift_closure_destructor.78Tm
- ___swift_closure_destructor.95Tm
CStrings:
+ "%ld deferred status update%{public}s %{public}s drained."
+ "A status update about the failed download with the unique ID “%{public}s” of the asset pack with the ID “%{public}s” couldn’t be deferred: %{public}@"
+ "A status update about the finished download with the unique ID “%{public}s” of the asset pack with the ID “%{public}s” couldn’t be deferred: %{public}@"
+ "App did become active: %{public}s"
+ "Asset pack management info: %@\n"
+ "Attempting to acquire exclusive control over the download manager before %{public}s…"
+ "BADownloadManager"
+ "Cancellation handler for: %{public}@"
+ "Defer status update about failed download with unique ID: %{public}s error: %{public}@ of asset pack with ID: %{public}s"
+ "Defer status update about finished download with unique ID: %{public}s of asset pack with ID: %{public}s"
+ "Deferred status updates couldn’t be drained: %{public}@"
+ "Deferring a status update about the failed download with the unique ID “%s” of the asset pack with the ID “%{public}s”…"
+ "Deferring a status update about the finished download with the unique ID “%{public}s” of the asset pack with the ID “%{public}s”…"
+ "Drain deferred status updates"
+ "Draining deferred status updates…"
+ "EXAppExtensionAttributes"
+ "EXExtensionPointIdentifier"
+ "Exclusive control over the download manager couldn’t be acquired before %{public}s."
+ "Exclusive control over the download manager couldn’t be acquired before %{public}s: %{public}@"
+ "Exclusive control over the download manager couldn’t be acquired."
+ "Exclusive control over the download manager couldn’t be acquired: %{public}@"
+ "Exclusive control over the download manager was acquired."
+ "Is running in downloader extension"
+ "NO"
+ "Refresh manifest"
+ "Relinquishing exclusive control over the download manager…"
+ "Report failed download of asset pack with ID: %{public}s version: %lu error: %{public}@"
+ "Report finished download of asset pack with ID: %{public}s version: %lu"
+ "The app became active."
+ "The asset pack with the ID “%{public}s” is currently being downloaded; canceling the download before updating the asset pack to the latest version…"
+ "The deferred-status-update kind “%{public}s” is unknown."
+ "The download with the ID “%{public}s” is essential and is already in the foreground; awaiting status updates…"
+ "The essential download with the ID “%{public}s” couldn’t be rescheduled as an optional download: %{public}@"
+ "The fact that version %lu of the asset pack with the ID “%{public}s” failed to be downloaded couldn’t be reported: %{public}@"
+ "The kind of the deferred status update with the record “%{public}s” couldn’t be determined: %{public}@"
+ "The manifest couldn’t be refreshed: %{public}@"
+ "U"
+ "Verify download be for known asset pack: %{public}@"
+ "Was foreground download: %@\n"
+ "With exclusive control before: %{public}s %{public}s"
+ "With exclusive control: %{public}s"
+ "YES"
+ "wasForegroundDownload"
+ "withExclusiveControl(_:)"
+ "withExclusiveControl(before:_:)"
- "No asset pack with the ID “%s” was found."
- "The download manifest couldn’t be retrieved: %{public}@"
- "The download with the ID “%{public}s” is essential and is already foreground; awaiting status updates…"
```
