## SIMSetupSupport

> `/System/Library/PrivateFrameworks/SIMSetupSupport.framework/SIMSetupSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe337c` | `0xe6494` | **`+0x3118`** |
| `__AUTH_CONST.__objc_const` | `0x4e0c8` | `0x4f8d8` | **`+0x1810`** |
| `__TEXT.__cstring` | `0x175c9` | `0x17aa0` | **`+0x4d7`** |
| `__TEXT.__objc_methlist` | `0xc474` | `0xc7ec` | **`+0x378`** |
| `__AUTH_CONST.__cfstring` | `0xab20` | `0xae60` | **`+0x340`** |
| `__TEXT.__oslogstring` | `0x8af5` | `0x8c70` | **`+0x17b`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e38` | `0x5f58` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x35c0` | `0x36b0` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x2fa8` | `0x3080` | **`+0xd8`** |
| `__DATA.__data` | `0xc70` | `0xd30` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x2120` | `0x218c` | **`+0x6c`** |
| `__DATA.__objc_ivar` | `0x130c` | `0x1358` | **`+0x4c`** |
| `__AUTH_CONST.__const` | `0xba0` | `0xbc0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xbf0` | `0xc10` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x7e0` | `0x7f8` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x578` | `0x590` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x518` | `0x530` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x108` | `0x118` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x2128` | `0x2130` | **`+0x8`** |

### Other Changes

```diff

+  - /System/Library/Frameworks/CallKit.framework/CallKit

-  Functions: 4889
-  Symbols:   7864
-  CStrings:  3110
+  Functions: 4970
+  Symbols:   7994
+  CStrings:  3151
Symbols:
+ +[TSSIMSetupFlow _maybeCreateSIMConfigFlowAsPreFlow:options:]
+ +[TSSIMSetupFlow _simConfigSwitchPreFlowForDeviceIdentifierOptions:]
+ -[SSSIMConfigSwitchFailedViewController .cxx_destruct]
+ -[SSSIMConfigSwitchFailedViewController _okTapped]
+ -[SSSIMConfigSwitchFailedViewController backOption]
+ -[SSSIMConfigSwitchFailedViewController delegate]
+ -[SSSIMConfigSwitchFailedViewController initWithSwitchToEuicc:parentFlowType:]
+ -[SSSIMConfigSwitchFailedViewController setDelegate:]
+ -[SSSIMConfigSwitchFailedViewController setSwitchToEuicc:]
+ -[SSSIMConfigSwitchFailedViewController switchToEuicc]
+ -[SSSIMConfigSwitchFailedViewController viewDidLoad]
+ -[SSSIMConfigSwitchFailedViewController viewWillAppear:]
+ -[SSSIMConfigSwitchViewController .cxx_destruct]
+ -[SSSIMConfigSwitchViewController _buildBodyMessageForSwitchToEuicc:]
+ -[SSSIMConfigSwitchViewController _cancelTapped]
+ -[SSSIMConfigSwitchViewController _continueTapped]
+ -[SSSIMConfigSwitchViewController _titleForFlowType:]
+ -[SSSIMConfigSwitchViewController _updateContinueButton]
+ -[SSSIMConfigSwitchViewController animating]
+ -[SSSIMConfigSwitchViewController backOption]
+ -[SSSIMConfigSwitchViewController cachedButtons]
+ -[SSSIMConfigSwitchViewController callObserver:callChanged:]
+ -[SSSIMConfigSwitchViewController callObserver]
+ -[SSSIMConfigSwitchViewController customizeSpinner]
+ -[SSSIMConfigSwitchViewController delegate]
+ -[SSSIMConfigSwitchViewController forceShow]
+ -[SSSIMConfigSwitchViewController initWithSwitchToEuicc:forceShow:flowType:]
+ -[SSSIMConfigSwitchViewController prepare:]
+ -[SSSIMConfigSwitchViewController setAnimating:]
+ -[SSSIMConfigSwitchViewController setCachedButtons:]
+ -[SSSIMConfigSwitchViewController setCallObserver:]
+ -[SSSIMConfigSwitchViewController setDelegate:]
+ -[SSSIMConfigSwitchViewController setForceShow:]
+ -[SSSIMConfigSwitchViewController setSpinner:]
+ -[SSSIMConfigSwitchViewController setSpinnerContainer:]
+ -[SSSIMConfigSwitchViewController setSwitchSucceeded:]
+ -[SSSIMConfigSwitchViewController setSwitchToEuicc:]
+ -[SSSIMConfigSwitchViewController spinnerContainer]
+ -[SSSIMConfigSwitchViewController spinner]
+ -[SSSIMConfigSwitchViewController switchSucceeded]
+ -[SSSIMConfigSwitchViewController switchToEuicc]
+ -[SSSIMConfigSwitchViewController viewDidLoad]
+ -[SSSIMConfigSwitchViewController viewWillAppear:]
+ -[TSCoreTelephonyClientCache appForegrounded]
+ -[TSCoreTelephonyClientCache isEuiccActiveCache]
+ -[TSCoreTelephonyClientCache requestEUICCHardware:completion:]
+ -[TSCoreTelephonyClientCache setIsEuiccActiveCache:]
+ -[TSCoreTelephonyClientCache simHardwareConfigurationChanged:]
+ -[TSQRCodeScanFlow _resetDeferredState]
+ -[TSQRCodeScanFlow _shouldDeferSwitchForCardData:]
+ -[TSQRCodeScanFlow _simConfigSwitchSubFlowVC]
+ -[TSSIMConfigSwitchFlow .cxx_destruct]
+ -[TSSIMConfigSwitchFlow _iseSIMInstallFlow]
+ -[TSSIMConfigSwitchFlow _maybePresentFirstViewController:firstViewControllerCallback:]
+ -[TSSIMConfigSwitchFlow cancelButton]
+ -[TSSIMConfigSwitchFlow firstViewController:]
+ -[TSSIMConfigSwitchFlow firstViewController]
+ -[TSSIMConfigSwitchFlow initWithFlowOptions:]
+ -[TSSIMConfigSwitchFlow initWithSwitchToEuicc:]
+ -[TSSIMConfigSwitchFlow isBootstrapAssertionRequired]
+ -[TSSIMConfigSwitchFlow nextViewControllerFrom:]
+ -[TSSIMConfigSwitchFlow optionsForNextFlow]
+ -[TSSIMConfigSwitchFlow setCancelButton:]
+ -[TSSIMConfigSwitchFlow setCancelNavigationBarItems:]
+ -[TSSIMConfigSwitchFlow setOptionsForNextFlow:]
+ -[TSSIMConfigSwitchFlow setSwitchToEuicc:]
+ -[TSSIMConfigSwitchFlow switchToEuicc]
+ GCC_except_table38
+ GCC_except_table51
+ _OBJC_CLASS_$_CXCallObserver
+ _OBJC_CLASS_$_SSSIMConfigSwitchFailedViewController
+ _OBJC_CLASS_$_SSSIMConfigSwitchViewController
+ _OBJC_CLASS_$_TSSIMConfigSwitchFlow
+ _OBJC_IVAR_$_SSSIMConfigSwitchFailedViewController._delegate
+ _OBJC_IVAR_$_SSSIMConfigSwitchFailedViewController._okButton
+ _OBJC_IVAR_$_SSSIMConfigSwitchFailedViewController._okButtonTitle
+ _OBJC_IVAR_$_SSSIMConfigSwitchFailedViewController._switchToEuicc
+ _OBJC_IVAR_$_SSSIMConfigSwitchViewController._animating
+ _OBJC_IVAR_$_SSSIMConfigSwitchViewController._cachedButtons
+ _OBJC_IVAR_$_SSSIMConfigSwitchViewController._callObserver
+ _OBJC_IVAR_$_SSSIMConfigSwitchViewController._cancelButton
+ _OBJC_IVAR_$_SSSIMConfigSwitchViewController._continueButton
+ _OBJC_IVAR_$_SSSIMConfigSwitchViewController._delegate
+ _OBJC_IVAR_$_SSSIMConfigSwitchViewController._forceShow
+ _OBJC_IVAR_$_SSSIMConfigSwitchViewController._spinner
+ _OBJC_IVAR_$_SSSIMConfigSwitchViewController._spinnerContainer
+ _OBJC_IVAR_$_SSSIMConfigSwitchViewController._switchSucceeded
+ _OBJC_IVAR_$_SSSIMConfigSwitchViewController._switchToEuicc
+ _OBJC_IVAR_$_TSCoreTelephonyClientCache._isEuiccActiveCache
+ _OBJC_IVAR_$_TSSIMConfigSwitchFlow._cancelButton
+ _OBJC_IVAR_$_TSSIMConfigSwitchFlow._optionsForNextFlow
+ _OBJC_IVAR_$_TSSIMConfigSwitchFlow._switchToEuicc
+ _OBJC_METACLASS_$_SSSIMConfigSwitchFailedViewController
+ _OBJC_METACLASS_$_SSSIMConfigSwitchViewController
+ _OBJC_METACLASS_$_TSSIMConfigSwitchFlow
+ _TSUserInfoSIMConfigSwitchToEuiccKey
+ __OBJC_$_INSTANCE_METHODS_SSSIMConfigSwitchFailedViewController
+ __OBJC_$_INSTANCE_METHODS_SSSIMConfigSwitchViewController
+ __OBJC_$_INSTANCE_METHODS_TSSIMConfigSwitchFlow
+ __OBJC_$_INSTANCE_VARIABLES_SSSIMConfigSwitchFailedViewController
+ __OBJC_$_INSTANCE_VARIABLES_SSSIMConfigSwitchViewController
+ __OBJC_$_INSTANCE_VARIABLES_TSSIMConfigSwitchFlow
+ __OBJC_$_PROP_LIST_SSSIMConfigSwitchFailedViewController
+ __OBJC_$_PROP_LIST_SSSIMConfigSwitchViewController
+ __OBJC_$_PROP_LIST_TSSIMConfigSwitchFlow
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CXCallObserverDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CoreTelephonyClientSimHardwareConfigurationDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CXCallObserverDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CoreTelephonyClientSimHardwareConfigurationDelegate
+ __OBJC_$_PROTOCOL_REFS_CXCallObserverDelegate
+ __OBJC_$_PROTOCOL_REFS_CoreTelephonyClientSimHardwareConfigurationDelegate
+ __OBJC_CLASS_PROTOCOLS_$_SSSIMConfigSwitchFailedViewController
+ __OBJC_CLASS_PROTOCOLS_$_SSSIMConfigSwitchViewController
+ __OBJC_CLASS_PROTOCOLS_$_TSCoreTelephonyClientCache
+ __OBJC_CLASS_PROTOCOLS_$_TSSIMConfigSwitchFlow
+ __OBJC_CLASS_RO_$_SSSIMConfigSwitchFailedViewController
+ __OBJC_CLASS_RO_$_SSSIMConfigSwitchViewController
+ __OBJC_CLASS_RO_$_TSSIMConfigSwitchFlow
+ __OBJC_LABEL_PROTOCOL_$_CXCallObserverDelegate
+ __OBJC_LABEL_PROTOCOL_$_CoreTelephonyClientSimHardwareConfigurationDelegate
+ __OBJC_METACLASS_RO_$_SSSIMConfigSwitchFailedViewController
+ __OBJC_METACLASS_RO_$_SSSIMConfigSwitchViewController
+ __OBJC_METACLASS_RO_$_TSSIMConfigSwitchFlow
+ __OBJC_PROTOCOL_$_CXCallObserverDelegate
+ __OBJC_PROTOCOL_$_CoreTelephonyClientSimHardwareConfigurationDelegate
+ ___46-[TSQRCodeScanFlow viewControllerDidComplete:]_block_invoke
+ ___46-[TSQRCodeScanFlow viewControllerDidComplete:]_block_invoke_2
+ ___50-[SSSIMConfigSwitchViewController _continueTapped]_block_invoke
+ ___62-[TSCoreTelephonyClientCache requestEUICCHardware:completion:]_block_invoke
+ ___86-[TSSIMConfigSwitchFlow _maybePresentFirstViewController:firstViewControllerCallback:]_block_invoke
CStrings:
+ "-[TSCoreTelephonyClientCache isESIMUnavailable]"
+ "-[TSCoreTelephonyClientCache requestEUICCHardware:completion:]_block_invoke"
+ "-[TSCoreTelephonyClientCache simHardwareConfigurationChanged:]"
+ "-[TSQRCodeScanFlow viewControllerDidComplete:]"
+ "-[TSSIMConfigSwitchFlow _maybePresentFirstViewController:firstViewControllerCallback:]"
+ "-[TSSIMConfigSwitchFlow _maybePresentFirstViewController:firstViewControllerCallback:]_block_invoke"
+ "-[TSSIMConfigSwitchFlow firstViewController]"
+ "Localizable-V63"
+ "SIM config switch succeeded, triggering deferred install @%s"
+ "SIM hardware configuration changed: isEuiccActive=%@ @%s"
+ "SIMConfigCancelButton"
+ "SIMConfigContinueButton"
+ "SIMConfigOKButton"
+ "SIMConfigSwitch"
+ "SIMConfigSwitchToEuiccKey"
+ "SS_SIM_CONFIG_BACK_SIM_ROW_%@"
+ "SS_SIM_CONFIG_CANCEL"
+ "SS_SIM_CONFIG_CURRENT_PE"
+ "SS_SIM_CONFIG_CURRENT_PP"
+ "SS_SIM_CONFIG_DONE"
+ "SS_SIM_CONFIG_ESIM1_ROW_%@"
+ "SS_SIM_CONFIG_ESIM2_ROW_%@"
+ "SS_SIM_CONFIG_ESIM_ROW_%@"
+ "SS_SIM_CONFIG_FRONT_SIM_ROW_%@"
+ "SS_SIM_CONFIG_NO_ACTIVE_NUMBERS"
+ "SS_SIM_CONFIG_SUGGEST_PE"
+ "SS_SIM_CONFIG_SUGGEST_PP"
+ "SS_SIM_CONFIG_SWITCHING_FOR_BACK_SIM"
+ "SS_SIM_CONFIG_SWITCHING_FOR_ESIM"
+ "SS_SIM_CONFIG_SWITCH_FAILED_MESSAGE_CURRENT_CONFIG_PE"
+ "SS_SIM_CONFIG_SWITCH_FAILED_MESSAGE_CURRENT_CONFIG_PP"
+ "SS_SIM_CONFIG_SWITCH_FAILED_TITLE"
+ "SS_SIM_CONFIG_TITLE"
+ "SS_SIM_CONFIG_TITLE_SHARE_IDENTIFIERS"
+ "SS_SIM_CONFIG_USE_DUAL_PSIM_BUTTON"
+ "SS_SIM_CONFIG_USE_ESIM_BUTTON"
+ "[E]Device does not support dynamic SIM configuration @%s"
+ "[E]Failed to query isEuiccActive: %@ @%s"
+ "[E]SIM config switch did not occur (isEuiccActive=%@, error=%@), cancelling QR scan flow @%s"
+ "[E]no deferred data; cancelling flow @%s"
+ "[E]sim config failed. %@ @%s"
```
