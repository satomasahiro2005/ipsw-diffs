## AccessoryComponentAuth

> `/System/Library/PrivateFrameworks/AccessoryComponentAuth.framework/AccessoryComponentAuth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x129d4` | `0x12a34` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x6f0` | `0x728` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x534` | `0x568` | **`+0x34`** |
| `__DATA_CONST.__objc_selrefs` | `0x498` | `0x4b0` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x1710` | `0x1720` | **`+0x10`** |
| `__TEXT.__const` | `0xd710` | `0xd720` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x60` | `0x64` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1216.2.2.0.0
+1219.40.5.0.0

-  Functions: 488
-  Symbols:   1502
+  Functions: 491
+  Symbols:   1508
Symbols:
+ -[ACCHWComponentAuthService signTouchControllerChallenge:completionHandler:componentIndex:]
+ -[ACCHWComponentAuthServiceParams setSigningHandler:]
+ -[ACCHWComponentAuthServiceParams signingHandler]
+ GCC_except_table72
+ _OBJC_IVAR_$_ACCHWComponentAuthServiceParams._signingHandler
+ __oidAppleExtendedKeyUsageSWUpdateSigning
+ _oidAppleExtendedKeyUsageSWUpdateSigning
- GCC_except_table70
CStrings:
+ "6)"
- "6("
```
