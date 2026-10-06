## MobileActivation

> `/System/Library/PrivateFrameworks/MobileActivation.framework/MobileActivation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeff4` | `0xf07c` | **`+0x88`** |
| `__AUTH_CONST.__cfstring` | `0x2840` | `0x2860` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x588` | `0x5a0` | **`+0x18`** |
| `__TEXT.__cstring` | `0x21e5` | `0x21f4` | **`+0xf`** |

### Other Changes

```diff

-1137.0.0.0.0
+1144.0.0.0.0

-  CStrings:  380
+  CStrings:  381
Functions:
~ _createTunnel1SessionRequestFromMAD : 944 -> 1028
~ -[NSDictionary(MobileActivation) objectForCaseInsensitiveKey:] : 352 -> 348
~ _createActivationRequest : 1240 -> 1296
CStrings:
+ "iOS Device Activator (MobileActivation-1144)"
+ "inboxupdaterd"
+ "x-jmet-serial"
- "iOS Device Activator (MobileActivation-1137)"
- "inboxupaterd"
```
