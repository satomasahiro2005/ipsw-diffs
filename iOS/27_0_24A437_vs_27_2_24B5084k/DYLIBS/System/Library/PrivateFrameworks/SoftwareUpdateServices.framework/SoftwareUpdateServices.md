## SoftwareUpdateServices

> `/System/Library/PrivateFrameworks/SoftwareUpdateServices.framework/SoftwareUpdateServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6aae8` | `0x6ad9c` | **`+0x2b4`** |
| `__TEXT.__cstring` | `0x15491` | `0x15531` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0xdf60` | `0xdfc0` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0xdf18` | `0xdf58` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x7064` | `0x708c` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x4038` | `0x4050` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1f10` | `0x1f18` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x6cc` | `0x6d0` | **`+0x4`** |

### Other Changes

```diff

-1112.0.3.0.0
+1114.40.9.0.0

-  Functions: 2907
-  Symbols:   4796
-  CStrings:  2222
+  Functions: 2912
+  Symbols:   4802
+  CStrings:  2225
Symbols:
+ -[SUDownloadOptions personalizationServerURL]
+ -[SUDownloadOptions setPersonalizationServerURL:]
+ -[SUPreferences overridePersonalizationURL]
+ _OBJC_IVAR_$_SUDownloadOptions._personalizationServerURL
+ ___45-[SUDownloadOptions personalizationServerURL]_block_invoke
+ ___49-[SUDownloadOptions setPersonalizationServerURL:]_block_invoke
CStrings:
+ "\n            ClientName: %@\n            downloadOnly: %@\n            autoDownload: %@\n            userUpdateTonight: %@\n            allowUnrestrictedCellularDownload: %@\n            downloadFeeAgreementStatus: %@\n            termsAndConditionsAgreementStatus: %@\n            activeDownloadPolicyType: %@\n            enabledForCellular: %@\n            enabledForWifi: %@\n            enabledOnBatteryPower: %@\n            enabledForCellularRoaming: %@\n            personalizationServerURL: %@\n            descriptor: %@\n"
+ "!$"
+ "Override Tatsu personalization URL; used when the client does not supply one"
+ "SUOverridePersonalizationURL"
+ "[Auto download] Beta: Downloading every 1 day"
+ "personalizationServerURL"
- "\n            ClientName: %@\n            downloadOnly: %@\n            autoDownload: %@\n            userUpdateTonight: %@\n            allowUnrestrictedCellularDownload: %@\n            downloadFeeAgreementStatus: %@\n            termsAndConditionsAgreementStatus: %@\n            activeDownloadPolicyType: %@\n            enabledForCellular: %@\n            enabledForWifi: %@\n            enabledOnBatteryPower: %@\n            enabledForCellularRoaming: %@\n            descriptor: %@\n"
- "!#"
- "[Auto download] Customer: Downloading every 5 days"
```
