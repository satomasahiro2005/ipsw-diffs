## LocalAuthenticationUIService

> `/Applications/LocalAuthenticationUIService.app/LocalAuthenticationUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f46c` | `0x6fdf4` | **`+0x988`** |
| `__TEXT.__objc_stubs` | `0x7260` | `0x75e0` | **`+0x380`** |
| `__TEXT.__objc_methname` | `0x9ad5` | `0x9cc5` | **`+0x1f0`** |
| `__DATA.__objc_selrefs` | `0x2620` | `0x26c0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x3c80` | `0x3d18` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x1ce8` | `0x1d48` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x710` | `0x74c` | **`+0x3c`** |
| `__DATA_CONST.__objc_intobj` | `0x408` | `0x438` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x28b7` | `0x28e7` | **`+0x30`** |
| `__DATA.__objc_const` | `0xc2f8` | `0xc318` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0xfe0` | `0x1000` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xb30` | `0xb50` | **`+0x20`** |
| `__TEXT.__cstring` | `0x15ee` | `0x15fe` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x338` | `0x33c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2319.40.35.0.1
+2319.40.43.0.0

-  Functions: 2745
-  Symbols:   8018
-  CStrings:  2403
+  Functions: 2760
+  Symbols:   8066
+  CStrings:  2426
Symbols:
+ -[PinView _applyInputTraitsToKeypad]
+ -[PinView _currentKeypadSize]
+ -[PinView _keypadFrameInBounds:]
+ -[PinView didMoveToWindow]
+ -[PinView invalidateKeypadLayout]
+ -[PinView safeAreaInsetsDidChange]
+ -[PinViewController viewWillTransitionToSize:withTransitionCoordinator:]
+ -[TouchIdViewController _alertActionOptions]
+ -[TouchIdViewController _isSensorOutOfReach]
+ -[TouchIdViewController _replaceLightweightUIWithAlertUIShakingGlyph:]
+ -[TouchIdViewController _sensorReachabilityDidChange]
+ -[TouchIdViewController _updateAlertController]
+ -[TouchIdViewControllerWithCoachings _sensorReachabilityDidChange]
+ -[TouchIdViewControllerWithCoachings _updateCoachingViewVisibility]
+ -[TouchIdViewModel alertActionsFromOptions:]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PasscodeContentViewControllerFullScreen-f006b6cd308f4822fd8f03e9d3811748.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PinViewController-469f79d5de40f58841639557848b699a.o
+ GCC_except_table0
+ GCC_except_table23
+ GCC_except_table41
+ GCC_except_table42
+ OBJC_IVAR_$_TouchIdViewController._sensorReachabilityMonitor
+ _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_s10_NativeSetVySo14UISceneSessionCG_s5NeverOTg506$ss13_ab8V013withd36B08capacity4bodyxSi_xABq_YKXEtq_YKs5i9R_r0_lFZxt12_YKXEfU_s10_kl6VySo14mn5CG_s5O4OTG5ABq_xRi_zRi0_zRi__Ri0__r0_lyApNIsgyrzr_Tf1nc_n06$ss10_kl29V6filteryAByxGSbxqd__YKXEqd__vi12Rd__lFADs13_ab5Vqd__y6U_So14mn4C_s5O4OTG5ANxSbq_Ri_zRi0_zRi__Ri0__r0_lyAmPIsgndzr_Tf1nc_n
+ _OBJC_CLASS_$_LACUITouchIDSensorReachabilityMonitor
+ _OBJC_CLASS_$_UITraitHorizontalSizeClass
+ _OBJC_CLASS_$_UITraitVerticalSizeClass
+ ___33-[TouchIdViewController loadView]_block_invoke
+ ___70-[TouchIdViewController _replaceLightweightUIWithAlertUIShakingGlyph:]_block_invoke
+ ___72-[PinViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
+ _objc_msgSend$_alertActionOptions
+ _objc_msgSend$_applyInputTraitsToKeypad
+ _objc_msgSend$_currentKeypadSize
+ _objc_msgSend$_isSensorOutOfReach
+ _objc_msgSend$_keypadFrameInBounds:
+ _objc_msgSend$_replaceLightweightUIWithAlertUIShakingGlyph:
+ _objc_msgSend$_sensorReachabilityDidChange
+ _objc_msgSend$_updateAlertController
+ _objc_msgSend$_updateCoachingViewVisibility
+ _objc_msgSend$alertActionsFromOptions:
+ _objc_msgSend$autocapitalizationType
+ _objc_msgSend$autocorrectionType
+ _objc_msgSend$defaultTextInputTraits
+ _objc_msgSend$deviceHasTouchIDSensorRequiringReachabilityMonitoring
+ _objc_msgSend$intrinsicContentSize
+ _objc_msgSend$invalidateKeypadLayout
+ _objc_msgSend$isSecureTextEntry
+ _objc_msgSend$isSensorOutOfReach
+ _objc_msgSend$keyboardAppearance
+ _objc_msgSend$keyboardSizeForInterfaceOrientation:
+ _objc_msgSend$keyboardType
+ _objc_msgSend$returnKeyType
+ _objc_msgSend$setAutocapitalizationType:
+ _objc_msgSend$setAutocorrectionType:
+ _objc_msgSend$setDefaultTextInputTraits:
+ _objc_msgSend$setSensorReachabilityDidChangeHandler:
+ _objc_msgSend$setSpellCheckingType:
+ _objc_msgSend$spellCheckingType
+ _objc_msgSend$start
+ _objc_msgSend$stop
- -[TouchIdViewController _replaceLightweightUIWithAlertUI]
- -[TouchIdViewControllerWithCoachings _updateCoachingInstructionVisibility]
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PasscodeContentViewControllerFullScreen-982d6894d4f053409cbbdf42170e850c.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PinViewController-70d28984536e4f1ac957531f9a16df6f.o
- GCC_except_table19
- GCC_except_table36
- GCC_except_table37
- _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_s10_NativeSetVySo14UISceneSessionCG_s5NeverOTg506$ss10_kl33V6filteryAByxGSbxqd__YKXEqd__YKs5i12Rd__lFADs13_ab16Vqd__YKXEfU_So14mn4C_s5O4OTG5ANxSbq_Ri_zRi0_zRi__Ri0__r0_lyAmPIsgndzr_Tf1nc_n
- ___57-[TouchIdViewController _replaceLightweightUIWithAlertUI]_block_invoke
- _objc_msgSend$_replaceLightweightUIWithAlertUI
- _objc_msgSend$_updateCoachingInstructionVisibility
CStrings:
+ "@\"<LACUITouchIDSensorReachabilityMonitoring>\""
+ "NoEarlyPasscode"
+ "_alertActionOptions"
+ "_applyInputTraitsToKeypad"
+ "_currentKeypadSize"
+ "_isSensorOutOfReach"
+ "_keypadFrameInBounds:"
+ "_replaceLightweightUIWithAlertUIShakingGlyph:"
+ "_sensorReachabilityDidChange"
+ "_sensorReachabilityMonitor"
+ "_updateAlertController"
+ "_updateCoachingViewVisibility"
+ "alertActionsFromOptions:"
+ "defaultTextInputTraits"
+ "deviceHasTouchIDSensorRequiringReachabilityMonitoring"
+ "didMoveToWindow"
+ "intrinsicContentSize"
+ "invalidateKeypadLayout"
+ "isSensorOutOfReach"
+ "keyboardSizeForInterfaceOrientation:"
+ "safeAreaInsetsDidChange"
+ "setDefaultTextInputTraits:"
+ "setSensorReachabilityDidChangeHandler:"
+ "start"
+ "stop"
- "_replaceLightweightUIWithAlertUI"
- "_updateCoachingInstructionVisibility"
```
