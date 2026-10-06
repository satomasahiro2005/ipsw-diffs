## InstalledContentLibrary

> `/System/Library/PrivateFrameworks/InstalledContentLibrary.framework/InstalledContentLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcee84` | `0xd3b00` | **`+0x4c7c`** |
| `__TEXT.__cstring` | `0x183ee` | `0x18bee` | **`+0x800`** |
| `__AUTH_CONST.__objc_const` | `0xa7d0` | `0xac00` | **`+0x430`** |
| `__TEXT.__objc_methlist` | `0x5be4` | `0x5eb4` | **`+0x2d0`** |
| `__AUTH_CONST.__cfstring` | `0xd4a0` | `0xd6c0` | **`+0x220`** |
| `__TEXT.__eh_frame` | `0x398` | `0x558` | **`+0x1c0`** |
| `__TEXT.__unwind_info` | `0x19f0` | `0x1b20` | **`+0x130`** |
| `__DATA_CONST.__objc_selrefs` | `0x30c0` | `0x31e0` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x1180` | `0x1260` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x1000` | `0x1078` | **`+0x78`** |
| `__AUTH.__data` | `0x78` | `0xd8` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0xc10` | `0xc68` | **`+0x58`** |
| `__DATA.__data` | `0xf38` | `0xf88` | **`+0x50`** |
| `__TEXT.__const` | `0xdb30` | `0xdb50` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x4f0` | `0x508` | **`+0x18`** |
| `__DATA.__bss` | `0x2d0` | `0x2e0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x228` | `0x238` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x30` | `0x38` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x5cc` | `0x5d0` | **`+0x4`** |

### Other Changes

```diff

-1674.2.1.0.0
+1680.40.6.502.1

-  Functions: 2412
-  Symbols:   3840
-  CStrings:  2262
+  Functions: 2510
+  Symbols:   3885
+  CStrings:  2306
Symbols:
+ -[ICLBundleRecord appReplacementSourceBundleIdentifier]
+ -[ICLBundleRecord setAppReplacementSourceBundleIdentifier:]
+ -[ICLWorkspace getAppLaunchProhibition:forBundleContainerURL:error:]
+ -[ICLWorkspace getAppReplacementState:forBundleContainerURL:error:]
+ -[MIBundle hasAtLeastOneExtensionImplementingExtensionPointIn:error:]
+ -[MIBundleContainer appLaunchProhibitionURL]
+ -[MIBundleContainer appReplacementStateURL]
+ -[MIBundleContainer getAppLaunchProhibition:withError:]
+ -[MIBundleContainer getAppReplacementState:withError:]
+ -[MIBundleContainer removeAppLaunchProhibitionWithError:]
+ -[MIBundleContainer removeAppReplacementStateWithError:]
+ -[MIBundleContainer saveAppLaunchProhibition:withError:]
+ -[MIBundleContainer saveAppReplacementState:withError:]
+ -[MIDataContainer supersedeExistingContainer:error:]
+ -[MIGlobalConfiguration OSBuildVersionWithError:]
+ -[MIMCMContainer supersedeExistingContainer:error:]
+ GCC_except_table56
+ _MIAppExtensionPointToExtensionPointIdentifierString
+ _MIAppReplacementMinimumBuildVersion
+ _MIAppReplacementStatusExpectsSourceAppIdentity
+ _MICopySupersededApplicationIdentifiersEntitlement
+ _MIHasHomeKitEntitlement
+ _MIIsRecordableAppReplacementStatus
+ _MIStringForAppReplacementStatus
+ _OBJC_CLASS_$_MIAppLaunchProhibition
+ _OBJC_CLASS_$_MIAppReplacementState
+ _OBJC_IVAR_$_ICLBundleRecord._appReplacementSourceBundleIdentifier
+ _OBJC_METACLASS_$_MIAppLaunchProhibition
+ _OBJC_METACLASS_$_MIAppReplacementState
+ __CLASS_METHODS_MIAppLaunchProhibition
+ __CLASS_METHODS_MIAppReplacementState
+ __CLASS_PROPERTIES_MIAppLaunchProhibition
+ __CLASS_PROPERTIES_MIAppReplacementState
+ __DATA_MIAppLaunchProhibition
+ __DATA_MIAppReplacementState
+ __INSTANCE_METHODS_MIAppLaunchProhibition
+ __INSTANCE_METHODS_MIAppReplacementState
+ __IVARS_MIAppLaunchProhibition
+ __IVARS_MIAppReplacementState
+ __METACLASS_DATA_MIAppLaunchProhibition
+ __METACLASS_DATA_MIAppReplacementState
+ __PROPERTIES_MIAppLaunchProhibition
+ __PROPERTIES_MIAppReplacementState
+ __PROTOCOLS_MIAppLaunchProhibition
+ __PROTOCOLS_MIAppReplacementState
+ _swift_errorRetain
+ _symbolic ______p s5ErrorP
- GCC_except_table48
- GCC_except_table54
CStrings:
+ " osBuildVersion="
+ " with a source app identity to ["
+ " without a source app identity to ["
+ "%@ does not have any app extensions that implement any of the required extension points for its configuration. Based on its configuration, this app must have at least one app extension that implements one of these extension points: %@."
+ "*I"
+ ", osBuildVersion="
+ ", sourceAppIdentity="
+ "-[ICLWorkspace getAppLaunchProhibition:forBundleContainerURL:error:]"
+ "-[ICLWorkspace getAppReplacementState:forBundleContainerURL:error:]"
+ "-[MIBundle hasAtLeastOneExtensionImplementingExtensionPointIn:error:]"
+ "-[MIDataContainer supersedeExistingContainer:error:]"
+ "-[MIGlobalConfiguration OSBuildVersionWithError:]"
+ "24B"
+ "AppLaunchProhibition.plist"
+ "AppReplacementState.plist"
+ "BuildVersion"
+ "Decoded a nil app replacement state from ["
+ "Failed to copy the OS build version"
+ "Failed to decode app launch prohibition from ["
+ "Failed to decode app replacement state from ["
+ "Failed to get app replacement state from %@ : %@"
+ "Failed to read app launch prohibition from ["
+ "Failed to read app replacement state from ["
+ "Failed to remove app launch prohibition at ["
+ "Failed to remove app replacement state at ["
+ "Failed to serialize app launch prohibition ["
+ "Failed to serialize app replacement state for ["
+ "Failed to supersede container %@ with %@"
+ "Failed to write serialized app launch prohibition to ["
+ "Failed to write serialized app replacement state to ["
+ "InstalledContentLibrary.MIAppLaunchProhibition"
+ "InstalledContentLibrary.MIAppReplacementState"
+ "MIAppReplacementStatusCompleted"
+ "MIAppReplacementStatusInProgress"
+ "MIAppReplacementStatusMax"
+ "MIAppReplacementStatusNotApplicable"
+ "MIAppReplacementStatusRefused"
+ "MIAppReplacementStatusUnknown"
+ "Refusing to write "
+ "Unknown MIAppReplacementStatus: %lu"
+ "appReplacementSourceBundleIdentifier"
+ "bundleContainerURL parameter was not a valid URL"
+ "com.apple.developer.homekit"
+ "com.apple.developer.superseded-application-identifiers"
+ "sourceAppIdentity"
- "*H"
```
