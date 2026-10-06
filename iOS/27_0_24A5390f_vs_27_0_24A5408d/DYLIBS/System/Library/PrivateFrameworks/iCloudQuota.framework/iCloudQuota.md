## iCloudQuota

> `/System/Library/PrivateFrameworks/iCloudQuota.framework/iCloudQuota`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77298` | `0x7be10` | **`+0x4b78`** |
| `__TEXT.__eh_frame` | `0x1160` | `0x1500` | **`+0x3a0`** |
| `__AUTH_CONST.__objc_const` | `0xb388` | `0xb5b0` | **`+0x228`** |
| `__TEXT.__oslogstring` | `0x8799` | `0x8999` | **`+0x200`** |
| `__TEXT.__const` | `0x1198` | `0x1378` | **`+0x1e0`** |
| `__AUTH_CONST.__const` | `0x1298` | `0x1450` | **`+0x1b8`** |
| `__AUTH.__data` | `0x490` | `0x5f0` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x1d70` | `0x1ec0` | **`+0x150`** |
| `__TEXT.__constg_swiftt` | `0x678` | `0x788` | **`+0x110`** |
| `__TEXT.__swift5_typeref` | `0x71c` | `0x7f8` | **`+0xdc`** |
| `__AUTH.__objc_data` | `0x15b0` | `0x1678` | **`+0xc8`** |
| `__TEXT.__swift5_fieldmd` | `0x320` | `0x3c8` | **`+0xa8`** |
| `__TEXT.__swift5_capture` | `0x32c` | `0x39c` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0xc20` | `0xc80` | **`+0x60`** |
| `__TEXT.__cstring` | `0x4ff0` | `0x5050` | **`+0x60`** |
| `__DATA.__data` | `0x558` | `0x5a8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x597c` | `0x59cc` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x2a1` | `0x2f1` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x3060` | `0x3088` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1e48` | `0x1e68` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0xc0` | `0xe0` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x64` | `0x84` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x64` | `0x80` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x810` | `0x828` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x3a0` | `0x3b8` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x4c` | `0x5c` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x8c` | `0x94` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x14` | `0x1c` | **`+0x8`** |

### Other Changes

```diff

-301.24.0.25.0
+301.24.0.27.0

+  - /System/Library/PrivateFrameworks/FamilyCircle.framework/FamilyCircle

-  Functions: 2941
-  Symbols:   4304
-  CStrings:  1634
+  Functions: 3036
+  Symbols:   4340
+  CStrings:  1644
Symbols:
+ _OBJC_CLASS_$_FAFamilyMember
+ _OBJC_CLASS_$_ICQUpsellHeaderSignalProvider
+ _OBJC_METACLASS_$_ICQUpsellHeaderSignalProvider
+ __CLASS_METHODS_ICQUpsellHeaderSignalProvider
+ __CLASS_PROPERTIES_ICQUpsellHeaderSignalProvider
+ __DATA_ICQUpsellHeaderSignalProvider
+ __DATA__TtC11iCloudQuota23RealFamilyCircleFetcher
+ __DATA__TtC11iCloudQuota26RealFamilyMembershipReader
+ __INSTANCE_METHODS_ICQUpsellHeaderSignalProvider
+ __IVARS_ICQUpsellHeaderSignalProvider
+ __IVARS__TtC11iCloudQuota23RealFamilyCircleFetcher
+ __IVARS__TtC11iCloudQuota26RealFamilyMembershipReader
+ __METACLASS_DATA_ICQUpsellHeaderSignalProvider
+ __METACLASS_DATA__TtC11iCloudQuota23RealFamilyCircleFetcher
+ __METACLASS_DATA__TtC11iCloudQuota26RealFamilyMembershipReader
+ ___swift_allocate_boxed_opaque_existential_1
+ ___swift_memcpy2_1
+ ___swift_mutable_project_boxed_opaque_existential_1
+ _swift_deallocPartialClassInstance
+ _swift_makeBoxUnique
+ _symbolic $s11iCloudQuota23ICQFamilyCircleFetchingP
+ _symbolic $s11iCloudQuota26ICQFamilyMembershipReadingP
+ _symbolic SDyS2SGIegg_
+ _symbolic SS_SSt
+ _symbolic So12NSDictionaryCIeyBy_
+ _symbolic _____ 11iCloudQuota23RealFamilyCircleFetcherC
+ _symbolic _____ 11iCloudQuota25ICQFamilyMembershipSignalV
+ _symbolic _____ 11iCloudQuota26RealFamilyMembershipReaderC
+ _symbolic _____ 11iCloudQuota29ICQUpsellHeaderSignalProviderC
+ _symbolic ______p 11iCloudQuota23ICQFamilyCircleFetchingP
+ _symbolic ______p 11iCloudQuota26ICQFamilyMembershipReadingP
+ _symbolic ______p 12FamilyCircle0aB8ProviderP
+ _symbolic _____ySSG s23_ContiguousArrayStorageC
+ _symbolic _____ySS_SStG s23_ContiguousArrayStorageC
+ _symbolic _____ySnySiGG s23_ContiguousArrayStorageC
+ _type_layout_string 11iCloudQuota25ICQFamilyMembershipSignalV
CStrings:
+ "X-Apple-iCloud-User-In-Family"
+ "X-Apple-iCloud-User-Under-18"
+ "[UpsellSignals] Applying signal headers to LiftUI request %s: %s"
+ "[UpsellSignals] Applying signal headers to upgrade request %@: %@"
+ "[UpsellSignals] Cached family circle result: %s"
+ "[UpsellSignals] Computed headers: %s"
+ "[UpsellSignals] Derived signal from cached circle: members=%ld, isMeFound=%{bool}d, isInFamily=%{bool}d, isUnder18=%{bool}d"
+ "[UpsellSignals] No cached family circle -> isInFamily=false, isUnder18=false"
+ "[UpsellSignals] Reading family circle from cache (cache-only)"
+ "no cached circle"
```
