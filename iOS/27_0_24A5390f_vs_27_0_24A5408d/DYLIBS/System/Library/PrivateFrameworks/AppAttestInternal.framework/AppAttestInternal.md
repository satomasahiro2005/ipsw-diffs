## AppAttestInternal

> `/System/Library/PrivateFrameworks/AppAttestInternal.framework/AppAttestInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69b78` | `0x69c58` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x651e` | `0x659e` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0xbe8` | `0xbf0` | **`+0x8`** |

### Other Changes

```diff

-154.0.0.0.0
+156.0.0.0.0

-  CStrings:  826
+  CStrings:  829
Functions:
~ sub_22c4e2670 -> sub_22bd0e670 : 8796 -> 8800
~ sub_22c4e53d8 -> sub_22bd113dc : 564 -> 784
CStrings:
+ "AppAttest (%@-156) - %@"
+ "Not fetching CD hash."
+ "Should fetch CD hash. { source=default }"
+ "Should fetch CD hash. { source=entitlement }"
- "AppAttest (%@-154) - %@"
```
