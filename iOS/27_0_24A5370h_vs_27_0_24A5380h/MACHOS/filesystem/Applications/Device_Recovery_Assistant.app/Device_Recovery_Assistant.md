## Device Recovery Assistant

> `/Applications/Device Recovery Assistant.app/Device Recovery Assistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f290` | `0x1e18c` | **`-0x1104`** |
| `__DATA.__objc_const` | `0x6ad8` | `0x64c8` | **`-0x610`** |
| `__TEXT.__objc_methname` | `0x8bcb` | `0x88a2` | **`-0x329`** |
| `__TEXT.__objc_stubs` | `0x63e0` | `0x6120` | **`-0x2c0`** |
| `__TEXT.__objc_methlist` | `0x2f08` | `0x2d18` | **`-0x1f0`** |
| `__TEXT.__oslogstring` | `0x3650` | `0x34ef` | **`-0x161`** |
| `__TEXT.__cstring` | `0x3644` | `0x3553` | **`-0xf1`** |
| `__DATA.__objc_selrefs` | `0x2340` | `0x2260` | **`-0xe0`** |
| `__TEXT.__objc_methtype` | `0x261b` | `0x2551` | **`-0xca`** |
| `__DATA.__data` | `0xd9c` | `0xcdc` | **`-0xc0`** |
| `__DATA.__objc_data` | `0xb90` | `0xaf0` | **`-0xa0`** |
| `__DATA_CONST.__cfstring` | `0x1a00` | `0x1960` | **`-0xa0`** |
| `__TEXT.__objc_classname` | `0x6f2` | `0x689` | **`-0x69`** |
| `__DATA_CONST.__const` | `0x9f0` | `0xa18` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x708` | `0x6e0` | **`-0x28`** |
| `__TEXT.__gcc_except_tab` | `0xf8` | `0x118` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x21c` | `0x200` | **`-0x1c`** |
| `__DATA_CONST.__objc_intobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x128` | `0x118` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x120` | `0x110` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x118` | `0x108` | **`-0x10`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`

### Other Changes

```diff

-144.0.0.0.0
+148.0.0.0.0

+  - /System/Library/Frameworks/LocalAuthenticationEmbeddedUI.framework/LocalAuthenticationEmbeddedUI

-  Functions: 813
-  Symbols:   307
-  CStrings:  2389
+  Functions: 781
+  Symbols:   306
+  CStrings:  2328
Symbols:
+ _OBJC_CLASS_$_LAPasscodeVerificationService
+ _OBJC_CLASS_$_LAPasscodeVerificationServiceOptions
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ _objc_copyWeak
+ _objc_initWeak
- _DeviceRecoveryErrorAttributePasscodeBackOffEndDate
- _DeviceRecoveryErrorDomain
- _OBJC_CLASS_$_BFFComplexPasscodeInputView
- _OBJC_CLASS_$_BFFSimplePasscodeInputView
- _objc_setProperty_atomic_copy
- _os_variant_allows_internal_security_policies
CStrings:
+ "%{public}s: Dismissing passcode."
+ "%{public}s: Passcode verification failed: %{public}@"
+ "%{public}s: Passcode verified via LAPasscodeVerificationService."
+ "%{public}s: Pushing passcode container onto stack."
+ "-[SceneDelegate dismissPasscode]"
+ "-[SceneDelegate showPasscodeView]_block_invoke"
+ "-[SceneDelegate showPasscodeView]_block_invoke_2"
+ "@\"LAContext\""
+ "@\"LAPasscodeVerificationService\""
+ "T@\"LAContext\",&,V_laContext"
+ "T@\"LAPasscodeVerificationService\",&,V_passcodeService"
+ "_laContext"
+ "_passcodeService"
+ "_passcodeTypeForUnlockScreenType:simplePasscodeType:"
+ "addChildViewController:"
+ "didMoveToParentViewController:"
+ "dismissPasscode"
+ "externalizedContext"
+ "laContext"
+ "passcodeService"
+ "q24@0:8i16i20"
+ "setDismissUIAfterCompletion:"
+ "setLaContext:"
+ "setNavigationBarHidden:animated:"
+ "setPasscodeService:"
+ "setPasscodeType:"
+ "setUserId:"
+ "startInParentVC:options:completion:"
+ "v24@?0@\"LAContext\"8@\"NSError\"16"
- "%{public}s: Calling didAuthenticate on delegate."
- "%{public}s: Device passcode is 4 digits"
- "%{public}s: Device passcode is 6 digits"
- "%{public}s: Device passcode is not simple"
- "%{public}s: Device passcode type is not known"
- "%{public}s: Enabling passcode VC."
- "%{public}s: Next button pressed. Calling didAuthenticate on delegate."
- "%{public}s: Passcode screen did provide passcode."
- "%{public}s: Pushing lockout screen onto stack."
- "%{public}s: Pushing passcode screen onto stack."
- "%{public}s: self.navigationController.topViewController is not a PasscodeViewController."
- "-[PasscodeViewController nextButtonPressed:]"
- "-[PasscodeViewController numberOfCharactersInSimpleDevicePasscode]"
- "-[PasscodeViewController passcodeInput:enteredPasscode:]"
- "-[SceneDelegate passcodeViewController:didEnterPasscode:]"
- "-[SceneDelegate resetPasscodeView]"
- "-[SceneDelegate showLockoutViewUntilDate:]"
- "@\"<PasscodeViewControllerDelegate>\""
- "@\"BFFPasscodeInputView\""
- "@\"NSDate\""
- "BFFPasscodeInputViewDelegate"
- "LOCKOUT_DETAIL_FORMAT"
- "LOCKOUT_TITLE"
- "LockoutViewController"
- "NEXT_BUTTON_TITLE"
- "PASSCODE_SCREEN_TITLE"
- "PasscodeViewController"
- "PasscodeViewControllerDelegate"
- "T@\"<PasscodeViewControllerDelegate>\",W,V_delegate"
- "T@\"BFFPasscodeInputView\",&,V_passcodeInputView"
- "T@\"NSDate\",C,V_endDate"
- "T@\"NSTimer\",&,V_activityTimer"
- "T@\"NSTimer\",&,V_lockoutTimer"
- "T@\"UIBarButtonItem\",&,V_nextItem"
- "T@\"UIBarButtonItem\",&,V_spinnerItem"
- "_activityTimer"
- "_descriptionStringForEndDate:"
- "_endDate"
- "_lockoutTimer"
- "_nextItem"
- "_passcodeInputView"
- "_spinnerItem"
- "activityTimer"
- "code"
- "deviceHasComplexNumericPasscode"
- "deviceHasSimplePasscode"
- "disable"
- "domain"
- "enable"
- "endDate"
- "initWithEndDate:"
- "initWithFrame:numberOfEntryFields:"
- "initWithFrame:numericOnly:"
- "initWithTitle:detailText:symbolName:contentLayout:"
- "lock"
- "lockoutTimer"
- "nextButtonPressed:"
- "nextItem"
- "now"
- "numberOfCharactersInSimpleDevicePasscode"
- "passcode"
- "passcodeInput:enteredPasscode:"
- "passcodeInput:tappedFooterButton:"
- "passcodeInput:willChangeContents:"
- "passcodeInputTappedInstructionsLink:"
- "passcodeInputView"
- "passcodeViewController:didEnterPasscode:"
- "popViewControllerAnimated:"
- "resetPasscodeView"
- "scheduledTimerWithTimeInterval:repeats:block:"
- "setActivityTimer:"
- "setEndDate:"
- "setHidesBackButton:animated:"
- "setLimitCharactersToNumbers:"
- "setLockoutTimer:"
- "setNextItem:"
- "setPasscode:"
- "setPasscodeInputView:"
- "setSpinnerItem:"
- "setZeroFormattingBehavior:"
- "showLockoutViewUntilDate:"
- "spinnerItem"
- "timeIntervalSinceDate:"
- "topViewController"
- "v16@?0@\"NSTimer\"8"
- "v24@0:8@\"BFFPasscodeInputView\"16"
- "v24@0:8@\"NSDate\"16"
- "v32@0:8@\"BFFPasscodeInputView\"16@\"NSString\"24"
- "v32@0:8@\"BFFPasscodeInputView\"16@\"UIButton\"24"
- "v32@0:8@\"PasscodeViewController\"16@\"NSString\"24"
```
