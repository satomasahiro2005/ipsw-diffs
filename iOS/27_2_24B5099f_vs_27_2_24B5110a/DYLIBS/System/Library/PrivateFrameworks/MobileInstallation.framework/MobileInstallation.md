## MobileInstallation

> `/System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x2b40` | `0x2b80` | **`+0x40`** |
| `__TEXT.__cstring` | `0x5129` | `0x5155` | **`+0x2c`** |
| `__TEXT.__text` | `0x296f0` | `0x2971c` | **`+0x2c`** |

### Other Changes

```diff

-  Functions: 889
-  Symbols:   1434
-  CStrings:  525
+  Functions: 890
+  Symbols:   1435
+  CStrings:  527
Symbols:
+ _MIHasHomeExtensionEntitlement
Functions:
~ _MIClassifyAppManagementDomainValue : 168 -> 196
+ _MIHasHomeKitEntitlement
CStrings:
+ "com.apple.AppClips"
+ "com.apple.developer.home"
```
