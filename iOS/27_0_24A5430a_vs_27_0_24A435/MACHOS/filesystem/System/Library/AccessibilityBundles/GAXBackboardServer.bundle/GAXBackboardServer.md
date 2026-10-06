## GAXBackboardServer

> `/System/Library/AccessibilityBundles/GAXBackboardServer.bundle/GAXBackboardServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b560` | `0x2b720` | **`+0x1c0`** |
| `__DATA_CONST.__cfstring` | `0x36a0` | `0x3720` | **`+0x80`** |
| `__TEXT.__cstring` | `0x46b9` | `0x4737` | **`+0x7e`** |
| `__TEXT.__objc_methtype` | `0x186b` | `0x18ca` | **`+0x5f`** |
| `__TEXT.__objc_stubs` | `0x6940` | `0x6980` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x8d43` | `0x8d7a` | **`+0x37`** |
| `__DATA.__objc_const` | `0x2a10` | `0x2a30` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2894` | `0x28ac` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1ec8` | `0x1ed8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x16a8` | `0x16b8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 965
-  Symbols:   581
-  CStrings:  2256
+  Functions: 967
+  Symbols:   583
+  CStrings:  2262
Symbols:
+ _GAXProfileAllowsDisplayChanges
+ _GAXProfileAllowsLayoutTransitions
CStrings:
+ "  allowsDisplayChanges: %ld\n"
+ "  allowsLayoutTransitions: %ld\n"
+ "B44@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16"
+ "B52@0:8@16{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24"
+ "B56@0:8@16I24{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}28"
+ "GAXProfileAllowsDisplayChanges"
+ "GAXProfileAllowsLayoutTransitions"
+ "shouldAllowDisplayChanges"
+ "shouldAllowLayoutTransitions"
+ "v44@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16"
+ "v52@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16@?44"
+ "v60@0:8I16B20{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24q52"
+ "v60@0:8Q16{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@?52"
+ "{?=\"mode\"I\"passcodeWindowContextID\"I\"voiceOverItemChooserWindowContextID\"I\"tripleClickSheetWindowContextID\"I\"assistiveTouchPort\"I\"profileConfiguration\"I\"shouldBlockAllEvents\"b1\"restartingAndWasActiveBeforeRestart\"b1\"verifyingDeviceUnlockInSAM\"b1\"isPasscodeViewVisible\"b1\"isRestricted\"b1\"overrideAllowsAllTouchSBMiniAlertIsShowing\"b1\"overrideAllowsAllTouchCallStateIsChanging\"b1\"overrideAllowsAllTouchMakingEmergencyCall\"b1\"overrideIgnoresAllTouchAllowedAppNotFound\"b1\"overrideIgnoresAllTouchVerifyingIntegrity\"b1\"allowsTouch\"b1\"allowsLockButton\"b1\"allowsAppExit\"b1\"allowsHomeButton\"b1\"allowsVolumeButtons\"b1\"allowsRingerSwitch\"b1\"allowsMotion\"b1\"allowsAutolock\"b1\"allowsKeyboardTextInput\"b1\"allowsProximity\"b1\"allowsLayoutTransitions\"b1\"allowsDisplayChanges\"b1}"
+ "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16@0:8"
+ "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@0:8@\"GAXEventProcessor\"16"
+ "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@0:8@\"GAXVerifier\"16"
+ "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@0:8@16"
- "B44@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16"
- "B52@0:8@16{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24"
- "B56@0:8@16I24{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}28"
- "v44@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16"
- "v52@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16@?44"
- "v60@0:8I16B20{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24q52"
- "v60@0:8Q16{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@?52"
- "{?=\"mode\"I\"passcodeWindowContextID\"I\"voiceOverItemChooserWindowContextID\"I\"tripleClickSheetWindowContextID\"I\"assistiveTouchPort\"I\"profileConfiguration\"I\"shouldBlockAllEvents\"b1\"restartingAndWasActiveBeforeRestart\"b1\"verifyingDeviceUnlockInSAM\"b1\"isPasscodeViewVisible\"b1\"isRestricted\"b1\"overrideAllowsAllTouchSBMiniAlertIsShowing\"b1\"overrideAllowsAllTouchCallStateIsChanging\"b1\"overrideAllowsAllTouchMakingEmergencyCall\"b1\"overrideIgnoresAllTouchAllowedAppNotFound\"b1\"overrideIgnoresAllTouchVerifyingIntegrity\"b1\"allowsTouch\"b1\"allowsLockButton\"b1\"allowsAppExit\"b1\"allowsHomeButton\"b1\"allowsVolumeButtons\"b1\"allowsRingerSwitch\"b1\"allowsMotion\"b1\"allowsAutolock\"b1\"allowsKeyboardTextInput\"b1\"allowsProximity\"b1}"
- "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16@0:8"
- "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@0:8@\"GAXEventProcessor\"16"
- "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@0:8@\"GAXVerifier\"16"
- "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@0:8@16"
```
