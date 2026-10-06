## PersonalizedSensingService

> `/System/Library/PrivateFrameworks/PersonalizedSensing.framework/XPCServices/PersonalizedSensingService.xpc/PersonalizedSensingService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b260` | `0x10b3b8` | **`+0x158`** |
| `__DATA_CONST.__got` | `0x9d0` | `0xab0` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0xad0d` | `0xadad` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xd430` | `0xd460` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0xe820` | `0xe840` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1b80` | `0x1b70` | **`-0x10`** |
| `__TEXT.__const` | `0x355e` | `0x356e` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xdd8` | `0xdd0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-412.0.0.0.0
+415.0.0.0.0

-  Symbols:   12266
-  CStrings:  5661
+  Symbols:   12267
+  CStrings:  5663
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/Moments/install/TempContent/Objects/Moments.build/PersonalizedSensingService.build/Objects-normal/arm64e/MOMotionManagerKeys.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Moments/momentsd/PromptEngine/PromptSource/Motion/
+ MOMotionManagerKeys.m
+ _$s26PersonalizedSensingService15PSSContextPlaceC24calculateConfidenceLevel33_349D149204877798F4B516A4E0978C04LL9placeType0o4UserP00o4NameG0SSSo016MOPlaceInferenceeP0V_So0stq8SpecificeP0VSdtFZTf4nnnd_n
+ _kMOMotionQueryInterval
- _$s26PersonalizedSensingService15PSSContextPlaceC24calculateConfidenceLevel33_349D149204877798F4B516A4E0978C04LL9placeType0o4UserP00o4NameG0SSSgSo016MOPlaceInferenceeP0V_So0stq8SpecificeP0VSdtFZTf4nnnd_n
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_willThrowTypedImpl
Functions:
~ -[MOEventBundleRanking _calculateRankingScore:withMinRecommendedBundleCountRequirement:] : 30688 -> 31016
~ _$s26PersonalizedSensingService11BaseDonatorC12getDonationsSDySSSaySo14NSSecureCoding_pGGyYaKFyScGys6ResultOyAGs5Error_pGGzYaXEfU_TY2_ : 1836 -> 1840
~ _$s26PersonalizedSensingService11BaseDonatorC12getDonations8intervalSDySSSaySo14NSSecureCoding_pGG10Foundation12DateIntervalV_tYaKFyScGys6ResultOyAHs5Error_pGGzYaXEfU_TY2_ : 1848 -> 1852
~ _$s26PersonalizedSensingService11BaseDonatorC12getDonations5count8bookmarkSDySSSaySo14NSSecureCoding_pGG_SDySSyXlGtSi_AJtYaKFyScGys6ResultOyAI_AJts5Error_pGGzYaXEfU_TY2_ : 2404 -> 2372
~ _$sSTsE7flatMapySay7ElementQyd__Gqd__ABQzKXEKSTRd__lFSay26PersonalizedSensingService16PSSContextSocialCG_SayAF0G6InviteCGTg504$s26de9Service15g101EventC5event5cache20correspondingBundlesACSgSo7MOEventC_AA10PlaceCacheCSaySo0J6BundleCGSgtcfcSayAA0D6i7CGAA0D6H7CXEfU1_Tf1cn_n : 832 -> 828
~ _$sSTsE7flatMapySay7ElementQyd__Gqd__ABQzKXEKSTRd__lFSaySo13MOEventBundleCG_Say26PersonalizedSensingService15PSSContextMediaCGTg504$s26fg9Service15i47EventC5event5cache20correspondingBundlesACSgSo7d25C_AA10PlaceCacheCSaySo0J6e16CGSgtcfcSayAA0D5J10CGAMXEfU2_Tf1cn_n : 808 -> 804
~ _$ss6_merge3low3mid4high6buffer2bySbSpyxG_A3GSbx_xtKXEtKlFSS_Tg5 : 1032 -> 1020
~ _$ss6_merge3low3mid4high6buffer2bySbSpyxG_A3GSbx_xtKXEtKlFSo13MOEventBundleC_Tg5089$s26PersonalizedSensingService15PSSContextEventC5event5cache20correspondingBundlesACSgSo7g25C_AA10PlaceCacheCSaySo0J6H21CGSgtcfcSbAM_AMtXEfU_Tf1nnnnc_n : 1224 -> 1216
~ _$ss6_merge3low3mid4high6buffer2bySbSpyxG_A3GSbx_xtKXEtKlFSS_Tg5144$s26PersonalizedSensingService20PSSSocialDescriptionC16formatOrganizers33_E9596D33CA59BAB22DA52593A03B4D62LL_4isMeSSSgSaySSG_SbSgtFSbSS_SStXEfU_Tf1nnnnc_nTm : 692 -> 688
~ _$ss17_NativeDictionaryV6filteryAByxq_GSbx3key_q_5valuet_tqd__YKXEqd__YKs5ErrorRd__lFSS_Sis5NeverOTg5014$sSSSiSbIggyd_i4Sbs5g157OIegnndzr_TR0156$s26PersonalizedSensingService37PSSPatternSummaryDescriptionGeneratorC16processHistogram33_90C55FE0D0ABE292AC72F5C2D5163D74LL_5limitSaySSGSDyI37G_SitFSbSS_Z13XEfU_Tf4nnd_nTf3nnnpf_nTf1cn_nTm : 844 -> 824
~ _$ss6_merge3low3mid4high6buffer2bySbSpyxG_A3GSbx_xtKXEtKlFSS3key_Si5valuet_Tg5187$s26PersonalizedSensingService37PSSPatternSummaryDescriptionGeneratorC16processHistogram33_90C55FE0D0ABE292AC72F5C2D5163D74LL_5limitSaySSGSDySSSiG_SitFSbSS3key_Si5valuet_SSAI_SiAJttXEfU0_Tf1nnnnc_n : 580 -> 576
~ _$ss6_merge3low3mid4high6buffer2bySbSpyxG_A3GSbx_xtKXEtKlFSS3key_Si5valuet_Tg5202$s26PersonalizedSensingService37PSSPatternSummaryDescriptionGeneratorC19generateWorkoutList33_90C55FE0D0ABE292AC72F5C2D5163D74LL4fromSSSgAA21BehavioralPatternDataC_tFSbSS3key_Si5valuet_SSAJ_SiAKttXEfU0_Tf1nnnnc_n : 684 -> 676
~ _$ss6_merge3low3mid4high6buffer2bySbSpyxG_A3GSbx_xtKXEtKlF26PersonalizedSensingService16PSSContextPersonC6person_SS4namet_Tg504$s26gh104Service20PSSPeopleDescriptionC27sortPeopleByPriorityAndName33_3C6F4EA6D0D5A8039817590447695C29LLySayAA16jK48C6person_SS4nametGAJFSbAgH_SSAIt_AgH_SSAIttXEfU_Tf1nnnnc_n : 924 -> 916
~ _$s26PersonalizedSensingService15PSSContextPlaceC24calculateConfidenceLevel33_972736DD7436CA1EE79FD113FEAF0335LL5visitSSSgSo7RTVisitC_tFZTf4nd_n : 256 -> 272
~ _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_AiBq_xRi_zRi0_zRi__Ri0__r0_lys5NeverOxIsgyrzr_xA2KRs_r0_lIetygrzo_Tpq5s10_NativeSetVySSG_Tg506$ss10_lm30V12intersectionyAByxGADFADs13_aB12VXEfU_SS_TG5A2NTf1nc_n -> _$ss10_NativeSetV12intersectionyAByxGADFSS_Tg5 : 132 -> 1172
~ _$ss10_NativeSetV13extractSubset5using5countAByxGs13_UnsafeBitsetV_SitFSS_Tg5 -> _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_AiBq_xRi_zRi0_zRi__Ri0__r0_lys5NeverOxIsgyrzr_xA2KRs_r0_lIetygrzo_Tpq5s10_NativeSetVySSG_Tg506$ss10_lm30V12intersectionyAByxGADFADs13_aB12VXEfU_SS_TG5A2NTf1nc_n : 544 -> 132
~ _$ss10_NativeSetV12intersectionyAByxGADFSS_Tg5 -> _$ss10_NativeSetV13extractSubset5using5countAByxGs13_UnsafeBitsetV_SitFSS_Tg5 : 1176 -> 544
~ _$s26PersonalizedSensingService15PSSContextPlaceC24calculateConfidenceLevel33_349D149204877798F4B516A4E0978C04LL9placeType0o4UserP00o4NameG0SSSgSo016MOPlaceInferenceeP0V_So0stq8SpecificeP0VSdtFZTf4nnnd_n -> _$s26PersonalizedSensingService15PSSContextPlaceC24calculateConfidenceLevel33_349D149204877798F4B516A4E0978C04LL9placeType0o4UserP00o4NameG0SSSo016MOPlaceInferenceeP0V_So0stq8SpecificeP0VSdtFZTf4nnnd_n : 168 -> 172
~ _$s26PersonalizedSensingService15PSSContextPlaceC4from02moE011isSensitive18correspondingEvent5cacheACSgSo7MOPlaceC_SbSgSo7MOEventCSgAA0E5CacheCtFZTf4nnndd_n : 2688 -> 2656
~ _$ss6_merge3low3mid4high6buffer2bySbSpyxG_A3GSbx_xtKXEtKlF26PersonalizedSensingService15PSSContextMediaC_Tg504$s26gh35Service19PSSMediaDescriptionC15sortk52ByTime33_E7D61B8A316BB5D3CEC3102CAEE4BFC9LLySayAA010J20G0CGAHFSbAG_AGtXEfU_Tf1nnnnc_n : 932 -> 1008
~ _$sSTsE7flatMapySay7ElementQyd__Gqd__ABQzKXEKSTRd__lFSay26PersonalizedSensingService15PSSContextEventCG_SayAF0G5PlaceCGTg504$s26de90Service21CleanTransformDonatorC13fuseDonationsySDySSSaySo14NSSecureCoding_pGGAGYaKFSayAA15gi7CGAA0K5H6CXEfU_Tf1cn_n : 888 -> 884
~ _$sSTsE7flatMapySay7ElementQyd__Gqd__ABQzKXEKSTRd__lFSay26PersonalizedSensingService15PSSContextEventCG_SayAF0G6PersonCGTg504$s26de90Service21CleanTransformDonatorC13fuseDonationsySDySSSaySo14NSSecureCoding_pGGAGYaKFSayAA16gi7CGAA0K5H7CXEfU0_Tf1cn_n : 888 -> 884
~ _$ss6_merge3low3mid4high6buffer2bySbSpyxG_A3GSbx_xtKXEtKlF26PersonalizedSensingService15PSSContextPlaceC_Tg504$s26gh103Service30PSSActivityLocationDescriptionC16sortPlacesByTime33_2CFC9B44FA2E8EBC6D25BA770A66A05FLLySayAA15jK18CGAHFSbAG_AGtXEfU_Tf1nnnnc_n : 932 -> 1008
~ _$sSa13_copyContents12initializings16IndexingIteratorVySayxGG_SitSryxG_tF26PersonalizedSensingService15PSSContextPlaceC_Tg5 : 416 -> 412
~ _$sSa13_copyContents12initializings16IndexingIteratorVySayxGG_SitSryxG_tF26PersonalizedSensingService15PSSContextMediaC_Tg5 : 416 -> 412
~ _$sSa13_copyContents12initializings16IndexingIteratorVySayxGG_SitSryxG_tFSo13MOEventBundleC_Tg5 : 416 -> 412
~ _$sSa13_copyContents12initializings16IndexingIteratorVySayxGG_SitSryxG_tF26PersonalizedSensingService17PSSContextPatternC_Tg5 : 416 -> 412
CStrings:
+ "MOInternalMotionActivityUITreatment"
+ "Phone-sensed motion activity suggestion was rejected from UI because elapsed time >%.2f days: bundleID %@, suggestionID %@, bundleSubType %lu, elapsedTime %.2f"
```
