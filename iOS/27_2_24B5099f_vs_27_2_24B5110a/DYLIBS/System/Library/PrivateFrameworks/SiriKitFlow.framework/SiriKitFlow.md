## SiriKitFlow

> `/System/Library/PrivateFrameworks/SiriKitFlow.framework/SiriKitFlow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x651928` | `0x650c5c` | **`-0xccc`** |
| `__AUTH_CONST.__const` | `0x3a9f8` | `0x3a3f0` | **`-0x608`** |
| `__TEXT.__oslogstring` | `0x24bb7` | `0x24f77` | **`+0x3c0`** |
| `__TEXT.__swift5_capture` | `0xfd9c` | `0xfafc` | **`-0x2a0`** |
| `__TEXT.__eh_frame` | `0x3a78c` | `0x3a81c` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x1c3d0` | `0x1c440` | **`+0x70`** |
| `__TEXT.__cstring` | `0x177d4` | `0x17834` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x3060` | `0x30a0` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x112d9` | `0x112fd` | **`+0x24`** |
| `__AUTH_CONST.__objc_const` | `0x11dd8` | `0x11db8` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x18a08` | `0x18a1c` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x2f24` | `0x2f38` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2bd0` | `0x2be0` | **`+0x10`** |
| `__DATA.__data` | `0xc588` | `0xc598` | **`+0x10`** |
| `__TEXT.__const` | `0x313d0` | `0x313e0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xed56` | `0xed46` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x3384` | `0x3390` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x1af8` | `0x1af0` | **`-0x8`** |
| `__TEXT.__swift5_fieldmd` | `0xed3c` | `0xed40` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x10c4` | `0x10c8` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x2bf8` | `0x2bfc` | **`+0x4`** |

### Other Changes

```diff

-3605.21.1.0.0
+3605.22.1.11.1

-  Functions: 40686
-  Symbols:   6463
-  CStrings:  4058
+  Functions: 40660
+  Symbols:   6464
+  CStrings:  4072
Symbols:
+ ___swift_closure_destructor.10Tm
+ ___swift_closure_destructor.37Tm
+ _symbolic _____ 11SiriKitFlow20SELFRequestHierarchyO
+ _symbolic _____Sg 11SiriKitFlow0aB7UIModelO27AppAccessCarPlayPromptModelV
+ _symbolic ySo19SISchemaRequestLinkCYbc
- _AFDeviceSupportsSAEByDeviceCapabilityAndFeatureFlags
- _OBJC_CLASS_$_AFFeatureFlags
- ___swift_closure_destructor.53Tm
- _symbolic ______p 11SiriKitFlow15FeatureCheckingP
CStrings:
+ "#SiriLocationAccessCheckFlow executeAccessCheck - bypassing guided access prompting on home accessory companion"
+ "#modes SiriEnvironment.forCurrentTask is nil; falling back to .root"
+ "#modes shouldPrintDialogForSmartDialog: executing for HomeAccessory -> return false"
+ "#modes shouldPrintDialogWhenNoVisuals: executing for HomeAccessory -> return false"
+ "#modes shouldUseAlwaysDisplay: executing for HomeAccessory -> return false"
+ "AppResolution ended with an error. Exiting..."
+ "Bypassing potential device unlock for HomeAccessory requests"
+ "COMPONENTNAME_RI"
+ "COMPONENTNAME_RISESSION"
+ "EAC: app-access prompt has no printable title or labels; not showing the CarPlay prompt"
+ "[CompanionCompatibilityCheckFlow] device cannot proceed with redirectToServerOnFailure, we will output error dialog"
+ "[MUX] Executing UserIdentityCheckFlow on HomeAccessory device. This flow is not supported on this platform: use HomeAccessoryIdentityCheckFlow instead."
+ "companionDeviceType"
+ "executingOnACompanion"
```
