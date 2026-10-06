## com.apple.driver.AppleSPIMC

> `com.apple.driver.AppleSPIMC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x7000` | `0x7040` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1757` | `0x1777` | **`+0x20`** |

### Other Changes

```diff

-39.0.0.0.0
+39.0.0.0.1

-  CStrings:  165
+  CStrings:  166
Functions:
~ __ZN20AppleSPIMCController21_executeSPICommandPIOEP18AppleARMSPICommand : 3912 -> 3976
CStrings:
+ "%s %s:%d: transaction timeout!\n"
```
