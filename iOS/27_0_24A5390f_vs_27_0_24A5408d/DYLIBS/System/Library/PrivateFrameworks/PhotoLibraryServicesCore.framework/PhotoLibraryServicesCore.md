## PhotoLibraryServicesCore

> `/System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/PhotoLibraryServicesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcb00c` | `0xcb61c` | **`+0x610`** |
| `__TEXT.__cstring` | `0x15d39` | `0x15f4c` | **`+0x213`** |
| `__AUTH_CONST.__cfstring` | `0x11ec0` | `0x12020` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0xb0b9` | `0xb0f7` | **`+0x3e`** |
| `__TEXT.__objc_methlist` | `0x8304` | `0x833c` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x35e8` | `0x35c8` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x3c60` | `0x3c40` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4c80` | `0x4ca0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x56fc` | `0x5710` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x3468` | `0x3478` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0xaa00` | `0xaa08` | **`+0x8`** |

### Other Changes

```diff

-910.33.102.0.0
+912.0.111.0.0

-  Functions: 3962
-  Symbols:   7890
-  CStrings:  3658
+  Functions: 3967
+  Symbols:   7891
+  CStrings:  3670
Symbols:
+ -[PLPhotoLibraryPathManager _pathsToExcludeFromAllDCIMBackups]
+ -[PLPhotoLibraryPathManager _pathsToExcludeFromICloudDCIMBackups]
+ -[PLPhotoLibraryPathManagerCore appLibraryContainerIdentifier]
+ GCC_except_table3078
+ GCC_except_table3086
+ GCC_except_table3239
+ GCC_except_table3241
+ GCC_except_table3243
+ GCC_except_table3247
+ GCC_except_table3264
+ GCC_except_table3349
+ GCC_except_table3474
+ GCC_except_table3545
+ GCC_except_table3552
+ GCC_except_table3605
+ GCC_except_table3608
+ GCC_except_table3614
+ GCC_except_table3617
+ GCC_except_table3620
+ GCC_except_table3623
+ GCC_except_table3629
+ GCC_except_table3651
+ GCC_except_table3672
+ GCC_except_table3675
+ GCC_except_table3684
+ GCC_except_table3697
+ GCC_except_table3715
+ GCC_except_table3723
+ GCC_except_table3725
+ GCC_except_table3734
+ GCC_except_table3740
+ GCC_except_table3745
+ GCC_except_table3748
+ GCC_except_table3755
+ GCC_except_table3758
+ GCC_except_table3765
+ GCC_except_table3768
+ GCC_except_table3771
+ GCC_except_table3778
+ GCC_except_table3781
+ GCC_except_table3784
+ GCC_except_table3787
+ GCC_except_table3798
+ GCC_except_table3812
+ GCC_except_table3815
+ GCC_except_table3859
+ GCC_except_table3883
+ GCC_except_table3888
+ GCC_except_table3890
+ GCC_except_table3891
+ GCC_except_table3896
+ GCC_except_table3897
+ GCC_except_table3906
+ GCC_except_table3919
+ GCC_except_table3924
+ GCC_except_table3931
+ GCC_except_table3936
- GCC_except_table3079
- GCC_except_table3085
- GCC_except_table3236
- GCC_except_table3238
- GCC_except_table3240
- GCC_except_table3244
- GCC_except_table3249
- GCC_except_table3346
- GCC_except_table3470
- GCC_except_table3537
- GCC_except_table3548
- GCC_except_table3601
- GCC_except_table3604
- GCC_except_table3610
- GCC_except_table3613
- GCC_except_table3616
- GCC_except_table3619
- GCC_except_table3625
- GCC_except_table3631
- GCC_except_table3668
- GCC_except_table3671
- GCC_except_table3680
- GCC_except_table3693
- GCC_except_table3711
- GCC_except_table3719
- GCC_except_table3721
- GCC_except_table3726
- GCC_except_table3736
- GCC_except_table3741
- GCC_except_table3744
- GCC_except_table3747
- GCC_except_table3754
- GCC_except_table3761
- GCC_except_table3764
- GCC_except_table3767
- GCC_except_table3770
- GCC_except_table3777
- GCC_except_table3780
- GCC_except_table3783
- GCC_except_table3786
- GCC_except_table3808
- GCC_except_table3811
- GCC_except_table3855
- GCC_except_table3878
- GCC_except_table3879
- GCC_except_table3880
- GCC_except_table3887
- GCC_except_table3889
- GCC_except_table3892
- GCC_except_table3902
- GCC_except_table3915
- GCC_except_table3920
- GCC_except_table3927
- GCC_except_table3932
- ___112-[PLPhotoLibraryPathManager setBackupExclusionAttributesForWellKnownLibrariesOrWithCreateOptions:andBackupType:]_block_invoke
- ___block_descriptor_32_e25_v32?0"NSString"8Q16^B24l
CStrings:
+ "Failed to set backup exclusion marker [all-DCIM], path: %@, error: %@"
+ "Failed to set backup exclusion marker [iCloud-DCIM], path: %@, error: %@"
+ "PLPhotosErrorAssetResourceUploadExtensionBaseURLDuplicate"
+ "PLPhotosErrorAssetResourceUploadExtensionBaseURLInvalid"
+ "PLPhotosErrorAssetResourceUploadExtensionBaseURLLimitExceeded"
+ "PLPhotosErrorAssetResourceUploadExtensionBaseURLMissing"
+ "PLPhotosErrorExtensionApplicationRecordMissing"
+ "PLPhotosErrorExtensionBundleRecordInvalid"
+ "PLPhotosErrorExtensionBundleRecordMissing"
+ "PLPhotosErrorExtensionPointIdentifierMismatch"
+ "PLPhotosErrorExtensionPointIdentifierMissing"
+ "PLPhotosErrorExtensionPointRecordMissing"
+ "PLPhotosErrorExtensionRecordMissing"
- "Failed to set backup exclusion marker [DCIM private caches], path: %@, error: %@"
```
