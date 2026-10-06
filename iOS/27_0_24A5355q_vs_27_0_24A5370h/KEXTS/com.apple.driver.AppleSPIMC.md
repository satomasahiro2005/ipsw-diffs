## com.apple.driver.AppleSPIMC

> `com.apple.driver.AppleSPIMC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x250` | **`+0x250`** |
| `__TEXT_EXEC.__text` | `0x6fd0` | `0x7000` | **`+0x30`** |

### Other Changes

```text
Functions:
~ sub_fffffff00963eb68 -> sub_fffffff009690db8 : 256 -> 300
~ __ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand : 2356 -> 2380
~ sub_fffffff009641c30 -> sub_fffffff009693ec4 : 312 -> 308
~ sub_fffffff009641d68 -> sub_fffffff009693ff8 : 40 -> 36
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize : 2500 -> 2488
```
