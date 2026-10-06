## com.apple.driver.AppleT8130TypeCPhy

> `com.apple.driver.AppleT8130TypeCPhy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x4c188` | `0x4c484` | **`+0x2fc`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x260` | **`+0x260`** |

### Other Changes

```diff

-311.0.0.0.0
+316.0.0.0.0
Functions:
~ __ZN18AppleT8130TypeCPhy5startEP9IOService : 7980 -> 8060
~ sub_fffffff0099b533c -> sub_fffffff009a1411c : 508 -> 520
~ __ZN18AppleT8130TypeCPhy30aciophy_dptx_set_rxtxeq_presetEbjj : 3068 -> 3144
~ __ZN18AppleT8130TypeCPhy28aciophy_dptx_set_txeq_presetEbjj : 4128 -> 4156
~ __ZN18AppleT8130TypeCPhy17interruptOccurredEP22IOInterruptEventSourcei : 9888 -> 9876
~ __ZN18AppleT8130TypeCPhy20aciophy_dptx_prog_txEjh : 11180 -> 11308
~ __ZN18AppleT8130TypeCPhy22aciophy_dptx_prog_rxtxEjh : 27796 -> 28016
~ __ZN18AppleT8130TypeCPhy24aciophy_dptx_shutdown_txEj : 6424 -> 6468
~ __ZN18AppleT8130TypeCPhy26aciophy_dptx_shutdown_rxtxEj : 9972 -> 10044
~ sub_fffffff0099e4394 -> sub_fffffff009a433ac : 1784 -> 1780
~ __ZN18AppleT8130TypeCPhy16loadS2RSavePartAEj : 56632 -> 56912
~ __ZN18AppleT8130TypeCPhy16loadS2RSavePartBEj : 11956 -> 11768
~ __ZN18AppleT8130TypeCPhy13applyTunablesEjPK6OSData : 1468 -> 1496
```
