## LocationAuthorizationXPC

> `/System/Library/PrivateFrameworks/LocationAuthorizationXPC.framework/LocationAuthorizationXPC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb830` | `0xb8c0` | **`+0x90`** |
| `__TEXT.__cstring` | `0x347` | `0x35e` | **`+0x17`** |
| `__AUTH_CONST.__auth_got` | `0x2d8` | `0x2e0` | **`+0x8`** |
| `__DATA.__data` | `0x200` | `0x208` | **`+0x8`** |

### Other Changes

```diff

-3176.0.0.0.0
+3183.0.0.0.0

-  Functions: 224
-  Symbols:   315
-  CStrings:  39
+  Functions: 225
+  Symbols:   317
+  CStrings:  41
Symbols:
+ _SetSupportsAuthSync2ForTesting
+ __os_feature_enabled_impl
CStrings:
+ "AuthSync2"
+ "CoreLocation"
```
