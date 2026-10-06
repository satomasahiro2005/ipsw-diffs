## com.apple.DriverKit-AppleEthernetIXGBE

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleEthernetIXGBE.dext/com.apple.DriverKit-AppleEthernetIXGBE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2de94` | `0x2df40` | **`+0xac`** |
| `__TEXT.__const` | `0xd28` | `0xd38` | **`+0x10`** |

### Same-size Content Changes

- `__DATA_CONST.__const`

### Other Changes

```diff

-161.0.0.0.0
+168.0.0.0.0
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/ApplePCINetworking_driverkit/install/TempContent/Objects/ApplePCINetworking.build/AppleEthernetIXGBE.build/Objects-normal/arm64e/DriverKit_AppleEthernetIXGBE-55cf9f8bba5fd1dcce49627992cd16b1.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/ApplePCINetworking_driverkit/install/TempContent/Objects/ApplePCINetworking.build/AppleEthernetIXGBE.build/Objects-normal/arm64e/DriverKit_AppleEthernetIXGBE-153f030a3eb3c6025c712b482adbce86.o
Functions:
~ __Z33ixgbe_write_ee_hostif_buffer_X550P8ixgbe_hwttPt : 340 -> 336
~ __Z25ixgbe_init_phy_ops_X550emP8ixgbe_hw : 896 -> 888
~ __ZL21ixgbe_identify_phy_fwP8ixgbe_hw : 224 -> 232
~ __Z23ixgbe_init_ops_X550EM_aP8ixgbe_hw : 472 -> 464
~ __ZL19ixgbe_setup_fw_linkP8ixgbe_hw : 296 -> 300
~ __Z24ixgbe_calc_checksum_X550P8ixgbe_hwPtj : 728 -> 724
~ __ZNK34DriverKit_AppleEthernetIXGBE_IVars8txSubmitEj : 348 -> 356
~ __Z28ixgbe_dcb_get_tc_stats_82599P8ixgbe_hwP14ixgbe_hw_statsh : 524 -> 544
~ __Z29ixgbe_dcb_get_pfc_stats_82599P8ixgbe_hwP14ixgbe_hw_statsh : 248 -> 268
~ __Z33ixgbe_dcb_config_rx_arbiter_82599P8ixgbe_hwPtS1_PhS2_S2_ : 276 -> 272
~ __Z38ixgbe_dcb_config_tx_desc_arbiter_82599P8ixgbe_hwPtS1_PhS2_ : 272 -> 260
~ __Z38ixgbe_dcb_config_tx_data_arbiter_82599P8ixgbe_hwPtS1_PhS2_S2_ : 300 -> 296
~ __Z26ixgbe_dcb_config_pfc_82599P8ixgbe_hwhPh : 616 -> 604
~ __Z21ixgbe_get_mac_addr_vfP8ixgbe_hwPh : 44 -> 40
~ __Z28ixgbe_update_mc_addr_list_vfP8ixgbe_hwPhjPFS1_S0_PS1_PjEb : 412 -> 420
~ __ZNK34DriverKit_AppleEthernetIXGBE_IVars6rxSyncEj : 712 -> 720
~ __ZN34DriverKit_AppleEthernetIXGBE_IVars9handleMODEv : 1084 -> 1080
~ __ZN34DriverKit_AppleEthernetIXGBE_IVars22getSupportedMediaArrayEPjS0_ : 508 -> 512
~ __ZN34DriverKit_AppleEthernetIXGBE_IVars5probeEP11IOPCIDevice : 552 -> 560
~ __ZN34DriverKit_AppleEthernetIXGBE_IVars15initReceiveUnitEv : 824 -> 820
~ __ZN34DriverKit_AppleEthernetIXGBE_IVars16initTransmitUnitEv : 592 -> 600
~ __ZN34DriverKit_AppleEthernetIXGBE_IVars8logStateEv : 2112 -> 2100
~ __Z21ixgbe_fc_enable_82598P8ixgbe_hw : 776 -> 800
~ __ZN34DriverKit_AppleEthernetIXGBE_IVars13allocateRingsEv : 196 -> 224
~ __ZN34DriverKit_AppleEthernetIXGBE_IVars9freeRingsEv : 100 -> 112
~ __Z30ixgbe_read_eerd_buffer_genericP8ixgbe_hwttPt : 396 -> 404
~ __Z42ixgbe_write_eeprom_buffer_bit_bang_genericP8ixgbe_hwttPt : 460 -> 464
~ __Z33ixgbe_update_mc_addr_list_genericP8ixgbe_hwPhjPFS1_S0_PS1_PjEb : 516 -> 512
~ __Z23ixgbe_fc_enable_genericP8ixgbe_hw : 712 -> 720
~ __ZL33ixgbe_read_eeprom_buffer_bit_bangP8ixgbe_hwttPt : 300 -> 296
~ __Z31ixgbe_write_eewr_buffer_genericP8ixgbe_hwttPt : 420 -> 436
~ __Z30ixgbe_get_san_mac_addr_genericP8ixgbe_hwPh : 316 -> 336
~ __Z30ixgbe_set_san_mac_addr_genericP8ixgbe_hwPh : 244 -> 268
~ __Z24ixgbe_calculate_checksumPhj : 132 -> 156
~ __Z18ixgbe_hic_unlockedP8ixgbe_hwPjjj : 628 -> 644
~ __Z28ixgbe_host_interface_commandP8ixgbe_hwPjjjb : 608 -> 612
~ __Z40ixgbe_get_supported_physical_layer_82599P8ixgbe_hw : 424 -> 420
~ __Z36ixgbe_atr_compute_perfect_hash_82599P15ixgbe_atr_inputS0_ : 292 -> 288
~ __Z30ixgbe_dcb_calculate_tc_creditsPhPtS0_i : 164 -> 156
~ __Z34ixgbe_dcb_calculate_tc_credits_ceeP8ixgbe_hwP16ixgbe_dcb_configjh : 316 -> 320
~ __Z24ixgbe_dcb_unpack_pfc_ceeP16ixgbe_dcb_configPhS1_ : 64 -> 60
~ __Z27ixgbe_dcb_unpack_refill_ceeP16ixgbe_dcb_configiPt : 44 -> 48
~ __Z26ixgbe_dcb_unpack_bwgid_ceeP16ixgbe_dcb_configiPh : 40 -> 48
~ __Z24ixgbe_dcb_unpack_tsa_ceeP16ixgbe_dcb_configiPh : 44 -> 48
~ __Z24ixgbe_dcb_get_tc_from_upP16ixgbe_dcb_configih : 92 -> 84
~ __Z24ixgbe_dcb_unpack_map_ceeP16ixgbe_dcb_configiPh : 112 -> 104
~ __Z26ixgbe_dcb_check_config_ceeP16ixgbe_dcb_config : 356 -> 352
~ __Z31ixgbe_dcb_config_rx_arbiter_ceeP8ixgbe_hwP16ixgbe_dcb_config : 492 -> 472
~ __Z36ixgbe_dcb_config_tx_data_arbiter_ceeP8ixgbe_hwP16ixgbe_dcb_config : 484 -> 464
~ __Z24ixgbe_dcb_config_pfc_ceeP8ixgbe_hwP16ixgbe_dcb_config : 320 -> 296
~ __Z23ixgbe_dcb_hw_config_ceeP8ixgbe_hwP16ixgbe_dcb_config : 692 -> 668
~ __ZL17ixgbe_read_mbx_vfP8ixgbe_hwPjtt : 228 -> 236
~ __ZL18ixgbe_write_mbx_vfP8ixgbe_hwPjtt : 232 -> 240
~ __ZL17ixgbe_read_mbx_pfP8ixgbe_hwPjtt : 248 -> 264
~ __ZL18ixgbe_write_mbx_pfP8ixgbe_hwPjtt : 260 -> 276
~ __Z28ixgbe_dcb_get_tc_stats_82598P8ixgbe_hwP14ixgbe_hw_statsh : 356 -> 388
~ __Z29ixgbe_dcb_get_pfc_stats_82598P8ixgbe_hwP14ixgbe_hw_statsh : 248 -> 268
~ __Z38ixgbe_dcb_config_tx_desc_arbiter_82598P8ixgbe_hwPtS1_PhS2_ : 252 -> 240
~ __Z38ixgbe_dcb_config_tx_data_arbiter_82598P8ixgbe_hwPtS1_PhS2_ : 312 -> 300
~ __Z26ixgbe_dcb_config_pfc_82598P8ixgbe_hwh : 416 -> 424
```
