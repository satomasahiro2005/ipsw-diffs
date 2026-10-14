## com.apple.driver.AppleM2ScalerCSCDriver

> `com.apple.driver.AppleM2ScalerCSCDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x140ed0` | `0x140e30` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x2534c` | `0x25390` | **`+0x44`** |

### Other Changes

```diff

-200.67.0.0.0
-  Functions: 10275
+200.69.0.0.0
+  Functions: 10276

-  CStrings:  3714
+  CStrings:  3715
Functions:
~ __ZN27M2ScalerScalingControlMSR2326commitFilters_gatedContextEP18M2ScalerCSCRequestPA3_jPjPPK18FilterCoefficients20VerticalOrHorizontalbS4_S4_S4_ : 1456 -> 1204
+ sub_fffffe0009158ad0
~ __ZN33IosaPolyphaseScalingPipeUnitMSR2314prepareFiltersEP16pipeUnitExchangeb20VerticalOrHorizontal : 1812 -> 1556
CStrings:
+ "[%s][%s]bin %d phase 16 gain %d != %d (2*%d + COEFFX %#x), err %+d\n"
```
