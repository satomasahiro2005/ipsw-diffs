## AppleAccountUI

> `/System/Library/PrivateFrameworks/AppleAccountUI.framework/AppleAccountUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x394de4` | `0x395154` | **`+0x370`** |
| `__TEXT.__oslogstring` | `0x1205c` | `0x1209c` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x3658` | `0x3680` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x7050` | `0x7070` | **`+0x20`** |
| `__DATA.__data` | `0x7620` | `0x7630` | **`+0x10`** |
| `__TEXT.__const` | `0x143a4` | `0x143b4` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x156ea` | `0x156fa` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1e48` | `0x1e50` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xc3cc` | `0xc3d4` | **`+0x8`** |

### Other Changes

```diff

-589.125.4.0.0
+589.125.7.0.0

-  Functions: 17531
-  Symbols:   10522
-  CStrings:  2872
+  Functions: 17528
+  Symbols:   10525
+  CStrings:  2873
Symbols:
+ -[AAUISignOutUtilities _signoutFromAuthKitForAltDSID:telemetryFlowID:completion:]
+ -[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:telemetryFlowID:context:completion:]
+ _OBJC_CLASS_$_AKSignoutInfo
+ ___122-[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:telemetryFlowID:context:completion:]_block_invoke
+ ___81-[AAUISignOutUtilities _signoutFromAuthKitForAltDSID:telemetryFlowID:completion:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ _get_witness_table 7SwiftUI15ModifiedContentVy012AppleAccountB028AddRecoveryContactControllerVAA30_SafeAreaRegionsIgnoringLayoutVGAA4ViewHPAfaJHPyHC_AhA0P8ModifierHPyHCHC
+ _symbolic _____y__________G 7SwiftUI15ModifiedContentV 012AppleAccountB028AddRecoveryContactControllerV AA30_SafeAreaRegionsIgnoringLayoutV
- -[AAUISignOutUtilities _signoutFromAuthKitForAltDSID:completion:]
- -[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:context:completion:]
- ___106-[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:context:completion:]_block_invoke
- ___65-[AAUISignOutUtilities _signoutFromAuthKitForAltDSID:completion:]_block_invoke
- _get_witness_table 14AppleAccountUI28AddRecoveryContactControllerV05SwiftC04ViewHPyHC
CStrings:
+ "Fetching avatar from primary source"
+ "Got avatar from primary source"
+ "No avatar from primary source"
+ "No avatar from primary source, falling back to monogram"
+ "Skipping profile picture update, managed by primary source"
- "Got avatar from IdentityStore"
- "No avatar from IdentityStore"
- "No avatar from IdentityStore, falling back to monogram"
- "Using IdentityStore to fetch avatar"
```
