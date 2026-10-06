## CoreRoutine

> `/System/Library/PrivateFrameworks/CoreRoutine.framework/CoreRoutine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d484` | `0x6de58` | **`+0x9d4`** |
| `__AUTH_CONST.__objc_const` | `0xfdb0` | `0xff48` | **`+0x198`** |
| `__TEXT.__objc_methlist` | `0x8b90` | `0x8c58` | **`+0xc8`** |
| `__AUTH_CONST.__cfstring` | `0x64a0` | `0x6520` | **`+0x80`** |
| `__TEXT.__cstring` | `0x7657` | `0x76c3` | **`+0x6c`** |
| `__AUTH.__objc_data` | `0x15e0` | `0x1630` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x14b8` | `0x1508` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2018` | `0x2060` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x340` | `0x374` | **`+0x34`** |
| `__DATA_CONST.__objc_selrefs` | `0x2be0` | `0x2bf8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x91c` | `0x92c` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x540` | `0x548` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x4d0` | `0x4d8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x498` | `0x4a0` | **`+0x8`** |

### Other Changes

```diff

-1109.0.3.0.0
+1114.0.0.0.0

-  Functions: 3095
-  Symbols:   5461
-  CStrings:  1212
+  Functions: 3111
+  Symbols:   5494
+  CStrings:  1216
Symbols:
+ +[RTPeopleDiscoveryAdvertisement supportsSecureCoding]
+ -[RTPeopleDiscoveryAdvertisement .cxx_destruct]
+ -[RTPeopleDiscoveryAdvertisement address]
+ -[RTPeopleDiscoveryAdvertisement contactID]
+ -[RTPeopleDiscoveryAdvertisement copyWithZone:]
+ -[RTPeopleDiscoveryAdvertisement descriptionDictionary]
+ -[RTPeopleDiscoveryAdvertisement description]
+ -[RTPeopleDiscoveryAdvertisement encodeWithCoder:]
+ -[RTPeopleDiscoveryAdvertisement hash]
+ -[RTPeopleDiscoveryAdvertisement initWithAddress:rssi:scanDate:contactID:]
+ -[RTPeopleDiscoveryAdvertisement initWithCoder:]
+ -[RTPeopleDiscoveryAdvertisement init]
+ -[RTPeopleDiscoveryAdvertisement isEqual:]
+ -[RTPeopleDiscoveryAdvertisement rssi]
+ -[RTPeopleDiscoveryAdvertisement scanDate]
+ GCC_except_table457
+ GCC_except_table585
+ _OBJC_CLASS_$_RTPeopleDiscoveryAdvertisement
+ _OBJC_IVAR_$_RTPeopleDiscoveryAdvertisement._address
+ _OBJC_IVAR_$_RTPeopleDiscoveryAdvertisement._contactID
+ _OBJC_IVAR_$_RTPeopleDiscoveryAdvertisement._rssi
+ _OBJC_IVAR_$_RTPeopleDiscoveryAdvertisement._scanDate
+ _OBJC_METACLASS_$_RTPeopleDiscoveryAdvertisement
+ __OBJC_$_CLASS_METHODS_RTPeopleDiscoveryAdvertisement
+ __OBJC_$_CLASS_PROP_LIST_RTPeopleDiscoveryAdvertisement
+ __OBJC_$_INSTANCE_METHODS_RTPeopleDiscoveryAdvertisement
+ __OBJC_$_INSTANCE_VARIABLES_RTPeopleDiscoveryAdvertisement
+ __OBJC_$_PROP_LIST_RTPeopleDiscoveryAdvertisement
+ __OBJC_CLASS_PROTOCOLS_$_RTPeopleDiscoveryAdvertisement
+ __OBJC_CLASS_RO_$_RTPeopleDiscoveryAdvertisement
+ __OBJC_METACLASS_RO_$_RTPeopleDiscoveryAdvertisement
+ ___50-[RTRoutineManager fetchAuthorizedLocationStatus:]_block_invoke_4
+ ___block_descriptor_56_e8_32bs40r_e48_v24?0"RTAuthorizedLocationStatus"8"NSError"16lr40l8s32l8
+ ___block_descriptor_56_e8_32s40bs48r_e26_v24?08"RTTransaction"16lr48l8s32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e48_v24?0"RTAuthorizedLocationStatus"8"NSError"16ls32l8s40l8s48l8
- GCC_except_table584
- ___block_descriptor_64_e8_32s40s48bs_e48_v24?0"RTAuthorizedLocationStatus"8"NSError"16ls32l8s40l8s48l8
CStrings:
+ "Date"
+ "RSSI"
+ "RTRoutineManager.%@.proxyAcquisition"
+ "RTRoutineManager.fetchAuthorizedLocationStatus.xpcInvocation"
```
