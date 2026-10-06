## com.apple.driver.AppleUVDMDriver

> `com.apple.driver.AppleUVDMDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x6bd4` | `0x6d0c` | **`+0x138`** |

### Other Changes

```text
Functions:
~ sub_fffffff009aa3f90 -> sub_fffffff009b2f7c0 : 72 -> 76
~ sub_fffffff009aa3fe0 -> sub_fffffff009b2f814 : 52 -> 56
~ sub_fffffff009aa4014 -> sub_fffffff009b2f84c : 52 -> 56
~ sub_fffffff009aa4058 -> sub_fffffff009b2f894 : 68 -> 72
~ sub_fffffff009aa40c4 -> sub_fffffff009b2f904 : 72 -> 76
~ sub_fffffff009aa410c -> sub_fffffff009b2f950 : 104 -> 108
~ sub_fffffff009aa4188 -> sub_fffffff009b2f9d0 : 88 -> 92
~ sub_fffffff009aa41e0 -> sub_fffffff009b2fa2c : 88 -> 92
~ __ZN17AppleUVDMEndpoint12initWithSelfEP9IOService : 436 -> 440
~ sub_fffffff009aa43ec -> sub_fffffff009b2fc40 : 596 -> 600
~ __ZN17AppleUVDMEndpoint16initWithEPNumberEP9IOServiceh : 196 -> 200
~ __ZN17AppleUVDMEndpoint5startEP9IOService : 256 -> 260
~ __ZN17AppleUVDMEndpoint4openEP9IOServicejPv : 232 -> 236
~ sub_fffffff009aa490c -> sub_fffffff009b30170 : 192 -> 196
~ __ZN17AppleUVDMEndpoint13setPropertiesEP8OSObject : 1692 -> 1696
~ __ZN17AppleUVDMEndpoint11writeStreamEPhthS0_ : 332 -> 336
~ __ZN17AppleUVDMEndpoint10readStreamEPhtPtS0_S0_h : 356 -> 360
~ __ZN17AppleUVDMEndpoint10readAccessEPhhS0_tS0_ : 340 -> 344
~ __ZN17AppleUVDMEndpoint11writeAccessEPhhtS0_ : 332 -> 336
~ sub_fffffff009aa569c -> sub_fffffff009b30f18 : 80 -> 84
~ sub_fffffff009aa56fc -> sub_fffffff009b30f7c : 72 -> 76
~ sub_fffffff009aa574c -> sub_fffffff009b30fd0 : 52 -> 56
~ sub_fffffff009aa5780 -> sub_fffffff009b31008 : 52 -> 56
~ sub_fffffff009aa57c4 -> sub_fffffff009b31050 : 68 -> 72
~ sub_fffffff009aa5830 -> sub_fffffff009b310c0 : 72 -> 76
~ sub_fffffff009aa5878 -> sub_fffffff009b3110c : 104 -> 108
~ sub_fffffff009aa58f4 -> sub_fffffff009b3118c : 88 -> 92
~ sub_fffffff009aa594c -> sub_fffffff009b311e8 : 88 -> 92
~ sub_fffffff009aa59a4 -> sub_fffffff009b31244 : 212 -> 216
~ sub_fffffff009aa5a94 -> sub_fffffff009b31338 : 112 -> 116
~ __ZN21AppleUVDMAceInterface16isUVDMModeActiveEv : 352 -> 356
~ __ZN21AppleUVDMAceInterface11writeAccessEhhPhhtS0_ : 764 -> 768
~ __ZN21AppleUVDMAceInterface10readAccessEhhPhhS0_tS0_ : 836 -> 840
~ __ZN21AppleUVDMAceInterface10readStreamEhhPhtPtS0_S0_h : 880 -> 884
~ __ZN21AppleUVDMAceInterface11writeStreamEhhPhthS0_ : 812 -> 816
~ __ZN21AppleUVDMAceInterface12getAppleVDOsEhP12OSDictionary : 1316 -> 1320
~ __ZN21AppleUVDMAceInterface11setUVDMModeEbPh : 304 -> 308
~ __ZN21AppleUVDMAceInterface11resetAccessEhhPh : 768 -> 772
~ sub_fffffff009aa72ac -> sub_fffffff009b32b74 : 252 -> 256
~ sub_fffffff009aa73a8 -> sub_fffffff009b32c74 : 168 -> 172
~ sub_fffffff009aa7450 -> sub_fffffff009b32d20 : 2232 -> 2236
~ sub_fffffff009aa7d10 -> sub_fffffff009b335e4 : 80 -> 84
~ sub_fffffff009aa7d70 -> sub_fffffff009b33648 : 72 -> 76
~ sub_fffffff009aa7dc0 -> sub_fffffff009b3369c : 64 -> 68
~ sub_fffffff009aa7e00 -> sub_fffffff009b336e0 : 64 -> 68
~ sub_fffffff009aa7e50 -> sub_fffffff009b33734 : 68 -> 72
~ sub_fffffff009aa7ebc -> sub_fffffff009b337a4 : 72 -> 76
~ sub_fffffff009aa7f04 -> sub_fffffff009b337f0 : 52 -> 56
~ sub_fffffff009aa7f54 -> sub_fffffff009b33844 : 100 -> 104
~ sub_fffffff009aa7fb8 -> sub_fffffff009b338ac : 136 -> 140
~ __ZN32IOPortTransportProtocolAppleUVDM5probeEP9IOServicePi : 228 -> 232
~ __ZN32IOPortTransportProtocolAppleUVDM5startEP9IOService : 912 -> 916
~ sub_fffffff009aa84b4 -> sub_fffffff009b33db4 : 60 -> 64
~ __ZN32IOPortTransportProtocolAppleUVDM20setupPowerManagementEv : 332 -> 336
~ sub_fffffff009aa863c -> sub_fffffff009b33f44 : 196 -> 200
~ sub_fffffff009aa8700 -> sub_fffffff009b3400c : 412 -> 416
~ sub_fffffff009aa889c -> sub_fffffff009b341ac : 192 -> 196
~ __ZN32IOPortTransportProtocolAppleUVDM9terminateEj : 156 -> 160
~ __ZN32IOPortTransportProtocolAppleUVDM12getAppleVDOsEhP12OSDictionary : 1724 -> 1728
~ __ZN32IOPortTransportProtocolAppleUVDM18readAccessForStartEhhPhhS0_tS0_iii : 1672 -> 1676
~ __ZN32IOPortTransportProtocolAppleUVDM11finishStartEP9IOService : 172 -> 176
~ __ZN32IOPortTransportProtocolAppleUVDM15setAvailableEPsEv : 624 -> 628
~ __ZN32IOPortTransportProtocolAppleUVDM13setPropertiesEP8OSObject : 400 -> 404
~ __ZN32IOPortTransportProtocolAppleUVDM15getAvailableEPsEPh : 256 -> 260
~ sub_fffffff009aa9d20 -> sub_fffffff009b35650 : 212 -> 216
~ sub_fffffff009aa9df4 -> sub_fffffff009b35728 : 252 -> 256
~ sub_fffffff009aa9ef0 -> sub_fffffff009b35828 : 204 -> 208
~ sub_fffffff009aa9fbc -> sub_fffffff009b358f8 : 180 -> 184
~ __ZN32IOPortTransportProtocolAppleUVDM12poweredStartEv : 868 -> 872
~ sub_fffffff009aaa5a4 -> sub_fffffff009b35ee8 : 80 -> 84
~ sub_fffffff009aaa604 -> sub_fffffff009b35f4c : 72 -> 76
~ sub_fffffff009aaa654 -> sub_fffffff009b35fa0 : 52 -> 56
~ sub_fffffff009aaa6a0 -> sub_fffffff009b35ff0 : 72 -> 76
~ __ZN30AppleUVDMPDControllerInterface4initEv : 136 -> 140
~ sub_fffffff009aaa7a8 -> sub_fffffff009b36100 : 84 -> 88
~ __ZN30AppleUVDMPDControllerInterface7lockBusEy : 436 -> 440
~ sub_fffffff009aaa9b0 -> sub_fffffff009b36310 : 96 -> 100
~ sub_fffffff009aaaa70 -> sub_fffffff009b363d4 : 80 -> 84
```
