## com.apple.MobileSoftwareUpdate.CleanupPreparePathService

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/XPCServices/com.apple.MobileSoftwareUpdate.CleanupPreparePathService.xpc/com.apple.MobileSoftwareUpdate.CleanupPreparePathService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29a1c` | `0x29b5c` | **`+0x140`** |
| `__DATA_CONST.__cfstring` | `0xaaa0` | `0xab60` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x1170b` | `0x117b9` | **`+0xae`** |
| `__TEXT.__objc_methname` | `0x3c3b` | `0x3c82` | **`+0x47`** |
| `__TEXT.__objc_stubs` | `0x3780` | `0x37c0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x1168` | `0x1180` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1714` | `0x172c` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x540` | `0x54c` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x2f8` | `0x300` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x8e0` | `0x8e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-2718.0.12.0.0
+2718.0.18.0.0

-  Functions: 819
-  Symbols:   2215
-  CStrings:  2990
+  Functions: 821
+  Symbols:   2220
+  CStrings:  2999
Symbols:
+ +[MSUBootFirmwareUpdater hasExclusiveUSBHostDeviceMode]
+ -[UMEventRecorder _getCoalescedSubTargetID]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/CleanupPreparePathService.build/Objects-normal/arm64e/common-47848c4b75f88441f64bf663032c47e0.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/CleanupPreparePathService.build/Objects-normal/arm64e/common-975c7d4158e0ac13103afc2974f458a2.o
+ GCC_except_table27
+ _OBJC_CLASS_$_NSSet
+ _objc_msgSend$_getCoalescedSubTargetID
+ _objc_msgSend$setWithObjects:
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/CleanupPreparePathService.build/Objects-normal/arm64e/common-3706ebc2097927ad32ceb88b9a080fef.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/CleanupPreparePathService.build/Objects-normal/arm64e/common-d1673c0c16fe748c195b69493adf3aaf.o
- GCC_except_table26
Functions:
~ _saveAccessibilityDomainsForDRE : 904 -> 1044
~ _submitRestoreLogFileToLogDir : 2600 -> 2656
~ _legacyInstallInfoFileWithDataMountPoint : 76 -> 72
~ -[UMEventRecorder _recordEvent:getPowerLog:information:callback:] : 2008 -> 2040
+ -[UMEventRecorder _getCoalescedSubTargetID]
+ +[MSUBootFirmwareUpdater hasExclusiveUSBHostDeviceMode]
CStrings:
+ "AXSVoiceOverTurnOnBluetoothEnabled"
+ "CoalescedSubTargetID"
+ "Skipping denied accessibility key: %@ in domain: %@\n"
+ "_getCoalescedSubTargetID"
+ "coalescedSubTargetID"
+ "hasExclusiveUSBHostDeviceMode"
+ "setWithObjects:"
+ "target_os_version"
+ "usb-host-device-exclusive"
```
