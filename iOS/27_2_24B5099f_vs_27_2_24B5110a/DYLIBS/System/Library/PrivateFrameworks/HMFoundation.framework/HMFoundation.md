## HMFoundation

> `/System/Library/PrivateFrameworks/HMFoundation.framework/HMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa1fd0` | `0xa2084` | **`+0xb4`** |
| `__AUTH_CONST.__cfstring` | `0x4b80` | `0x4ba0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3227` | `0x3235` | **`+0xe`** |
| `__AUTH_CONST.__auth_got` | `0x1460` | `0x1468` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1660` | `0x1668` | **`+0x8`** |

### Other Changes

```diff

-1520.2.3.0.2
+1520.2.7.1.3

-  Symbols:   5555
-  CStrings:  1430
+  Symbols:   5556
+  CStrings:  1431
Symbols:
+ __os_feature_enabled_impl
Functions:
~ -[__HMFMobileGestaltDataSource init] : 2640 -> 2744
~ -[HMFProductInfo attributeDescriptions] : 632 -> 620
~ _HMFProductClassFromString : 628 -> 716
CStrings:
+ "HomeAccessory"
```
