## com.apple.driver.AppleT8110DART

> `com.apple.driver.AppleT8110DART`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xf058` | `0xf5f4` | **`+0x59c`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x320` | **`+0x320`** |

### Other Changes

```diff

-498.0.0.0.1
+501.0.0.0.0
Functions:
~ __ZN14AppleT8110DART5startEP9IOService : 2652 -> 2644
~ __ZN14AppleT8110DART6_setupER19t8110dart_init_data : 4364 -> 4360
~ __ZN14AppleT8110DART10_dartSetupER19t8110dart_init_data : 5780 -> 5824
~ sub_fffffff009739f7c -> sub_fffffff00978fc9c : 352 -> 396
~ __ZN14AppleT8110DART17_apfSetupInstanceEjjPKNS_10instance_tER19t8110dart_init_data : 2416 -> 2528
~ __ZN14AppleT8110DART10_gapfSetupEv : 492 -> 524
~ sub_fffffff00973ad68 -> sub_fffffff009790b44 : 124 -> 120
~ __ZN14AppleT8110DART20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 296 -> 292
~ __ZN14AppleT8110DART20_prepareForPowerDownEbb : 976 -> 1020
~ sub_fffffff00973b2dc -> sub_fffffff0097910dc : 112 -> 108
~ sub_fffffff00973b8e8 -> sub_fffffff0097916e4 : 672 -> 668
~ __ZN14AppleT8110DART8_powerUpEv : 620 -> 632
~ sub_fffffff00973c4e8 -> sub_fffffff0097922ec : 308 -> 304
~ __ZN14AppleT8110DART16_interruptActionEP22IOInterruptEventSourcei : 984 -> 1040
~ sub_fffffff00973d758 -> sub_fffffff009793590 : 260 -> 252
~ __ZN14AppleT8110DART30_handleFatalExceptionPreGen2_2Ejb : 1344 -> 1340
~ __ZN14AppleT8110DART15_fatalExceptionEjPKN6IODART16interruptState_tEbb : 1608 -> 1604
~ sub_fffffff00973f414 -> sub_fffffff00979523c : 1924 -> 1968
~ sub_fffffff00973fbbc -> sub_fffffff009795a10 : 544 -> 568
~ sub_fffffff00973fddc -> sub_fffffff009795c48 : 888 -> 908
~ __ZN14AppleT8110DART19_secondaryExceptionEjPNS_39dart_blk_err_status_v18_parameterized_tE : 1348 -> 1356
~ __ZN14AppleT8110DART16_handleInterruptEP22IOInterruptEventSource : 716 -> 732
~ sub_fffffff009740cdc -> sub_fffffff009796b74 : 200 -> 216
~ sub_fffffff009740f14 -> sub_fffffff009796dbc : 380 -> 404
~ sub_fffffff0097410a0 -> sub_fffffff009796f60 : 600 -> 632
~ sub_fffffff0097412f8 -> sub_fffffff0097971d8 : 360 -> 416
~ sub_fffffff009741460 -> sub_fffffff009797378 : 596 -> 708
~ sub_fffffff0097416b4 -> sub_fffffff00979763c : 8240 -> 8796
~ sub_fffffff009743734 -> sub_fffffff0097998e8 : 776 -> 920
~ __ZN14AppleT8110DART24_dartPrepareForPowerDownEjb : 1128 -> 1168
~ sub_fffffff0097448fc -> sub_fffffff00979ab68 : 260 -> 264
~ sub_fffffff009744a38 -> sub_fffffff00979aca8 : 480 -> 484
~ sub_fffffff009744c18 -> sub_fffffff00979ae8c : 304 -> 300
~ sub_fffffff009744d48 -> sub_fffffff00979afb8 : 60 -> 76
~ sub_fffffff009745004 -> sub_fffffff00979b284 : 108 -> 136
```
