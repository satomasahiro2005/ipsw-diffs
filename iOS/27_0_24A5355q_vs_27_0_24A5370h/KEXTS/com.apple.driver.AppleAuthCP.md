## com.apple.driver.AppleAuthCP

> `com.apple.driver.AppleAuthCP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x490` | **`+0x490`** |
| `__TEXT_EXEC.__text` | `0x1a414` | `0x1a454` | **`+0x40`** |

### Other Changes

```diff

-184.0.0.0.0
+185.0.0.0.0
Functions:
~ sub_fffffff008850e88 -> sub_fffffff008862438 : 252 -> 276
~ sub_fffffff008852900 -> sub_fffffff008863ec8 : 20 -> 12
~ sub_fffffff008852920 -> sub_fffffff008863ee0 : 12 -> 20
~ __ZN15AppleAuthCPDock23createFormattedResponseEPKvyPvPyy : 380 -> 388
~ __ZN26MogulAuthSMCRelayInterface12transferDataEjyPhyPv : 536 -> 552
~ __ZN27Area51AuthSMCRelayInterface12transferDataEjyPhyPv : 536 -> 552
~ __ZN27Area51AuthSMCRelayInterface20_smcIICRegisterWriteEyPhh : 1136 -> 1140
~ __ZN14AppleAuthCPI2C5startEP9IOService : 2312 -> 2308
```
