## NetworkExtension

> `/System/Library/Frameworks/NetworkExtension.framework/NetworkExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x248f1` | `0x24b23` | **`+0x232`** |
| `__AUTH_CONST.__objc_const` | `0x23150` | `0x23210` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x19467` | `0x194c0` | **`+0x59`** |
| `__AUTH_CONST.__cfstring` | `0x19060` | `0x190a0` | **`+0x40`** |
| `__DATA.__bss` | `0x1628` | `0x1668` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xf2b8` | `0xf2e8` | **`+0x30`** |
| `__TEXT.__text` | `0x2078cc` | `0x2078fc` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x5618` | `0x5640` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x2498` | `0x24b0` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x63d8` | `0x63f0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1c28` | `0x1c3c` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x5328` | `0x5338` | **`+0x10`** |
| `__TEXT.__const` | `0x368c` | `0x367c` | **`-0x10`** |

### Other Changes

```diff

-2303.0.0.0.2
+2315.0.0.0.2

-  Functions: 8246
-  Symbols:   14309
-  CStrings:  7185
+  Functions: 8250
+  Symbols:   14327
+  CStrings:  7198
Symbols:
+ +[NEIKEv2Crypto writeRandomBytesTo:withSize:]
+ +[NEIKEv2TLSSPI unregisterInboundSPI:]
+ -[NEConfiguration isDDMSystemScope]
+ -[NEConfiguration setIsDDMSystemScope:]
+ -[NEDeclarationInstaller payloadTypeForDeclarationType]
+ -[NEIKEv2Packet fillIKEv2Header:length:nextPayloadType:]
+ -[NEIKEv2Packet getEncryptedHeaderWithLength:nextPayloadType:securityContext:fragmentNumber:totalFragments:]
+ -[NEIKEv2SessionConfiguration isSystemScopedDDMCredentials]
+ -[NEIKEv2SessionConfiguration setIsSystemScopedDDMCredentials:]
+ GCC_except_table1029
+ GCC_except_table1118
+ GCC_except_table1176
+ GCC_except_table1177
+ GCC_except_table1183
+ GCC_except_table1184
+ GCC_except_table1352
+ GCC_except_table1353
+ GCC_except_table1363
+ GCC_except_table1364
+ GCC_except_table1370
+ GCC_except_table1375
+ GCC_except_table1376
+ GCC_except_table1389
+ GCC_except_table1400
+ GCC_except_table1401
+ GCC_except_table1526
+ GCC_except_table1651
+ GCC_except_table1652
+ GCC_except_table1657
+ GCC_except_table1660
+ GCC_except_table1720
+ GCC_except_table1721
+ GCC_except_table1726
+ GCC_except_table1730
+ GCC_except_table1733
+ GCC_except_table1739
+ GCC_except_table1740
+ GCC_except_table1747
+ GCC_except_table1771
+ GCC_except_table1797
+ GCC_except_table2009
+ GCC_except_table273
+ GCC_except_table2919
+ GCC_except_table3169
+ GCC_except_table3175
+ GCC_except_table3178
+ GCC_except_table3193
+ GCC_except_table3194
+ GCC_except_table3195
+ GCC_except_table3210
+ GCC_except_table3224
+ GCC_except_table3225
+ GCC_except_table3267
+ GCC_except_table3271
+ GCC_except_table3317
+ GCC_except_table3368
+ GCC_except_table3428
+ GCC_except_table3447
+ GCC_except_table3456
+ GCC_except_table3458
+ GCC_except_table3477
+ GCC_except_table3478
+ GCC_except_table3479
+ GCC_except_table3490
+ GCC_except_table3497
+ GCC_except_table3536
+ GCC_except_table3542
+ GCC_except_table3544
+ GCC_except_table3579
+ GCC_except_table3581
+ GCC_except_table3582
+ GCC_except_table3671
+ GCC_except_table3699
+ GCC_except_table3941
+ GCC_except_table3948
+ GCC_except_table3950
+ GCC_except_table3951
+ GCC_except_table3953
+ GCC_except_table400
+ GCC_except_table4045
+ GCC_except_table4210
+ GCC_except_table4221
+ GCC_except_table4227
+ GCC_except_table4247
+ GCC_except_table4248
+ GCC_except_table4249
+ GCC_except_table4254
+ GCC_except_table4259
+ GCC_except_table4260
+ GCC_except_table4266
+ GCC_except_table4273
+ GCC_except_table4274
+ GCC_except_table4346
+ GCC_except_table4347
+ GCC_except_table4355
+ GCC_except_table4450
+ GCC_except_table4452
+ GCC_except_table4453
+ GCC_except_table4455
+ GCC_except_table4549
+ GCC_except_table467
+ GCC_except_table4727
+ GCC_except_table4732
+ GCC_except_table4739
+ GCC_except_table4770
+ GCC_except_table4784
+ GCC_except_table4796
+ GCC_except_table4816
+ GCC_except_table4818
+ GCC_except_table4824
+ GCC_except_table4826
+ GCC_except_table4918
+ GCC_except_table4992
+ GCC_except_table5012
+ GCC_except_table5025
+ GCC_except_table5123
+ GCC_except_table5128
+ GCC_except_table5169
+ GCC_except_table5215
+ GCC_except_table5217
+ GCC_except_table5281
+ GCC_except_table5284
+ GCC_except_table5320
+ GCC_except_table5342
+ GCC_except_table5344
+ GCC_except_table5352
+ GCC_except_table5391
+ GCC_except_table5394
+ GCC_except_table5396
+ GCC_except_table5399
+ GCC_except_table5443
+ GCC_except_table5465
+ GCC_except_table5468
+ GCC_except_table5559
+ GCC_except_table5886
+ GCC_except_table5923
+ GCC_except_table5926
+ GCC_except_table5991
+ GCC_except_table5997
+ GCC_except_table5998
+ GCC_except_table6006
+ GCC_except_table6009
+ GCC_except_table6019
+ GCC_except_table6038
+ GCC_except_table6039
+ GCC_except_table6044
+ GCC_except_table6045
+ GCC_except_table6046
+ GCC_except_table6053
+ GCC_except_table6062
+ GCC_except_table6069
+ GCC_except_table6146
+ GCC_except_table6147
+ GCC_except_table6294
+ GCC_except_table6295
+ GCC_except_table6296
+ GCC_except_table6297
+ GCC_except_table6306
+ GCC_except_table631
+ GCC_except_table6311
+ GCC_except_table6312
+ GCC_except_table6313
+ GCC_except_table6318
+ GCC_except_table632
+ GCC_except_table6344
+ GCC_except_table638
+ GCC_except_table6421
+ GCC_except_table6422
+ GCC_except_table6423
+ GCC_except_table6424
+ GCC_except_table643
+ GCC_except_table644
+ GCC_except_table651
+ GCC_except_table658
+ GCC_except_table659
+ GCC_except_table752
+ GCC_except_table819
+ GCC_except_table824
+ GCC_except_table873
+ GCC_except_table878
+ GCC_except_table896
+ GCC_except_table904
+ GCC_except_table905
+ GCC_except_table933
+ GCC_except_table976
+ GCC_except_table981
+ GCC_except_table982
+ _OBJC_IVAR_$_NEConfiguration._isDDMSystemScope
+ _OBJC_IVAR_$_NEIKEv2PacketConstructor._currentPayload
+ _OBJC_IVAR_$_NEIKEv2PacketConstructor._payloadEnumerator
+ _OBJC_IVAR_$_NEIKEv2SessionConfiguration._isSystemScopedDDMCredentials
+ _OBJC_IVAR_$_NEPvDFetcher._retryScheduled
+ _OBJC_IVAR_$_NERelay._isSystemScopedDDMIdentity
+ _OBJC_IVAR_$_NEVPNProtocol._isSystemScopedDDMCredentials
+ ___block_descriptor_48_e8_32s40r_e34_v20?0i8"NSObject<OS_nw_error>"12ls32l8r40l8
+ __oidSmtpUTF8Mailbox
+ _currentInboundTLSSPIs
+ _currentInboundTLSSPIsLock
+ _dispatch_data_create_alloc
+ _dispatch_data_get_size
+ _g_has_delegation_audit_token
+ _getprogname
+ _kNEDDMDeclarationScopeKey
+ _oidSmtpUTF8Mailbox
- +[NEIKEv2Crypto appendRandomBytesToData:withSize:]
- -[NEDeclarationInstaller payloadTypeForDeclaratype]
- -[NEIKEv2Packet constructHeadersForNextPayloadType:payloadsLength:fragmentNumber:totalFragments:securityContext:]
- -[NEIKEv2Session processFragment:]
- -[NEIKEv2Session receiveDeleteIKESA:]
- GCC_except_table1027
- GCC_except_table1116
- GCC_except_table1174
- GCC_except_table1175
- GCC_except_table1180
- GCC_except_table1181
- GCC_except_table1350
- GCC_except_table1351
- GCC_except_table1354
- GCC_except_table1355
- GCC_except_table1368
- GCC_except_table1373
- GCC_except_table1374
- GCC_except_table1387
- GCC_except_table1398
- GCC_except_table1399
- GCC_except_table1524
- GCC_except_table1649
- GCC_except_table1650
- GCC_except_table1655
- GCC_except_table1658
- GCC_except_table1703
- GCC_except_table1704
- GCC_except_table1724
- GCC_except_table1728
- GCC_except_table1731
- GCC_except_table1737
- GCC_except_table1738
- GCC_except_table1745
- GCC_except_table1769
- GCC_except_table1795
- GCC_except_table2007
- GCC_except_table271
- GCC_except_table2915
- GCC_except_table3159
- GCC_except_table3170
- GCC_except_table3173
- GCC_except_table3188
- GCC_except_table3189
- GCC_except_table3190
- GCC_except_table3205
- GCC_except_table3219
- GCC_except_table3220
- GCC_except_table3262
- GCC_except_table3266
- GCC_except_table3312
- GCC_except_table3363
- GCC_except_table3424
- GCC_except_table3443
- GCC_except_table3452
- GCC_except_table3454
- GCC_except_table3473
- GCC_except_table3474
- GCC_except_table3475
- GCC_except_table3486
- GCC_except_table3493
- GCC_except_table3532
- GCC_except_table3538
- GCC_except_table3540
- GCC_except_table3575
- GCC_except_table3577
- GCC_except_table3578
- GCC_except_table3667
- GCC_except_table3695
- GCC_except_table3937
- GCC_except_table3944
- GCC_except_table3945
- GCC_except_table3946
- GCC_except_table3947
- GCC_except_table396
- GCC_except_table4041
- GCC_except_table4206
- GCC_except_table4217
- GCC_except_table4223
- GCC_except_table4238
- GCC_except_table4239
- GCC_except_table4240
- GCC_except_table4241
- GCC_except_table4255
- GCC_except_table4256
- GCC_except_table4262
- GCC_except_table4269
- GCC_except_table4270
- GCC_except_table4342
- GCC_except_table4343
- GCC_except_table4351
- GCC_except_table4444
- GCC_except_table4445
- GCC_except_table4446
- GCC_except_table4447
- GCC_except_table4545
- GCC_except_table465
- GCC_except_table4723
- GCC_except_table4728
- GCC_except_table4735
- GCC_except_table4766
- GCC_except_table4776
- GCC_except_table4792
- GCC_except_table4812
- GCC_except_table4814
- GCC_except_table4820
- GCC_except_table4822
- GCC_except_table4914
- GCC_except_table4984
- GCC_except_table5008
- GCC_except_table5021
- GCC_except_table5119
- GCC_except_table5124
- GCC_except_table5165
- GCC_except_table5211
- GCC_except_table5213
- GCC_except_table5277
- GCC_except_table5280
- GCC_except_table5316
- GCC_except_table5336
- GCC_except_table5338
- GCC_except_table5348
- GCC_except_table5387
- GCC_except_table5388
- GCC_except_table5390
- GCC_except_table5395
- GCC_except_table5439
- GCC_except_table5461
- GCC_except_table5464
- GCC_except_table5555
- GCC_except_table5882
- GCC_except_table5918
- GCC_except_table5919
- GCC_except_table5987
- GCC_except_table5993
- GCC_except_table5994
- GCC_except_table6002
- GCC_except_table6005
- GCC_except_table6015
- GCC_except_table6030
- GCC_except_table6031
- GCC_except_table6032
- GCC_except_table6033
- GCC_except_table6042
- GCC_except_table6049
- GCC_except_table6058
- GCC_except_table6061
- GCC_except_table6142
- GCC_except_table6143
- GCC_except_table624
- GCC_except_table625
- GCC_except_table6273
- GCC_except_table6274
- GCC_except_table6275
- GCC_except_table6276
- GCC_except_table6302
- GCC_except_table6307
- GCC_except_table6308
- GCC_except_table6309
- GCC_except_table6314
- GCC_except_table6340
- GCC_except_table636
- GCC_except_table641
- GCC_except_table6417
- GCC_except_table6418
- GCC_except_table6419
- GCC_except_table642
- GCC_except_table6420
- GCC_except_table649
- GCC_except_table656
- GCC_except_table657
- GCC_except_table750
- GCC_except_table817
- GCC_except_table822
- GCC_except_table871
- GCC_except_table876
- GCC_except_table894
- GCC_except_table900
- GCC_except_table901
- GCC_except_table931
- GCC_except_table970
- GCC_except_table971
- GCC_except_table978
- _OBJC_IVAR_$_NEIKEv2PacketConstructor._index
- _OBJC_IVAR_$_NEIKEv2PacketConstructor._payloadVector
- ___block_descriptor_56_e8_32s40bs48r_e34_v20?0i8"NSObject<OS_nw_error>"12ls32l8s40l8r48l8
CStrings:
+ "%@ Ignoring old retransmission with message ID %u (lower edge %u)"
+ "%@ Rejecting reply with message ID %u beyond last request %u"
+ "%@ Rejecting stale reply with message ID %u (current request %u)"
+ "%@ Sending reply fragment %u/%u of length %zu with ID %u on %@\n"
+ "%@ Sending reply of length %zu with ID %u on %@\n"
+ "%@ Sending request fragment %u/%u of length %zu with ID %u on %@\n"
+ "%@ Sending request of length %zu with ID %u on %@\n"
+ "%@ received %s scoped declaration: %@"
+ "%@: [%s](uid:%d) is %s declaration for type=[%@]"
+ "%@: [%s](uid:%d) is fetching declaration keys for type [%@]"
+ "%@: [%s](uid:%d) is removing declaration with key [%@] and type [%@]"
+ "%@: saving %s scoped configuration [%@] with User UUID [%@]"
+ "%s called with null dispatch_data_get_size(data)"
+ "(system scoped)"
+ "(user scoped)"
+ "Aggregated payloads length overflow"
+ "Child SA proposals mix TLS and IPsec protocols"
+ "DeclarationScope"
+ "Encrypted payload data length overflow"
+ "Encrypted payload length overflow"
+ "Failed to construct data vector for IKE_INTERMEDIATE"
+ "Failed to construct encrypted fragment packet headers"
+ "Failed to construct encrypted packet headers"
+ "Failed to construct unencrypted packet headers"
+ "IKEv2 session configuration %s DDM sourced%s"
+ "IsDDMSystemScope"
+ "IsSystemScopedDDMCredentials"
+ "IsSystemScopedDDMIdentity"
+ "Packet construction state not finalized"
+ "Packet length overflow"
+ "Payload length overflow %@"
+ "Payload sub-header length too large (%zu > %u) %@"
+ "PvD retry already scheduled this cycle, ignoring duplicate (statusCode=%ld)"
+ "Request to write no plaintext with un-finalized construction state"
+ "Request to write plaintext (length %u) with finalized construction state"
+ "[self copyPreferredLocalSecIdentity]"
- "%@ Discarding stale fragment"
- "%@ Discarding stale reply"
- "%@ Discarding stale request"
- "%@ Discarding too new fragment"
- "%@ Sending reply fragment %u/%u of length %u with ID %u on %@\n"
- "%@ Sending reply of length %u with ID %u on %@\n"
- "%@ Sending request fragment %u/%u of length %u with ID %u on %@\n"
- "%@ Sending request of length %u with ID %u on %@\n"
- "%@ received declaration: %@"
- "%@: %s declaration for type=[%@]"
- "%@: fetching declaration keys for type [%@]"
- "%@: removing declaration with key [%@] and type [%@]"
- "%s called with null data.length"
- "Connection failed"
- "Construction state after processing fragment %u: Index %zu, Offset %zu"
- "Failed to get construct data vector for IKE_INTERMEDIATE"
- "IKEv2 session configuration %s DDM sourced"
- "Packet construction state not finalized: index %zu, offset %zu"
- "Request to write no plaintext with non-empty payload vector"
- "Request to write plaintext (length %u) with empty payload vector"
- "Request to write plaintext with finalized construction state"
- "[self copyLocalSecIdentity]"
- "isSourceDDM"
```
