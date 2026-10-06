## AddDevicesToAutomatedDeviceEnrollmentExtension

> `/System/Library/Frameworks/AutomatedDeviceEnrollment.framework/PlugIns/AddDevicesToAutomatedDeviceEnrollmentExtension.appex/AddDevicesToAutomatedDeviceEnrollmentExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x951e4` | `0x971c0` | **`+0x1fdc`** |
| `__TEXT.__const` | `0x8ab4` | `0x8c94` | **`+0x1e0`** |
| `__TEXT.__eh_frame` | `0x44e8` | `0x46c8` | **`+0x1e0`** |
| `__DATA_CONST.__const` | `0x4a40` | `0x4be0` | **`+0x1a0`** |
| `__TEXT.__swift5_reflstr` | `0x290c` | `0x2aac` | **`+0x1a0`** |
| `__TEXT.__objc_methname` | `0x2345` | `0x24a5` | **`+0x160`** |
| `__DATA.__bss` | `0x7c60` | `0x7d90` | **`+0x130`** |
| `__DATA.__data` | `0x6928` | `0x6a50` | **`+0x128`** |
| `__DATA.__objc_const` | `0x3ac0` | `0x3be0` | **`+0x120`** |
| `__TEXT.__swift5_typeref` | `0x8a34` | `0x8b52` | **`+0x11e`** |
| `__TEXT.__constg_swiftt` | `0x366c` | `0x3778` | **`+0x10c`** |
| `__TEXT.__unwind_info` | `0x2640` | `0x26e0` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x2054` | `0x20e8` | **`+0x94`** |
| `__TEXT.__oslogstring` | `0x2120` | `0x21a0` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0xaac` | `0xb24` | **`+0x78`** |
| `__DATA.__objc_data` | `0xfe8` | `0x1030` | **`+0x48`** |
| `__TEXT.__cstring` | `0x4155` | `0x4175` | **`+0x20`** |
| `__DATA.__common` | `0x1e1` | `0x1f9` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xe08` | `0xe20` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x368` | `0x380` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x160` | `0x174` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x170` | `0x180` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x41c` | `0x424` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x240` | `0x244` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-41.0.0.0.0
+42.0.0.0.0

-  Functions: 2999
+  Functions: 3041

-  CStrings:  950
+  CStrings:  962
CStrings:
+ "%s authentication session invalid: %{public}s"
+ "%s authentication session is valid"
+ "%s no account to validate"
+ "_isEnrollmentInProgress"
+ "didValidateAuthenticationSession"
+ "isPausedForReauthentication"
+ "onValidateAuthenticationSession"
+ "reauthenticationStateSubject"
+ "reauthenticationSubscription"
+ "validateAuthenticationSession()"
+ "validateAuthenticationSessionCallCount"
+ "viewHostWillEnterForegroundObserver"
```
