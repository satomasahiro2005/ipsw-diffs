## com.apple.driver.AppleIOPADMAStream

> `com.apple.driver.AppleIOPADMAStream`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x4b0` | **`+0x4b0`** |
| `__TEXT_EXEC.__text` | `0x13bb8` | `0x13de0` | **`+0x228`** |

### Other Changes

```text
Functions:
~ __ZN11AppleIASMCA22initExternalPowerGatedEP9IOService : 772 -> 788
~ sub_fffffff008fb3f44 -> sub_fffffff008fe02f4 : 420 -> 416
~ __ZN18AppleIOPADMAStream5startEP9IOService : 968 -> 996
~ __ZN18AppleIOPADMAStream18deferredStartGatedEv : 636 -> 664
~ sub_fffffff008fb56ec -> sub_fffffff008fe1ad0 : 352 -> 380
~ __ZN18AppleIOPADMAStream29setIISControllerActive_ForcedEb : 1016 -> 1044
~ sub_fffffff008fb5c44 -> sub_fffffff008fe2060 : 284 -> 312
~ __ZN18AppleIOPADMAStream14validIISConfigEP17AppleARMIISDeviceP17AppleARMIISConfig : 896 -> 924
~ __ZN18AppleIOPADMAStream12setIISConfigEP17AppleARMIISDeviceP17AppleARMIISConfig : 672 -> 700
~ __ZN18AppleIOPADMAStream17executeIISCommandEP18AppleARMIISCommand : 1024 -> 1048
~ __ZN18AppleIOPADMAStream15abortIISCommandEj : 816 -> 844
~ sub_fffffff008fb703c -> sub_fffffff008fe34e0 : 368 -> 388
~ __ZN18AppleIOPADMAStream15startIISCommandEj : 1088 -> 1144
~ __ZN18AppleIOPADMAStream14stopIISCommandEj : 732 -> 760
~ __ZN18AppleIOPADMAStream9initForPMEP9IOService : 484 -> 512
~ sub_fffffff008fb7b58 -> sub_fffffff008fe4080 : 244 -> 272
~ sub_fffffff008fb7c4c -> sub_fffffff008fe4190 : 216 -> 244
~ __ZN18AppleIOPADMAStream18setPowerStateGatedEmP9IOService : 1008 -> 1036
~ sub_fffffff008fb8494 -> sub_fffffff008fe4a10 : 236 -> 264
~ sub_fffffff008fb8580 -> sub_fffffff008fe4b18 : 196 -> 224
~ __ZNK16IASClientManager20validIISConfigCommonERK17AppleARMIISConfigPKcRK14AppleMCATiming : 2916 -> 2924
~ __ZNK16IASClientManager20generateAPMCAFromIISERK17AppleARMIISConfigRK14AppleMCATimingP11APMCAConfig : 1720 -> 1724
~ __ZN16IASClientManager15setIISConfigMcaEP17AppleARMIISConfig : 1324 -> 1332
~ __ZN20IASDMAChannelManager16hasDMAPropertiesEP9IOService : 528 -> 524
~ __ZN20IASDMAChannelManager24initWithIODMAEventSourceE11OSSharedPtrI9IOServiceERKS2_ : 2476 -> 2484
~ __ZNK20IASDMAChannelManager17computeParametersEhhjPNS_17ChannelParametersE : 756 -> 752
```
