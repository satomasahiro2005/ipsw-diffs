## AccessorySetupUI

> `/Applications/AccessorySetupUI.app/AccessorySetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9c0ac` | `0x9f860` | **`+0x37b4`** |
| `__DATA_CONST.__const` | `0x6160` | `0x63e0` | **`+0x280`** |
| `__TEXT.__objc_methname` | `0x5f47` | `0x6111` | **`+0x1ca`** |
| `__TEXT.__oslogstring` | `0x31aa` | `0x32aa` | **`+0x100`** |
| `__TEXT.__swift5_capture` | `0x1f98` | `0x2098` | **`+0x100`** |
| `__TEXT.__cstring` | `0x2d2f` | `0x2e0f` | **`+0xe0`** |
| `__DATA.__objc_const` | `0x40c8` | `0x4190` | **`+0xc8`** |
| `__TEXT.__objc_stubs` | `0x3680` | `0x3740` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x1913` | `0x19c3` | **`+0xb0`** |
| `__TEXT.__auth_stubs` | `0x1e00` | `0x1e90` | **`+0x90`** |
| `__DATA.__data` | `0x2968` | `0x29e8` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x2b6e` | `0x2bd4` | **`+0x66`** |
| `__TEXT.__unwind_info` | `0x1458` | `0x14b8` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x1be8` | `0x1c38` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x1598` | `0x15e0` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0xf08` | `0xf50` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x158c` | `0x15d4` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x1830` | `0x1870` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x2029` | `0x2059` | **`+0x30`** |
| `__DATA.__objc_data` | `0x2fc0` | `0x2fe0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x648` | `0x660` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x708` | `0x718` | **`+0x10`** |
| `__TEXT.__const` | `0x26e4` | `0x26f4` | **`+0x10`** |
| `__DATA.__common` | `0xd1` | `0xd9` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0xca8` | `0xcb0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2700.22.0.0.0
+2700.26.0.0.0

+  - /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag

+  - /System/Library/PrivateFrameworks/Sharing.framework/Sharing

-  Functions: 2468
-  Symbols:   886
-  CStrings:  1631
+  Functions: 2528
+  Symbols:   900
+  CStrings:  1658
Symbols:
+ _$s8Dispatch0A8WorkItemC5flags5blockAcA0abC5FlagsV_yyXBtcfc
+ _$s8Dispatch0A8WorkItemC6cancelyyFTj
+ _$s8Dispatch0A8WorkItemCMa
+ _$s8Dispatch0A8WorkItemCMn
+ _$sSo17OS_dispatch_queueC8DispatchE10asyncAfter8deadline7executeyAC0D4TimeV_AC0D8WorkItemCtF
+ _$ss5Int32VMn
+ _CFPreferencesAppSynchronize
+ _CFPreferencesCopyAppValue
+ _MKBGetDeviceLockState
+ _OBJC_CLASS_$_NSNotificationCenter
+ _OBJC_CLASS_$_SFClient
+ _SBSRequestPasscodeUnlockUI
+ _kMobileKeyBagLockStatusNotifyToken
+ _notify_cancel
+ _notify_register_dispatch
- _swift_retain_x11
CStrings:
+ "ASUIDeviceLockStateChanged"
+ "Bluetooth restriction changed, restricted: %{bool}d, reason: %ld"
+ "Requesting device unlock"
+ "SBParentalControlsCapabilities"
+ "Sharing declined prox card transaction; another prox card is active"
+ "Timed out waiting for Sharing prox card transaction response"
+ "Unlock to Set Up"
+ "_canShowWhileLocked"
+ "_isSecure"
+ "addObserver:selector:name:object:"
+ "com.apple.Preferences.ChangedRestrictionsEnabledStateNotification"
+ "com.apple.springboard"
+ "defaultCenter"
+ "defaultPrimaryButtonTitle"
+ "deviceLockNotifyToken"
+ "deviceLockStateDidChange"
+ "invalidateSession"
+ "kTCCServiceBluetoothAlways"
+ "lastBluetoothRestricted"
+ "postNotificationName:object:"
+ "proxCardSharingClient"
+ "proxCardTransactionTimeoutWork"
+ "removeObserver:name:object:"
+ "restrictionsNotifyToken"
+ "startProxCardTransactionWithOptions:completion:"
+ "unlockInProgress"
+ "v12@?0C8"
+ "v12@?0i8"
- "bluetoothRestricted"
```
