## KeychainCircle

> `/System/Library/PrivateFrameworks/KeychainCircle.framework/KeychainCircle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x39a0` | `0x3ac0` | **`+0x120`** |
| `__TEXT.__cstring` | `0x35a8` | `0x36b9` | **`+0x111`** |
| `__DATA_CONST.__const` | `0x1250` | `0x1298` | **`+0x48`** |
| `__DATA.__bss` | `0x140` | `0x170` | **`+0x30`** |
| `__DATA_DIRTY.__bss` | `0x30` | `—` | **`-0x30`** |

### Other Changes

```diff

-62460.0.22.0.0
+62460.0.38.0.1

-  Symbols:   1846
-  CStrings:  790
+  Symbols:   1855
+  CStrings:  799
Symbols:
+ _kSecurityRTCEventNameRKSponsorSelection
+ _kSecurityRTCEventNameRecoverRKTLKShares
+ _kSecurityRTCEventNameTLKProofInvalid
+ _kSecurityRTCEventNameVouchWithRK
+ _kSecurityRTCFieldAuthenticatedRKSponsorSelected
+ _kSecurityRTCFieldDistrustEveryoneOnJoin
+ _kSecurityRTCFieldNumRKTLKShares
+ _kSecurityRTCFieldNumRKTLKSharesRecovered
+ _kSecurityRTCFieldPotentialRKSponsorsWithStableInfoFlagSet
CStrings:
+ "RKSponsorWasChosen"
+ "anyPotentialSponsorsWithFlagSet"
+ "com.apple.security.RKSponsorSelection"
+ "com.apple.security.TLKProofInvalid"
+ "com.apple.security.recoverRKTLKShares"
+ "com.apple.security.vouchWithRecoveryKeyOperation"
+ "distrustEveryoneOnJoin"
+ "numRKTLKShares"
+ "numRKTLKSharesRecovered"
```
