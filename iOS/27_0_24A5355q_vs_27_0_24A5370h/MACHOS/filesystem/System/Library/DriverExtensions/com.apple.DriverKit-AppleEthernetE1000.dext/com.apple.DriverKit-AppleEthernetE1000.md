## com.apple.DriverKit-AppleEthernetE1000

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleEthernetE1000.dext/com.apple.DriverKit-AppleEthernetE1000`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x308f4` | `0x30a88` | **`+0x194`** |

### Same-size Content Changes

- `__DATA_CONST.__const`

### Other Changes

```diff

-161.0.0.0.0
+168.0.0.0.0
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/ApplePCINetworking_driverkit/install/TempContent/Objects/ApplePCINetworking.build/AppleEthernetE1000.build/Objects-normal/arm64e/DriverKit_AppleEthernetE1000-a7f55903b078fa07dd14ba65d188db77.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/ApplePCINetworking_driverkit/install/TempContent/Objects/ApplePCINetworking.build/AppleEthernetE1000.build/Objects-normal/arm64e/DriverKit_AppleEthernetE1000-98d7ebe546e9a8e991c679bc9c9afc3f.o
Functions:
~ __ZL27e1000_init_phy_params_82575P8e1000_hw : 2016 -> 2004
~ __ZNK34DriverKit_AppleEthernetE1000_IVars10igb_rxSyncEj : 720 -> 728
~ __ZNK34DriverKit_AppleEthernetE1000_IVars10lem_rxSyncEj : 692 -> 700
~ __ZN34DriverKit_AppleEthernetE1000_IVars22getSupportedMediaArrayEPjS0_ : 152 -> 164
~ __ZNK34DriverKit_AppleEthernetE1000_IVars8txSubmitEj : 504 -> 520
~ __Z18e1000_read_nvm_spiP8e1000_hwttPt : 248 -> 256
~ __Z24e1000_read_nvm_microwireP8e1000_hwttPt : 236 -> 232
~ __Z19e1000_read_nvm_eerdP8e1000_hwttPt : 204 -> 220
~ __Z28e1000_tbi_adjust_stats_82543P8e1000_hwP14e1000_hw_statsjPhj : 304 -> 292
~ __ZL17e1000_read_mbx_pfP8e1000_hwPjtt : 1948 -> 1956
~ __ZL18e1000_write_mbx_pfP8e1000_hwPjtt : 1992 -> 2000
~ __Z26e1000_get_cable_length_m88P8e1000_hw : 140 -> 136
~ __Z31e1000_get_cable_length_m88_gen2P8e1000_hw : 624 -> 620
~ __Z28e1000_get_cable_length_igp_2P8e1000_hw : 284 -> 292
~ __ZL29e1000_init_nvm_params_ich8lanP8e1000_hw : 432 -> 440
~ __Z33e1000_lv_jumbo_workaround_ich8lanP8e1000_hwb : 1504 -> 1500
~ __ZL33e1000_update_mc_addr_list_pch2lanP8e1000_hwPhj : 264 -> 272
~ __ZL18e1000_read_nvm_sptP8e1000_hwttPt : 480 -> 492
~ __ZL29e1000_update_nvm_checksum_sptP8e1000_hw : 504 -> 520
~ __ZL22e1000_read_nvm_ich8lanP8e1000_hwttPt : 268 -> 284
~ __ZL33e1000_update_nvm_checksum_ich8lanP8e1000_hw : 532 -> 552
~ __ZL23e1000_write_nvm_ich8lanP8e1000_hwttPt : 172 -> 180
~ __ZL25e1000_read_mac_addr_82540P8e1000_hw : 168 -> 188
~ __Z31e1000_get_bus_info_pcie_genericP8e1000_hw : 156 -> 152
~ __Z32e1000_check_alt_mac_addr_genericP8e1000_hw : 308 -> 332
~ __Z33e1000_update_mc_addr_list_genericP8e1000_hwPhj : 420 -> 392
~ __ZL34e1000_get_cable_length_80003es2lanP8e1000_hw : 156 -> 152
~ __ZN34DriverKit_AppleEthernetE1000_IVars5probeEP11IOPCIDevice : 568 -> 576
~ __ZN34DriverKit_AppleEthernetE1000_IVars16initTransmitUnitEv : 948 -> 960
~ __ZN34DriverKit_AppleEthernetE1000_IVars25setAllMulticastModeEnableEb : 436 -> 432
~ __ZN34DriverKit_AppleEthernetE1000_IVars17setMcastAddressesEPhj : 2880 -> 2904
~ __ZN34DriverKit_AppleEthernetE1000_IVars13mDNS_CallbackEP15nicproxy_info_s : 2096 -> 2076
~ __ZN34DriverKit_AppleEthernetE1000_IVars13sendNSCommandEv : 772 -> 856
~ __ZN34DriverKit_AppleEthernetE1000_IVars20expand_and_save_nameEPN5e10008cur_ctxtEPhP15nicproxy_info_s : 336 -> 332
~ __ZN34DriverKit_AppleEthernetE1000_IVars22expand_and_save_answerEPN5e10008cur_ctxtEPhP15nicproxy_info_sP16RRecord_header_t : 832 -> 828
~ __ZN34DriverKit_AppleEthernetE1000_IVars14buildRRrecordsEPvP15nicproxy_info_sj : 1832 -> 1828
~ __Z28flasher_need_to_erase_sectorPKhS0_ : 104 -> 100
~ __Z19flasher_dump_sectorP8e1000_hwPKhj : 1028 -> 1080
~ __ZL21igb_setup_flex_filterP8e1000_hwiiPhS1_ : 472 -> 468
~ __ZN34DriverKit_AppleEthernetE1000_IVars13allocateRingsEv : 216 -> 252
~ __ZN34DriverKit_AppleEthernetE1000_IVars9freeRingsEv : 104 -> 120
~ __Z24e1000_calculate_checksumPhj : 44 -> 68
~ __Z37e1000_enable_tx_pkt_filtering_genericP8e1000_hw : 244 -> 252
~ __Z34e1000_mng_write_cmd_header_genericP8e1000_hwP29e1000_host_mng_command_header : 172 -> 168
~ __Z31e1000_mng_host_if_write_genericP8e1000_hwPhttS1_ : 504 -> 492
~ __Z28e1000_host_interface_commandP8e1000_hwPhj : 404 -> 416
~ __Z19e1000_load_firmwareP8e1000_hwPhj : 676 -> 672
~ __ZL25e1000_read_mac_addr_82542P8e1000_hw : 144 -> 164
~ __ZL27e1000_init_phy_params_82571P8e1000_hw : 1176 -> 1172
~ __ZL21e1000_write_nvm_82571P8e1000_hwttPt : 248 -> 256
~ __ZL32e1000_get_cable_length_igp_82541P8e1000_hw : 276 -> 284
~ __ZN34DriverKit_AppleEthernetE1000_IVars15initReceiveUnitEv : 2176 -> 2188
```
