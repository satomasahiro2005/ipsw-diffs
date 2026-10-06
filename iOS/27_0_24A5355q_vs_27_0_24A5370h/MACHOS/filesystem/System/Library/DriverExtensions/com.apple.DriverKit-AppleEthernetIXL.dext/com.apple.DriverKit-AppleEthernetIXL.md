## com.apple.DriverKit-AppleEthernetIXL

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleEthernetIXL.dext/com.apple.DriverKit-AppleEthernetIXL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b018` | `0x1b188` | **`+0x170`** |

### Same-size Content Changes

- `__DATA_CONST.__const`

### Other Changes

```diff

-161.0.0.0.0
+168.0.0.0.0
Functions:
~ __ZN3ixl11ixl_pf_qmgr12get_num_freeEv : 52 -> 64
~ __ZN3ixl11ixl_pf_qmgr26find_free_contiguous_blockEi : 100 -> 104
~ __ZN3ixl11ixl_pf_qmgr7releaseEPNS_11ixl_pf_qtagE : 176 -> 172
~ __ZN3ixl11ixl_pf_qmgr14get_first_freeEt : 84 -> 76
~ __ZN3ixl11ixl_pf_qmgr18mark_queue_enabledEPNS_11ixl_pf_qtagEtb : 112 -> 120
~ __ZN3ixl11ixl_pf_qmgr19mark_queue_disabledEPNS_11ixl_pf_qtagEtb : 108 -> 112
~ __ZN3ixl11ixl_pf_qmgr21mark_queue_configuredEPNS_11ixl_pf_qtagEtb : 112 -> 120
~ __ZN3ixl11ixl_pf_qmgr17clear_queue_flagsEPNS_11ixl_pf_qtagE : 112 -> 108
~ __ZNK38DriverKit_AppleEthernetIXL_NetIf_IVars8txSubmitEj : 1180 -> 1192
~ __ZZN26DriverKit_AppleEthernetIXL10Start_ImplEP9IOServiceEN3$_08__invokeEv : 356 -> 348
~ __ZN32DriverKit_AppleEthernetIXL_IVars5probeEP11IOPCIDevice : 712 -> 728
~ __ZN38DriverKit_AppleEthernetIXL_NetIf_IVars2upEv : 2304 -> 2328
~ __ZN38DriverKit_AppleEthernetIXL_NetIf_IVars14add_hw_filtersEPN3ixl12ixl_ftl_headEi : 1344 -> 1340
~ __ZN38DriverKit_AppleEthernetIXL_NetIf_IVars14del_hw_filtersEPN3ixl12ixl_ftl_headEi : 1264 -> 1268
~ __Z26i40e_delete_lan_hmc_objectP7i40e_hwP28i40e_hmc_lan_delete_obj_info : 864 -> 856
~ __ZL22i40e_hmc_get_object_vaP7i40e_hwPPh22i40e_hmc_lan_rsrc_typej : 340 -> 344
~ __ZL20i40e_get_hmc_contextPhP16i40e_context_eleS_ : 292 -> 300
~ __ZL20i40e_set_hmc_contextPhP16i40e_context_eleS_ : 340 -> 348
~ __Z23i40e_lldp_to_dcb_configPhP16i40e_dcbx_config : 1168 -> 1216
~ __Z19i40e_get_dcb_configP7i40e_hw : 748 -> 772
~ __Z23i40e_dcb_config_to_lldpPhPtP16i40e_dcbx_config : 708 -> 756
~ __ZN32DriverKit_AppleEthernetIXL_IVars16otherIntrHandlerEv : 1408 -> 1404
~ __Z13i40e_init_asqP7i40e_hw : 340 -> 336
~ __ZL18i40e_free_asq_bufsP7i40e_hw : 148 -> 136
~ __Z13i40e_init_arqP7i40e_hw : 432 -> 408
~ __Z17i40e_shutdown_arqP7i40e_hw : 280 -> 268
~ __ZNK38DriverKit_AppleEthernetIXL_NetIf_IVars6rxSyncEj : 704 -> 708
~ __Z13i40e_debug_aqP7i40e_hw15i40e_debug_maskPvS2_t : 764 -> 852
~ __Z20i40e_read_pba_stringP7i40e_hwPhj : 552 -> 544
~ __Z27i40e_aq_send_driver_versionP7i40e_hwP19i40e_driver_versionP20i40e_asq_cmd_details : 164 -> 160
~ __Z19i40e_aq_add_macvlanP7i40e_hwtP33i40e_aqc_add_macvlan_element_datatP20i40e_asq_cmd_details : 208 -> 212
~ __Z25i40e_aq_add_cloud_filtersP7i40e_hwtP35i40e_aqc_cloud_filters_element_datah : 176 -> 180
~ __Z28i40e_aq_add_cloud_filters_bbP7i40e_hwtP33i40e_aqc_cloud_filters_element_bbh : 184 -> 188
~ __Z25i40e_aq_rem_cloud_filtersP7i40e_hwtP35i40e_aqc_cloud_filters_element_datah : 176 -> 180
~ __Z28i40e_aq_rem_cloud_filters_bbP7i40e_hwtP33i40e_aqc_cloud_filters_element_bbh : 184 -> 188
~ __ZL26i40e_read_nvm_buffer_srctlP7i40e_hwtPtS1_ : 188 -> 184
~ __ZN38DriverKit_AppleEthernetIXL_NetIf_IVars13allocateRingsEv : 140 -> 164
~ __ZN38DriverKit_AppleEthernetIXL_NetIf_IVars9freeRingsEv : 344 -> 380
~ __ZN38DriverKit_AppleEthernetIXL_NetIf_IVars14startInterfaceEj : 908 -> 928
~ __ZN38DriverKit_AppleEthernetIXL_NetIf_IVars6enableEv : 228 -> 264
~ __ZN38DriverKit_AppleEthernetIXL_NetIf_IVars7disableEv : 208 -> 224
```
