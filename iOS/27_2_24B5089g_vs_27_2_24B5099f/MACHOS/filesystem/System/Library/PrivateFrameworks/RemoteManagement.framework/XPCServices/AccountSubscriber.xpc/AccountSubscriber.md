## AccountSubscriber

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/XPCServices/AccountSubscriber.xpc/AccountSubscriber`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14824` | `0x14c80` | **`+0x45c`** |
| `__TEXT.__cstring` | `0x11e9` | `0x120e` | **`+0x25`** |
| `__DATA_CONST.__cfstring` | `0xdc0` | `0xde0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2380` | `0x23a0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1fad` | `0x1fca` | **`+0x1d`** |
| `__DATA_CONST.__got` | `0x440` | `0x450` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xa08` | `0xa10` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x940` | `0x948` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-624.40.13.0.0
+624.40.15.0.0

+  - /System/Library/PrivateFrameworks/ExchangeSync.framework/Frameworks/DAEAS.framework/DAEAS

-  Symbols:   318
-  CStrings:  582
+  Symbols:   321
+  CStrings:  584
Symbols:
+ _AccountPropertyRemoteManagementExchangeProtocolType
+ _kASEncryptionIdentityPersistentReference
+ _kASSigningIdentityPersistentReference
Functions:
~ sub_100005698 -> sub_100005710 : 680 -> 728
~ sub_100007310 -> sub_1000073b8 : 1600 -> 1640
~ sub_10000b504 -> sub_10000b5d4 : 5332 -> 5768
~ sub_10000cc48 -> sub_10000cecc : 2736 -> 2788
~ sub_1000108ec -> sub_100010ba4 : 3692 -> 4108
~ sub_100011810 -> sub_100011c68 : 2024 -> 2040
~ sub_100011ff8 -> sub_100012460 : 2120 -> 2188
~ sub_100012840 -> sub_100012cec : 716 -> 756
CStrings:
+ "RemoteManagementExchangeProtocolType"
+ "removeAccountPropertyForKey:"
```
