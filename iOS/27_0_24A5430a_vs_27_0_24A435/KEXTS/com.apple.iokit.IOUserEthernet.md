## com.apple.iokit.IOUserEthernet

> `com.apple.iokit.IOUserEthernet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x57a4` | `0x5914` | **`+0x170`** |

### Other Changes

```text
Functions:
~ sub_fffffff00a711670 -> sub_fffffff00a7f1940 : 72 -> 76
~ sub_fffffff00a7116c0 -> sub_fffffff00a7f1994 : 52 -> 56
~ sub_fffffff00a7116f4 -> sub_fffffff00a7f19cc : 52 -> 56
~ sub_fffffff00a711738 -> sub_fffffff00a7f1a14 : 68 -> 72
~ sub_fffffff00a7117a4 -> sub_fffffff00a7f1a84 : 72 -> 76
~ sub_fffffff00a7117ec -> sub_fffffff00a7f1ad0 : 104 -> 108
~ sub_fffffff00a711868 -> sub_fffffff00a7f1b50 : 88 -> 92
~ sub_fffffff00a7118c0 -> sub_fffffff00a7f1bac : 88 -> 92
~ sub_fffffff00a711988 -> sub_fffffff00a7f1c78 : 28 -> 32
~ sub_fffffff00a7119a4 -> sub_fffffff00a7f1c98 : 80 -> 84
~ __ZN32IOUserEthernetResourceUserClient12initWithTaskEP4taskPvj : 284 -> 288
~ sub_fffffff00a711b10 -> sub_fffffff00a7f1e0c : 164 -> 168
~ __ZN32IOUserEthernetResourceUserClient5startEP9IOService : 272 -> 276
~ sub_fffffff00a711cc4 -> sub_fffffff00a7f1fc8 : 184 -> 188
~ __ZN32IOUserEthernetResourceUserClient19terminateControllerEv : 208 -> 212
~ sub_fffffff00a711e4c -> sub_fffffff00a7f2158 : 56 -> 60
~ sub_fffffff00a711e84 -> sub_fffffff00a7f2194 : 204 -> 208
~ sub_fffffff00a711fa8 -> sub_fffffff00a7f22bc : 112 -> 116
~ __ZN32IOUserEthernetResourceUserClient11clientCloseEv : 172 -> 176
~ __ZN32IOUserEthernetResourceUserClient10clientDiedEv : 176 -> 180
~ __ZN32IOUserEthernetResourceUserClient21createControllerGatedEP25IOExternalMethodArguments : 876 -> 880
~ sub_fffffff00a7125ac -> sub_fffffff00a7f28d0 : 204 -> 208
~ sub_fffffff00a7126d4 -> sub_fffffff00a7f29fc : 80 -> 84
~ sub_fffffff00a712758 -> sub_fffffff00a7f2a84 : 80 -> 84
~ sub_fffffff00a7127b8 -> sub_fffffff00a7f2ae8 : 72 -> 76
~ sub_fffffff00a712808 -> sub_fffffff00a7f2b3c : 52 -> 56
~ sub_fffffff00a71283c -> sub_fffffff00a7f2b74 : 52 -> 56
~ sub_fffffff00a712880 -> sub_fffffff00a7f2bbc : 68 -> 72
~ sub_fffffff00a7128ec -> sub_fffffff00a7f2c2c : 72 -> 76
~ sub_fffffff00a712934 -> sub_fffffff00a7f2c78 : 104 -> 108
~ sub_fffffff00a7129b0 -> sub_fffffff00a7f2cf8 : 88 -> 92
~ sub_fffffff00a712a08 -> sub_fffffff00a7f2d54 : 88 -> 92
~ sub_fffffff00a712a68 -> sub_fffffff00a7f2db8 : 140 -> 144
~ sub_fffffff00a712af4 -> sub_fffffff00a7f2e48 : 108 -> 112
~ sub_fffffff00a712b6c -> sub_fffffff00a7f2ec4 : 220 -> 224
~ sub_fffffff00a712c50 -> sub_fffffff00a7f2fac : 80 -> 84
~ sub_fffffff00a712cb0 -> sub_fffffff00a7f3010 : 72 -> 76
~ sub_fffffff00a712d00 -> sub_fffffff00a7f3064 : 52 -> 56
~ sub_fffffff00a712d34 -> sub_fffffff00a7f309c : 52 -> 56
~ sub_fffffff00a712d78 -> sub_fffffff00a7f30e4 : 68 -> 72
~ sub_fffffff00a712de4 -> sub_fffffff00a7f3154 : 72 -> 76
~ sub_fffffff00a712e2c -> sub_fffffff00a7f31a0 : 104 -> 108
~ sub_fffffff00a712ea8 -> sub_fffffff00a7f3220 : 88 -> 92
~ sub_fffffff00a712f00 -> sub_fffffff00a7f327c : 88 -> 92
~ __ZL24__client_attach_callbackP9en_clientPvm : 404 -> 408
~ sub_fffffff00a7131c0 -> sub_fffffff00a7f3544 : 220 -> 224
~ sub_fffffff00a713968 -> sub_fffffff00a7f3cf0 : 268 -> 272
~ __ZN24IOUserEthernetController27startWithStateEventCallbackEP9IOServicePFvP8OSObjectPS_PvES3_S5_ : 1412 -> 1416
~ sub_fffffff00a713ff8 -> sub_fffffff00a7f4388 : 336 -> 340
~ sub_fffffff00a71415c -> sub_fffffff00a7f44f0 : 240 -> 244
~ __ZN24IOUserEthernetController18configureInterfaceEP18IONetworkInterface : 400 -> 404
~ sub_fffffff00a71450c -> sub_fffffff00a7f48a8 : 84 -> 88
~ sub_fffffff00a714560 -> sub_fffffff00a7f4900 : 140 -> 144
~ sub_fffffff00a7145ec -> sub_fffffff00a7f4990 : 32 -> 36
~ __ZN24IOUserEthernetController14setEnableStateEb : 236 -> 240
~ sub_fffffff00a7146f8 -> sub_fffffff00a7f4aa4 : 32 -> 36
~ __ZN24IOUserEthernetController11outputStartEP18IONetworkInterfacej : 672 -> 676
~ __ZN24IOUserEthernetController28invalidateStateEventCallbackEv : 276 -> 280
~ __ZN24IOUserEthernetController15setRunningStateEb : 216 -> 220
~ __ZN24IOUserEthernetController12reportLinkUpEb : 280 -> 284
~ __ZN24IOUserEthernetController18handleClientAttachEP9en_client : 888 -> 892
~ __ZN24IOUserEthernetController19handleClientPacketsEP9en_clientP6__mbuf : 612 -> 616
~ __ZN24IOUserEthernetController18handleClientDetachEP9en_client : 668 -> 672
~ __ZN24IOUserEthernetController15handleBSDAttachEP18IONetworkInterface : 332 -> 336
~ __ZN24IOUserEthernetController15handleBSDDetachEP18IONetworkInterface : 320 -> 324
~ __ZN24IOUserEthernetController12setLinkStateEb : 332 -> 336
~ __ZN24IOUserEthernetController22setIfpPowerSavingsMaskEb : 388 -> 392
~ sub_fffffff00a715b34 -> sub_fffffff00a7f5f10 : 80 -> 84
~ _en_register : 336 -> 340
~ sub_fffffff00a715ce4 -> sub_fffffff00a7f60c8 : 64 -> 68
~ sub_fffffff00a715df4 -> sub_fffffff00a7f61dc : 64 -> 68
~ sub_fffffff00a715e58 -> sub_fffffff00a7f6244 : 80 -> 84
~ sub_fffffff00a715ea8 -> sub_fffffff00a7f6298 : 88 -> 92
~ sub_fffffff00a715f00 -> sub_fffffff00a7f62f4 : 56 -> 60
~ _en_set_route_cleanup : 132 -> 136
~ _virtio_mbuf_prepend_header : 716 -> 720
~ _virtio_mbuf_ingest_header : 544 -> 548
~ sub_fffffff00a7164c4 -> sub_fffffff00a7f68c8 : 72 -> 76
~ sub_fffffff00a716514 -> sub_fffffff00a7f691c : 52 -> 56
~ sub_fffffff00a716548 -> sub_fffffff00a7f6954 : 52 -> 56
~ sub_fffffff00a71658c -> sub_fffffff00a7f699c : 68 -> 72
~ sub_fffffff00a7165f8 -> sub_fffffff00a7f6a0c : 72 -> 76
~ sub_fffffff00a716640 -> sub_fffffff00a7f6a58 : 104 -> 108
~ sub_fffffff00a7166bc -> sub_fffffff00a7f6ad8 : 88 -> 92
~ sub_fffffff00a716714 -> sub_fffffff00a7f6b34 : 88 -> 92
~ sub_fffffff00a716774 -> sub_fffffff00a7f6b98 : 68 -> 72
~ __ZN23IOUserEthernetInterface21attachToDataLinkLayerEjPv : 284 -> 288
~ __ZN23IOUserEthernetInterface23detachFromDataLinkLayerEjPv : 380 -> 384
~ __ZN23IOUserEthernetInterface15registerServiceEj : 280 -> 284
~ __ZNK23IOUserEthernetInterface13getNamePrefixEv : 240 -> 244
~ sub_fffffff00a716c60 -> sub_fffffff00a7f7098 : 80 -> 84
~ sub_fffffff00a716d44 -> sub_fffffff00a7f7180 : 108 -> 112
```
