## CoreUtils

> `/System/Library/PrivateFrameworks/CoreUtils.framework/CoreUtils`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11252c` | `0x114a14` | **`+0x24e8`** |
| `__TEXT.__oslogstring` | `0x3deb` | `0x47ba` | **`+0x9cf`** |
| `__TEXT.__cstring` | `0x1d96b` | `0x1d530` | **`-0x43b`** |
| `__TEXT.__gcc_except_tab` | `0x19c0` | `0x1b14` | **`+0x154`** |
| `__AUTH_CONST.__const` | `0x2908` | `0x2808` | **`-0x100`** |
| `__TEXT.__objc_methlist` | `0x9e38` | `0x9ed0` | **`+0x98`** |
| `__TEXT.__const` | `0x2224` | `0x229c` | **`+0x78`** |
| `__DATA_CONST.__const` | `0x28f0` | `0x2960` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x5008` | `0x5070` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x3900` | `0x3968` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x138c0` | `0x13870` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0x44a0` | `0x44c0` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x240` | `0x258` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x14d8` | `0x14c8` | **`-0x10`** |
| `__AUTH.__data` | `0xa08` | `0xa00` | **`-0x8`** |

### Other Changes

```diff

-900.25.0.0.0
+900.37.0.0.0

-  Functions: 5734
-  Symbols:   10083
-  CStrings:  4808
+  Functions: 5749
+  Symbols:   10110
+  CStrings:  4816
Symbols:
+ +[CUPairingManager pairedPeersCountWithOptions:error:]
+ -[CUHomeKitManager _findPairedPeerWithContext:label:pairingIdentity:pairingTypes:error:]
+ -[CUPairedPeer pairingTypes]
+ -[CUPairedPeer setPairingTypes:]
+ -[CUPairingDaemon _findPairedPeerDirect:options:error:]
+ -[CUPairingSession managerEndpoint]
+ -[CUPairingSession setManagerEndpoint:]
+ -[CUSystemMonitor _netInterfaceState]
+ -[CUSystemMonitorImp _netInterfaceMonitorHandleActivated:]
+ -[CUSystemMonitorImp _netInterfaceMonitorHandleFlagsChanged:]
+ -[CUSystemMonitorImp _netInterfaceMonitorHandlePrimaryIPChanged:]
+ -[CUSystemMonitorImp _netInterfaceMonitorHandlePrimaryNetworkChanged:]
+ -[CUSystemMonitorImp _netInterfaceMonitorStartUseNW:]
+ -[CUSystemMonitorImp _netInterfaceMonitorStopUseNW:]
+ GCC_except_table1339
+ GCC_except_table1374
+ GCC_except_table1379
+ GCC_except_table1380
+ GCC_except_table1383
+ GCC_except_table1430
+ GCC_except_table1431
+ GCC_except_table1462
+ GCC_except_table1465
+ GCC_except_table1471
+ GCC_except_table1476
+ GCC_except_table1479
+ GCC_except_table1527
+ GCC_except_table1528
+ GCC_except_table2263
+ GCC_except_table2264
+ GCC_except_table2287
+ GCC_except_table2332
+ GCC_except_table2415
+ GCC_except_table2439
+ GCC_except_table2476
+ GCC_except_table2480
+ GCC_except_table2587
+ GCC_except_table2588
+ GCC_except_table2591
+ GCC_except_table2598
+ GCC_except_table2602
+ GCC_except_table2605
+ GCC_except_table2608
+ GCC_except_table2611
+ GCC_except_table2618
+ GCC_except_table2621
+ GCC_except_table2635
+ GCC_except_table2696
+ GCC_except_table3026
+ GCC_except_table3027
+ GCC_except_table3115
+ GCC_except_table3137
+ GCC_except_table3175
+ GCC_except_table3222
+ GCC_except_table3223
+ GCC_except_table3225
+ GCC_except_table3248
+ GCC_except_table3257
+ GCC_except_table3532
+ GCC_except_table3588
+ GCC_except_table3961
+ GCC_except_table4009
+ GCC_except_table4274
+ GCC_except_table4332
+ GCC_except_table4347
+ GCC_except_table4528
+ GCC_except_table4530
+ GCC_except_table4532
+ GCC_except_table4555
+ GCC_except_table4629
+ GCC_except_table4631
+ GCC_except_table4634
+ GCC_except_table4640
+ GCC_except_table4644
+ GCC_except_table4646
+ GCC_except_table4658
+ GCC_except_table4665
+ GCC_except_table4670
+ GCC_except_table4674
+ GCC_except_table4675
+ GCC_except_table4676
+ GCC_except_table4677
+ GCC_except_table4679
+ GCC_except_table4681
+ GCC_except_table4707
+ GCC_except_table4711
+ GCC_except_table4713
+ GCC_except_table4714
+ GCC_except_table4716
+ GCC_except_table4717
+ GCC_except_table4718
+ GCC_except_table4720
+ GCC_except_table5303
+ GCC_except_table5307
+ GCC_except_table5312
+ GCC_except_table5329
+ GCC_except_table5338
+ GCC_except_table5587
+ GCC_except_table5588
+ GCC_except_table5601
+ _OBJC_IVAR_$_CUPairedPeer._pairingTypes
+ _OBJC_IVAR_$_CUPairingSession._managerEndpoint
+ _OBJC_IVAR_$_CUSystemMonitorImp._netInterfaceNW
+ _OBJC_IVAR_$_CUSystemMonitorImp._netInterfaceSC
+ _PairingSessionSetDispatchQueue
+ _PairingSessionSetManagerEndpoint
+ __AddIRKInfoTLV
+ __UpdatePeerIRKFromTLV
+ ___53-[CUSystemMonitorImp _netInterfaceMonitorStartUseNW:]_block_invoke
+ ___53-[CUSystemMonitorImp _netInterfaceMonitorStartUseNW:]_block_invoke_2
+ ___53-[CUSystemMonitorImp _netInterfaceMonitorStartUseNW:]_block_invoke_3
+ ___53-[CUSystemMonitorImp _netInterfaceMonitorStartUseNW:]_block_invoke_4
+ ___58-[CUSystemMonitorImp _netInterfaceMonitorHandleActivated:]_block_invoke
+ ___58-[CUSystemMonitorImp _netInterfaceMonitorHandleActivated:]_block_invoke_2
+ ___58-[CUSystemMonitorImp _netInterfaceMonitorHandleActivated:]_block_invoke_3
+ ___58-[CUSystemMonitorImp _netInterfaceMonitorHandleActivated:]_block_invoke_4
+ ___58-[CUSystemMonitorImp _netInterfaceMonitorHandleActivated:]_block_invoke_5
+ ___58-[CUSystemMonitorImp _netInterfaceMonitorHandleActivated:]_block_invoke_6
+ ___61-[CUSystemMonitorImp _netInterfaceMonitorHandleFlagsChanged:]_block_invoke
+ ___61-[CUSystemMonitorImp _netInterfaceMonitorHandleFlagsChanged:]_block_invoke_2
+ ___65-[CUSystemMonitorImp _netInterfaceMonitorHandlePrimaryIPChanged:]_block_invoke
+ ___65-[CUSystemMonitorImp _netInterfaceMonitorHandlePrimaryIPChanged:]_block_invoke_2
+ ___70-[CUSystemMonitorImp _netInterfaceMonitorHandlePrimaryNetworkChanged:]_block_invoke
+ ___70-[CUSystemMonitorImp _netInterfaceMonitorHandlePrimaryNetworkChanged:]_block_invoke_2
+ ____PairingSessionUpdatePeerPairingManager_block_invoke
+ ____UpdatePeerIRKFromTLV_block_invoke
+ ____UpdatePeerIRKFromTLV_block_invoke_2
+ ___block_descriptor_33_e25_B16?0"CUSystemMonitor"8l
+ ___block_descriptor_41_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_56_e8_32s40s48bs_e17_v16?0"NSError"8ls32l8s40l8s48l8
+ ___block_descriptor_56_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
+ ___destructor_8_s0_s72_s80_s96
- -[CUBluetoothClient _btDeviceWithID:error:]
- -[CUHomeKitManager _findPairedPeerWithContext:label:pairingIdentity:error:]
- -[CUSystemMonitorImp _netInterfaceMonitorStart]
- -[CUSystemMonitorImp _netInterfaceMonitorStop]
- GCC_except_table1341
- GCC_except_table1376
- GCC_except_table1381
- GCC_except_table1382
- GCC_except_table1385
- GCC_except_table1432
- GCC_except_table1433
- GCC_except_table1464
- GCC_except_table1467
- GCC_except_table1473
- GCC_except_table1478
- GCC_except_table1481
- GCC_except_table1529
- GCC_except_table1530
- GCC_except_table2265
- GCC_except_table2266
- GCC_except_table2289
- GCC_except_table2334
- GCC_except_table2417
- GCC_except_table2441
- GCC_except_table2478
- GCC_except_table2482
- GCC_except_table2589
- GCC_except_table2592
- GCC_except_table2595
- GCC_except_table2600
- GCC_except_table2603
- GCC_except_table2606
- GCC_except_table2609
- GCC_except_table2612
- GCC_except_table2619
- GCC_except_table2622
- GCC_except_table2636
- GCC_except_table2697
- GCC_except_table3022
- GCC_except_table3023
- GCC_except_table3111
- GCC_except_table3133
- GCC_except_table3167
- GCC_except_table3215
- GCC_except_table3218
- GCC_except_table3221
- GCC_except_table3244
- GCC_except_table3249
- GCC_except_table3580
- GCC_except_table4001
- GCC_except_table4266
- GCC_except_table4324
- GCC_except_table4331
- GCC_except_table4516
- GCC_except_table4520
- GCC_except_table4522
- GCC_except_table4547
- GCC_except_table4621
- GCC_except_table4622
- GCC_except_table4623
- GCC_except_table4624
- GCC_except_table4626
- GCC_except_table4628
- GCC_except_table4650
- GCC_except_table4657
- GCC_except_table4659
- GCC_except_table4660
- GCC_except_table4662
- GCC_except_table4663
- GCC_except_table4664
- GCC_except_table4666
- GCC_except_table4669
- GCC_except_table4673
- GCC_except_table4682
- GCC_except_table4683
- GCC_except_table4686
- GCC_except_table4687
- GCC_except_table4689
- GCC_except_table4692
- GCC_except_table4701
- GCC_except_table5294
- GCC_except_table5305
- GCC_except_table5315
- GCC_except_table5324
- GCC_except_table5572
- GCC_except_table5573
- GCC_except_table5586
- _OBJC_IVAR_$_CUSystemMonitorImp._netFlags
- _OBJC_IVAR_$_CUSystemMonitorImp._netInterfaceMonitor
- _OBJC_IVAR_$_CUSystemMonitorImp._primaryIPIsCellular
- _OBJC_IVAR_$_CUSystemMonitorImp._primaryIPv4Addr
- _OBJC_IVAR_$_CUSystemMonitorImp._primaryIPv4NetworkSignature
- _OBJC_IVAR_$_CUSystemMonitorImp._primaryIPv6Addr
- _OBJC_IVAR_$_CUSystemMonitorImp._primaryIPv6NetworkSignature
- _OBJC_IVAR_$_CUSystemMonitorImp._primaryNetworkSignature
- ___29-[CUSystemMonitorImp _update]_block_invoke_27
- ___47-[CUSystemMonitorImp _netInterfaceMonitorStart]_block_invoke
- ___47-[CUSystemMonitorImp _netInterfaceMonitorStart]_block_invoke_2
- ___47-[CUSystemMonitorImp _netInterfaceMonitorStart]_block_invoke_3
- ___47-[CUSystemMonitorImp _netInterfaceMonitorStart]_block_invoke_4
- ___47-[CUSystemMonitorImp _netInterfaceMonitorStart]_block_invoke_5
- ___47-[CUSystemMonitorImp _netInterfaceMonitorStart]_block_invoke_6
- ___block_descriptor_76_e8_32s40s_e5_v8?0ls32l8s40l8
- _initBTDeviceFromAddress
- _softLinkBTDeviceFromAddress
CStrings:
+ "### Error on wait for close: %{public}@\n"
+ "### Error: CID 0x%08X, Peer %s, %{public}@\n"
+ "### FindPairedPeer failed: id=%@, duration=%llu ms, error=%@"
+ "### PairVerify update peer IRK failed: %@"
+ "### Publish L2CAP channel failed: %@"
+ "### SavePeer failed: peer=%@, error=%@"
+ "### Set SO_NOADDRERR failed: %{public}@"
+ "### Set TCP timeout to %d seconds failed: %{public}@\n"
+ ", %@ %@"
+ "-[CUHomeKitManager _findPairedPeerWithContext:label:pairingIdentity:pairingTypes:error:]"
+ "BOOL _PairingSessionUpdatePeerPairingManager(PairingSessionRef, CUPairedPeer *__strong, NSError *__autoreleasing *)"
+ "CUPairingUpdatePeer"
+ "Connect failed: CID 0x%08X, Peer %s, %{public}@\n"
+ "FindPairedPeer found: id=%@, label=%@, types=%@, duration=%llu ms\n"
+ "FindPairedPeer found: id=%@, label=HAP, types=%@, duration=%llu ms\n"
+ "FindPairedPeer found: id=%@, types=%@, duration=%llu ms"
+ "Get Keychain items error"
+ "Get Keychain items no array"
+ "Get Keychain items non-array"
+ "OPACK decode non-array"
+ "OPACK decode non-number"
+ "PairVerify update peer IRK: id=%@, IRK=%ld bytes"
+ "Published L2CAP channel with PSM 0x%04X"
+ "Request written: CID 0x%08X, Header %zu bytes, Body %zu bytes, Type '%s'\n"
+ "SavePeer daemon failed"
+ "SavePeer manager timeout"
+ "Socket events: raw 0x%llX, flags %{public}@"
+ "[%llu] ### Family bad member type: %@"
+ "[%llu] ### Family get members failed: %@"
+ "[%llu] ### Location visit no bundle"
+ "[%llu] ### MeDevice check failed: %@"
+ "[%llu] ### Motion orientation failed: %@"
+ "[%llu] ### Region monitor CTServerConnectionCreate failed"
+ "[%llu] ### Region monitor LOI fetch failed: %@"
+ "[%llu] ### Region monitor get CT subscription context failed: %@"
+ "[%llu] ### Region monitor get MCC failed: MCC %@, %@"
+ "[%llu] ### SCDynamicStoreCreate failed: %@"
+ "[%llu] ### SCDynamicStoreSetDispatchQueue failed: %@"
+ "[%llu] ### SCDynamicStoreSetNotificationKeys failed: %@"
+ "[%llu] ### ScreenState no monitor"
+ "[%llu] ### ScreenState no monitor config"
+ "[%llu] ### WiFi monitoring start failed: %@"
+ "[%llu] Active calls changed: %d -> %d"
+ "[%llu] Active calls unchanged (%d)"
+ "[%llu] Bluetooth address changed: %@ -> %@"
+ "[%llu] Bluetooth address monitor start"
+ "[%llu] Bluetooth address monitor stop"
+ "[%llu] Bluetooth address unchanged: %@"
+ "[%llu] Call flags changed: %@ -> %@"
+ "[%llu] Call flags unchanged: %@"
+ "[%llu] Call info changed: incoming connected %d -> %d, incoming unconnected %d -> %d, outgoing connected %d -> %d, outgoing unconnected %d -> %d"
+ "[%llu] Call info unchanged: incoming connected %d, incoming unconnected %d, outgoing connected %d, outgoing unconnected %d"
+ "[%llu] Call monitoring start"
+ "[%llu] Call monitoring stop"
+ "[%llu] Calls initial: active %d, connected %d, call flags %@"
+ "[%llu] Connected calls changed: %d -> %d"
+ "[%llu] Connected calls unchanged (%d)"
+ "[%llu] Family get members %s"
+ "[%llu] Family get members skipped when setup needs to run"
+ "[%llu] Family initial: %d family member(s)"
+ "[%llu] Family monitoring start"
+ "[%llu] Family monitoring stop"
+ "[%llu] Family re-check on PrimaryAppleID active"
+ "[%llu] Family retry on network change: IPv4 %@, IPv6 %@"
+ "[%llu] Family setup state changed: %llu"
+ "[%llu] Family updated"
+ "[%llu] Family updated: %d family member(s)"
+ "[%llu] FirstUnlock changed: No -> Yes"
+ "[%llu] FirstUnlock initial: %s"
+ "[%llu] FirstUnlock monitoring start"
+ "[%llu] FirstUnlock monitoring stop"
+ "[%llu] FirstUnlock monitoring stop after unlock"
+ "[%llu] FirstUnlock unchanged (No)"
+ "[%llu] Location authorization changed: %d"
+ "[%llu] Location updated locations: %d"
+ "[%llu] Location visit arrived: %s, confidence %f"
+ "[%llu] Location visit changed: %@ -> %@"
+ "[%llu] Location visit departed: %s, confidence %f"
+ "[%llu] Location visit failed: %@"
+ "[%llu] Location visit monitoring start: %f"
+ "[%llu] Location visit monitoring stop"
+ "[%llu] Location visit unchanged: %@"
+ "[%llu] Location visited: %s, confidence %f"
+ "[%llu] Manatee State unchanged: %s, error=%@"
+ "[%llu] Manatee monitoring start"
+ "[%llu] Manatee monitoring stop"
+ "[%llu] Manatee read: %s, %@"
+ "[%llu] Manatee retry timer cancel"
+ "[%llu] Manatee retry timer fired"
+ "[%llu] Manatee retry timer start: %@"
+ "[%llu] MeDevice changed: FMF <%@>, IDS <%@>, Name '%@', Me %s"
+ "[%llu] MeDevice check"
+ "[%llu] MeDevice device list changed"
+ "[%llu] MeDevice device retry notification"
+ "[%llu] MeDevice initial: FMF <%@>, IDS <%@>, Name '%@', Me %s"
+ "[%llu] MeDevice me device changed"
+ "[%llu] MeDevice monitoring start"
+ "[%llu] MeDevice monitoring start (FML)"
+ "[%llu] MeDevice monitoring stop"
+ "[%llu] MeDevice monitoring stop (FML)"
+ "[%llu] MeDevice override: IDS %@"
+ "[%llu] MeDevice provided device info, but reported an error? : %@"
+ "[%llu] MeDevice retry timer disabled on unsupported device"
+ "[%llu] MeDevice retry timer fired"
+ "[%llu] MeDevice retry timer start"
+ "[%llu] MeDevice retry timer stop"
+ "[%llu] MeDevice unchanged: FMF <%@>, IDS <%@>, Name '%@', Me %s"
+ "[%llu] MeDevice updated: fml=<%@>, ids=<%@>, name='%@', isThisDevice=%s"
+ "[%llu] Motion changed: %@ -> %@, confidence %s"
+ "[%llu] Motion monitor start"
+ "[%llu] Motion monitor stop"
+ "[%llu] Motion orientation unchanged: %s"
+ "[%llu] Motion orientation: %s -> %s"
+ "[%llu] Motion unchanged: %@, confidence %s"
+ "[%llu] NetInterface monitor activated: flags=%@, IPv4=%@, IPv4Sig=%@, IPv6=%@, IPv6Sig=%@, scSig=%@, cellular=%s, useNW=%s"
+ "[%llu] NetInterface monitor flags changed: flags=%@, useNW=%s"
+ "[%llu] NetInterface monitor primaryIP changed: IPv4=%@, IPv4Sig=%@, IPv6=%@, IPv6Sig=%@, cellular=%s, useNW=%s"
+ "[%llu] NetInterface monitor primaryNetwork changed: signature=%@, useNW=%s"
+ "[%llu] NetInterface monitoring start: useNW=%s"
+ "[%llu] NetInterface monitoring stop: useNW=%s"
+ "[%llu] NetInterfaces changed: %@"
+ "[%llu] PowerUnlimited changed: %s -> %s"
+ "[%llu] PowerUnlimited initial: %s"
+ "[%llu] PowerUnlimited monitoring start"
+ "[%llu] PowerUnlimited monitoring stop"
+ "[%llu] PowerUnlimited unchanged (%s)"
+ "[%llu] PrimaryAppleID change notification"
+ "[%llu] PrimaryAppleID changed: %@, HSA2 %s -> %@, HSA2 %s"
+ "[%llu] PrimaryAppleID initial: %@, HSA2 %s"
+ "[%llu] PrimaryAppleID unchanged (%@, HSA2 %s)"
+ "[%llu] Region changed: MCC %@, ISO %@"
+ "[%llu] Region monitor CopyISOForMCC: %@, ISO %@, error %d/%d"
+ "[%llu] Region monitor LOI fetch completed: %d total"
+ "[%llu] Region monitor LOI fetch start %s"
+ "[%llu] Region monitor LOI none found"
+ "[%llu] Region monitor cell update: %d items"
+ "[%llu] Region monitor get CT subscription context"
+ "[%llu] Region monitor get MCC"
+ "[%llu] Region monitor mapping %@ -> null (get)"
+ "[%llu] Region monitor mapping %d -> null (update)"
+ "[%llu] Region monitor start"
+ "[%llu] Region monitor stop"
+ "[%llu] Region routine changed: Country %@, State %@"
+ "[%llu] Region routine unchanged: Country %@, State %@"
+ "[%llu] Region unchanged: MCC %@, ISO %@"
+ "[%llu] Rotating identifier changed timer: %@ -> %@"
+ "[%llu] Rotating identifier monitor start: %@"
+ "[%llu] Rotating identifier monitor stop"
+ "[%llu] ScreenLocked changed: %s -> %s"
+ "[%llu] ScreenLocked initial: %s"
+ "[%llu] ScreenLocked monitoring start"
+ "[%llu] ScreenLocked monitoring stop"
+ "[%llu] ScreenLocked unchanged (%s)"
+ "[%llu] ScreenState changed: %@ -> %@ (raw %d)"
+ "[%llu] ScreenState monitor start"
+ "[%llu] ScreenState monitor stop"
+ "[%llu] ScreenState update no layout/backlight"
+ "[%llu] SystemConfig monitoring add: %@"
+ "[%llu] SystemConfig monitoring remove: %@"
+ "[%llu] SystemConfig monitoring start"
+ "[%llu] SystemConfig monitoring stop"
+ "[%llu] SystemConfig unknown key changed: '%@'"
+ "[%llu] SystemConfig watch: Keys %@, Patterns %@"
+ "[%llu] SystemLockState changed: %s -> %s"
+ "[%llu] SystemLockState initial: %s"
+ "[%llu] SystemLockState monitoring start"
+ "[%llu] SystemLockState monitoring stop"
+ "[%llu] SystemLockState unchanged: %s"
+ "[%llu] SystemName changed: '%@' -> '%@'"
+ "[%llu] SystemName initial: '%@'"
+ "[%llu] SystemName unchanged '%@'"
+ "[%llu] SystemUI changed: %@, diff %@"
+ "[%llu] SystemUI monitoring start"
+ "[%llu] SystemUI monitoring stop"
+ "[%llu] SystemUI unknown identifier: '%@' / '%@'"
+ "[%llu] TUCallCenter changed"
+ "[%llu] WiFi monitoring start"
+ "[%llu] WiFi monitoring stop"
+ "[%llu] WiFi state changed: %s -> %s, %@"
+ "[%llu] WiFi state initial: %s, %@"
+ "[%llu] WiFi state unchanged: %s, %@"
+ "ccspake_verifier_initialize failed: %d"
+ "null"
+ "pairingTypes"
+ "void _UpdatePeerIRKFromTLV(PairingSessionRef, const uint8_t *, const uint8_t *)"
- "### Error on wait for close: %#m\n"
- "### Error: CID 0x%08X, Peer %s, %#m\n"
- "### Family bad member type: %@"
- "### Family get members failed: %@"
- "### Location visit no bundle"
- "### MeDevice check failed: %@"
- "### Motion orientation failed: %@"
- "### Publish L2CAP channel failed: %{error}\n"
- "### Region monitor CTServerConnectionCreate failed"
- "### Region monitor LOI fetch failed: %@"
- "### Region monitor get CT subscription context failed: %@"
- "### Region monitor get MCC failed: MCC %@, %@"
- "### SCDynamicStoreCreate failed: %@"
- "### SCDynamicStoreSetDispatchQueue failed: %@"
- "### SCDynamicStoreSetNotificationKeys failed: %@"
- "### ScreenState no monitor"
- "### ScreenState no monitor config"
- "### Set SO_NOADDRERR failed: %#m"
- "### WiFi monitoring start failed: %@"
- "-[CUHomeKitManager _findPairedPeerWithContext:label:pairingIdentity:error:]"
- "Active calls changed: %d -> %d"
- "Active calls unchanged (%d)"
- "BTDeviceFromAddress"
- "BTDeviceFromAddress failed"
- "BTDeviceFromIdentifier failed"
- "Bad device ID UTF-8: '%@'"
- "Bad device ID format: '%s'"
- "Bluetooth address changed: %@ -> %@"
- "Bluetooth address monitor start"
- "Bluetooth address monitor stop"
- "Bluetooth address unchanged: %@"
- "Call flags changed: %@ -> %@"
- "Call flags unchanged: %@"
- "Call info changed: incoming connected %d -> %d, incoming unconnected %d -> %d, outcoming connected %d -> %d, outcoming unconnected %d -> %d"
- "Call info unchanged: incoming connected %d, incoming unconnected %d, outcoming connected %d, outcoming unconnected %d"
- "Call monitoring start"
- "Call monitoring stop"
- "Calls initial: active %d, connected %d, call flags %@"
- "Connect failed: CID 0x%08X, Peer %s, %#m\n"
- "Connected calls changed: %d -> %d"
- "Connected calls unchanged (%d)"
- "Family get members %s"
- "Family get members skipped when setup needs to run"
- "Family initial: %d family member(s)"
- "Family monitoring start"
- "Family monitoring stop"
- "Family re-check on PrimaryAppleID active"
- "Family retry on network change: IPv4 %@, IPv6 %@"
- "Family setup state changed: %llu"
- "Family updated"
- "Family updated: %d family member(s)"
- "FindPairedPeer found: '%@', %@, %llu ms\n"
- "FindPairedPeer found: '%@', HAP, %llu ms\n"
- "FirstUnlock changed: No -> Yes"
- "FirstUnlock initial: %s"
- "FirstUnlock monitoring start"
- "FirstUnlock monitoring stop"
- "FirstUnlock monitoring stop after unlock"
- "FirstUnlock unchanged (No)"
- "Location authorization changed: %d"
- "Location updated locations: %d"
- "Location visit arrived: %s, confidence %f"
- "Location visit changed: %@ -> %@"
- "Location visit departed: %s, confidence %f"
- "Location visit failed: %@"
- "Location visit monitoring start: %f"
- "Location visit monitoring stop"
- "Location visit unchanged: %@"
- "Location visited: %s, confidence %f"
- "Manatee State unchanged: %s, error=%@"
- "Manatee monitoring start"
- "Manatee monitoring stop"
- "Manatee read: %s, %@"
- "Manatee retry timer cancel"
- "Manatee retry timer fired"
- "Manatee retry timer start: %@"
- "MeDevice changed: FMF <%@>, IDS <%@>, Name '%@', Me %s"
- "MeDevice check"
- "MeDevice device list changed"
- "MeDevice device retry notification"
- "MeDevice initial: FMF <%@>, IDS <%@>, Name '%@', Me %s"
- "MeDevice me device changed"
- "MeDevice monitoring start"
- "MeDevice monitoring start (FML)"
- "MeDevice monitoring stop"
- "MeDevice monitoring stop (FML)"
- "MeDevice override: IDS %@"
- "MeDevice provided device info, but reported an error? : %@"
- "MeDevice retry timer disabled on unsupported device"
- "MeDevice retry timer fired"
- "MeDevice retry timer start"
- "MeDevice retry timer stop"
- "MeDevice unchanged: FMF <%@>, IDS <%@>, Name '%@', Me %s"
- "MeDevice updated: fml=<%@>, ids=<%@>, name='%@', isThisDevice=%s"
- "Motion changed: %@ -> %@, confidence %s"
- "Motion monitor start"
- "Motion monitor stop"
- "Motion orientation unchanged: %s"
- "Motion orientation: %s -> %s"
- "Motion unchanged: %@, confidence %s"
- "NetInterface initial: flags=%@, IPv4=%@, IPv4Sig=%@, IPv6=%@, IPv6Sig=%@, scSig=%@, cellular=%s"
- "NetInterface monitoring start: useNW=%s"
- "NetInterface monitoring stop"
- "NetInterfaces changed: %@"
- "Network interface flags changed: %@"
- "OSStatus HTTPClientDetach(HTTPClientRef, HTTPClientDetachHandler_f, void *, void *, void *)"
- "OSStatus HTTPClientSendBinaryBytes(HTTPClientRef, HTTPMessageFlags, uint8_t, const void *, size_t, HTTPMessageBinaryCompletion_f, void *)"
- "PowerUnlimited changed: %s -> %s"
- "PowerUnlimited initial: %s"
- "PowerUnlimited monitoring start"
- "PowerUnlimited monitoring stop"
- "PowerUnlimited unchanged (%s)"
- "PrimaryAppleID change notification"
- "PrimaryAppleID changed: %@, HSA2 %s -> %@, HSA2 %s"
- "PrimaryAppleID initial: %@, HSA2 %s"
- "PrimaryAppleID unchanged (%@, HSA2 %s)"
- "PrimaryIP changed: IPv4=%@, IPv4Sig=%@, IPv6=%@, IPv6Sig=%@, cellular=%s"
- "PrimaryNetwork changed: %@"
- "Published L2CAP channel with PSM 0x%04X\n"
- "Region changed: MCC %@, ISO %@"
- "Region monitor CopyISOForMCC: %@, ISO %@, error %d/%d"
- "Region monitor LOI fetch completed: %d total"
- "Region monitor LOI fetch start %s"
- "Region monitor LOI none found"
- "Region monitor cell update: %d items"
- "Region monitor get CT subscription context"
- "Region monitor get MCC"
- "Region monitor mapping %@ -> null (get)"
- "Region monitor mapping %d -> null (update)"
- "Region monitor start"
- "Region monitor stop"
- "Region routine changed: Country %@, State %@"
- "Region routine unchanged: Country %@, State %@"
- "Region unchanged: MCC %@, ISO %@"
- "Request written: CID 0x%08X, Header %zu bytes, Body %zu bytes%?{end}, Type %'s\n"
- "Rotating identifier changed timer: %@ -> %@"
- "Rotating identifier monitor start: %@"
- "Rotating identifier monitor stop"
- "ScreenLocked changed: %s -> %s"
- "ScreenLocked initial: %s"
- "ScreenLocked monitoring start"
- "ScreenLocked monitoring stop"
- "ScreenLocked unchanged (%s)"
- "ScreenState changed: %@ -> %@ (raw %d)"
- "ScreenState monitor start"
- "ScreenState monitor stop"
- "ScreenState update no layout/backlight"
- "Socket events: raw 0x%llX, flags %#{flags}"
- "SystemConfig monitoring add: %@"
- "SystemConfig monitoring remove: %@"
- "SystemConfig monitoring start"
- "SystemConfig monitoring stop"
- "SystemConfig unknown key changed: '%@'"
- "SystemConfig watch: Keys %@, Patterns %@"
- "SystemLockState changed: %s -> %s"
- "SystemLockState initial: %s"
- "SystemLockState monitoring start"
- "SystemLockState monitoring stop"
- "SystemLockState unchanged: %s"
- "SystemName changed: '%@' -> '%@'"
- "SystemName initial: '%@'"
- "SystemName unchanged '%@'"
- "SystemUI changed: %@, diff %@"
- "SystemUI monitoring start"
- "SystemUI monitoring stop"
- "SystemUI unknown identifier: '%@' / '%@'"
- "TUCallCenter changed"
- "WiFi monitoring start"
- "WiFi monitoring stop"
- "WiFi state changed: %s -> %s, %@"
- "WiFi state initial: %s, %@"
- "WiFi state unchanged: %s, %@"
- "void HTTPClientSetTimeout(HTTPClientRef, int)"
- "void _HTTPClientConnectHandler(SocketRef, OSStatus, void *)"
- "void _HTTPClientErrorHandler(HTTPClientRef, OSStatus)"
- "void _HTTPClientRunStateMachine(HTTPClientRef)"
- "void _HTTPClientSocketEventsHandler(void *)"
```
