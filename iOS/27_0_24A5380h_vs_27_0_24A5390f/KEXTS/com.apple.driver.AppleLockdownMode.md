## com.apple.driver.AppleLockdownMode

> `com.apple.driver.AppleLockdownMode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4892` | `0x48cf` | **`+0x3d`** |
| `__TEXT_EXEC.__text` | `0x15064` | `0x150a0` | **`+0x3c`** |

### Other Changes

```diff

-128.0.4.0.0
+128.0.5.0.0

-  CStrings:  494
+  CStrings:  495
Functions:
~ _DeserializeCredential : 1380 -> 1440
CStrings:
+ "sigSize > 0 && sigSize <= kACMCredentialDataSignatureMaxSize"
```
