## ProtectedCloudStorage

> `/System/Library/PrivateFrameworks/ProtectedCloudStorage.framework/ProtectedCloudStorage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ddf0` | `0x6df34` | **`+0x144`** |
| `__TEXT.__cstring` | `0xe0b4` | `0xe153` | **`+0x9f`** |
| `__AUTH_CONST.__cfstring` | `0x18920` | `0x189a0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x4089` | `0x40af` | **`+0x26`** |
| `__TEXT.__gcc_except_tab` | `0x3630` | `0x363c` | **`+0xc`** |
| `__AUTH.__data` | `0x13a8` | `0x13b0` | **`+0x8`** |
| `__AUTH_CONST.__auth_got` | `0xc58` | `0xc50` | **`-0x8`** |
| `__DATA.__bss` | `0x3a8` | `0x3b0` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x4240` | `0x4248` | **`+0x8`** |

### Other Changes

```diff

-1303.0.6.0.0
+1303.40.9.0.0

-  CStrings:  3796
+  CStrings:  3800
Functions:
~ _PCSDBRRepairWrappingKeyFromEscrowIdentityOuterBlob : 1700 -> 1740
~ _PCSDBRRepairWrappingKeyFromEscrowIdentity : 696 -> 728
~ ___PCSDBRUnwrapKeys_block_invoke : 724 -> 972
~ __PCSUpdateKeychainForwardTable : 76 -> 68
~ _PCSCacheCurrentIdentitiesForServices : 1044 -> 1056
CStrings:
+ "FlagMissingDBRRecord"
+ "No Primary DBR Record. Account needs DBR repair."
+ "get wrapping key failed with no error"
+ "unable to unwrap wrapping key with escrow identity"
```
