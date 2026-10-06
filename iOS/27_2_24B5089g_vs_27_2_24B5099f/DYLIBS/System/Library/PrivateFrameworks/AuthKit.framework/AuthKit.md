## AuthKit

> `/System/Library/PrivateFrameworks/AuthKit.framework/AuthKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a7cb0` | `0x1a80e8` | **`+0x438`** |
| `__AUTH_CONST.__cfstring` | `0x14240` | `0x142e0` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x2f530` | `0x2f4b0` | **`-0x80`** |
| `__TEXT.__ustring` | `0x34a` | `0x3be` | **`+0x74`** |
| `__TEXT.__cstring` | `0x1323c` | `0x132ad` | **`+0x71`** |
| `__TEXT.__oslogstring` | `0x160e3` | `0x1611e` | **`+0x3b`** |
| `__DATA_CONST.__const` | `0x79c8` | `0x79e8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8360` | `0x8348` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x10934` | `0x1091c` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x1290` | `0x1284` | **`-0xc`** |
| `__DATA_CONST.__got` | `0xbd8` | `0xbd0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x4930` | `0x4928` | **`-0x8`** |

### Other Changes

```diff

-560.125.4.1.0
+560.125.6.0.0

-  Functions: 6192
-  Symbols:   12471
-  CStrings:  4678
+  Functions: 6189
+  Symbols:   12468
+  CStrings:  4684
Symbols:
+ +[AKCommandLineUtilities serverFaultForResponse:]
+ GCC_except_table156
+ GCC_except_table158
+ _AKRiskingSignalActiveCallTypeKey
+ _AKRiskingSignalCallerContactRecencyKey
+ _AKRiskingSignalsActionKey
+ _AKRiskingSignalsDirectiveKey
+ _AKRiskingSignalsPostbackKey
+ __OBJC_$_CLASS_METHODS_AKCommandLineUtilities
+ _kApprovalFlowAppleAccountAvatarViewRemoteUITag
- -[AKDevice coverGlassColor]
- -[AKDevice setCoverGlassColor:]
- -[AKRemoteDevice coverGlassColorCode]
- -[AKRemoteDevice setCoverGlassColorCode:]
- GCC_except_table150
- _AKDeviceCoverGlassColorCodeKey
- _NRDevicePropertyDeviceCoverGlassColor
- _OBJC_IVAR_$_AKDevice._coverGlassColor
- _OBJC_IVAR_$_AKDevice._shouldUpdateCoverGlassColor
- _OBJC_IVAR_$_AKRemoteDevice._coverGlassColorCode
- __AKCoverGlassColorKey
- ___27-[AKDevice coverGlassColor]_block_invoke
- ___31-[AKDevice setCoverGlassColor:]_block_invoke
CStrings:
+ "AppleAccountAvatarView"
+ "No matching flow step found for status %ld"
+ "Passcode verification failed: %@"
+ "Security code verification failed: %@"
+ "Server returned status %ld, content type %@"
+ "activeCallType"
+ "ak:collectRiskingSignals"
+ "callerContactRecency"
+ "riskingSignals"
+ "signals"
+ "❌ Password change failed: the server returned status %ld."
- "DeviceCoverGlassColor"
- "No matching flow step found"
- "_coverGlassColor"
- "_coverGlassColorCode"
- "clcg"
```
