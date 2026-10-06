## iTunesCloud

> `/System/Library/PrivateFrameworks/iTunesCloud.framework/iTunesCloud`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x4c40` | `0x53c0` | **`+0x780`** |
| `__DATA_DIRTY.__objc_data` | `0x3b10` | `0x33e0` | **`-0x730`** |
| `__TEXT.__text` | `0x3c08d0` | `0x3c0d48` | **`+0x478`** |
| `__AUTH_CONST.__objc_const` | `0x307c8` | `0x30900` | **`+0x138`** |
| `__DATA.__data` | `0x2fb8` | `0x3078` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0xf98` | `0x1058` | **`+0xc0`** |
| `__DATA_DIRTY.__data` | `0x1c0` | `0x108` | **`-0xb8`** |
| `__TEXT.__oslogstring` | `0x2098b` | `0x20a3c` | **`+0xb1`** |
| `__TEXT.__objc_methlist` | `0x1808c` | `0x18114` | **`+0x88`** |
| `__DATA.__bss` | `0x480` | `0x4d0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x1759a` | `0x175df` | **`+0x45`** |
| `__DATA_DIRTY.__bss` | `0x3d8` | `0x398` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xa2e0` | `0xa310` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x18418` | `0x18438` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x23e8` | `0x23fc` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0xd88` | `0xd90` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xbb8` | `0xbc0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6968` | `0x6970` | **`+0x8`** |

### Other Changes

```diff

-4026.100.69.0.0
+4026.100.72.0.0

-  Functions: 9990
-  Symbols:   17513
-  CStrings:  5383
+  Functions: 10002
+  Symbols:   17540
+  CStrings:  5386
Symbols:
+ +[ICUserProfileStore sharedStore]
+ -[ICMusicSubscriptionStatusMonitor _handleDefaultMediaUserProfileDidChange:]
+ -[ICUserProfileStore .cxx_destruct]
+ -[ICUserProfileStore _handleProfileStoreUpdate]
+ -[ICUserProfileStore _loadDefaultMediaUserProfileIfNeeded:]
+ -[ICUserProfileStore dealloc]
+ -[ICUserProfileStore init]
+ -[_ICContentKeyRequestItemMap beginKeyDiscovery]
+ -[_ICContentKeyRequestItemMap endKeyDiscovery]
+ -[_ICContentKeyRequestItemMap hasPendingKeyDiscovery]
+ GCC_except_table5560
+ GCC_except_table5608
+ GCC_except_table5632
+ GCC_except_table5673
+ GCC_except_table5674
+ GCC_except_table5747
+ GCC_except_table5765
+ GCC_except_table6025
+ GCC_except_table6032
+ GCC_except_table6040
+ GCC_except_table6052
+ GCC_except_table6053
+ GCC_except_table6054
+ GCC_except_table6055
+ GCC_except_table6060
+ GCC_except_table6065
+ GCC_except_table6070
+ GCC_except_table6081
+ GCC_except_table6096
+ GCC_except_table6098
+ GCC_except_table6122
+ GCC_except_table6156
+ GCC_except_table6188
+ GCC_except_table6201
+ GCC_except_table6208
+ GCC_except_table6209
+ GCC_except_table6269
+ GCC_except_table6272
+ GCC_except_table6286
+ GCC_except_table6309
+ GCC_except_table6344
+ GCC_except_table6347
+ GCC_except_table6350
+ GCC_except_table6451
+ GCC_except_table6665
+ GCC_except_table6672
+ GCC_except_table6846
+ GCC_except_table6850
+ GCC_except_table6852
+ GCC_except_table6879
+ GCC_except_table6925
+ GCC_except_table7098
+ GCC_except_table7230
+ GCC_except_table7350
+ GCC_except_table7361
+ GCC_except_table7384
+ GCC_except_table7462
+ GCC_except_table7477
+ GCC_except_table7500
+ GCC_except_table7511
+ GCC_except_table7555
+ GCC_except_table7556
+ GCC_except_table7557
+ GCC_except_table7558
+ GCC_except_table7559
+ GCC_except_table7600
+ GCC_except_table7618
+ GCC_except_table7673
+ GCC_except_table7682
+ GCC_except_table7689
+ GCC_except_table7736
+ GCC_except_table7755
+ GCC_except_table7788
+ GCC_except_table7846
+ GCC_except_table7847
+ GCC_except_table7860
+ GCC_except_table8279
+ GCC_except_table8283
+ GCC_except_table8287
+ GCC_except_table8309
+ GCC_except_table8316
+ GCC_except_table8327
+ GCC_except_table8332
+ GCC_except_table8367
+ GCC_except_table8370
+ GCC_except_table8441
+ GCC_except_table8486
+ GCC_except_table8534
+ GCC_except_table8563
+ GCC_except_table8568
+ GCC_except_table8570
+ GCC_except_table8572
+ GCC_except_table8604
+ GCC_except_table8736
+ GCC_except_table8744
+ GCC_except_table8749
+ GCC_except_table8764
+ GCC_except_table8772
+ GCC_except_table8816
+ GCC_except_table8965
+ GCC_except_table8969
+ GCC_except_table8971
+ GCC_except_table9009
+ GCC_except_table9012
+ GCC_except_table9019
+ GCC_except_table9022
+ GCC_except_table9245
+ GCC_except_table9255
+ GCC_except_table9313
+ GCC_except_table9400
+ GCC_except_table9405
+ GCC_except_table9645
+ _ICUserProfileStoreDefaultMediaUserDidChangeNotification
+ _OBJC_CLASS_$_ICUserProfileStore
+ _OBJC_IVAR_$_ICUserProfileStore._hasLoadedDefaultMediaUserProfile
+ _OBJC_IVAR_$_ICUserProfileStore._lock
+ _OBJC_IVAR_$_ICUserProfileStore._profileStoreObserver
+ _OBJC_IVAR_$_ICUserProfileStore._queue
+ _OBJC_IVAR_$__ICContentKeyRequestItemMap._pendingKeyDiscoveryCount
+ _OBJC_METACLASS_$_ICUserProfileStore
+ __OBJC_$_CLASS_METHODS_ICUserProfileStore
+ __OBJC_$_INSTANCE_METHODS_ICUserProfileStore
+ __OBJC_$_INSTANCE_VARIABLES_ICUserProfileStore
+ __OBJC_CLASS_RO_$_ICUserProfileStore
+ __OBJC_METACLASS_RO_$_ICUserProfileStore
+ ___26-[ICUserProfileStore init]_block_invoke
+ ___33+[ICUserProfileStore sharedStore]_block_invoke
+ ___47-[ICUserProfileStore _handleProfileStoreUpdate]_block_invoke
+ ___block_descriptor_56_e8_32s40s48w_e5_v8?0lw48l8s32l8s40l8
+ _sharedStore.sOnceToken
+ _sharedStore.sSharedProfileStore
- -[ICMusicSubscriptionStatusMonitor _handleHomeManagerPropertiesDidChange:]
- GCC_except_table5551
- GCC_except_table5599
- GCC_except_table5623
- GCC_except_table5664
- GCC_except_table5665
- GCC_except_table5738
- GCC_except_table5756
- GCC_except_table6016
- GCC_except_table6023
- GCC_except_table6031
- GCC_except_table6042
- GCC_except_table6043
- GCC_except_table6044
- GCC_except_table6045
- GCC_except_table6046
- GCC_except_table6056
- GCC_except_table6061
- GCC_except_table6072
- GCC_except_table6087
- GCC_except_table6089
- GCC_except_table6095
- GCC_except_table6147
- GCC_except_table6179
- GCC_except_table6192
- GCC_except_table6199
- GCC_except_table6200
- GCC_except_table6260
- GCC_except_table6263
- GCC_except_table6277
- GCC_except_table6300
- GCC_except_table6305
- GCC_except_table6311
- GCC_except_table6317
- GCC_except_table6442
- GCC_except_table6656
- GCC_except_table6663
- GCC_except_table6837
- GCC_except_table6841
- GCC_except_table6843
- GCC_except_table6870
- GCC_except_table6916
- GCC_except_table7089
- GCC_except_table7221
- GCC_except_table7338
- GCC_except_table7349
- GCC_except_table7372
- GCC_except_table7450
- GCC_except_table7465
- GCC_except_table7488
- GCC_except_table7499
- GCC_except_table7543
- GCC_except_table7544
- GCC_except_table7545
- GCC_except_table7546
- GCC_except_table7547
- GCC_except_table7588
- GCC_except_table7606
- GCC_except_table7658
- GCC_except_table7661
- GCC_except_table7677
- GCC_except_table7724
- GCC_except_table7743
- GCC_except_table7776
- GCC_except_table7834
- GCC_except_table7835
- GCC_except_table7848
- GCC_except_table8267
- GCC_except_table8271
- GCC_except_table8275
- GCC_except_table8297
- GCC_except_table8304
- GCC_except_table8315
- GCC_except_table8320
- GCC_except_table8355
- GCC_except_table8358
- GCC_except_table8429
- GCC_except_table8474
- GCC_except_table8522
- GCC_except_table8551
- GCC_except_table8556
- GCC_except_table8558
- GCC_except_table8560
- GCC_except_table8592
- GCC_except_table8724
- GCC_except_table8732
- GCC_except_table8737
- GCC_except_table8752
- GCC_except_table8760
- GCC_except_table8804
- GCC_except_table8953
- GCC_except_table8957
- GCC_except_table8959
- GCC_except_table8997
- GCC_except_table9000
- GCC_except_table9007
- GCC_except_table9010
- GCC_except_table9233
- GCC_except_table9243
- GCC_except_table9301
- GCC_except_table9388
- GCC_except_table9393
- GCC_except_table9633
- ___block_descriptor_64_e8_32s40s48w_e5_v8?0lw48l8s32l8s40l8
CStrings:
+ "%{public}@ Reloading user profiles for store update notification"
+ "%{public}@ [SKD] - Deferring renewal/revocation of key %{public}@ until in-flight asset key discovery completes"
+ "ICUserProfileStoreDefaultMediaUserDidChangeNotification"
+ "com.apple.iTunesCloud.ICUserProfileStore.queue"
- "Unexpected nil item for asset: %@"
```
