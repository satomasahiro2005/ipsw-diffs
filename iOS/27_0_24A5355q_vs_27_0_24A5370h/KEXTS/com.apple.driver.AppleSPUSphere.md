## com.apple.driver.AppleSPUSphere

> `com.apple.driver.AppleSPUSphere`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x200` | **`+0x200`** |
| `__TEXT_EXEC.__text` | `0x1b18` | `0x1b58` | **`+0x40`** |

### Other Changes

```diff

-1084.0.0.0.0
+1087.0.0.0.0
Functions:
~ __ZN20AppleSPUSphereDriver12setDataGatedEP8OSStringPvS2_ : 1000 -> 1020
~ __ZN20AppleSPUSphereDriver28printServiceStatsForEndpointEP15_SPUSphereStats19SphereEndpointIndex : 492 -> 520
~ sub_fffffff0096bcca4 -> sub_fffffff009711874 : 228 -> 248
~ __ZN20AppleSPUSphereDriver14setEnableGatedEbPv : 300 -> 296
```
