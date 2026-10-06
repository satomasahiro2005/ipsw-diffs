## DigitalAccess

> `/System/Library/PrivateFrameworks/DigitalAccess.framework/DigitalAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39700` | `0x3ab0c` | **`+0x140c`** |
| `__AUTH_CONST.__objc_const` | `0x4b40` | `0x4ef0` | **`+0x3b0`** |
| `__DATA_DIRTY.__objc_data` | `0x8c0` | `0xc30` | **`+0x370`** |
| `__AUTH.__objc_data` | `0x370` | `0xa0` | **`-0x2d0`** |
| `__TEXT.__cstring` | `0x892d` | `0x8bc2` | **`+0x295`** |
| `__AUTH_CONST.__cfstring` | `0x2a60` | `0x2c60` | **`+0x200`** |
| `__TEXT.__objc_methlist` | `0x2adc` | `0x2c1c` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x2334` | `0x23fe` | **`+0xca`** |
| `__DATA_CONST.__objc_selrefs` | `0x1598` | `0x1618` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0xdc8` | `0xe18` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x11cc` | `0x1208` | **`+0x3c`** |
| `__DATA.__objc_ivar` | `0x364` | `0x398` | **`+0x34`** |
| `__DATA_CONST.__const` | `0x1180` | `0x11a8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x380` | `0x3a0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x240` | `0x250` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x138` | `0x148` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x120` | `0x130` | **`+0x10`** |
| `__DATA.__bss` | `0x78` | `0x80` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x20` | `0x28` | **`+0x8`** |

### Other Changes

```diff

-70.34.0.0.0
+70.35.1.0.0

-  Functions: 1067
-  Symbols:   1866
-  CStrings:  975
+  Functions: 1098
+  Symbols:   1926
+  CStrings:  1000
Symbols:
+ +[DAKeySharingInvitationParsedData supportsSecureCoding]
+ +[DAPairingTimestamp sharedInstance]
+ -[DAKeyPairingConfig initWithPassword:displayName:transport:bindingAttestation:brand:ppid:pendingPairingIdentifier:enableConnectionTimeout:additionalParameters:pairingStartTime:]
+ -[DAKeyPairingConfig pairingStartTime]
+ -[DAKeySharingInvitationParsedData .cxx_destruct]
+ -[DAKeySharingInvitationParsedData accessProfile]
+ -[DAKeySharingInvitationParsedData accountRole]
+ -[DAKeySharingInvitationParsedData description]
+ -[DAKeySharingInvitationParsedData encodeWithCoder:]
+ -[DAKeySharingInvitationParsedData friendlyName]
+ -[DAKeySharingInvitationParsedData initWithCoder:]
+ -[DAKeySharingInvitationParsedData initWithInvitationIdentifier:accessProfile:friendlyName:notBefore:notAfter:accountRole:secondFactorRequired:supportedTransports:sharingPasswordLength:]
+ -[DAKeySharingInvitationParsedData invitationIdentifier]
+ -[DAKeySharingInvitationParsedData notAfter]
+ -[DAKeySharingInvitationParsedData notBefore]
+ -[DAKeySharingInvitationParsedData secondFactorRequired]
+ -[DAKeySharingInvitationParsedData sharingPasswordLength]
+ -[DAKeySharingInvitationParsedData supportedTransports]
+ -[DAKeySharingSession parseSharingInvitation:completionHandler:]
+ -[DAPairingTimestamp .cxx_destruct]
+ -[DAPairingTimestamp init]
+ -[DAPairingTimestamp recordPreWarmStartForManufacturer:]
+ -[DAPairingTimestamp retrieveMostRecentPreWarmTimestamp]
+ GCC_except_table39
+ GCC_except_table45
+ GCC_except_table98
+ _OBJC_CLASS_$_DAKeySharingInvitationParsedData
+ _OBJC_CLASS_$_DAPairingTimestamp
+ _OBJC_IVAR_$_DAKeyPairingConfig._pairingStartTime
+ _OBJC_IVAR_$_DAKeySharingInvitationParsedData._accessProfile
+ _OBJC_IVAR_$_DAKeySharingInvitationParsedData._accountRole
+ _OBJC_IVAR_$_DAKeySharingInvitationParsedData._friendlyName
+ _OBJC_IVAR_$_DAKeySharingInvitationParsedData._invitationIdentifier
+ _OBJC_IVAR_$_DAKeySharingInvitationParsedData._notAfter
+ _OBJC_IVAR_$_DAKeySharingInvitationParsedData._notBefore
+ _OBJC_IVAR_$_DAKeySharingInvitationParsedData._secondFactorRequired
+ _OBJC_IVAR_$_DAKeySharingInvitationParsedData._sharingPasswordLength
+ _OBJC_IVAR_$_DAKeySharingInvitationParsedData._supportedTransports
+ _OBJC_IVAR_$_DAPairingTimestamp._expiryTime
+ _OBJC_IVAR_$_DAPairingTimestamp._lock
+ _OBJC_IVAR_$_DAPairingTimestamp._timestamp
+ _OBJC_METACLASS_$_DAKeySharingInvitationParsedData
+ _OBJC_METACLASS_$_DAPairingTimestamp
+ __OBJC_$_CLASS_METHODS_DAKeySharingInvitationParsedData
+ __OBJC_$_CLASS_METHODS_DAPairingTimestamp
+ __OBJC_$_CLASS_PROP_LIST_DAKeySharingInvitationParsedData
+ __OBJC_$_INSTANCE_METHODS_DAKeySharingInvitationParsedData
+ __OBJC_$_INSTANCE_METHODS_DAPairingTimestamp
+ __OBJC_$_INSTANCE_VARIABLES_DAKeySharingInvitationParsedData
+ __OBJC_$_INSTANCE_VARIABLES_DAPairingTimestamp
+ __OBJC_$_PROP_LIST_DAKeySharingInvitationParsedData
+ __OBJC_CLASS_PROTOCOLS_$_DAKeySharingInvitationParsedData
+ __OBJC_CLASS_RO_$_DAKeySharingInvitationParsedData
+ __OBJC_CLASS_RO_$_DAPairingTimestamp
+ __OBJC_METACLASS_RO_$_DAKeySharingInvitationParsedData
+ __OBJC_METACLASS_RO_$_DAPairingTimestamp
+ ___36+[DAPairingTimestamp sharedInstance]_block_invoke
+ ___64-[DAKeySharingSession parseSharingInvitation:completionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32r40r_e54_v24?0"DAKeySharingInvitationParsedData"8"NSError"16lr32l8r40l8
+ _kmlUtcDateFormatter
+ _kmlUtilDateFromTimeData
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _sharedInstance.instance
+ _sharedInstance.onceToken
- GCC_except_table20
- GCC_except_table32
- GCC_except_table44
- GCC_except_table51
- GCC_except_table54
CStrings:
+ "%s : %i : No timestamp stored"
+ "%s : %i : Recorded preWarm start for manufacturer: %{public}@ at %{public}@"
+ "%s : %i : Retrieved timestamp (age: %.2f seconds), cleared"
+ "%s : %i : Timestamp expired, cleared"
+ "-[DAKeySharingSession parseSharingInvitation:completionHandler:]"
+ "-[DAKeySharingSession parseSharingInvitation:completionHandler:]_block_invoke"
+ "-[DAPairingTimestamp recordPreWarmStartForManufacturer:]"
+ "-[DAPairingTimestamp retrieveMostRecentPreWarmTimestamp]"
+ "2nd Factor Required   : %@\n"
+ "Access Profile        : 0x%02x\n"
+ "Account Role          : 0x%04x\n"
+ "Friendly Name         : %@\n"
+ "Not After             : %@\n"
+ "Not Before            : %@\n"
+ "Sharing Pwd Length    : %u"
+ "Supported Transports  : %@\n"
+ "accessProfile"
+ "accountRole"
+ "friendlyName"
+ "notAfter"
+ "notBefore"
+ "pairingStartTime"
+ "secondFactorRequired"
+ "sharingPasswordLength"
+ "v24@?0@\"DAKeySharingInvitationParsedData\"8@\"NSError\"16"
```
