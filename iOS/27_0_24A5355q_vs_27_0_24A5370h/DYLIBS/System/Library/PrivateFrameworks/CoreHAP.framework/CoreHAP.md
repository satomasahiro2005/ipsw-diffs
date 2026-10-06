## CoreHAP

> `/System/Library/PrivateFrameworks/CoreHAP.framework/CoreHAP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27f5fc` | `0x291238` | **`+0x11c3c`** |
| `__TEXT.__oslogstring` | `0x41369` | `0x434f1` | **`+0x2188`** |
| `__AUTH_CONST.__objc_const` | `0x2a728` | `0x2aae0` | **`+0x3b8`** |
| `__AUTH_CONST.__const` | `0xf08` | `0x1298` | **`+0x390`** |
| `__DATA.__bss` | `0xc20` | `0xf20` | **`+0x300`** |
| `__TEXT.__objc_methlist` | `0x184f0` | `0x187d0` | **`+0x2e0`** |
| `__TEXT.__unwind_info` | `0x72f0` | `0x7580` | **`+0x290`** |
| `__AUTH.__objc_data` | `0x6f88` | `0x71c8` | **`+0x240`** |
| `__TEXT.__constg_swiftt` | `0x6b0` | `0x8c8` | **`+0x218`** |
| `__TEXT.__const` | `0x1010` | `0x1220` | **`+0x210`** |
| `__DATA_CONST.__const` | `0x5720` | `0x5900` | **`+0x1e0`** |
| `__AUTH_CONST.__cfstring` | `0xfe00` | `0xffc0` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x14168` | `0x14327` | **`+0x1bf`** |
| `__TEXT.__swift5_reflstr` | `0x263` | `0x404` | **`+0x1a1`** |
| `__DATA_CONST.__objc_selrefs` | `0x7ef0` | `0x8070` | **`+0x180`** |
| `__TEXT.__swift5_fieldmd` | `0x2a4` | `0x3c0` | **`+0x11c`** |
| `__TEXT.__eh_frame` | `0xc20` | `0xd38` | **`+0x118`** |
| `__DATA.__data` | `0x2c68` | `0x2d42` | **`+0xda`** |
| `__TEXT.__swift5_capture` | `0x134` | `0x204` | **`+0xd0`** |
| `__AUTH_CONST.__auth_got` | `0x1210` | `0x12d8` | **`+0xc8`** |
| `__TEXT.__gcc_except_tab` | `0x5dac` | `0x5e50` | **`+0xa4`** |
| `__TEXT.__swift5_typeref` | `0x2f6` | `0x38e` | **`+0x98`** |
| `__DATA_CONST.__got` | `0xf68` | `0xfc0` | **`+0x58`** |
| `__DATA.__objc_ivar` | `0x18a4` | `0x18c4` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xd8` | `0xc0` | **`-0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x720` | `0x738` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0xa8` | `0xc0` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x38` | `0x50` | **`+0x18`** |
| `__DATA.__common` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x208` | `0x200` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x28` | `0x30` | **`+0x8`** |

### Other Changes

```diff

-1468.5.0.0.6
+1479.0.0.1.0

+  - /usr/lib/libdns_services.dylib

-  Functions: 9460
-  Symbols:   16214
-  CStrings:  6912
+  Functions: 9663
+  Symbols:   16340
+  CStrings:  7055
Symbols:
+ -[HAP2AccessoryServer _setNextMergeAccessory:]
+ -[HAP2AccessoryServer _takeNextMergeAccessory]
+ -[HAP2AccessoryServer(Unpaired) pairingDriver:requestPairVerifyTLKWithCompletion:]
+ -[HAP2AccessoryServerController secureTransport:needsPairVerifyTLKsWithCompletion:]
+ -[HAP2AccessoryServerSecureTransportPairVerify _attemptIPIterationOrFailWithError:failureCloseHandler:]
+ -[HAP2AccessoryServerSecureTransportPairVerify _claimStateChangeCompletion]
+ -[HAP2AccessoryServerSecureTransportPairVerify _setStateChangeCompletion:]
+ -[HAP2AccessoryServerTransportCoAP addressList]
+ -[HAPAccessoryServerBrowser pairSetupSession:pairSetupType:features:pairVerifyTLK:error:]
+ -[HAPAccessoryServerBrowserNFC _notifyDelegateOfDiscoveryFailureWithError:]
+ -[HAPAccessoryServerHAP2Adapter accessoryServer:requestPairVerifyTLKWithCompletion:]
+ -[HAPAccessoryServerIP _ensurePairingSessionIsInitializedWithType:completion:]
+ -[HAPAccessoryServerIP hasAdvertisement]
+ -[HAPAccessoryServerNFC _logPairingStepTiming:]
+ -[HAPAccessoryServerNFC _logPairingTotalTimeWithStatus:]
+ -[HAPAccessoryServerNFC apduTxMode]
+ -[HAPAccessoryServerNFC isCommissionedOverNFCWithoutPower]
+ -[HAPAccessoryServerNFC nfcLastStepTime]
+ -[HAPAccessoryServerNFC nfcM1SendTime]
+ -[HAPAccessoryServerNFC nfcPairingStartTime]
+ -[HAPAccessoryServerNFC pairSetupSession:confirmMFiTokenWithUUID:newToken:]
+ -[HAPAccessoryServerNFC pairSetupSession:validateAndRollMFiTokenWithUUID:token:completionHandler:]
+ -[HAPAccessoryServerNFC prefetchedMFiTokenUUID]
+ -[HAPAccessoryServerNFC prefetchedMFiToken]
+ -[HAPAccessoryServerNFC providePrefetchedMFiTokenWithToken:uuidData:]
+ -[HAPAccessoryServerNFC refreshHAPWithCompletion:]
+ -[HAPAccessoryServerNFC setApduTxMode:]
+ -[HAPAccessoryServerNFC setIsCommissionedOverNFCWithoutPower:]
+ -[HAPAccessoryServerNFC setNfcLastStepTime:]
+ -[HAPAccessoryServerNFC setNfcM1SendTime:]
+ -[HAPAccessoryServerNFC setNfcPairingStartTime:]
+ -[HAPAccessoryServerNFC setPrefetchedMFiToken:]
+ -[HAPAccessoryServerNFC setPrefetchedMFiTokenUUID:]
+ -[HAPSystemKeychainStore deleteDeferredMatterOnboardingPayloadForAccessoryUUID:error:]
+ -[HAPSystemKeychainStore readDeferredMatterOnboardingPayloadForAccessoryUUID:error:]
+ -[HAPSystemKeychainStore saveDeferredMatterOnboardingPayload:forAccessoryUUID:error:]
+ -[_HAPAccessoryServerBTLE200 _mapPairingBootstrapCharacteristicsToGATT]
+ -[_HAPAccessoryServerBTLE200 _obtainPairVerifyTLKWithCompletion:]
+ GCC_except_table1032
+ GCC_except_table1034
+ GCC_except_table1140
+ GCC_except_table1145
+ GCC_except_table1160
+ GCC_except_table1172
+ GCC_except_table1174
+ GCC_except_table1176
+ GCC_except_table1178
+ GCC_except_table1304
+ GCC_except_table1308
+ GCC_except_table1310
+ GCC_except_table1527
+ GCC_except_table1744
+ GCC_except_table1750
+ GCC_except_table1752
+ GCC_except_table1758
+ GCC_except_table1760
+ GCC_except_table1764
+ GCC_except_table1768
+ GCC_except_table1770
+ GCC_except_table1772
+ GCC_except_table1774
+ GCC_except_table1779
+ GCC_except_table1783
+ GCC_except_table1793
+ GCC_except_table1801
+ GCC_except_table1808
+ GCC_except_table1812
+ GCC_except_table1816
+ GCC_except_table1820
+ GCC_except_table1858
+ GCC_except_table1977
+ GCC_except_table1982
+ GCC_except_table1984
+ GCC_except_table1986
+ GCC_except_table1998
+ GCC_except_table2003
+ GCC_except_table2007
+ GCC_except_table2010
+ GCC_except_table2015
+ GCC_except_table2032
+ GCC_except_table2042
+ GCC_except_table2051
+ GCC_except_table2057
+ GCC_except_table2066
+ GCC_except_table2069
+ GCC_except_table2074
+ GCC_except_table2076
+ GCC_except_table2080
+ GCC_except_table2084
+ GCC_except_table2092
+ GCC_except_table2103
+ GCC_except_table2141
+ GCC_except_table2160
+ GCC_except_table2161
+ GCC_except_table2164
+ GCC_except_table2165
+ GCC_except_table2167
+ GCC_except_table2168
+ GCC_except_table2190
+ GCC_except_table2194
+ GCC_except_table2202
+ GCC_except_table2375
+ GCC_except_table2379
+ GCC_except_table2383
+ GCC_except_table2387
+ GCC_except_table2390
+ GCC_except_table2392
+ GCC_except_table2394
+ GCC_except_table2397
+ GCC_except_table2403
+ GCC_except_table2405
+ GCC_except_table2408
+ GCC_except_table2409
+ GCC_except_table2411
+ GCC_except_table2505
+ GCC_except_table2513
+ GCC_except_table2514
+ GCC_except_table2515
+ GCC_except_table2516
+ GCC_except_table2517
+ GCC_except_table2518
+ GCC_except_table2533
+ GCC_except_table2547
+ GCC_except_table2627
+ GCC_except_table2639
+ GCC_except_table2665
+ GCC_except_table2673
+ GCC_except_table2684
+ GCC_except_table2698
+ GCC_except_table2701
+ GCC_except_table2706
+ GCC_except_table2714
+ GCC_except_table2720
+ GCC_except_table2722
+ GCC_except_table2916
+ GCC_except_table2925
+ GCC_except_table2942
+ GCC_except_table2976
+ GCC_except_table2992
+ GCC_except_table2994
+ GCC_except_table3013
+ GCC_except_table3035
+ GCC_except_table3049
+ GCC_except_table3050
+ GCC_except_table3051
+ GCC_except_table3054
+ GCC_except_table3060
+ GCC_except_table3067
+ GCC_except_table3070
+ GCC_except_table3075
+ GCC_except_table3080
+ GCC_except_table3085
+ GCC_except_table3124
+ GCC_except_table3141
+ GCC_except_table3144
+ GCC_except_table3149
+ GCC_except_table3151
+ GCC_except_table3167
+ GCC_except_table3181
+ GCC_except_table3183
+ GCC_except_table3187
+ GCC_except_table3195
+ GCC_except_table3203
+ GCC_except_table3267
+ GCC_except_table3274
+ GCC_except_table3276
+ GCC_except_table3277
+ GCC_except_table3300
+ GCC_except_table3320
+ GCC_except_table3548
+ GCC_except_table3616
+ GCC_except_table3626
+ GCC_except_table3629
+ GCC_except_table3638
+ GCC_except_table3648
+ GCC_except_table3651
+ GCC_except_table3662
+ GCC_except_table3663
+ GCC_except_table3665
+ GCC_except_table3667
+ GCC_except_table3670
+ GCC_except_table3673
+ GCC_except_table3675
+ GCC_except_table3678
+ GCC_except_table3681
+ GCC_except_table3693
+ GCC_except_table3695
+ GCC_except_table3699
+ GCC_except_table3703
+ GCC_except_table3707
+ GCC_except_table3733
+ GCC_except_table3751
+ GCC_except_table3755
+ GCC_except_table3758
+ GCC_except_table3760
+ GCC_except_table3762
+ GCC_except_table3769
+ GCC_except_table3770
+ GCC_except_table3771
+ GCC_except_table3852
+ GCC_except_table3853
+ GCC_except_table3855
+ GCC_except_table3856
+ GCC_except_table3857
+ GCC_except_table3858
+ GCC_except_table3859
+ GCC_except_table3860
+ GCC_except_table3861
+ GCC_except_table3862
+ GCC_except_table3863
+ GCC_except_table3864
+ GCC_except_table3865
+ GCC_except_table3904
+ GCC_except_table3931
+ GCC_except_table4041
+ GCC_except_table4048
+ GCC_except_table4090
+ GCC_except_table4094
+ GCC_except_table4097
+ GCC_except_table4103
+ GCC_except_table4112
+ GCC_except_table4115
+ GCC_except_table4118
+ GCC_except_table4123
+ GCC_except_table4136
+ GCC_except_table4141
+ GCC_except_table4145
+ GCC_except_table4147
+ GCC_except_table4150
+ GCC_except_table4173
+ GCC_except_table4179
+ GCC_except_table4183
+ GCC_except_table4184
+ GCC_except_table4204
+ GCC_except_table4206
+ GCC_except_table4207
+ GCC_except_table4210
+ GCC_except_table4216
+ GCC_except_table4219
+ GCC_except_table4221
+ GCC_except_table4227
+ GCC_except_table4229
+ GCC_except_table4232
+ GCC_except_table4243
+ GCC_except_table4254
+ GCC_except_table4256
+ GCC_except_table4265
+ GCC_except_table4267
+ GCC_except_table4269
+ GCC_except_table4275
+ GCC_except_table4535
+ GCC_except_table4541
+ GCC_except_table4558
+ GCC_except_table4562
+ GCC_except_table4579
+ GCC_except_table4585
+ GCC_except_table4598
+ GCC_except_table4612
+ GCC_except_table4616
+ GCC_except_table4729
+ GCC_except_table5183
+ GCC_except_table5191
+ GCC_except_table5201
+ GCC_except_table5243
+ GCC_except_table5246
+ GCC_except_table5247
+ GCC_except_table5248
+ GCC_except_table5249
+ GCC_except_table5383
+ GCC_except_table5384
+ GCC_except_table5386
+ GCC_except_table5387
+ GCC_except_table5388
+ GCC_except_table5394
+ GCC_except_table5395
+ GCC_except_table5397
+ GCC_except_table5404
+ GCC_except_table5407
+ GCC_except_table5409
+ GCC_except_table5414
+ GCC_except_table5417
+ GCC_except_table5420
+ GCC_except_table5424
+ GCC_except_table5428
+ GCC_except_table5914
+ GCC_except_table5915
+ GCC_except_table5934
+ GCC_except_table5944
+ GCC_except_table5947
+ GCC_except_table5952
+ GCC_except_table5955
+ GCC_except_table5959
+ GCC_except_table599
+ GCC_except_table606
+ GCC_except_table609
+ GCC_except_table6228
+ GCC_except_table6232
+ GCC_except_table6277
+ GCC_except_table6281
+ GCC_except_table6283
+ GCC_except_table6285
+ GCC_except_table643
+ GCC_except_table6477
+ GCC_except_table6483
+ GCC_except_table6487
+ GCC_except_table6488
+ GCC_except_table6489
+ GCC_except_table6490
+ GCC_except_table6496
+ GCC_except_table6512
+ GCC_except_table653
+ GCC_except_table6547
+ GCC_except_table6549
+ GCC_except_table6569
+ GCC_except_table6581
+ GCC_except_table6584
+ GCC_except_table6589
+ GCC_except_table6591
+ GCC_except_table6605
+ GCC_except_table661
+ GCC_except_table6828
+ GCC_except_table6841
+ GCC_except_table6846
+ GCC_except_table6849
+ GCC_except_table6850
+ GCC_except_table6852
+ GCC_except_table6853
+ GCC_except_table6855
+ GCC_except_table688
+ GCC_except_table6907
+ GCC_except_table6911
+ GCC_except_table6915
+ GCC_except_table692
+ GCC_except_table6920
+ GCC_except_table6924
+ GCC_except_table6928
+ GCC_except_table6932
+ GCC_except_table6936
+ GCC_except_table6946
+ GCC_except_table6948
+ GCC_except_table695
+ GCC_except_table697
+ GCC_except_table6987
+ GCC_except_table703
+ GCC_except_table705
+ GCC_except_table7092
+ GCC_except_table7122
+ GCC_except_table718
+ GCC_except_table7207
+ GCC_except_table7208
+ GCC_except_table7209
+ GCC_except_table7210
+ GCC_except_table7211
+ GCC_except_table7212
+ GCC_except_table722
+ GCC_except_table726
+ GCC_except_table7275
+ GCC_except_table7285
+ GCC_except_table7286
+ GCC_except_table7298
+ GCC_except_table7304
+ GCC_except_table7317
+ GCC_except_table7320
+ GCC_except_table7321
+ GCC_except_table7326
+ GCC_except_table7336
+ GCC_except_table7339
+ GCC_except_table7360
+ GCC_except_table7366
+ GCC_except_table737
+ GCC_except_table7375
+ GCC_except_table7382
+ GCC_except_table7401
+ GCC_except_table7410
+ GCC_except_table742
+ GCC_except_table7425
+ GCC_except_table7426
+ GCC_except_table7431
+ GCC_except_table7435
+ GCC_except_table7436
+ GCC_except_table7439
+ GCC_except_table7445
+ GCC_except_table7449
+ GCC_except_table7453
+ GCC_except_table7455
+ GCC_except_table7457
+ GCC_except_table7461
+ GCC_except_table748
+ GCC_except_table753
+ GCC_except_table7576
+ GCC_except_table7613
+ GCC_except_table763
+ GCC_except_table764
+ GCC_except_table7670
+ GCC_except_table7673
+ GCC_except_table7677
+ GCC_except_table7683
+ GCC_except_table769
+ GCC_except_table770
+ GCC_except_table7707
+ GCC_except_table7711
+ GCC_except_table7712
+ GCC_except_table7713
+ GCC_except_table7762
+ GCC_except_table7763
+ GCC_except_table7765
+ GCC_except_table7795
+ GCC_except_table7796
+ GCC_except_table7801
+ GCC_except_table7821
+ GCC_except_table7839
+ GCC_except_table7850
+ GCC_except_table7856
+ GCC_except_table7857
+ GCC_except_table7872
+ GCC_except_table7875
+ GCC_except_table7882
+ GCC_except_table7889
+ GCC_except_table7894
+ GCC_except_table7900
+ GCC_except_table7912
+ GCC_except_table7913
+ GCC_except_table7918
+ GCC_except_table7927
+ GCC_except_table7933
+ GCC_except_table7934
+ GCC_except_table7938
+ GCC_except_table7940
+ GCC_except_table7942
+ GCC_except_table7946
+ GCC_except_table796
+ GCC_except_table7967
+ GCC_except_table7969
+ GCC_except_table7970
+ GCC_except_table7996
+ GCC_except_table803
+ GCC_except_table810
+ GCC_except_table811
+ GCC_except_table8161
+ GCC_except_table8224
+ GCC_except_table8256
+ GCC_except_table8259
+ GCC_except_table839
+ GCC_except_table8426
+ GCC_except_table8464
+ GCC_except_table8501
+ GCC_except_table8576
+ GCC_except_table862
+ GCC_except_table8630
+ GCC_except_table8632
+ GCC_except_table8634
+ GCC_except_table8636
+ GCC_except_table8638
+ GCC_except_table8640
+ GCC_except_table8642
+ GCC_except_table8645
+ GCC_except_table8647
+ GCC_except_table8651
+ GCC_except_table8656
+ GCC_except_table8658
+ GCC_except_table8660
+ GCC_except_table8667
+ GCC_except_table8673
+ GCC_except_table8678
+ GCC_except_table8681
+ GCC_except_table8686
+ GCC_except_table8691
+ GCC_except_table8723
+ GCC_except_table8726
+ GCC_except_table8727
+ GCC_except_table8767
+ GCC_except_table8768
+ GCC_except_table8770
+ GCC_except_table8771
+ GCC_except_table8774
+ GCC_except_table8775
+ GCC_except_table8777
+ GCC_except_table8778
+ GCC_except_table8780
+ GCC_except_table8784
+ GCC_except_table8785
+ GCC_except_table8789
+ GCC_except_table880
+ GCC_except_table8840
+ GCC_except_table8847
+ GCC_except_table8952
+ GCC_except_table8971
+ GCC_except_table8975
+ GCC_except_table8977
+ GCC_except_table8979
+ GCC_except_table8982
+ GCC_except_table8984
+ GCC_except_table8986
+ GCC_except_table8988
+ GCC_except_table8989
+ GCC_except_table8991
+ GCC_except_table8993
+ GCC_except_table8998
+ GCC_except_table9000
+ GCC_except_table9001
+ GCC_except_table904
+ GCC_except_table908
+ GCC_except_table922
+ GCC_except_table927
+ _OBJC_IVAR_$_HAP2AccessoryServer._nextMergeAccessory
+ _OBJC_IVAR_$_HAPAccessoryServerNFC._apduTxMode
+ _OBJC_IVAR_$_HAPAccessoryServerNFC._isCommissionedOverNFCWithoutPower
+ _OBJC_IVAR_$_HAPAccessoryServerNFC._nfcLastStepTime
+ _OBJC_IVAR_$_HAPAccessoryServerNFC._nfcM1SendTime
+ _OBJC_IVAR_$_HAPAccessoryServerNFC._nfcPairingStartTime
+ _OBJC_IVAR_$_HAPAccessoryServerNFC._prefetchedMFiToken
+ _OBJC_IVAR_$_HAPAccessoryServerNFC._prefetchedMFiTokenUUID
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HAP2AccessoryServerTransportCommon
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HAPSpakePairSetupSessionDelegate
+ ___103-[HAP2AccessoryServerSecureTransportPairVerify _attemptIPIterationOrFailWithError:failureCloseHandler:]_block_invoke
+ ___103-[HAP2AccessoryServerSecureTransportPairVerify _attemptIPIterationOrFailWithError:failureCloseHandler:]_block_invoke_2
+ ___43-[HAPAccessoryServerNFC _startHAPPairSetup]_block_invoke
+ ___43-[HAPAccessoryServerNFC _startHAPPairSetup]_block_invoke_2
+ ___43-[HAPAccessoryServerNFC _startHAPPairSetup]_block_invoke_3
+ ___46-[HAP2AccessoryServer _setNextMergeAccessory:]_block_invoke
+ ___46-[HAP2AccessoryServer _takeNextMergeAccessory]_block_invoke
+ ___50-[HAPAccessoryServerNFC refreshHAPWithCompletion:]_block_invoke
+ ___53-[_HAPAccessoryServerBTLE200 _establishSecureSession]_block_invoke
+ ___53-[_HAPAccessoryServerBTLE200 _establishSecureSession]_block_invoke_2
+ ___53-[_HAPAccessoryServerBTLE200 _establishSecureSession]_block_invoke_3
+ ___59-[HAPAccessoryServerIP _pairSetupStartWithConsentRequired:]_block_invoke_2
+ ___61-[_HAPAccessoryServerBTLE200 tearDownSessionOnAuthCompletion]_block_invoke_2
+ ___65-[_HAPAccessoryServerBTLE200 _obtainPairVerifyTLKWithCompletion:]_block_invoke
+ ___65-[_HAPAccessoryServerBTLE200 _obtainPairVerifyTLKWithCompletion:]_block_invoke_2
+ ___65-[_HAPAccessoryServerBTLE200 _obtainPairVerifyTLKWithCompletion:]_block_invoke_3
+ ___69-[HAPAccessoryServerNFC providePrefetchedMFiTokenWithToken:uuidData:]_block_invoke
+ ___73-[HAP2AccessoryServerPairingDriverPairSetupWorkItem runForPairingDriver:]_block_invoke
+ ___73-[HAP2AccessoryServerPairingDriverPairSetupWorkItem runForPairingDriver:]_block_invoke_2
+ ___74-[HAP2AccessoryServerSecureTransportPairVerify _setStateChangeCompletion:]_block_invoke
+ ___75-[HAP2AccessoryServerSecureTransportPairVerify _claimStateChangeCompletion]_block_invoke
+ ___75-[HAP2AccessoryServerSecureTransportPairVerify _handleECDSASessionFailure:]_block_invoke_3
+ ___75-[HAP2AccessoryServerSecureTransportPairVerify _handleECDSASessionFailure:]_block_invoke_4
+ ___75-[HAPAccessoryServerBrowserNFC _notifyDelegateOfDiscoveryFailureWithError:]_block_invoke
+ ___75-[HAPAccessoryServerNFC pairSetupSession:confirmMFiTokenWithUUID:newToken:]_block_invoke
+ ___78-[HAPAccessoryServerIP _ensurePairingSessionIsInitializedWithType:completion:]_block_invoke
+ ___78-[HAPAccessoryServerIP _ensurePairingSessionIsInitializedWithType:completion:]_block_invoke_2
+ ___78-[HAPAccessoryServerIP _ensurePairingSessionIsInitializedWithType:completion:]_block_invoke_3
+ ___80-[HAP2AccessoryServerSecureTransportPairVerify _createECDSAKeyPairVerifySession]_block_invoke
+ ___80-[HAP2AccessoryServerSecureTransportPairVerify _createECDSAKeyPairVerifySession]_block_invoke_2
+ ___80-[HAP2AccessoryServerSecureTransportPairVerify _createECDSAKeyPairVerifySession]_block_invoke_3
+ ___82-[HAP2AccessoryServerSecureTransportPairVerify pairSetupSession:didStopWithError:]_block_invoke_3
+ ___82-[HAP2AccessoryServerSecureTransportPairVerify pairSetupSession:didStopWithError:]_block_invoke_4
+ ___84-[HAPAccessoryServerHAP2Adapter accessoryServer:requestPairVerifyTLKWithCompletion:]_block_invoke
+ ___90-[HAPAccessoryServerNFC pairSetupSession:didPairWithPeerIdentifier:ecdsaPairingKey:error:]_block_invoke
+ ___98-[HAPAccessoryServerNFC pairSetupSession:validateAndRollMFiTokenWithUUID:token:completionHandler:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e41_v32?0"NSData"8"NSString"16"NSError"24ls32l8
+ ___block_descriptor_40_e8_32s_e8_v12?0i8ls32l8
+ ___block_descriptor_48_e8_32bs40w_e8_v12?0B8lw40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e8_v12?0i8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40w_e29_v24?0"NSArray"8"NSError"16ls32l8w40l8
+ ___block_descriptor_49_e8_32bs40w_e5_v8?0lw40l8s32l8
+ ___block_descriptor_56_e8_32s40w_e28_v24?0"NSData"8"NSError"16ls32l8w40l8
+ ___block_descriptor_57_e8_32s40s48bs_e28_v24?0"NSData"8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_60_e8_32s40bs_e28_v24?0"NSData"8"NSError"16ls32l8s40l8
+ ___block_descriptor_60_e8_32s40bs_e5_v8?0ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48bs56r_e28_v24?0"NSData"8"NSError"16ls32l8r56l8s40l8s48l8
+ ___block_descriptor_68_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
+ __swiftEmptyDictionarySingleton
+ _associated conformance 7CoreHAP20PairSetupCipherSuite33_FFB3B66732484B0775DD4AE3FA14FD0DLLOSHAASQ
+ _associated conformance 7CoreHAP24HAPSpakePairSetupSessionC21MFiTokenPrefetchState33_FFB3B66732484B0775DD4AE3FA14FD0DLLOSHAASQ
+ _kHAPNFCAPDUStatusWordUserInfoKey_block_invoke._hmf_once_t0
+ _kHAPNFCAPDUStatusWordUserInfoKey_block_invoke._hmf_once_v1
+ _logCategory._hmf_once_t214
+ _logCategory._hmf_once_t854
+ _logCategory._hmf_once_t891
+ _logCategory._hmf_once_v215
+ _logCategory._hmf_once_v855
+ _logCategory._hmf_once_v892
+ _swift_bridgeObjectRetain_n
+ _swift_dynamicCastClass
+ _swift_initStackObject
+ _swift_setDeallocating
+ _symbolic SSIego_
+ _symbolic SS_ypt
+ _symbolic Say_____GSg 10Foundation4DataV
+ _symbolic Sb
+ _symbolic SiIegd_
+ _symbolic SiIegr_
+ _symbolic So6NSLockC
+ _symbolic _____ 7CoreHAP20PairSetupCipherSuite33_FFB3B66732484B0775DD4AE3FA14FD0DLLO
+ _symbolic _____ 7CoreHAP24HAPSpakePairSetupSessionC21MFiTokenPrefetchState33_FFB3B66732484B0775DD4AE3FA14FD0DLLO
+ _symbolic _____Sg 7CoreHAP20PairSetupCipherSuite33_FFB3B66732484B0775DD4AE3FA14FD0DLLO
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _symbolic _____ySSypG s18_DictionaryStorageC
+ _symbolic _____y_____AB_G s12Zip2SequenceV8IteratorV 10Foundation4DataV
+ _symbolic _____y_____G 9CryptoKit24HashedAuthenticationCodeV AA6SHA256V
- -[HAPAccessoryServerBrowser pairSetupSession:pairSetupType:features:error:]
- -[HAPAccessoryServerIP _ensurePairingSessionIsInitializedWithType:]
- GCC_except_table1019
- GCC_except_table1021
- GCC_except_table1127
- GCC_except_table1132
- GCC_except_table1134
- GCC_except_table1159
- GCC_except_table1161
- GCC_except_table1163
- GCC_except_table1165
- GCC_except_table1291
- GCC_except_table1295
- GCC_except_table1297
- GCC_except_table1514
- GCC_except_table1724
- GCC_except_table1726
- GCC_except_table1731
- GCC_except_table1745
- GCC_except_table1747
- GCC_except_table1751
- GCC_except_table1755
- GCC_except_table1757
- GCC_except_table1762
- GCC_except_table1766
- GCC_except_table1776
- GCC_except_table1784
- GCC_except_table1791
- GCC_except_table1795
- GCC_except_table1799
- GCC_except_table1803
- GCC_except_table1841
- GCC_except_table1960
- GCC_except_table1964
- GCC_except_table1965
- GCC_except_table1967
- GCC_except_table1969
- GCC_except_table1983
- GCC_except_table1987
- GCC_except_table1990
- GCC_except_table1992
- GCC_except_table1995
- GCC_except_table2022
- GCC_except_table2024
- GCC_except_table2026
- GCC_except_table2031
- GCC_except_table2034
- GCC_except_table2037
- GCC_except_table2040
- GCC_except_table2049
- GCC_except_table2052
- GCC_except_table2056
- GCC_except_table2083
- GCC_except_table2116
- GCC_except_table2121
- GCC_except_table2137
- GCC_except_table2138
- GCC_except_table2331
- GCC_except_table2338
- GCC_except_table2342
- GCC_except_table2346
- GCC_except_table2350
- GCC_except_table2353
- GCC_except_table2355
- GCC_except_table2357
- GCC_except_table2360
- GCC_except_table2366
- GCC_except_table2371
- GCC_except_table2372
- GCC_except_table2374
- GCC_except_table2468
- GCC_except_table2476
- GCC_except_table2477
- GCC_except_table2478
- GCC_except_table2479
- GCC_except_table2480
- GCC_except_table2481
- GCC_except_table2496
- GCC_except_table2510
- GCC_except_table2590
- GCC_except_table2602
- GCC_except_table2628
- GCC_except_table2636
- GCC_except_table2647
- GCC_except_table2661
- GCC_except_table2664
- GCC_except_table2669
- GCC_except_table2677
- GCC_except_table2683
- GCC_except_table2685
- GCC_except_table2887
- GCC_except_table2904
- GCC_except_table2938
- GCC_except_table2954
- GCC_except_table2956
- GCC_except_table2968
- GCC_except_table2975
- GCC_except_table2991
- GCC_except_table3005
- GCC_except_table3007
- GCC_except_table3010
- GCC_except_table3016
- GCC_except_table3023
- GCC_except_table3026
- GCC_except_table3031
- GCC_except_table3036
- GCC_except_table3041
- GCC_except_table3092
- GCC_except_table3095
- GCC_except_table3100
- GCC_except_table3102
- GCC_except_table3118
- GCC_except_table3132
- GCC_except_table3134
- GCC_except_table3138
- GCC_except_table3146
- GCC_except_table3154
- GCC_except_table3217
- GCC_except_table3224
- GCC_except_table3226
- GCC_except_table3227
- GCC_except_table3250
- GCC_except_table3270
- GCC_except_table3498
- GCC_except_table3565
- GCC_except_table3566
- GCC_except_table3570
- GCC_except_table3573
- GCC_except_table3575
- GCC_except_table3576
- GCC_except_table3578
- GCC_except_table3579
- GCC_except_table3581
- GCC_except_table3588
- GCC_except_table3598
- GCC_except_table3601
- GCC_except_table3612
- GCC_except_table3613
- GCC_except_table3617
- GCC_except_table3643
- GCC_except_table3645
- GCC_except_table3649
- GCC_except_table3653
- GCC_except_table3657
- GCC_except_table3683
- GCC_except_table3701
- GCC_except_table3705
- GCC_except_table3708
- GCC_except_table3710
- GCC_except_table3712
- GCC_except_table3719
- GCC_except_table3720
- GCC_except_table3721
- GCC_except_table3802
- GCC_except_table3803
- GCC_except_table3804
- GCC_except_table3805
- GCC_except_table3806
- GCC_except_table3807
- GCC_except_table3808
- GCC_except_table3809
- GCC_except_table3810
- GCC_except_table3811
- GCC_except_table3812
- GCC_except_table3813
- GCC_except_table3814
- GCC_except_table3815
- GCC_except_table3881
- GCC_except_table4002
- GCC_except_table4009
- GCC_except_table4051
- GCC_except_table4055
- GCC_except_table4058
- GCC_except_table4061
- GCC_except_table4064
- GCC_except_table4067
- GCC_except_table4070
- GCC_except_table4073
- GCC_except_table4076
- GCC_except_table4079
- GCC_except_table4084
- GCC_except_table4095
- GCC_except_table4104
- GCC_except_table4120
- GCC_except_table4128
- GCC_except_table4132
- GCC_except_table4138
- GCC_except_table4139
- GCC_except_table4142
- GCC_except_table4143
- GCC_except_table4163
- GCC_except_table4165
- GCC_except_table4166
- GCC_except_table4175
- GCC_except_table4178
- GCC_except_table4186
- GCC_except_table4188
- GCC_except_table4191
- GCC_except_table4213
- GCC_except_table4215
- GCC_except_table4224
- GCC_except_table4226
- GCC_except_table4228
- GCC_except_table4234
- GCC_except_table4494
- GCC_except_table4500
- GCC_except_table4517
- GCC_except_table4521
- GCC_except_table4538
- GCC_except_table4544
- GCC_except_table4557
- GCC_except_table4571
- GCC_except_table4575
- GCC_except_table4688
- GCC_except_table5142
- GCC_except_table5150
- GCC_except_table5160
- GCC_except_table5202
- GCC_except_table5205
- GCC_except_table5206
- GCC_except_table5207
- GCC_except_table5208
- GCC_except_table5340
- GCC_except_table5341
- GCC_except_table5342
- GCC_except_table5343
- GCC_except_table5344
- GCC_except_table5345
- GCC_except_table5351
- GCC_except_table5352
- GCC_except_table5354
- GCC_except_table5361
- GCC_except_table5364
- GCC_except_table5366
- GCC_except_table5371
- GCC_except_table5374
- GCC_except_table5377
- GCC_except_table5381
- GCC_except_table5871
- GCC_except_table5872
- GCC_except_table5891
- GCC_except_table5901
- GCC_except_table5904
- GCC_except_table5909
- GCC_except_table5912
- GCC_except_table5916
- GCC_except_table598
- GCC_except_table605
- GCC_except_table608
- GCC_except_table6185
- GCC_except_table6189
- GCC_except_table6234
- GCC_except_table6238
- GCC_except_table6240
- GCC_except_table6242
- GCC_except_table631
- GCC_except_table641
- GCC_except_table6434
- GCC_except_table6440
- GCC_except_table6444
- GCC_except_table6445
- GCC_except_table6446
- GCC_except_table6447
- GCC_except_table6453
- GCC_except_table6469
- GCC_except_table649
- GCC_except_table6504
- GCC_except_table6505
- GCC_except_table6506
- GCC_except_table6526
- GCC_except_table6538
- GCC_except_table6541
- GCC_except_table6546
- GCC_except_table6562
- GCC_except_table676
- GCC_except_table6785
- GCC_except_table6798
- GCC_except_table680
- GCC_except_table6803
- GCC_except_table6806
- GCC_except_table6807
- GCC_except_table6809
- GCC_except_table6810
- GCC_except_table6812
- GCC_except_table683
- GCC_except_table6842
- GCC_except_table685
- GCC_except_table6864
- GCC_except_table6868
- GCC_except_table6872
- GCC_except_table6877
- GCC_except_table6881
- GCC_except_table6889
- GCC_except_table6893
- GCC_except_table6901
- GCC_except_table6903
- GCC_except_table6905
- GCC_except_table691
- GCC_except_table693
- GCC_except_table7029
- GCC_except_table706
- GCC_except_table710
- GCC_except_table7136
- GCC_except_table7137
- GCC_except_table7138
- GCC_except_table7139
- GCC_except_table714
- GCC_except_table7140
- GCC_except_table7141
- GCC_except_table7142
- GCC_except_table7203
- GCC_except_table7214
- GCC_except_table7226
- GCC_except_table7232
- GCC_except_table724
- GCC_except_table7245
- GCC_except_table7248
- GCC_except_table7249
- GCC_except_table725
- GCC_except_table7254
- GCC_except_table7257
- GCC_except_table7264
- GCC_except_table7267
- GCC_except_table7281
- GCC_except_table7288
- GCC_except_table7294
- GCC_except_table730
- GCC_except_table7303
- GCC_except_table7305
- GCC_except_table7309
- GCC_except_table7310
- GCC_except_table7327
- GCC_except_table733
- GCC_except_table7338
- GCC_except_table7354
- GCC_except_table7359
- GCC_except_table7363
- GCC_except_table7364
- GCC_except_table7367
- GCC_except_table7373
- GCC_except_table7383
- GCC_except_table7385
- GCC_except_table741
- GCC_except_table7504
- GCC_except_table751
- GCC_except_table752
- GCC_except_table7541
- GCC_except_table758
- GCC_except_table7598
- GCC_except_table7601
- GCC_except_table7605
- GCC_except_table7611
- GCC_except_table7618
- GCC_except_table7619
- GCC_except_table7635
- GCC_except_table7639
- GCC_except_table7640
- GCC_except_table7641
- GCC_except_table7693
- GCC_except_table7696
- GCC_except_table7723
- GCC_except_table7724
- GCC_except_table7729
- GCC_except_table7749
- GCC_except_table7767
- GCC_except_table7769
- GCC_except_table7778
- GCC_except_table7783
- GCC_except_table7784
- GCC_except_table7785
- GCC_except_table7800
- GCC_except_table7803
- GCC_except_table7810
- GCC_except_table7817
- GCC_except_table7822
- GCC_except_table7828
- GCC_except_table784
- GCC_except_table7846
- GCC_except_table7861
- GCC_except_table7862
- GCC_except_table7866
- GCC_except_table7868
- GCC_except_table7870
- GCC_except_table7874
- GCC_except_table7895
- GCC_except_table7897
- GCC_except_table7898
- GCC_except_table791
- GCC_except_table7924
- GCC_except_table798
- GCC_except_table799
- GCC_except_table8089
- GCC_except_table8152
- GCC_except_table8184
- GCC_except_table8187
- GCC_except_table827
- GCC_except_table8354
- GCC_except_table8392
- GCC_except_table8429
- GCC_except_table850
- GCC_except_table8503
- GCC_except_table8509
- GCC_except_table8557
- GCC_except_table8559
- GCC_except_table8561
- GCC_except_table8563
- GCC_except_table8565
- GCC_except_table8567
- GCC_except_table8569
- GCC_except_table8571
- GCC_except_table8573
- GCC_except_table8575
- GCC_except_table8577
- GCC_except_table8579
- GCC_except_table8584
- GCC_except_table8586
- GCC_except_table8593
- GCC_except_table8599
- GCC_except_table8604
- GCC_except_table8607
- GCC_except_table8612
- GCC_except_table8617
- GCC_except_table8620
- GCC_except_table8623
- GCC_except_table8652
- GCC_except_table867
- GCC_except_table8692
- GCC_except_table8693
- GCC_except_table8696
- GCC_except_table8699
- GCC_except_table8700
- GCC_except_table8701
- GCC_except_table8703
- GCC_except_table8704
- GCC_except_table8706
- GCC_except_table8710
- GCC_except_table8711
- GCC_except_table8715
- GCC_except_table8867
- GCC_except_table8886
- GCC_except_table8890
- GCC_except_table8892
- GCC_except_table8894
- GCC_except_table8897
- GCC_except_table8899
- GCC_except_table8901
- GCC_except_table8903
- GCC_except_table8904
- GCC_except_table8906
- GCC_except_table8908
- GCC_except_table891
- GCC_except_table8913
- GCC_except_table895
- GCC_except_table909
- GCC_except_table914
- ___92-[HAP2AccessoryServerTransportBaseOperationClose initWithTransport:desiredError:completion:]_block_invoke_2
- __block_invoke._hmf_once_t0
- __block_invoke._hmf_once_v1
- _logCategory._hmf_once_t212
- _logCategory._hmf_once_t838
- _logCategory._hmf_once_t889
- _logCategory._hmf_once_v213
- _logCategory._hmf_once_v839
- _logCategory._hmf_once_v890
- _swift_unknownObjectRetain_n
CStrings:
+ "!Aq"
+ "%@ - close: state change completion has already been handled"
+ "%@ - open: state change completion has already been handled"
+ "%@ - request completion has already been handled"
+ "%@ No accessory server for pair-verify TLKs lookup"
+ "%@ No storage for pair-verify TLKs lookup"
+ "(Base) closeWithError:completion: enqueued close operation"
+ "(Base) openWithCompletion: enqueued open operation"
+ "(PairVerify) _claimStateChangeCompletion: already claimed by another path"
+ "(PairVerify) _openTransport invoking openWithCompletion (inner.state=%lu)"
+ "(SecureBase) doCloseWithError:completion: entered, forwarding to inner (inner.state=%lu)"
+ "AID selected"
+ "Decrypted M2 proof data didn't include required TLVs"
+ "Deferred Matter Onboarding Payload: "
+ "Delegate does not support confirmMFiToken; rolled token not committed"
+ "Delegate does not support requestPairVerifyTLKWithCompletion: - cannot proceed with NFC pair-setup"
+ "Delegate does not support validateAndRollMFiToken; echoing M4 token in M5"
+ "Failed to REFRESH HAP: %@"
+ "Failed to retrieve TLKs for ECDSA pair-verify: %@"
+ "HAP REFRESHED successfully"
+ "HAP2AccessoryServerControllerOperation _openTransport:%d (sessionNumber=%lu)"
+ "HAP2AccessoryServerTransportBaseOperationClose completionBlock fired (error.code=%ld)"
+ "HAP2AccessoryServerTransportBaseOperationClose main() executing"
+ "HAP2AccessoryServerTransportBaseOperationOpen main() executing"
+ "HAPNFCAPDUStatusWord"
+ "HK ECDSA Privacy IPK"
+ "HK ECDSA Privacy v1 IPK"
+ "HK ECDSA Privacy v1 TLK"
+ "HomeKit-Pair-Setup-HomeKit-Pair-Setup-HomeKit-Pair-Setup"
+ "Ignoring prefetched MFi token (token empty or uuid not 16 bytes)"
+ "Ignoring prefetched MFi token injection (token empty or uuid not 16 bytes)"
+ "Including TLK TLV in M5 encrypted data"
+ "Including WiFi country code in M5 encrypted data"
+ "Injected prefetched MFi token (%ld bytes); starting parallel validate+roll"
+ "Injecting prefetched MFi token into SPAKE2+ session for parallel validate+roll"
+ "M%u received"
+ "M%u sending"
+ "M2 IPK-based session key derivation with %ld TLK(s)"
+ "M2 TLK decryption succeeded"
+ "M2 TLK derivation failed, trying next"
+ "M2 no TLK produced a valid session key"
+ "M2: Using hashed setup code"
+ "M2: Using repeated setup code"
+ "M2: cipherSuite %llu (%{public}s)"
+ "M2: extraFlags 0x%s"
+ "M2: flags 0x%s"
+ "M2: no cipherSuite advertised; defaulting to legacy (suite 0)"
+ "M2: unknown cipherSuite raw value %llu"
+ "M4: Accessory using %{public}s KDF"
+ "M4: Accessory using CMAC-CTR KDF (detected via trial-decrypt)"
+ "M4: UNEXPECTED — 32-byte MFi token hash with no prefetched NDEF token to verify it; failing pair-setup instead of rolling the hash (would corrupt the accessory's token slot)"
+ "M4: prefetched token does not match M4 hash — failing pair-setup"
+ "M4: received mfiToken (%ld bytes), uuid (%ld bytes)"
+ "M4: requesting MFi token validate+roll"
+ "M5: %{public}s mfiToken (%ld bytes)"
+ "M5: no rolled token and nothing to echo"
+ "M5: no rolled token — echoing token (%ld bytes)"
+ "M5: no rolled/echo token and only the 32-byte M4 hash remains — failing rather than transmitting it"
+ "M5: using rolled MFi token (%ld bytes)"
+ "M6: confirming rolled MFi token"
+ "MFi early-auth: DISMISSED — M4 sent a full token (%ld bytes), not the primed hash; abandoning tap-time validate+roll, validating M4 token"
+ "MFi early-auth: INTERRUPTED — abandoning validate+roll still in flight (state inProgress → cancelled)"
+ "MFi early-auth: M4 hash VERIFIED against tap-time NDEF token — early auth accepted; consuming validate+roll for M5"
+ "MFi early-auth: M4 hash verified and validate+roll already finished — using its result for M5"
+ "MFi early-auth: M4 hash verified but validate+roll still in flight — M5 will continue when it returns"
+ "MFi early-auth: M4 was waiting on the validate+roll — driving M5 now"
+ "MFi early-auth: cancel requested (state %{public}s → cancelled)"
+ "MFi early-auth: delegate did not handle validate+roll — completing with no rolled token"
+ "MFi early-auth: discarding already-finished validate+roll (state completed → cancelled)"
+ "MFi early-auth: state notStarted → inProgress (validate+roll started for tap-time NDEF token, %ld bytes)"
+ "MFi early-auth: validate+roll FAILED (state inProgress → completed): %s"
+ "MFi early-auth: validate+roll finished (state inProgress → completed) — no rolled token returned"
+ "MFi early-auth: validate+roll finished (state inProgress → completed) — rolled token ready (%ld bytes)"
+ "MFi early-auth: validate+roll in unexpected state at M4 (hash verified) — failing pair-setup"
+ "MFi early-auth: validate+roll returned after it was abandoned at M4 — discarding result"
+ "MFi token roll completed but session no longer in M5 — discarding"
+ "MFi token validate/roll failed: %s"
+ "Mapping bootstrap characteristic %{public}@ to its GATT handle to bypass proxy"
+ "NFC REFRESH completed in %.2fms"
+ "NFC REFRESH failed after %.2fms: %@"
+ "NFC tag detection timed out after %.0f seconds"
+ "No GATT characteristic for bootstrap characteristic %{public}@"
+ "No NFC tag detected within %.0f seconds"
+ "Pair verify TLK not available - failing pair setup"
+ "Pair-Setup-Accessory-Sign"
+ "Pair-Setup-Controller-Sign"
+ "Pair-Setup-Encrypt"
+ "Pair-setup TLK required but not provided for AES-CCM accessory"
+ "Pair-setup(NFC) complete"
+ "Pair-setup(NFC+keysave) complete"
+ "Pair-verify TLKs required but not provided"
+ "Pair-verify using removed accessory ECDSA key without TLKs"
+ "Per-accessory deferred Matter onboarding payload"
+ "Prefetched MFi token already injected; ignoring"
+ "REFRESH failed with status: 0x%04X"
+ "REFRESH failed: 0x%04X"
+ "REFRESH response shorter than 2 bytes"
+ "REFRESH response: %@"
+ "Refreshing HAP pre calc on NFC tag"
+ "SPAKE2+ session committing rolled MFi token for UUID %{public}@"
+ "SPAKE2+ session requesting MFi token validate+roll for UUID %{public}@"
+ "Secure Transport: Failed to fetch pair-verify TLKs: %@"
+ "Secure Transport: Finished force closing after ECDSA pair verify failure"
+ "Secure Transport: Finished force closing after ECDSA session failure"
+ "Secure Transport: No delegate for pair-verify IPKs lookup"
+ "Secure Transport: PV failed (%@), asking transport to advance endpoint"
+ "Secure Transport: Transport advanced endpoint, restarting Pair Verify from M1"
+ "Secure Transport: Transport could not advance endpoint, surfacing original PV error"
+ "Skipping TLK with invalid length %ld"
+ "Starting %.0f-second timeout timer for tag detection"
+ "Stashing prefetched MFi token (%lu bytes) for parallel validate+roll"
+ "TLK data available for M5"
+ "TLK not available for NFC pair-setup"
+ "Unable to map pairing bootstrap characteristics: Pairing GATT service not discovered"
+ "[%{public}@] Delegate does not support confirmMFiToken; rolled token not committed"
+ "[%{public}@] Delegate does not support requestPairVerifyTLKWithCompletion: - cannot proceed with NFC pair-setup"
+ "[%{public}@] Delegate does not support validateAndRollMFiToken; echoing M4 token in M5"
+ "[%{public}@] Failed to REFRESH HAP: %@"
+ "[%{public}@] Failed to retrieve TLKs for ECDSA pair-verify: %@"
+ "[%{public}@] HAP REFRESHED successfully"
+ "[%{public}@] Ignoring prefetched MFi token (token empty or uuid not 16 bytes)"
+ "[%{public}@] Injecting prefetched MFi token into SPAKE2+ session for parallel validate+roll"
+ "[%{public}@] Mapping bootstrap characteristic %{public}@ to its GATT handle to bypass proxy"
+ "[%{public}@] NFC REFRESH completed in %.2fms"
+ "[%{public}@] NFC REFRESH failed after %.2fms: %@"
+ "[%{public}@] NFC tag detection timed out after %.0f seconds"
+ "[%{public}@] No GATT characteristic for bootstrap characteristic %{public}@"
+ "[%{public}@] No NFC tag connected"
+ "[%{public}@] No active NFC reader session"
+ "[%{public}@] Pair-verify using removed accessory ECDSA key without TLKs"
+ "[%{public}@] REFRESH failed with status: 0x%04X"
+ "[%{public}@] REFRESH response: %@"
+ "[%{public}@] Refreshing HAP pre calc on NFC tag"
+ "[%{public}@] SPAKE2+ session committing rolled MFi token for UUID %{public}@"
+ "[%{public}@] SPAKE2+ session requesting MFi token validate+roll for UUID %{public}@"
+ "[%{public}@] Starting %.0f-second timeout timer for tag detection"
+ "[%{public}@] Stashing prefetched MFi token (%lu bytes) for parallel validate+roll"
+ "[%{public}@] Unable to map pairing bootstrap characteristics: Pairing GATT service not discovered"
+ "[%{public}@] [NFC APDU] Extended-APDU probe accepted; using extended for the rest of the session"
+ "[%{public}@] [NFC APDU] Extended-APDU probe rejected (%{public}@ %ld); falling back to simple-fragmented"
+ "[%{public}@] [NFC APDU] Extended-APDU probe rejected (status 0x%04X); falling back to simple-fragmented"
+ "[%{public}@] [Timing] %{public}@: +%.2fms (delta %.2fms)"
+ "[%{public}@] [Timing] M1 -> M6 total: %.2fms"
+ "[%{public}@] [Timing] NFC pairing total (%{public}@): %.2fms"
+ "[%{public}@] [Timing] Pairing started"
+ "[NFC APDU] Extended-APDU probe accepted; using extended for the rest of the session"
+ "[NFC APDU] Extended-APDU probe rejected (%{public}@ %ld); falling back to simple-fragmented"
+ "[NFC APDU] Extended-APDU probe rejected (status 0x%04X); falling back to simple-fragmented"
+ "[Timing] %{public}@: +%.2fms (delta %.2fms)"
+ "[Timing] M1 -> M6 total: %.2fms"
+ "[Timing] NFC pairing total (%{public}@): %.2fms"
+ "[Timing] Pairing started"
+ "accessoryUUID"
+ "failure"
+ "mtOU"
+ "openTransportWithResume entered (isResume=%d, sessionNumber=%lu, transport.state=%lu)"
+ "p256NistKdfCmacAes128Sha256 not yet supported"
+ "payload"
+ "v32@?0@\"NSData\"8@\"NSString\"16@\"NSError\"24"
- "M2: flags %llu"
- "M4: Accessory using CMAC-CTR KDF"
- "M4: Accessory using HKDF-SHA512"
- "NFC tag detection timed out"
- "No NFC tag detected within 5 seconds"
- "No tag connected or no active session"
- "Pair-Setup-Accessory-Sign-Info"
- "Pair-Setup-Accessory-Sign-Salt"
- "Pair-Setup-Controller-Sign-Info"
- "Pair-Setup-Controller-Sign-Salt"
- "Pair-Setup-Encrypt-Info"
- "Pair-Setup-Encrypt-Salt"
- "Starting 5-second timeout timer for tag detection"
- "[%{public}@] NFC tag detection timed out"
- "[%{public}@] No tag connected or no active session"
- "[%{public}@] Starting 5-second timeout timer for tag detection"
```
