## NPKCompanionAgent

> `/System/Library/PrivateFrameworks/NanoPassKit.framework/NPKCompanionAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0xc472` | `0xc4d2` | **`+0x60`** |
| `__TEXT.__text` | `0x423a8` | `0x423f0` | **`+0x48`** |
| `__TEXT.__objc_methtype` | `0x3621` | `0x3665` | **`+0x44`** |
| `__TEXT.__auth_stubs` | `0xd40` | `0xd60` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x9ad3` | `0x9ae7` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0x6b0` | `0x6c0` | **`+0x10`** |
| `__DATA.__objc_const` | `0x5c20` | `0x5c28` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x28a0` | `0x28a8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x6e0` | `0x6e8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x3588` | `0x3590` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1334.0.0.0.0
+1338.0.0.0.0

-  Symbols:   447
-  CStrings:  2740
+  Symbols:   449
+  CStrings:  2742
Symbols:
+ _NPKGetRemoteBiometricAuthenticationStatusSuspensionReason
+ _NSStringFromNPKIDVDeviceCredentialPrearmStatus
Functions:
~ sub_10001dd78 : 404 -> 476
CStrings:
+ "Notice: NPKIDVRemoteDeviceService: Found trustLost:%@ suspensionReason:%@ for remoteBiometricAuthenticationStatusForCredentialType:%@"
+ "paymentWebService:didFailToDownloadRemoteCloudStoreAssetWithLocalURL:forPassWithUniqueID:error:"
+ "v40@0:8@\"NPKIDVRemoteDevicesManager\"16Q24@?<v@?Bq>32"
+ "v48@0:8@\"PKPaymentWebService\"16@\"NSURL\"24@\"NSString\"32@\"NSError\"40"
- "Notice: NPKIDVRemoteDeviceService: Found trustLost:%@ for remoteBiometricAuthenticationStatusForCredentialType:%@"
- "v40@0:8@\"NPKIDVRemoteDevicesManager\"16Q24@?<v@?B>32"
```
