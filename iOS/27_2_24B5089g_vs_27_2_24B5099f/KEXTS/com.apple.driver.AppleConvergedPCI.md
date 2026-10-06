## com.apple.driver.AppleConvergedPCI

> `com.apple.driver.AppleConvergedPCI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x3c508` | `0x3c5f4` | **`+0xec`** |
| `__TEXT.__cstring` | `0x6819` | `0x682d` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x48d8` | `0x48e8` | **`+0x10`** |

### Other Changes

```diff

-197.0.0.0.0
-  Functions: 1089
+197.40.2.0.0
+  Functions: 1091

-  CStrings:  899
+  CStrings:  900
Functions:
~ __ZN24AppleConvergedIPCControl15providerMessageEPvjP9IOServiceS0_m : 1968 -> 2088
+ sub_fffffff008a583d4
+ sub_fffffff008a58448
CStrings:
+ "kACIPCAFLinkTimeout"
```
