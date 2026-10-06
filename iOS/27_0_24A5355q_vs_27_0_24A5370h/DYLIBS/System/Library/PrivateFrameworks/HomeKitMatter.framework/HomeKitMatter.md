## HomeKitMatter

> `/System/Library/PrivateFrameworks/HomeKitMatter.framework/HomeKitMatter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18068c` | `0x186be8` | **`+0x655c`** |
| `__TEXT.__oslogstring` | `0x4f036` | `0x508b3` | **`+0x187d`** |
| `__AUTH_CONST.__objc_const` | `0xfbe0` | `0x10318` | **`+0x738`** |
| `__TEXT.__objc_methlist` | `0xa99c` | `0xadc4` | **`+0x428`** |
| `__DATA_CONST.__objc_selrefs` | `0x6fa8` | `0x71f0` | **`+0x248`** |
| `__TEXT.__unwind_info` | `0x3010` | `0x3178` | **`+0x168`** |
| `__AUTH.__objc_data` | `0x1db0` | `0x1ef0` | **`+0x140`** |
| `__AUTH_CONST.__cfstring` | `0x6f60` | `0x7060` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x48d0` | `0x49c8` | **`+0xf8`** |
| `__TEXT.__gcc_except_tab` | `0x3058` | `0x3150` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x7083` | `0x7103` | **`+0x80`** |
| `__DATA.__data` | `0xe40` | `0xea0` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0xb18` | `0xb78` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x1100` | `0x1140` | **`+0x40`** |
| `__DATA.__bss` | `0x4a8` | `0x4c8` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x438` | `0x458` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x2f8` | `0x318` | **`+0x20`** |
| `__TEXT.__const` | `0x278` | `0x298` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x9f0` | `0xa08` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x130` | `0x138` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x18` | **`+0x8`** |

### Other Changes

```diff

-1468.5.0.0.6
+1479.0.0.1.0

-  Functions: 4394
-  Symbols:   7224
-  CStrings:  5802
+  Functions: 4494
+  Symbols:   7395
+  CStrings:  5884
Symbols:
+ +[HMMTRBackgroundCommissionableNodeScanController logCategory]
+ +[HMMTRExclusiveServerActionQueue logCategory]
+ -[HMMTRAccessoryServer _attemptDeferredMatterCommissioning]
+ -[HMMTRAccessoryServer _discoveredDiscriminator:matchesOnboardingSetupPayload:]
+ -[HMMTRAccessoryServer _stopDeferredMatterCommissioning]
+ -[HMMTRAccessoryServer beginDeferredMatterCommissioningWithOnboardingURL:]
+ -[HMMTRAccessoryServer deferredMatterAttemptInFlight]
+ -[HMMTRAccessoryServer deferredMatterOnboardingURL]
+ -[HMMTRAccessoryServer exclusivePairingQueue]
+ -[HMMTRAccessoryServer handleDiscoveredCommissionableNodeDiscriminator:]
+ -[HMMTRAccessoryServer isUnpairedFromStorageWithCompletion:]
+ -[HMMTRAccessoryServer markNFCDeferredSetupNotNecessary]
+ -[HMMTRAccessoryServer nfcDeferredSetupNotNecessary]
+ -[HMMTRAccessoryServer performStartPairingWithRequest:]
+ -[HMMTRAccessoryServer setDeferredMatterAttemptInFlight:]
+ -[HMMTRAccessoryServer setDeferredMatterOnboardingURL:]
+ -[HMMTRAccessoryServer setExclusivePairingQueue:]
+ -[HMMTRAccessoryServer setNfcDeferredSetupNotNecessary:]
+ -[HMMTRAccessoryServerBrowser _addDiscoveredAccessoryServerWithNodeID:fabricUUID:deferredMatterOnboardingURL:]
+ -[HMMTRAccessoryServerBrowser _anyScanRequested]
+ -[HMMTRAccessoryServerBrowser _cleanupDisappearedBackgroundNodesOverBLE]
+ -[HMMTRAccessoryServerBrowser _discoveredAccessoryServersDidChange]
+ -[HMMTRAccessoryServerBrowser _dispatchHandleHomeAddedAccessoryWithNodeID:fabricUUID:localControl:deferredMatterOnboardingURL:]
+ -[HMMTRAccessoryServerBrowser _forgetPresentCommissionableNodeDiscriminatorsIfScanningStopped]
+ -[HMMTRAccessoryServerBrowser _keyForDiscriminator:vendorID:productID:]
+ -[HMMTRAccessoryServerBrowser _prepareBackgroundNodesForBLEDiscovery]
+ -[HMMTRAccessoryServerBrowser _recordBackgroundDiscoveredNodeWithDiscriminator:vendorID:productID:deviceName:overBLE:]
+ -[HMMTRAccessoryServerBrowser _replayPresentCommissionableNodeDiscriminatorsToServer:]
+ -[HMMTRAccessoryServerBrowser _server:isRemovedFromStorageWithCompletion:]
+ -[HMMTRAccessoryServerBrowser backgroundCommissionableNodeScanControllerStartScan:]
+ -[HMMTRAccessoryServerBrowser backgroundCommissionableNodeScanControllerStopScan:]
+ -[HMMTRAccessoryServerBrowser backgroundScanController]
+ -[HMMTRAccessoryServerBrowser exclusivePairingQueue]
+ -[HMMTRAccessoryServerBrowser handleHomeAddedAccessoryWithNodeID:fabricUUID:localControl:deferredMatterOnboardingURL:]
+ -[HMMTRAccessoryServerBrowser requestedBackgroundScan]
+ -[HMMTRAccessoryServerBrowser setRequestedBackgroundScan:]
+ -[HMMTRAccessoryServerBrowser startBackgroundCommissionableNodeScan]
+ -[HMMTRAccessoryServerBrowser stopBackgroundCommissionableNodeScan]
+ -[HMMTRBackgroundCommissionableNodeScanController .cxx_destruct]
+ -[HMMTRBackgroundCommissionableNodeScanController _evaluate]
+ -[HMMTRBackgroundCommissionableNodeScanController deferredPairingServerIdentifiers]
+ -[HMMTRBackgroundCommissionableNodeScanController delegate]
+ -[HMMTRBackgroundCommissionableNodeScanController handleUpdatedAccessoryServerDeferredPairingState:inDeferredPairingState:]
+ -[HMMTRBackgroundCommissionableNodeScanController handleUpdatedDiscoveredAccessoryServers:]
+ -[HMMTRBackgroundCommissionableNodeScanController initWithQueue:delegate:]
+ -[HMMTRBackgroundCommissionableNodeScanController queue]
+ -[HMMTRBackgroundCommissionableNodeScanController scanRequested]
+ -[HMMTRBackgroundCommissionableNodeScanController setScanRequested:]
+ -[HMMTRBackgroundDiscoveredNode .cxx_destruct]
+ -[HMMTRBackgroundDiscoveredNode blePending]
+ -[HMMTRBackgroundDiscoveredNode deviceName]
+ -[HMMTRBackgroundDiscoveredNode discriminator]
+ -[HMMTRBackgroundDiscoveredNode initWithDiscriminator:vendorID:productID:deviceName:overBLE:]
+ -[HMMTRBackgroundDiscoveredNode overBLE]
+ -[HMMTRBackgroundDiscoveredNode productID]
+ -[HMMTRBackgroundDiscoveredNode setBlePending:]
+ -[HMMTRBackgroundDiscoveredNode vendorID]
+ -[HMMTRExclusiveServerActionQueue .cxx_destruct]
+ -[HMMTRExclusiveServerActionQueue _cancelServer:]
+ -[HMMTRExclusiveServerActionQueue _enqueueAndDequeueServer:block:]
+ -[HMMTRExclusiveServerActionQueue _enqueueAtFrontAndDequeueServer:block:]
+ -[HMMTRExclusiveServerActionQueue _finishServer:]
+ -[HMMTRExclusiveServerActionQueue _popNextLiveEntryBlock]
+ -[HMMTRExclusiveServerActionQueue cancelServer:]
+ -[HMMTRExclusiveServerActionQueue currentServer]
+ -[HMMTRExclusiveServerActionQueue enqueueServer:block:]
+ -[HMMTRExclusiveServerActionQueue enqueueServerAtFront:block:]
+ -[HMMTRExclusiveServerActionQueue init]
+ -[HMMTRExclusiveServerActionQueue pendingEntries]
+ -[HMMTRExclusiveServerActionQueue queue]
+ -[HMMTRExclusiveServerActionQueue serverDidFinishAction:]
+ -[HMMTRExclusiveServerActionQueue setCurrentServer:]
+ -[HMMTRExclusiveServerActionQueueEntry .cxx_destruct]
+ -[HMMTRExclusiveServerActionQueueEntry block]
+ -[HMMTRExclusiveServerActionQueueEntry initWithServer:block:]
+ -[HMMTRExclusiveServerActionQueueEntry server]
+ GCC_except_table1061
+ GCC_except_table1065
+ GCC_except_table1067
+ GCC_except_table1191
+ GCC_except_table1251
+ GCC_except_table1297
+ GCC_except_table1305
+ GCC_except_table1354
+ GCC_except_table1362
+ GCC_except_table1399
+ GCC_except_table1436
+ GCC_except_table1465
+ GCC_except_table1700
+ GCC_except_table1853
+ GCC_except_table1854
+ GCC_except_table1857
+ GCC_except_table1877
+ GCC_except_table1878
+ GCC_except_table1879
+ GCC_except_table1880
+ GCC_except_table1881
+ GCC_except_table1884
+ GCC_except_table1887
+ GCC_except_table1888
+ GCC_except_table1889
+ GCC_except_table1890
+ GCC_except_table1891
+ GCC_except_table1892
+ GCC_except_table1893
+ GCC_except_table1952
+ GCC_except_table1958
+ GCC_except_table1996
+ GCC_except_table2079
+ GCC_except_table2192
+ GCC_except_table2194
+ GCC_except_table2224
+ GCC_except_table2232
+ GCC_except_table2234
+ GCC_except_table2283
+ GCC_except_table2320
+ GCC_except_table2343
+ GCC_except_table2408
+ GCC_except_table2684
+ GCC_except_table2686
+ GCC_except_table2692
+ GCC_except_table2750
+ GCC_except_table2791
+ GCC_except_table2833
+ GCC_except_table2835
+ GCC_except_table2866
+ GCC_except_table2867
+ GCC_except_table2891
+ GCC_except_table2892
+ GCC_except_table2893
+ GCC_except_table2894
+ GCC_except_table2895
+ GCC_except_table2896
+ GCC_except_table2897
+ GCC_except_table2907
+ GCC_except_table2909
+ GCC_except_table2920
+ GCC_except_table2939
+ GCC_except_table2955
+ GCC_except_table2961
+ GCC_except_table2974
+ GCC_except_table2981
+ GCC_except_table2996
+ GCC_except_table2999
+ GCC_except_table3003
+ GCC_except_table3005
+ GCC_except_table3030
+ GCC_except_table3037
+ GCC_except_table3042
+ GCC_except_table3054
+ GCC_except_table3105
+ GCC_except_table3106
+ GCC_except_table3491
+ GCC_except_table3516
+ GCC_except_table3517
+ GCC_except_table3518
+ GCC_except_table3522
+ GCC_except_table3527
+ GCC_except_table3530
+ GCC_except_table3546
+ GCC_except_table3631
+ GCC_except_table3639
+ GCC_except_table3641
+ GCC_except_table3648
+ GCC_except_table3649
+ GCC_except_table3678
+ GCC_except_table3685
+ GCC_except_table3717
+ GCC_except_table3720
+ GCC_except_table3728
+ GCC_except_table3748
+ GCC_except_table3751
+ GCC_except_table3789
+ GCC_except_table3791
+ GCC_except_table3793
+ GCC_except_table3810
+ GCC_except_table3812
+ GCC_except_table3830
+ GCC_except_table3907
+ GCC_except_table3954
+ GCC_except_table3972
+ GCC_except_table3995
+ GCC_except_table3999
+ GCC_except_table4014
+ GCC_except_table4015
+ GCC_except_table4016
+ GCC_except_table4022
+ GCC_except_table4029
+ GCC_except_table4034
+ GCC_except_table4089
+ GCC_except_table4111
+ GCC_except_table4154
+ GCC_except_table4159
+ GCC_except_table4162
+ GCC_except_table4246
+ GCC_except_table4247
+ GCC_except_table4303
+ GCC_except_table4306
+ GCC_except_table4368
+ GCC_except_table4430
+ GCC_except_table4434
+ GCC_except_table4438
+ GCC_except_table4441
+ GCC_except_table4474
+ GCC_except_table540
+ GCC_except_table542
+ GCC_except_table571
+ GCC_except_table575
+ GCC_except_table577
+ GCC_except_table579
+ GCC_except_table739
+ GCC_except_table740
+ GCC_except_table797
+ GCC_except_table798
+ GCC_except_table799
+ GCC_except_table874
+ GCC_except_table914
+ GCC_except_table977
+ GCC_except_table981
+ GCC_except_table983
+ GCC_except_table985
+ GCC_except_table987
+ GCC_except_table991
+ GCC_except_table995
+ GCC_except_table998
+ _OBJC_CLASS_$_HAPAccessoryPairingRequest
+ _OBJC_CLASS_$_HMMTRBackgroundCommissionableNodeScanController
+ _OBJC_CLASS_$_HMMTRBackgroundDiscoveredNode
+ _OBJC_CLASS_$_HMMTRExclusiveServerActionQueue
+ _OBJC_CLASS_$_HMMTRExclusiveServerActionQueueEntry
+ _OBJC_IVAR_$_HMMTRAccessoryServer._deferredMatterAttemptInFlight
+ _OBJC_IVAR_$_HMMTRAccessoryServer._deferredMatterOnboardingURL
+ _OBJC_IVAR_$_HMMTRAccessoryServer._exclusivePairingQueue
+ _OBJC_IVAR_$_HMMTRAccessoryServer._nfcDeferredSetupNotNecessary
+ _OBJC_IVAR_$_HMMTRAccessoryServerBrowser._backgroundDiscoveredNodes
+ _OBJC_IVAR_$_HMMTRAccessoryServerBrowser._backgroundScanController
+ _OBJC_IVAR_$_HMMTRAccessoryServerBrowser._exclusivePairingQueue
+ _OBJC_IVAR_$_HMMTRAccessoryServerBrowser._presentCommissionableNodeDiscriminators
+ _OBJC_IVAR_$_HMMTRAccessoryServerBrowser._requestedBackgroundScan
+ _OBJC_IVAR_$_HMMTRBackgroundCommissionableNodeScanController._deferredPairingServerIdentifiers
+ _OBJC_IVAR_$_HMMTRBackgroundCommissionableNodeScanController._delegate
+ _OBJC_IVAR_$_HMMTRBackgroundCommissionableNodeScanController._queue
+ _OBJC_IVAR_$_HMMTRBackgroundCommissionableNodeScanController._scanRequested
+ _OBJC_IVAR_$_HMMTRBackgroundDiscoveredNode._blePending
+ _OBJC_IVAR_$_HMMTRBackgroundDiscoveredNode._deviceName
+ _OBJC_IVAR_$_HMMTRBackgroundDiscoveredNode._discriminator
+ _OBJC_IVAR_$_HMMTRBackgroundDiscoveredNode._overBLE
+ _OBJC_IVAR_$_HMMTRBackgroundDiscoveredNode._productID
+ _OBJC_IVAR_$_HMMTRBackgroundDiscoveredNode._vendorID
+ _OBJC_IVAR_$_HMMTRExclusiveServerActionQueue._currentServer
+ _OBJC_IVAR_$_HMMTRExclusiveServerActionQueue._pendingEntries
+ _OBJC_IVAR_$_HMMTRExclusiveServerActionQueue._queue
+ _OBJC_IVAR_$_HMMTRExclusiveServerActionQueueEntry._block
+ _OBJC_IVAR_$_HMMTRExclusiveServerActionQueueEntry._server
+ _OBJC_METACLASS_$_HMMTRBackgroundCommissionableNodeScanController
+ _OBJC_METACLASS_$_HMMTRBackgroundDiscoveredNode
+ _OBJC_METACLASS_$_HMMTRExclusiveServerActionQueue
+ _OBJC_METACLASS_$_HMMTRExclusiveServerActionQueueEntry
+ __OBJC_$_CLASS_METHODS_HMMTRBackgroundCommissionableNodeScanController
+ __OBJC_$_CLASS_METHODS_HMMTRExclusiveServerActionQueue
+ __OBJC_$_INSTANCE_METHODS_HMMTRBackgroundCommissionableNodeScanController
+ __OBJC_$_INSTANCE_METHODS_HMMTRBackgroundDiscoveredNode
+ __OBJC_$_INSTANCE_METHODS_HMMTRExclusiveServerActionQueue
+ __OBJC_$_INSTANCE_METHODS_HMMTRExclusiveServerActionQueueEntry
+ __OBJC_$_INSTANCE_VARIABLES_HMMTRBackgroundCommissionableNodeScanController
+ __OBJC_$_INSTANCE_VARIABLES_HMMTRBackgroundDiscoveredNode
+ __OBJC_$_INSTANCE_VARIABLES_HMMTRExclusiveServerActionQueue
+ __OBJC_$_INSTANCE_VARIABLES_HMMTRExclusiveServerActionQueueEntry
+ __OBJC_$_PROP_LIST_HMMTRBackgroundCommissionableNodeScanController
+ __OBJC_$_PROP_LIST_HMMTRBackgroundDiscoveredNode
+ __OBJC_$_PROP_LIST_HMMTRExclusiveServerActionQueue
+ __OBJC_$_PROP_LIST_HMMTRExclusiveServerActionQueueEntry
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HMMTRBackgroundCommissionableNodeScanControllerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HMMTRBackgroundCommissionableNodeScanControllerDelegate
+ __OBJC_$_PROTOCOL_REFS_HMMTRBackgroundCommissionableNodeScanControllerDelegate
+ __OBJC_CLASS_RO_$_HMMTRBackgroundCommissionableNodeScanController
+ __OBJC_CLASS_RO_$_HMMTRBackgroundDiscoveredNode
+ __OBJC_CLASS_RO_$_HMMTRExclusiveServerActionQueue
+ __OBJC_CLASS_RO_$_HMMTRExclusiveServerActionQueueEntry
+ __OBJC_LABEL_PROTOCOL_$_HMMTRBackgroundCommissionableNodeScanControllerDelegate
+ __OBJC_METACLASS_RO_$_HMMTRBackgroundCommissionableNodeScanController
+ __OBJC_METACLASS_RO_$_HMMTRBackgroundDiscoveredNode
+ __OBJC_METACLASS_RO_$_HMMTRExclusiveServerActionQueue
+ __OBJC_METACLASS_RO_$_HMMTRExclusiveServerActionQueueEntry
+ __OBJC_PROTOCOL_$_HMMTRBackgroundCommissionableNodeScanControllerDelegate
+ __OBJC_PROTOCOL_REFERENCE_$_HAPAccessoryServerDelegate
+ ___123-[HMMTRBackgroundCommissionableNodeScanController handleUpdatedAccessoryServerDeferredPairingState:inDeferredPairingState:]_block_invoke
+ ___127-[HMMTRAccessoryServerBrowser _dispatchHandleHomeAddedAccessoryWithNodeID:fabricUUID:localControl:deferredMatterOnboardingURL:]_block_invoke
+ ___46+[HMMTRExclusiveServerActionQueue logCategory]_block_invoke
+ ___49-[HMMTRExclusiveServerActionQueue _cancelServer:]_block_invoke
+ ___49-[HMMTRExclusiveServerActionQueue _finishServer:]_block_invoke
+ ___55-[HMMTRAccessoryServer performStartPairingWithRequest:]_block_invoke
+ ___56-[HMMTRAccessoryServer markNFCDeferredSetupNotNecessary]_block_invoke
+ ___59-[HMMTRAccessoryServer _attemptDeferredMatterCommissioning]_block_invoke
+ ___60-[HMMTRAccessoryServer isUnpairedFromStorageWithCompletion:]_block_invoke
+ ___62+[HMMTRBackgroundCommissionableNodeScanController logCategory]_block_invoke
+ ___66-[HMMTRExclusiveServerActionQueue _enqueueAndDequeueServer:block:]_block_invoke
+ ___67-[HMMTRAccessoryServerBrowser stopBackgroundCommissionableNodeScan]_block_invoke
+ ___68-[HMMTRAccessoryServerBrowser startBackgroundCommissionableNodeScan]_block_invoke
+ ___72-[HMMTRAccessoryServer handleDiscoveredCommissionableNodeDiscriminator:]_block_invoke
+ ___73-[HMMTRAccessoryServerBrowser _updateLocallyDiscoveredServerPairedStates]_block_invoke
+ ___73-[HMMTRExclusiveServerActionQueue _enqueueAtFrontAndDequeueServer:block:]_block_invoke
+ ___74-[HMMTRAccessoryServer beginDeferredMatterCommissioningWithOnboardingURL:]_block_invoke
+ ___74-[HMMTRAccessoryServerBrowser _server:isRemovedFromStorageWithCompletion:]_block_invoke
+ ___74-[HMMTRAccessoryServerBrowser _server:isRemovedFromStorageWithCompletion:]_block_invoke_2
+ ___78-[HMMTRAccessoryServerBrowser _cleanupDiscoveredServersWithReason:completion:]_block_invoke_3
+ ___91-[HMMTRBackgroundCommissionableNodeScanController handleUpdatedDiscoveredAccessoryServers:]_block_invoke
+ ___block_descriptor_41_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32s40bs_e8_v12?0B8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e8_v12?0B8ls32l8s40l8
+ ___block_descriptor_49_e8_32s40w_e5_v8?0lw40l8s32l8
+ ___block_descriptor_64_e8_32s40s48s56s_e8_v12?0B8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_65_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56r64w_e29_v16?0"MTRDeviceController"8lw64l8s32l8r56l8s40l8s48l8
+ _logCategory._hmf_once_t1359
+ _logCategory._hmf_once_t491
+ _logCategory._hmf_once_t749
+ _logCategory._hmf_once_v1360
+ _logCategory._hmf_once_v492
+ _logCategory._hmf_once_v750
- GCC_except_table1020
- GCC_except_table1024
- GCC_except_table1026
- GCC_except_table1150
- GCC_except_table1210
- GCC_except_table1256
- GCC_except_table1264
- GCC_except_table1313
- GCC_except_table1321
- GCC_except_table1358
- GCC_except_table1395
- GCC_except_table1424
- GCC_except_table1618
- GCC_except_table1811
- GCC_except_table1812
- GCC_except_table1813
- GCC_except_table1816
- GCC_except_table1836
- GCC_except_table1837
- GCC_except_table1838
- GCC_except_table1839
- GCC_except_table1840
- GCC_except_table1843
- GCC_except_table1846
- GCC_except_table1847
- GCC_except_table1848
- GCC_except_table1849
- GCC_except_table1850
- GCC_except_table1851
- GCC_except_table1911
- GCC_except_table1917
- GCC_except_table1955
- GCC_except_table2038
- GCC_except_table2151
- GCC_except_table2153
- GCC_except_table2183
- GCC_except_table2191
- GCC_except_table2193
- GCC_except_table2242
- GCC_except_table2279
- GCC_except_table2302
- GCC_except_table2367
- GCC_except_table2627
- GCC_except_table2631
- GCC_except_table2729
- GCC_except_table2770
- GCC_except_table2772
- GCC_except_table2797
- GCC_except_table2798
- GCC_except_table2799
- GCC_except_table2821
- GCC_except_table2822
- GCC_except_table2823
- GCC_except_table2824
- GCC_except_table2825
- GCC_except_table2826
- GCC_except_table2827
- GCC_except_table2828
- GCC_except_table2838
- GCC_except_table2840
- GCC_except_table2851
- GCC_except_table2884
- GCC_except_table2903
- GCC_except_table2906
- GCC_except_table2910
- GCC_except_table2925
- GCC_except_table2928
- GCC_except_table2932
- GCC_except_table2934
- GCC_except_table2953
- GCC_except_table2960
- GCC_except_table2965
- GCC_except_table3028
- GCC_except_table3029
- GCC_except_table3406
- GCC_except_table3429
- GCC_except_table3430
- GCC_except_table3431
- GCC_except_table3435
- GCC_except_table3440
- GCC_except_table3443
- GCC_except_table3459
- GCC_except_table3474
- GCC_except_table3544
- GCC_except_table3552
- GCC_except_table3554
- GCC_except_table3562
- GCC_except_table3591
- GCC_except_table3622
- GCC_except_table3625
- GCC_except_table3633
- GCC_except_table3652
- GCC_except_table3655
- GCC_except_table3693
- GCC_except_table3695
- GCC_except_table3697
- GCC_except_table3714
- GCC_except_table3716
- GCC_except_table3734
- GCC_except_table3811
- GCC_except_table3858
- GCC_except_table3876
- GCC_except_table3899
- GCC_except_table3903
- GCC_except_table3918
- GCC_except_table3919
- GCC_except_table3920
- GCC_except_table3926
- GCC_except_table3933
- GCC_except_table3991
- GCC_except_table4011
- GCC_except_table4054
- GCC_except_table4059
- GCC_except_table4062
- GCC_except_table4146
- GCC_except_table4147
- GCC_except_table4203
- GCC_except_table4206
- GCC_except_table4268
- GCC_except_table4330
- GCC_except_table4334
- GCC_except_table4338
- GCC_except_table4341
- GCC_except_table4374
- GCC_except_table698
- GCC_except_table699
- GCC_except_table756
- GCC_except_table757
- GCC_except_table758
- GCC_except_table833
- GCC_except_table873
- GCC_except_table936
- GCC_except_table940
- GCC_except_table942
- GCC_except_table944
- GCC_except_table946
- GCC_except_table950
- GCC_except_table954
- GCC_except_table957
- ___74-[HMMTRSyncClusterDoorLock addOrUpdatePinCodeWithValue:forUserIndex:flow:]_block_invoke_3
- ___74-[HMMTRSyncClusterDoorLock addOrUpdatePinCodeWithValue:forUserIndex:flow:]_block_invoke_4
- ___90-[HMMTRAccessoryServerBrowser handleHomeAddedAccessoryWithNodeID:fabricUUID:localControl:]_block_invoke
- ___block_descriptor_64_e8_32s40s48r56w_e29_v16?0"MTRDeviceController"8lw56l8s32l8r48l8s40l8
- _logCategory._hmf_once_t1329
- _logCategory._hmf_once_t483
- _logCategory._hmf_once_t730
- _logCategory._hmf_once_v1330
- _logCategory._hmf_once_v484
- _logCategory._hmf_once_v731
CStrings:
+ "%@-%@-%@"
+ "Accessory for nodeID %@ is not user configuration ready; skipping"
+ "Accessory server already exists for node %@, fabric %@; skipping creation (matter onboarding %@)"
+ "Accessory with node ID %@ was added to home with fabric %@, for local control: %@ with Matter onboarding payload: %{private}@"
+ "AccessoryRequest"
+ "Adding server with deferred onboarding URL for nodeID %@"
+ "Attempting deferred Matter commissioning"
+ "BDX transfer failed for accessory %@, error = %@"
+ "Cancelling holder server %{public}@ (pending=%lu)"
+ "Cannot parse deferred Matter onboarding payload %{public}@: %{public}@"
+ "Deferred Matter commissioning attempt already in flight; ignoring"
+ "Deferred Matter commissioning attempt failed; will retry on the next matching discovery"
+ "Discovered commissionable node matches deferred Matter onboarding discriminator %@; attempting commissioning"
+ "Failed to update vendorID to %{public}@ and productID to %{public}@ after deferred Matter commissioning with error domain: %{public}@ code: %ld"
+ "Invalidating server %@ because it is disabled(%d) or was removed from storage(%d)"
+ "Marking NFC deferred setup as not necessary"
+ "NFC deferred setup not necessary (accessory completed via prox-pairing path); skipping without invoking completion"
+ "No delegate/queue to attach for deferred-onboarding node %@; system commissioner pairing will not run"
+ "Notifying deferred Matter paired accessory server and persisting server data"
+ "Pruned deferred pairing targets to discovered set (%lu -> %lu)"
+ "Removed %lu pending entries for server %{public}@ (pending=%lu)"
+ "Requesting background commissionable node scan start"
+ "Requesting background commissionable node scan stop"
+ "Server %{public}@ acquired slot from FIFO (pending=%lu)"
+ "Server %{public}@ acquired slot immediately (pending=%lu)"
+ "Server %{public}@ called serverDidFinishAction: while not holding slot (current=%{public}@); ignoring"
+ "Server %{public}@ deferred pairing state -> %d (targets=%lu)"
+ "Server %{public}@ enqueued at front behind holder %{public}@ (pending=%lu)"
+ "Server %{public}@ enqueued behind %{public}@ (pending=%lu)"
+ "Server %{public}@ released slot (pending=%lu)"
+ "Skipping deferred Matter commissioning attempt: already completed"
+ "Skipping pending entry whose server was deallocated (pending=%lu)"
+ "Starting background commissionable node scan"
+ "Stopping background commissionable node scan"
+ "Stored deferred Matter onboarding URL %{private}@; awaiting commissionable-node discovery"
+ "Successfully updated vendorID to %{public}@ and productID to %{public}@ after deferred Matter commissioning"
+ "Unable to create server for deferred Matter onboarding of node %@"
+ "Vendor ID %{public}@ and product ID %{public}@ not updated after deferred Matter commissioning because both are not available"
+ "[%{public}@] Accessory for nodeID %@ is not user configuration ready; skipping"
+ "[%{public}@] Accessory server already exists for node %@, fabric %@; skipping creation (matter onboarding %@)"
+ "[%{public}@] Accessory with node ID %@ was added to home with fabric %@, for local control: %@ with Matter onboarding payload: %{private}@"
+ "[%{public}@] Adding server with deferred onboarding URL for nodeID %@"
+ "[%{public}@] Attempting deferred Matter commissioning"
+ "[%{public}@] BDX transfer failed for accessory %@, error = %@"
+ "[%{public}@] Cancelling holder server %{public}@ (pending=%lu)"
+ "[%{public}@] Cannot parse deferred Matter onboarding payload %{public}@: %{public}@"
+ "[%{public}@] Deferred Matter commissioning attempt already in flight; ignoring"
+ "[%{public}@] Deferred Matter commissioning attempt failed; will retry on the next matching discovery"
+ "[%{public}@] Discovered commissionable node matches deferred Matter onboarding discriminator %@; attempting commissioning"
+ "[%{public}@] Failed to update vendorID to %{public}@ and productID to %{public}@ after deferred Matter commissioning with error domain: %{public}@ code: %ld"
+ "[%{public}@] Invalidating server %@ because it is disabled(%d) or was removed from storage(%d)"
+ "[%{public}@] Marking NFC deferred setup as not necessary"
+ "[%{public}@] NFC deferred setup not necessary (accessory completed via prox-pairing path); skipping without invoking completion"
+ "[%{public}@] No delegate/queue to attach for deferred-onboarding node %@; system commissioner pairing will not run"
+ "[%{public}@] Notifying deferred Matter paired accessory server and persisting server data"
+ "[%{public}@] Pruned deferred pairing targets to discovered set (%lu -> %lu)"
+ "[%{public}@] Removed %lu pending entries for server %{public}@ (pending=%lu)"
+ "[%{public}@] Requesting background commissionable node scan start"
+ "[%{public}@] Requesting background commissionable node scan stop"
+ "[%{public}@] Server %{public}@ acquired slot from FIFO (pending=%lu)"
+ "[%{public}@] Server %{public}@ acquired slot immediately (pending=%lu)"
+ "[%{public}@] Server %{public}@ called serverDidFinishAction: while not holding slot (current=%{public}@); ignoring"
+ "[%{public}@] Server %{public}@ deferred pairing state -> %d (targets=%lu)"
+ "[%{public}@] Server %{public}@ enqueued at front behind holder %{public}@ (pending=%lu)"
+ "[%{public}@] Server %{public}@ enqueued behind %{public}@ (pending=%lu)"
+ "[%{public}@] Server %{public}@ released slot (pending=%lu)"
+ "[%{public}@] Skipping deferred Matter commissioning attempt: already completed"
+ "[%{public}@] Skipping pending entry whose server was deallocated (pending=%lu)"
+ "[%{public}@] Starting background commissionable node scan"
+ "[%{public}@] Stopping background commissionable node scan"
+ "[%{public}@] Stored deferred Matter onboarding URL %{private}@; awaiting commissionable-node discovery"
+ "[%{public}@] Successfully updated vendorID to %{public}@ and productID to %{public}@ after deferred Matter commissioning"
+ "[%{public}@] Unable to create server for deferred Matter onboarding of node %@"
+ "[%{public}@] Vendor ID %{public}@ and product ID %{public}@ not updated after deferred Matter commissioning because both are not available"
+ "[%{public}@] [Flow: %@] Checking if user is at credentials-per-user cap: user.credentials.count = %lu, numberOfCredentialsPerUser = %@"
+ "[%{public}@] [Flow: %@] Checking if user is at credentials-per-user cap: userResponse.credentials.count = %lu, numberOfCredentialsPerUser = %@"
+ "[%{public}@] [Flow: %@] Credentials per user limit reached, and no evictable credentials to remove"
+ "[%{public}@] [Flow: %@] Failure to remove all abandoned users with error: %@"
+ "[%{public}@] [Flow: %@] numberOfCredentialsSupportedPerUser: %@"
+ "[%{public}@] beginDeferredMatterCommissioningWithOnboardingURL called twice; ignoring duplicate URL %{private}@"
+ "[%{public}@] fetchClusterRevisionForDevice: For endpoint %@ of node %@, cluster %@, retrieved the revision number %@"
+ "[Flow: %@] Checking if user is at credentials-per-user cap: user.credentials.count = %lu, numberOfCredentialsPerUser = %@"
+ "[Flow: %@] Checking if user is at credentials-per-user cap: userResponse.credentials.count = %lu, numberOfCredentialsPerUser = %@"
+ "[Flow: %@] Credentials per user limit reached, and no evictable credentials to remove"
+ "[Flow: %@] Failure to remove all abandoned users with error: %@"
+ "[Flow: %@] numberOfCredentialsSupportedPerUser: %@"
+ "beginDeferredMatterCommissioningWithOnboardingURL called twice; ignoring duplicate URL %{private}@"
+ "block"
+ "deferredMatterOnboardingURL"
+ "delegate"
+ "fetchClusterRevisionForDevice: For endpoint %@ of node %@, cluster %@, retrieved the revision number %@"
+ "hmmtr.bg.scan.controller"
+ "hmmtr.exclusiveserveractionqueue"
+ "queue"
+ "server"
+ "\xb1\x81\x91"
+ "\xf0\xd2\xf0\xf0\xf01с"
- "AccesoryRequest"
- "Accessory with node ID %@ was added to home with fabric %@, for local control: %@"
- "BDX transfer failed for accessory %@, error = %@}"
- "Invalidating server because it is disabled(%d) or was removed from storage(%d). Server:%@"
- "No paired accessory found for nodeID %@ for accessory %@"
- "[%{public}@] Accessory with node ID %@ was added to home with fabric %@, for local control: %@"
- "[%{public}@] BDX transfer failed for accessory %@, error = %@}"
- "[%{public}@] Invalidating server because it is disabled(%d) or was removed from storage(%d). Server:%@"
- "[%{public}@] No paired accessory found for nodeID %@ for accessory %@"
- "[%{public}@] [Flow: %@] Failure to remove all abandonded users with error: %@"
- "[%{public}@] fetchClusterRevisionForDevice: For endpoint %@ of node %@, cluster %@, retrieved the revison number %@"
- "[Flow: %@] Failure to remove all abandonded users with error: %@"
- "fetchClusterRevisionForDevice: For endpoint %@ of node %@, cluster %@, retrieved the revison number %@"
- "\x91\x81\x91"
- "\xf0\xd2\xf0\xf0\xf0!\xd1"
```
