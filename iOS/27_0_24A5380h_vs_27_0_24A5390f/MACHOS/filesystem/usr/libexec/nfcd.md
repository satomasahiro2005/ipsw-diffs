## nfcd

> `/usr/libexec/nfcd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e677c` | `0x1e71b0` | **`+0xa34`** |
| `__TEXT.__oslogstring` | `0x2038d` | `0x205b3` | **`+0x226`** |
| `__TEXT.__cstring` | `0x226d3` | `0x22880` | **`+0x1ad`** |
| `__DATA_CONST.__cfstring` | `0x112a0` | `0x11320` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x1585d` | `0x158cd` | **`+0x70`** |
| `__DATA.__objc_const` | `0x14e48` | `0x14ea8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x9a00` | `0x9a50` | **`+0x50`** |
| `__TEXT.__delay_stubs` | `0x500` | `0x540` | **`+0x40`** |
| `__TEXT.__delay_helper` | `0x16f4` | `0x172c` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x9d6c` | `0x9d9c` | **`+0x30`** |
| `__DATA_CONST.__objc_dictobj` | `0x1018` | `0x1040` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x4dfe` | `0x4e1f` | **`+0x21`** |
| `__DATA_CONST.__objc_arraydata` | `0x1e38` | `0x1e58` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xdf20` | `0xdf40` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x4b60` | `0x4b78` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x112c` | `0x1134` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xcd8` | `0xce0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x9f8` | `0xa00` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2c50` | `0x2c48` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-370.38.2.0.0
+370.40.2.0.0

-  Functions: 4269
-  Symbols:   669
-  CStrings:  11365
+  Functions: 4274
+  Symbols:   671
+  CStrings:  11389
Symbols:
+ _ACMContextGetExternalForm
+ _OBJC_CLASS_$_SECPresentmentAuthorizationStore
CStrings:
+ "%@ { applet=%@ endpoint=%@ didError=%@ result=%@ brandCode=%@ background=%@ }"
+ "%{public}s:%i Context & credential binding failed, status=%d"
+ "%{public}s:%i Context creation failed, status=%d"
+ "%{public}s:%i Credential creation failed, status=%d"
+ "%{public}s:%i Invalid NLEN value; 0xFFFF is RFU"
+ "%{public}s:%i NDEF message is larger than storage (%lu bytes)"
+ "%{public}s:%i NLEN=%d exceeds NDEF capacity (%lu bytes); rejecting out-of-bounds message"
+ "%{public}s:%i Stash presentment auth error, %{public}@"
+ "%{public}s:%i Touch system ready event expired"
+ "%{public}s:%i Touch system ready event expired, last systemAvailable=%d"
+ "%{public}s:%i Unexpected context"
+ "%{public}s:%i Unexpected state; workQueue is nil"
+ "-[NFBackgroundTagReadingManager initWithQueue:driverWrapper:]_block_invoke_2"
+ "-[NFTNEPHandler _updateTagMemoryWithNDEF:]"
+ "-[NFWalletPresentationEventPublisher _createButtonPressedACMRef]"
+ "-[NFWalletPresentationEventPublisher _createButtonPressedACMRef]_block_invoke"
+ "@\"NSMutableDictionary\"8@?0"
+ "Invalid NLEN detected"
+ "NFCD built from (B&I) Stockholm_Base-370.40.2"
+ "TNEP reader writes an invalid NDEF message; abort transaction attempt"
+ "Vv24@0:8@?<v@?@\"NSDictionary\">16"
+ "_assertionHeld"
+ "currentDeviceCAParametersWithCompletion:"
+ "disableFuryStandby"
+ "endSessionWithReason:completion:"
+ "localDeviceCAParameters"
+ "stashPresentmentAuthExternalForm:bundleID:error:"
+ "v24@?0r^v8Q16"
- "%@ { applet=%@ endpoint=%@ didError=%@ result=%@ brandCode=%@ }"
- "%{public}s:%i Touch system ready event expired, systemAvailable=%d"
- "NFCD built from (B&I) Stockholm_Base-370.38.2"
- "unarchivedArrayOfObjectsOfClasses:fromData:error:"
```
