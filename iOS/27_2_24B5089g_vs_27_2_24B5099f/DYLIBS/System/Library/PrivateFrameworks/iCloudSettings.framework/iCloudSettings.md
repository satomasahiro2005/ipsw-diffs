## iCloudSettings

> `/System/Library/PrivateFrameworks/iCloudSettings.framework/iCloudSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d94f8` | `0x1d9b7c` | **`+0x684`** |
| `__TEXT.__const` | `0x13364` | `0x13414` | **`+0xb0`** |
| `__AUTH_CONST.__const` | `0xc6c8` | `0xc728` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0xb0e4` | `0xb144` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x5e20` | `0x5e60` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x1453c` | `0x1457c` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x2f0c` | `0x2f44` | **`+0x38`** |
| `__TEXT.__cstring` | `0x669a` | `0x66ca` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x12a0` | `0x12c8` | **`+0x28`** |
| `__AUTH.__objc_data` | `0x4b28` | `0x4b40` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3190` | `0x31a8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x6ca8` | `0x6cc0` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x4410` | `0x4420` | **`+0x10`** |
| `__AUTH.__data` | `0x44e8` | `0x44f0` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x16a70` | `0x16a68` | **`-0x8`** |
| `__DATA.__common` | `0x320` | `0x318` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x7e8` | `0x7f0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x4d0` | `0x4d8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x414` | `0x41c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x944` | `0x948` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x84` | `0x88` | **`+0x4`** |

### Other Changes

```diff

-301.24.1.4.0
+301.24.1.6.0

-  Functions: 9241
-  Symbols:   5164
-  CStrings:  1730
+  Functions: 9248
+  Symbols:   5168
+  CStrings:  1732
Symbols:
+ -[ICSDataclassDetailSpecifierProvider _countOfAppsSyncingToDrive:]
+ -[ICSUbiquitySpecifierProvider visibleAppsUsingUbiquity]
+ ___56-[ICSUbiquitySpecifierProvider visibleAppsUsingUbiquity]_block_invoke
+ ___block_descriptor_40_e8_32s_e21_B24?0"NSString"8Q16ls32l8
+ ___block_descriptor_48_e8_32s40s_e43_v24?0"ICQAppsSyncingToDrive"8"NSError"16ls32l8s40l8
+ _symbolic $s14iCloudSettings24DataclassBundleProvidingP
+ _symbolic SaySo11PSSpecifierCG
- -[ICSUbiquitySpecifierProvider appsUsingUbiquity]
- ___72-[ICSDataclassDetailSpecifierProvider _fetchNumberOfAppsSyncingToDrive:]_block_invoke_3
- ___block_descriptor_64_e8_32s40s48s56s_e43_v24?0"ICQAppsSyncingToDrive"8"NSError"16ls32l8s40l8s48l8s56l8
CStrings:
+ "B24@?0@\"NSString\"8Q16"
+ "configureToggle(in:)"
```
