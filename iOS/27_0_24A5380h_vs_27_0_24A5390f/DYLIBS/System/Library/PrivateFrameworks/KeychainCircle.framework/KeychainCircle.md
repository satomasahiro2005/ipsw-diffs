## KeychainCircle

> `/System/Library/PrivateFrameworks/KeychainCircle.framework/KeychainCircle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x36b9` | `0x36fb` | **`+0x42`** |
| `__AUTH_CONST.__cfstring` | `0x3ac0` | `0x3a80` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x1298` | `0x1288` | **`-0x10`** |

### Other Changes

```diff

-62460.0.38.0.1
+62460.0.55.0.1

-  Symbols:   1855
-  CStrings:  799
+  Symbols:   1853
+  CStrings:  797
Symbols:
+ _kSecurityRTCEventNameJoinButDistrustEveryone
+ _kSecurityRTCEventNameRKSponsorsWithFlagSet
+ _kSecurityRTCEventNameRecoverRKTLKSharesFetchSharesForRecovery
+ _kSecurityRTCEventNameRecoverRKTLKSharesResult
- _kSecurityRTCEventNameRecoverRKTLKShares
- _kSecurityRTCFieldAuthenticatedRKSponsorSelected
- _kSecurityRTCFieldDistrustEveryoneOnJoin
- _kSecurityRTCFieldNumRKTLKShares
- _kSecurityRTCFieldNumRKTLKSharesRecovered
- _kSecurityRTCFieldPotentialRKSponsorsWithStableInfoFlagSet
CStrings:
+ "com.apple.security.anyPotentialRKSponsorsWithFlagSet"
+ "com.apple.security.joinWithCircleReset"
+ "com.apple.security.recoverRKTLKShares.fetchRKTLKSharesForRecovery"
+ "com.apple.security.recoverRKTLKShares.recoveredRKTLKShares"
- "RKSponsorWasChosen"
- "anyPotentialSponsorsWithFlagSet"
- "com.apple.security.recoverRKTLKShares"
- "distrustEveryoneOnJoin"
- "numRKTLKShares"
- "numRKTLKSharesRecovered"
```
