## AddDevicesToAutomatedDeviceEnrollmentExtension

> `/System/Library/Frameworks/AutomatedDeviceEnrollment.framework/PlugIns/AddDevicesToAutomatedDeviceEnrollmentExtension.appex/AddDevicesToAutomatedDeviceEnrollmentExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x90d30` | `0x951e4` | **`+0x44b4`** |
| `__TEXT.__cstring` | `0x3804` | `0x4155` | **`+0x951`** |
| `__DATA.__objc_const` | `0x37f0` | `0x3ac0` | **`+0x2d0`** |
| `__DATA.__data` | `0x6688` | `0x6928` | **`+0x2a0`** |
| `__TEXT.__const` | `0x8874` | `0x8ab4` | **`+0x240`** |
| `__TEXT.__constg_swiftt` | `0x3480` | `0x366c` | **`+0x1ec`** |
| `__TEXT.__eh_frame` | `0x4318` | `0x44e8` | **`+0x1d0`** |
| `__DATA_CONST.__const` | `0x4898` | `0x4a40` | **`+0x1a8`** |
| `__TEXT.__swift5_reflstr` | `0x2790` | `0x290c` | **`+0x17c`** |
| `__TEXT.__swift5_fieldmd` | `0x1f4c` | `0x2054` | **`+0x108`** |
| `__TEXT.__swift5_typeref` | `0x892c` | `0x8a34` | **`+0x108`** |
| `__DATA.__bss` | `0x7b60` | `0x7c60` | **`+0x100`** |
| `__DATA.__objc_data` | `0xef0` | `0xfe8` | **`+0xf8`** |
| `__TEXT.__unwind_info` | `0x2550` | `0x2640` | **`+0xf0`** |
| `__DATA.__common` | `0x120` | `0x1e1` | **`+0xc1`** |
| `__TEXT.__objc_methname` | `0x2285` | `0x2345` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x2060` | `0x2120` | **`+0xc0`** |
| `__TEXT.__objc_classname` | `0x174e` | `0x17fe` | **`+0xb0`** |
| `__TEXT.__auth_stubs` | `0x2540` | `0x25e0` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0x12a8` | `0x12f8` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0xa5c` | `0xaac` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x10c0` | `0x1100` | **`+0x40`** |
| `__DATA_CONST.__auth_ptr` | `0xdf0` | `0xe08` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x7a8` | `0x7c0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x50` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x410` | `0x41c` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x234` | `0x240` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x35c` | `0x368` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x610` | `0x618` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x8` | `0x10` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-38.0.0.0.0
+41.0.0.0.0

-  Functions: 2924
-  Symbols:   278
-  CStrings:  906
+  Functions: 2999
+  Symbols:   284
+  CStrings:  950
Symbols:
+ _NSDebugDescriptionErrorKey
+ _OBJC_CLASS_$_CATRemoteTaskOperation
+ _swift_isEscapingClosureAtFileLocation
+ _swift_task_deinitOnExecutor
+ _swift_task_getMainExecutor
+ _swift_task_isCurrentExecutor
CStrings:
+ "%s: transport event %{public}s — publishing transportDisconnected"
+ "AddDevicesToAutomatedDeviceEnrollmentExtension/AXMEnroller.swift"
+ "AddDevicesToAutomatedDeviceEnrollmentExtension/FakeCatalaystRequestPerforming.swift"
+ "An administrator for your organization needs to accept the latest Terms and Conditions in Apple School Manager or Apple Business before you can continue adding devices."
+ "CATRemoteTaskOperation.invalidRemoteTask returned nil in a test fake"
+ "Cannot Read Device Information"
+ "Enrollment Failed"
+ "Enrollment Timed Out"
+ "Fatal error"
+ "Incorrect actor executor assumption; Expected same executor as "
+ "Message for the alert shown when fetching the device's serial number or UDID fails after pairing."
+ "Message for the alert shown when sending enrollment information to the paired device fails."
+ "Message for the alert shown when the connection to the paired device is lost during enrollment."
+ "Message for the alert shown when the device cannot be enrolled because no Wi-Fi or network configuration is available to share."
+ "Message for the alert shown when the post-pair enrollment exceeds the per-operation timeout."
+ "Message for the alert shown when the user signs out before a paired device finishes enrolling."
+ "No Network Information"
+ "Sign in authentication mode could not be fetched: %@"
+ "Sign-In Required"
+ "The account used to start enrollment is no longer signed in. Please sign in again and retry adding the device."
+ "The connection to the device was lost before enrollment could finish. Please try adding the device again."
+ "The device could not be enrolled. Please try adding the device again."
+ "The device could not provide the information needed to enroll it. Please try adding the device again."
+ "The device took too long to respond. Please try adding the device again."
+ "There is no Wi-Fi or network configuration to share with the device. Please check your network selection and try again."
+ "Title for the alert shown when fetching the device's serial number or UDID fails after pairing."
+ "Title for the alert shown when sending enrollment information to the paired device fails."
+ "Title for the alert shown when the connection to the paired device is lost during enrollment."
+ "Title for the alert shown when the device cannot be enrolled because no Wi-Fi or network configuration is available to share."
+ "Title for the alert shown when the post-pair enrollment exceeds the per-operation timeout."
+ "Title for the alert shown when the user signs out before a paired device finishes enrolling."
+ "Unexpected resultObject from prerequisites operation: %{public}s"
+ "_TtC46AddDevicesToAutomatedDeviceEnrollmentExtension26FakeKeyValueCodableStorage"
+ "_TtC46AddDevicesToAutomatedDeviceEnrollmentExtension30FakeCatalaystRequestPerforming"
+ "fetchNonceError"
+ "handleTransportEvent(_:)"
+ "invalidRemoteTaskWithRequest:error:"
+ "isEnrollmentInFlight"
+ "isWatchdogArmed"
+ "lastReturnedOperation"
+ "nonceFetchTask"
+ "operationError"
+ "operationTimeout"
+ "transportEventSubject"
+ "transportSubscription"
+ "watchdogTimer"
- "An administrator for your organization needs to accept the latest Terms and Conditions in Apple School Manager or Apple Business in order to continue adding devices."
- "Unexpected resultObject from %@"
```
