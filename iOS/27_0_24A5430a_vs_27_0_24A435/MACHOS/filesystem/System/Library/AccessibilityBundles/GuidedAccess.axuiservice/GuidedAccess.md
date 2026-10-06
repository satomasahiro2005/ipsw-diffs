## GuidedAccess

> `/System/Library/AccessibilityBundles/GuidedAccess.axuiservice/GuidedAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f6fc` | `0x2f818` | **`+0x11c`** |
| `__DATA_CONST.__cfstring` | `0x2a00` | `0x2a80` | **`+0x80`** |
| `__TEXT.__cstring` | `0x3e48` | `0x3ec6` | **`+0x7e`** |
| `__TEXT.__objc_methtype` | `0x24f1` | `0x2530` | **`+0x3f`** |
| `__DATA_CONST.__const` | `0x1b38` | `0x1b48` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xc60` | `0xc70` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x640` | `0x648` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   669
-  CStrings:  2569
+  Symbols:   672
+  CStrings:  2573
Symbols:
+ _AXDeviceIsViridian
+ _GAXProfileAllowsDisplayChanges
+ _GAXProfileAllowsLayoutTransitions
Functions:
~ sub_5070 : 500 -> 556
~ sub_24778 -> sub_247b0 : 56 -> 132
~ sub_2dfa0 -> sub_2e024 : 2852 -> 2948
~ _gaxDebugDescriptionForGAXBackboardState : 764 -> 820
CStrings:
+ "  allowsDisplayChanges: %ld\n"
+ "  allowsLayoutTransitions: %ld\n"
+ "GAXProfileAllowsDisplayChanges"
+ "GAXProfileAllowsLayoutTransitions"
+ "v44@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16"
+ "v52@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16@?44"
+ "v60@0:8I16B20{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24q52"
+ "{?=\"mode\"I\"passcodeWindowContextID\"I\"voiceOverItemChooserWindowContextID\"I\"tripleClickSheetWindowContextID\"I\"assistiveTouchPort\"I\"profileConfiguration\"I\"shouldBlockAllEvents\"b1\"restartingAndWasActiveBeforeRestart\"b1\"verifyingDeviceUnlockInSAM\"b1\"isPasscodeViewVisible\"b1\"isRestricted\"b1\"overrideAllowsAllTouchSBMiniAlertIsShowing\"b1\"overrideAllowsAllTouchCallStateIsChanging\"b1\"overrideAllowsAllTouchMakingEmergencyCall\"b1\"overrideIgnoresAllTouchAllowedAppNotFound\"b1\"overrideIgnoresAllTouchVerifyingIntegrity\"b1\"allowsTouch\"b1\"allowsLockButton\"b1\"allowsAppExit\"b1\"allowsHomeButton\"b1\"allowsVolumeButtons\"b1\"allowsRingerSwitch\"b1\"allowsMotion\"b1\"allowsAutolock\"b1\"allowsKeyboardTextInput\"b1\"allowsProximity\"b1\"allowsLayoutTransitions\"b1\"allowsDisplayChanges\"b1}"
- "v44@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16"
- "v52@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16@?44"
- "v60@0:8I16B20{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24q52"
- "{?=\"mode\"I\"passcodeWindowContextID\"I\"voiceOverItemChooserWindowContextID\"I\"tripleClickSheetWindowContextID\"I\"assistiveTouchPort\"I\"profileConfiguration\"I\"shouldBlockAllEvents\"b1\"restartingAndWasActiveBeforeRestart\"b1\"verifyingDeviceUnlockInSAM\"b1\"isPasscodeViewVisible\"b1\"isRestricted\"b1\"overrideAllowsAllTouchSBMiniAlertIsShowing\"b1\"overrideAllowsAllTouchCallStateIsChanging\"b1\"overrideAllowsAllTouchMakingEmergencyCall\"b1\"overrideIgnoresAllTouchAllowedAppNotFound\"b1\"overrideIgnoresAllTouchVerifyingIntegrity\"b1\"allowsTouch\"b1\"allowsLockButton\"b1\"allowsAppExit\"b1\"allowsHomeButton\"b1\"allowsVolumeButtons\"b1\"allowsRingerSwitch\"b1\"allowsMotion\"b1\"allowsAutolock\"b1\"allowsKeyboardTextInput\"b1\"allowsProximity\"b1}"
```
