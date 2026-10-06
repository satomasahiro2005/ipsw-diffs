## com.apple.driver.AppleSEPHDCPManager

> `com.apple.driver.AppleSEPHDCPManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x4870` | `0x49e8` | **`+0x178`** |

### Other Changes

```text
Functions:
~ sub_fffffff00953db20 -> sub_fffffff0095bb570 : 72 -> 76
~ sub_fffffff00953db70 -> sub_fffffff0095bb5c4 : 52 -> 56
~ sub_fffffff00953dba4 -> sub_fffffff0095bb5fc : 52 -> 56
~ sub_fffffff00953dbe8 -> sub_fffffff0095bb644 : 68 -> 72
~ sub_fffffff00953dc54 -> sub_fffffff0095bb6b4 : 72 -> 76
~ __ZN16AppleHDCPManager18serializeDebugInfoEPvP11OSSerialize : 552 -> 556
~ sub_fffffff00953dee4 -> sub_fffffff0095bb94c : 112 -> 116
~ sub_fffffff00953df68 -> sub_fffffff0095bb9d4 : 80 -> 84
~ sub_fffffff00953e1a8 -> sub_fffffff0095bbc18 : 96 -> 100
~ sub_fffffff00953e208 -> sub_fffffff0095bbc7c : 120 -> 124
~ sub_fffffff00953e280 -> sub_fffffff0095bbcf8 : 140 -> 144
~ sub_fffffff00953e30c -> sub_fffffff0095bbd88 : 72 -> 76
~ sub_fffffff00953e35c -> sub_fffffff0095bbddc : 52 -> 56
~ sub_fffffff00953e390 -> sub_fffffff0095bbe14 : 52 -> 56
~ sub_fffffff00953e3d4 -> sub_fffffff0095bbe5c : 68 -> 72
~ sub_fffffff00953e440 -> sub_fffffff0095bbecc : 72 -> 76
~ sub_fffffff00953e488 -> sub_fffffff0095bbf18 : 104 -> 108
~ sub_fffffff00953e504 -> sub_fffffff0095bbf98 : 88 -> 92
~ sub_fffffff00953e55c -> sub_fffffff0095bbff4 : 88 -> 92
~ __ZN18AppleHDCPInterface11withOptionsEP9IOServiceP25AppleHDCPEndpointProtocolP20SEPHDCPInterfaceInfo : 356 -> 360
~ __ZN18AppleHDCPInterface11handleCloseEP9IOService : 240 -> 244
~ sub_fffffff00953e86c -> sub_fffffff0095bc310 : 80 -> 84
~ sub_fffffff00953e928 -> sub_fffffff0095bc3d0 : 20 -> 28
~ sub_fffffff00953e93c -> sub_fffffff0095bc3ec : 28 -> 20
~ sub_fffffff00953ea1c -> sub_fffffff0095bc4c4 : 72 -> 76
~ sub_fffffff00953ea6c -> sub_fffffff0095bc518 : 52 -> 56
~ sub_fffffff00953eaa0 -> sub_fffffff0095bc550 : 52 -> 56
~ sub_fffffff00953eae4 -> sub_fffffff0095bc598 : 68 -> 72
~ sub_fffffff00953eb50 -> sub_fffffff0095bc608 : 72 -> 76
~ sub_fffffff00953eb98 -> sub_fffffff0095bc654 : 104 -> 108
~ sub_fffffff00953ec14 -> sub_fffffff0095bc6d4 : 88 -> 92
~ sub_fffffff00953ec6c -> sub_fffffff0095bc730 : 88 -> 92
~ __ZN19AppleSEPHDCPManager5startEP9IOService : 168 -> 172
~ sub_fffffff00953ed80 -> sub_fffffff0095bc84c : 80 -> 84
~ sub_fffffff00953ede0 -> sub_fffffff0095bc8b0 : 72 -> 76
~ sub_fffffff00953ee30 -> sub_fffffff0095bc904 : 84 -> 88
~ sub_fffffff00953ee84 -> sub_fffffff0095bc95c : 84 -> 88
~ sub_fffffff00953eef4 -> sub_fffffff0095bc9d0 : 68 -> 72
~ sub_fffffff00953ef50 -> sub_fffffff0095bca30 : 72 -> 76
~ sub_fffffff00953efa8 -> sub_fffffff0095bca8c : 72 -> 76
~ sub_fffffff00953eff0 -> sub_fffffff0095bcad8 : 136 -> 140
~ sub_fffffff00953f08c -> sub_fffffff0095bcb78 : 120 -> 124
~ sub_fffffff00953f104 -> sub_fffffff0095bcbf4 : 120 -> 124
~ _panic : 304 -> 308
~ __ZN20AppleSEPHDCPEndpoint6actionEPvS0_ : 380 -> 384
~ sub_fffffff00953f428 -> sub_fffffff0095bcf24 : 152 -> 156
~ sub_fffffff00953f4c0 -> sub_fffffff0095bcfc0 : 144 -> 148
~ sub_fffffff00953f598 -> sub_fffffff0095bd09c : 144 -> 148
~ sub_fffffff00953f628 -> sub_fffffff0095bd130 : 144 -> 148
~ __ZN20AppleSEPHDCPEndpoint12disableGatedEv : 76 -> 80
~ sub_fffffff00953f704 -> sub_fffffff0095bd214 : 144 -> 148
~ sub_fffffff00953f794 -> sub_fffffff0095bd2a8 : 156 -> 160
~ sub_fffffff00953f830 -> sub_fffffff0095bd348 : 156 -> 160
~ __ZN20AppleSEPHDCPEndpoint27waitForEndpointAvailabilityEPKN25AppleHDCPEndpointProtocol11RequestArgsE : 568 -> 572
~ __ZN20AppleSEPHDCPEndpoint28signalForEndpointAvailabiltyEPKN25AppleHDCPEndpointProtocol11RequestArgsE : 240 -> 244
~ sub_fffffff00953fbfc -> sub_fffffff0095bd720 : 80 -> 84
~ __ZN16AppleHDCPManager5startEP9IOServiceP25AppleHDCPEndpointProtocol : 584 -> 588
~ __ZN16AppleHDCPManager16launchInterfacesEv : 840 -> 844
~ sub_fffffff009540464 -> sub_fffffff0095bdf94 : 144 -> 148
~ __ZN18AppleHDCPInterface11handleStartEP9IOService : 320 -> 324
~ __ZN18AppleHDCPInterface19serializeDeviceRoleEPvP11OSSerialize : 136 -> 140
~ __ZN18AppleHDCPInterface18matchPropertyTableEP12OSDictionaryPi : 468 -> 472
~ sub_fffffff009540a94 -> sub_fffffff0095be5d4 : 88 -> 92
~ sub_fffffff009540aec -> sub_fffffff0095be630 : 88 -> 92
~ sub_fffffff009540b44 -> sub_fffffff0095be68c : 104 -> 108
~ sub_fffffff009540bac -> sub_fffffff0095be6f8 : 104 -> 108
~ __ZN18AppleHDCPInterface8readCertEP11IOHDCP_Cert : 216 -> 220
~ sub_fffffff009540d54 -> sub_fffffff0095be8a8 : 96 -> 100
~ sub_fffffff009540db4 -> sub_fffffff0095be90c : 104 -> 108
~ sub_fffffff009540e80 -> sub_fffffff0095be9dc : 96 -> 100
~ sub_fffffff009540ee0 -> sub_fffffff0095bea40 : 108 -> 112
~ sub_fffffff009540f4c -> sub_fffffff0095beab0 : 96 -> 100
~ __ZN18AppleHDCPInterface12consumeNewKmE14IOHDCP_EKpubKm : 248 -> 252
~ sub_fffffff0095410a4 -> sub_fffffff0095bec10 : 128 -> 132
~ sub_fffffff009541124 -> sub_fffffff0095bec94 : 96 -> 100
~ sub_fffffff0095411ec -> sub_fffffff0095bed60 : 96 -> 100
~ sub_fffffff00954124c -> sub_fffffff0095bedc4 : 108 -> 112
~ sub_fffffff0095412b8 -> sub_fffffff0095bee34 : 88 -> 92
~ sub_fffffff009541310 -> sub_fffffff0095bee90 : 104 -> 108
~ sub_fffffff0095413cc -> sub_fffffff0095bef50 : 88 -> 92
~ sub_fffffff009541424 -> sub_fffffff0095befac : 104 -> 108
~ sub_fffffff0095414e0 -> sub_fffffff0095bf06c : 88 -> 92
~ sub_fffffff0095415fc -> sub_fffffff0095bf18c : 116 -> 120
~ sub_fffffff009541670 -> sub_fffffff0095bf204 : 88 -> 92
~ sub_fffffff0095417d0 -> sub_fffffff0095bf368 : 144 -> 148
~ sub_fffffff009541860 -> sub_fffffff0095bf3fc : 88 -> 92
~ __ZN18AppleHDCPInterface11withOptionsEP9IOServiceP25AppleHDCPEndpointProtocolP20SEPHDCPInterfaceInfo.cold.1 : 64 -> 68
~ __ZN18AppleHDCPInterface11withOptionsEP9IOServiceP25AppleHDCPEndpointProtocolP20SEPHDCPInterfaceInfo.cold.2 : 64 -> 68
~ __ZN18AppleHDCPInterface11withOptionsEP9IOServiceP25AppleHDCPEndpointProtocolP20SEPHDCPInterfaceInfo.cold.3 : 196 -> 200
~ __ZN19AppleSEPHDCPManager5startEP9IOService.cold.1 : 84 -> 88
~ __ZN19AppleSEPHDCPManager5startEP9IOService.cold.2 : 84 -> 88
~ __ZN20AppleSEPHDCPEndpoint21initWithDeviceServiceEP21AppleSEPDeviceService : 128 -> 132
~ __ZN20AppleSEPHDCPEndpoint18handleRequestGatedEPKN25AppleHDCPEndpointProtocol11RequestArgsE : 1456 -> 1460
~ __ZN20AppleSEPHDCPEndpoint21initWithDeviceServiceEP21AppleSEPDeviceService.cold.1 : 44 -> 48
~ __ZN20AppleSEPHDCPEndpoint12disableGatedEv.cold.1 : 44 -> 48
~ __ZN20AppleSEPHDCPEndpoint28signalForEndpointAvailabiltyEPKN25AppleHDCPEndpointProtocol11RequestArgsE.cold.1 : 68 -> 72
```
