## DisembarkUI

> `/System/Library/PrivateFrameworks/DisembarkUI.framework/DisembarkUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f474` | `0x1f3b8` | **`-0xbc`** |
| `__TEXT.__cstring` | `0x1e04` | `0x1d54` | **`-0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x16a0` | `0x1620` | **`-0x80`** |
| `__AUTH_CONST.__objc_const` | `0x4fa0` | `0x4ff8` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x28d8` | `0x2920` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a68` | `0x1a78` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7f0` | `0x7f8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2c4` | `0x2c8` | **`+0x4`** |

### Other Changes

```diff

-281.0.0.0.0
+282.0.0.0.0

-  Functions: 946
-  Symbols:   1878
-  CStrings:  363
+  Functions: 950
+  Symbols:   1883
+  CStrings:  359
Symbols:
+ -[DKFindMyProvider setUsePartnerFinancingPrompt:]
+ -[DKFindMyProvider usePartnerFinancingPrompt]
+ -[DKPasscodeViewController viewDidLoad]
+ -[DKScreenTimePasscodeViewController viewDidLoad]
+ _OBJC_IVAR_$_DKFindMyProvider.usePartnerFinancingPrompt
Functions:
~ -[DKFindMyProvider disableFindMyWithPresentingViewController:completion:] : 784 -> 928
+ -[DKFindMyProvider usePartnerFinancingPrompt]
+ -[DKFindMyProvider setStateChangeBlock:]
~ -[DKIntroViewController viewDidLoad] : 1036 -> 1048
~ -[DKInternetWarningViewController viewDidLoad] : 1588 -> 1600
+ -[DKPasscodeViewController viewDidLoad]
~ -[DKPartnerFinancingConfirmationController viewDidLoad] : 860 -> 872
~ -[DKPromptCloudUploadViewController viewDidLoad] : 432 -> 444
+ -[DKScreenTimePasscodeViewController viewDidLoad]
~ -[DKCloudUploadViewController viewDidLoad] : 612 -> 624
~ -[DKCloudUploadViewController _showUploadFailureAlertForResults:] : 3292 -> 2692
~ ___27-[DKEraseFlow prepareFlow:]_block_invoke_5 : 220 -> 248
CStrings:
+ "BACKUP_DISABLED_ALERT_BODY"
+ "TURN_OFF_FIND_MY_DISCLOSURE_PARTNER_FINANCING"
+ "UNABLE_TO_BACKUP_TITLE"
- "BACKUP_DISABLED_ALERT_MESSAGE"
- "BACKUP_DISABLED_ALERT_MULTIPLE_ACCOUNTS_MESSAGE"
- "BACKUP_DISABLED_ALERT_MULTIPLE_ACCOUNTS_TITLE"
- "BACKUP_DISABLED_ALERT_SINGLE_ACCOUNT_MESSAGE"
- "BACKUP_DISABLED_ALERT_SINGLE_ACCOUNT_TITLE"
- "BACKUP_DISABLED_ALERT_TITLE"
- "BACKUP_NO_INTERNET_ALERT_TITLE"
```
