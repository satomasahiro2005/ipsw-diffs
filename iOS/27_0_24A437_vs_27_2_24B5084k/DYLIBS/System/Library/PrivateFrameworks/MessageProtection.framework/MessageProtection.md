## MessageProtection

> `/System/Library/PrivateFrameworks/MessageProtection.framework/MessageProtection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7a51c` | `0x7a900` | **`+0x3e4`** |
| `__TEXT.__oslogstring` | `0x25e1` | `0x2673` | **`+0x92`** |
| `__TEXT.__cstring` | `0x3197` | `0x31f7` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x11a8` | `0x11b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x618` | `0x620` | **`+0x8`** |

### Other Changes

```diff

-398.0.0.0.0
+398.40.2.0.0

-  Symbols:   6779
-  CStrings:  520
+  Symbols:   6781
+  CStrings:  523
Symbols:
+ _$s10Foundation4DataV15_RepresentationOys5UInt8VSicis
+ _$s17MessageProtection29TetraIncomingSymmetricRatchetV04openA0_12messageIndex0H12KeyIndicator07discardaJ0020onChainWithReceivingJ0AA0c5InnerA0V10Foundation4DataV_s6UInt32VAMSb9CryptoKit4P256O0J9AgreementO06PublicJ0VSgtKF
+ _$ss6UInt64Vs23CustomStringConvertiblesWP
+ _swift_bridgeObjectRelease_n
- _$s10Foundation13__DataStorageC27ensureUniqueBufferReference9growingTo5clearySi_SbtF
- _$s17MessageProtection29TetraIncomingSymmetricRatchetV04openA0_12messageIndex0H12KeyIndicator07discardaJ0AA0c5InnerA0V10Foundation4DataV_s6UInt32VALSbtKF
Functions:
~ _$s17MessageProtection5I2OSP5value15outputByteCount10Foundation4DataVSi_SitF : 1168 -> 372
~ _$s17MessageProtection17TetraRatchetStateV04openA0_10sessionDST03didD0AA0c5InnerA0Vx_10Foundation4DataVSbXESbztKAA0c5OuterA0RzlFAA0c2NodmA0V_Tg5Tm : 1832 -> 2072
~ _$s17MessageProtection17TetraRatchetStateV13ratchetedOpen7message10sessionDST03didD0AA0c5InnerA0Vx_10Foundation4DataVSbXESbztKAA0c5OuterA0RzlFAA0c2NodoA0V_Tg5Tm : 8668 -> 9016
~ _$s17MessageProtection29TetraIncomingSymmetricRatchetV04openA0_12messageIndex0H12KeyIndicator07discardaJ0AA0c5InnerA0V10Foundation4DataV_s6UInt32VALSbtKF -> _$s17MessageProtection29TetraIncomingSymmetricRatchetV04openA0_12messageIndex0H12KeyIndicator07discardaJ0020onChainWithReceivingJ0AA0c5InnerA0V10Foundation4DataV_s6UInt32VAMSb9CryptoKit4P256O0J9AgreementO06PublicJ0VSgtKF : 1124 -> 2328
CStrings:
+ " indexes behind current location (previously derived key)"
+ "Mismatch in ratchet state on %s at index %llu for incoming index %u, attempting to decrypt with message key with indicator: %s instead of %s."
+ "Tetra ratchet on %s at index %llu opening incoming index %u, %s, with discardMessageKey: %{bool}d."
+ "Tetra ratchet on %s failed to provide the message key for incoming index %u at current index %llu: %s."
+ "unidentified chain"
- "Mismatch in ratchet state, attempting to decrypt with message key with indicator: %s instead of %s."
- "Tetra ratchet with current index %llu and incoming %u for delta of: %llu, and overflow %{bool}d "
```
