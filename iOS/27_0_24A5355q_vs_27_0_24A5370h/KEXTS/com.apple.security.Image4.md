## com.apple.security.Image4

> `com.apple.security.Image4`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x4f0` | **`+0x4f0`** |
| `__TEXT_EXEC.__text` | `0x10800` | `0x10900` | **`+0x100`** |
| `__TEXT.__cstring` | `0x38ee` | `0x39cd` | **`+0xdf`** |
| `__DATA_CONST.__auth_got` | `0x268` | `0x278` | **`+0x10`** |

### Other Changes

```diff

-27.0.0.0.0
+27.0.2.0.0

-  CStrings:  338
+  CStrings:  343
CStrings:
+ "Image4: owning task is not entitled for user-client access\n"
+ "com.apple.private.image4.user-client"
+ "com.apple.private.pmap.load-trust-cache"
+ "com.apple.private.security.AppleImage4.user-client"
+ "personalized.cryptex1.update-brain"
```
