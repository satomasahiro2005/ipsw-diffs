## UARPiCloud

> `/System/Library/PrivateFrameworks/UARPiCloud.framework/UARPiCloud`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x17a8` | `0x1548` | **`-0x260`** |
| `__TEXT.__objc_methlist` | `0xa34` | `0x9a4` | **`-0x90`** |
| `__TEXT.__text` | `0x1c074` | `0x1c030` | **`-0x44`** |
| `__AUTH_CONST.__auth_got` | `0x360` | `0x380` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0xdc0` | `0xda0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x247e` | `0x2464` | **`-0x1a`** |
| `__TEXT.__unwind_info` | `0x618` | `0x608` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x148` | `0x140` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1c0` | `0x1b8` | **`-0x8`** |

### Other Changes

```diff

-1576.0.0.0.0
+1587.0.3.0.3

-  Functions: 701
-  Symbols:   1036
+  Functions: 691
+  Symbols:   1021
Symbols:
+ _dispatch_queue_attr_make_with_autorelease_frequency
+ _objc_destroyWeak
+ _objc_loadWeakRetained
+ _objc_storeWeak
- +[CHIPAccessoryFirmwareRecord supportsSecureCoding]
- +[CHIPAttestationCertificateRecord supportsSecureCoding]
- -[CHIPAccessoryFirmwareRecord ckRecord]
- -[CHIPAccessoryFirmwareRecord copyWithZone:]
- -[CHIPAccessoryFirmwareRecord encodeWithCoder:]
- -[CHIPAccessoryFirmwareRecord initWithCoder:]
- -[CHIPAttestationCertificateRecord ckRecord]
- -[CHIPAttestationCertificateRecord copyWithZone:]
- -[CHIPAttestationCertificateRecord encodeWithCoder:]
- -[CHIPAttestationCertificateRecord initWithCoder:]
- _OBJC_CLASS_$_NSRegularExpression
- _OBJC_IVAR_$_CHIPAccessoryFirmwareRecord._ckRecord
- _OBJC_IVAR_$_CHIPAttestationCertificateRecord._ckRecord
- __OBJC_$_CLASS_METHODS_CHIPAccessoryFirmwareRecord
- __OBJC_$_CLASS_METHODS_CHIPAttestationCertificateRecord
- __OBJC_$_CLASS_PROP_LIST_CHIPAccessoryFirmwareRecord
- __OBJC_$_CLASS_PROP_LIST_CHIPAttestationCertificateRecord
- __OBJC_CLASS_PROTOCOLS_$_CHIPAccessoryFirmwareRecord
- __OBJC_CLASS_PROTOCOLS_$_CHIPAttestationCertificateRecord
CStrings:
+ "!"
- "^%@\\S+\\/\\S+\\/(%@|%@)\\/.+$"
```
