## mmaintenanced

> `/usr/libexec/mmaintenanced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24db4` | `0x2739c` | **`+0x25e8`** |
| `__TEXT.__auth_stubs` | `0x13e0` | `0x1580` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x1bfd` | `0x1cfd` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x2dc6` | `0x2ea2` | **`+0xdc`** |
| `__DATA_CONST.__auth_got` | `0xa00` | `0xad0` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0xa00` | `0xa30` | **`+0x30`** |
| `__TEXT.__const` | `0x7b8` | `0x7e0` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0xfe` | `0x120` | **`+0x22`** |
| `__DATA.__data` | `0x1a8` | `0x1c8` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0xa0` | `0xb8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x1458` | `0x1468` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x238` | `0x240` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-233.0.5.0.0
+233.40.4.0.0

-  Functions: 698
-  Symbols:   1405
-  CStrings:  485
+  Functions: 712
+  Symbols:   1459
+  CStrings:  496
Symbols:
+ _$s10Foundation6LocaleVMa
+ _$s10Foundation6LocaleVMn
+ _$s10Foundation6LocaleVSgMR
+ _$s10Foundation6LocaleVSgMd
+ _$s13ExclavesStats0aB6ServerC13statsDescribe10startIndex5countSaySSGSi_SiSgtKFTj
+ _$s13ExclavesStats0aB6ServerC8serverIdACSS_tKcfc
+ _$s13ExclavesStats0aB6ServerC9statsRead10startIndex5count9excludingSaySdGSi_SiSgSaySSGtKFTj
+ _$s23MemoryMaintenance_Swift23conclaveAddrspaceSuffix33_25EA3A169A1CD17386F15AB940E8360CLLSSvp
+ _$s23MemoryMaintenance_Swift25reportConclaveLaunchStatsSbyF
+ _$sS2SSysWL
+ _$sS2SSysWl
+ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_s6UInt64VTt0g5Tf4g_n
+ _$sSS14_fromSubstringySSSshFZ
+ _$sSS18_fromUTF8RepairingySS6result_Sb11repairsMadetSRys5UInt8VGFZ
+ _$sSS5countSivg
+ _$sSS5index_8offsetBy07limitedC0SS5IndexVSgAE_SiAEtF
+ _$sSS8UTF8ViewV13_foreignIndex5afterSS0D0VAF_tF
+ _$sSS8UTF8ViewV13_foreignIndex_8offsetBy07limitedF0SS0D0VSgAG_SiAGtF
+ _$sSS8UTF8ViewV13_foreignIndex_8offsetBySS0D0VAF_SitF
+ _$sSS8UTF8ViewV17_foreignSubscript8positions5UInt8VSS5IndexV_tF
+ _$sSS9UTF16ViewV5index_8offsetBySS5IndexVAF_SitF
+ _$sSS9hasSuffixySbSSF
+ _$sSSSysMc
+ _$sSSySsSnySS5IndexVGcig
+ _$sSTsE21_copySequenceContents12initializing8IteratorQz_SitSry7ElementQzG_tFSs8UTF8ViewV_Tgq5
+ _$sSlsE6prefixy11SubSequenceQzSiFSS8UTF8ViewV_Tg5
+ _$sSs8UTF8ViewV8distance4from2toSiSS5IndexV_AGtF
+ _$sSy10FoundationE20replacingOccurrences2of4with7options5rangeSSqd___qd_0_So22NSStringCompareOptionsVSnySS5IndexVGSgtSyRd__SyRd_0_r0_lF
+ _$sSy10FoundationE5range2of7optionsAB6localeSnySS5IndexVGSgqd___So22NSStringCompareOptionsVAiA6LocaleVSgtSyRd__lF
+ _$ss11_StringGutsV22validateSubscalarRangeySnySS5IndexVGAFF
+ _$ss11_StringGutsV27_slowEnsureMatchingEncodingySS5IndexVAEF
+ _$ss15ContiguousArrayV16_createNewBuffer14bufferIsUnique15minimumCapacity13growForAppendySb_SiSbtFSS_Tg5
+ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFSS_So8NSObjectCTg5
+ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFSS_s6UInt64VTg5
+ _$ss17_NativeDictionaryV4copyyyFSS_So8NSObjectCTg5
+ _$ss17_NativeDictionaryV4copyyyFSS_s6UInt64VTg5
+ _$ss17_NativeDictionaryV8setValue_6forKey8isUniqueyq_n_xSbtFSS_So8NSObjectCTg5
+ _$ss18_DictionaryStorageC4copy8originalAByxq_Gs05__RawaB0C_tFZ
+ _$ss18_DictionaryStorageC6resize8original8capacity4moveAByxq_Gs05__RawaB0C_SiSbtFZ
+ _$ss18_DictionaryStorageCySSs6UInt64VGMR
+ _$ss18_DictionaryStorageCySSs6UInt64VGMd
+ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSS_Tg5
+ _$ss23_ContiguousArrayStorageCySSGMR
+ _$ss23_ContiguousArrayStorageCySSGMd
+ _$ss53KEY_TYPE_OF_DICTIONARY_VIOLATES_HASHABLE_REQUIREMENTSys5NeverOypXpF
+ _$ss6UInt64V10FoundationE19_bridgeToObjectiveCSo8NSNumberCyF
+ _$ss6UInt64VMn
+ _objc_release_x1
+ _objc_retain_x21
+ _objc_retain_x26
+ _swift_release_x28
+ _symbolic _____Sg 10Foundation6LocaleV
+ _symbolic _____ySSG s23_ContiguousArrayStorageC
+ _symbolic _____ySS_____G s18_DictionaryStorageC s6UInt64V
CStrings:
+ ".conclave_launcherAddrSpace"
+ ".launch_time_ns."
+ "Failed to sample conclave launcher address spaces"
+ "Failed to sample launch stats for %s: %@"
+ "No conclave launch stats available"
+ "Sent %ld conclave launch stats to Core Analytics"
+ "com.apple.memorytools.stats.conclave_launch_time"
+ "conclave_launcherAddrSpace"
+ "first_launch_time_ns"
+ "rolling_avg_launch_time_ns"
+ "rolling_stddev_launch_time_ns"
```
