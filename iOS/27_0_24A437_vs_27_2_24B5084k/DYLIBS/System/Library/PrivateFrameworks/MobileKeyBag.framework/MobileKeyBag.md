## MobileKeyBag

> `/System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16624` | `0x16764` | **`+0x140`** |
| `__TEXT.__cstring` | `0x5f24` | `0x5fc3` | **`+0x9f`** |
| `__AUTH_CONST.__cfstring` | `0x3de0` | `0x3e40` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x8a0` | `0x8a8` | **`+0x8`** |

### Other Changes

```diff

-697.0.6.0.0
+697.40.4.0.0

-  Symbols:   953
-  CStrings:  774
+  Symbols:   954
+  CStrings:  777
Symbols:
+ _objc_release_x9
Functions:
~ _MKBCopyCryptoIDKeysForFileDescriptor : 2216 -> 2492
~ __MKBBackupCheckKey : 396 -> 440
CStrings:
+ "backup key from db too large (%zu > %zu), ignoring"
+ "entry overruns blob offset=%zu keysize=%u blob_size=%zu"
+ "got oversized key (%u > %zu) for crypto id 0x%016qx"
+ "wrapped key size too big (%u>%zu)"
- "wrapped key size too big (%lu>%u)"
```
