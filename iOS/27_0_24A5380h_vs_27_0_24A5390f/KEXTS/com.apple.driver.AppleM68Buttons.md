## com.apple.driver.AppleM68Buttons

> `com.apple.driver.AppleM68Buttons`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4e79` | `0x4eb6` | **`+0x3d`** |
| `__TEXT_EXEC.__text` | `0x1d094` | `0x1d0d0` | **`+0x3c`** |

### Other Changes

```diff

-  CStrings:  628
+  CStrings:  629
Functions:
~ _DeserializeCredential : 1380 -> 1440
CStrings:
+ "sigSize > 0 && sigSize <= kACMCredentialDataSignatureMaxSize"
```
