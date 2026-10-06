## DMCUtilities

> `/System/Library/PrivateFrameworks/DMCUtilities.framework/DMCUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36538` | `0x36938` | **`+0x400`** |
| `__AUTH_CONST.__objc_const` | `0x4520` | `0x4640` | **`+0x120`** |
| `__AUTH.__objc_data` | `0xf00` | `0xfa0` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x6b8` | `0x710` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x2fbc` | `0x3004` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x5a2f` | `0x5a74` | **`+0x45`** |
| `__TEXT.__cstring` | `0x3b06` | `0x3b2d` | **`+0x27`** |
| `__AUTH_CONST.__cfstring` | `0x4440` | `0x4460` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0xce0` | `0xd00` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x26b0` | `0x26d0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xe28` | `0xe40` | **`+0x18`** |
| `__DATA.__bss` | `0x918` | `0x928` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x190` | `0x1a0` | **`+0x10`** |

### Other Changes

```diff

-113.2.5.0.0
+113.40.17.0.0

-  Functions: 1433
-  Symbols:   2812
-  CStrings:  1042
+  Functions: 1441
+  Symbols:   2841
+  CStrings:  1044
Symbols:
+ +[DMCAccountUtilities hasUserAccountsOfTypes:]
+ +[DMCDeviceEligibility isEligibleForNoninteractiveEnhancedLogCollection]
+ +[DMCDeviceEligibility userAccountTypeIdentifiersForNoninteractiveEnhancedLogCollection]
+ +[DMCLockdownUtilities isDevicePasscodeSet]
+ GCC_except_table32
+ _ACAccountTypeIdentifierCalDAV
+ _ACAccountTypeIdentifierCardDAV
+ _ACAccountTypeIdentifierExchange
+ _ACAccountTypeIdentifierGmail
+ _ACAccountTypeIdentifierHotmail
+ _ACAccountTypeIdentifierIMAP
+ _ACAccountTypeIdentifierIMAPMail
+ _ACAccountTypeIdentifierIMAPNotes
+ _ACAccountTypeIdentifierPOP
+ _ACAccountTypeIdentifierYahoo
+ _AppleMediaServicesBundle
+ _DMCEnsureAppleMediaServicesLoaded
+ _MDMMigrationConfigFetchRetryInfoFilePath
+ _MDMMigrationConfigFetchRetryInfoFilePath.once
+ _MDMMigrationConfigFetchRetryInfoFilePath.str
+ _OBJC_CLASS_$_DMCDeviceEligibility
+ _OBJC_CLASS_$_DMCLockdownUtilities
+ _OBJC_METACLASS_$_DMCDeviceEligibility
+ _OBJC_METACLASS_$_DMCLockdownUtilities
+ __OBJC_$_CLASS_METHODS_DMCDeviceEligibility
+ __OBJC_$_CLASS_METHODS_DMCLockdownUtilities
+ __OBJC_CLASS_RO_$_DMCDeviceEligibility
+ __OBJC_CLASS_RO_$_DMCLockdownUtilities
+ __OBJC_METACLASS_RO_$_DMCDeviceEligibility
+ __OBJC_METACLASS_RO_$_DMCLockdownUtilities
+ ___MDMMigrationConfigFetchRetryInfoFilePath_block_invoke
+ ___block_descriptor_65_e8_32s40s48r56r_e5_v8?0ls32l8s40l8r48l8r56l8
- GCC_except_table33
- ___89-[ACAccountStore(DeviceManagementClient) dmc_conflictingAccountsExistWithUsername:error:]_block_invoke_2
- ___block_descriptor_81_e8_32s40s48s56s64r72r_e5_v8?0ls32l8s40l8s48l8s56l8r64l8r72l8
CStrings:
+ "Failed to fetch accounts to determine user-data presence: %{public}@"
+ "MDMMigrationConfigFetchRetryInfo.plist"
```
