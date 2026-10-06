## icloudmailagent

> `/usr/libexec/icloudmailagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ffcc` | `0x3febc` | **`-0x110`** |
| `__TEXT.__auth_stubs` | `0x1900` | `0x18f0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xc88` | `0xc80` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xdf0` | `0xde8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.0.3.0.0
+2027.0.4.0.0

-  Functions: 1207
-  Symbols:   3557
+  Functions: 1205
+  Symbols:   3553
Symbols:
- _$sSD8IteratorV8_VariantOySSSo8NSNumberC__GWOe
- _$sSS3key_So8NSNumberC5valuetSgWOe
- _$ss15LazyMapSequenceV8IteratorV4nextq_SgyFSDySSSo8NSNumberCG_SS_AHtTg5
- _swift_retain_x21
Functions:
~ _$s15icloudmailagent25CategorizationSyncManagerC14startPingTimer33_D3B0FCFF93C920EE1A43E2A9ED08676CLLyyFySo7NSTimerCYbcfU_ : 632 -> 644
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 280 -> 276
~ _$sSo32MCCRulesListenerNotificationTypeVs25ExpressibleByArrayLiteralSCsACP05arrayH0x0gH7ElementQzd_tcfCTW : 172 -> 176
~ _$s15icloudmailagent11APNSManagerC15setupConnection33_998E1D3CCAB34753418533F4D78E05C6LLyyFySo18AAURLConfigurationCSg_s5Error_pSgtYbcfU_ : 2024 -> 2020
~ _$s15icloudmailagent31FetchSenderOverridesAPIResponseV06mappedD0SaySo14RCOverrideRuleCGyF : 664 -> 684
~ _$s15icloudmailagent15GroupedOverrideV10dictionarySDySSypGvg : 684 -> 696
~ _$sSTsE21_copySequenceContents12initializing8IteratorQz_SitSry7ElementQzG_tFSD6ValuesVySS15icloudmailagent15GroupedOverrideV_G_Tg5 : 380 -> 384
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_ypTt0g5Tf4g_n : 256 -> 276
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_SSTt0g5Tf4g_n : 272 -> 276
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_SdTt0g5Tf4g_n : 252 -> 268
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_SDySSypGTt0g5Tf4g_n : 252 -> 276
~ _$s15icloudmailagent16RCOverrideHelperC18groupOverrideRules012_3C0A607C6E0G19E915DD11F93B07A5810LL5rulesSayAA07GroupedE0VGSaySo0B4RuleCG_tFZTf4nd_n : 1380 -> 1392
~ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFSS_SSTg5 : 692 -> 684
~ _$ss17_NativeDictionaryV4copyyyFSS_ypTg5 : 412 -> 388
~ _$ss17_NativeDictionaryV4copyyyFSS_15icloudmailagent15GroupedOverrideVTg5 : 412 -> 400
~ _$ss17_NativeDictionaryV4copyyyFSS_SSTg5 : 376 -> 372
~ _$ss17_NativeDictionaryV4copyyyFSo8NSStringC_ypTg5 : 380 -> 376
~ _$ss17_NativeDictionaryV4copyyyFSS_So8NSNumberCTg5 : 364 -> 356
~ _$ss17_NativeDictionaryV7_insert2at3key5valueys10_HashTableV6BucketV_xnq_ntFSS_SSTg5 : 84 -> 80
~ _$s15icloudmailagent25CategorizationSyncManagerC19notifyRuleListeners9overridesSbSaySo010RCOverrideF0CG_tF : 1552 -> 1564
~ _$s15icloudmailagent25CategorizationSyncManagerC06notifyC12AllListeners9overridesSbSaySo14RCOverrideRuleCG_tF : 1552 -> 1564
~ _$s15icloudmailagent25CategorizationSyncManagerC21notifyNewOldListeners10categoriesSbSDySSSdG_tF : 1900 -> 1888
~ _$s15icloudmailagent25CategorizationSyncManagerC16handleNewOldPush5stateySDySSSdG_tF : 1092 -> 1084
~ _$s15icloudmailagent25CategorizationSyncManagerC19fetchRecatOverrides33_D3B0FCFF93C920EE1A43E2A9ED08676CLL13callingMethodySS_tFyyYacfU_TY3_ : 1892 -> 1900
~ _$s15icloudmailagent25CategorizationSyncManagerC37registerCategoryRulesCallbackListener8endpoint17notificationTypes10completionySo21NSXPCListenerEndpointC_So08MCCRulesI16NotificationTypeVySb_s5Error_pSgtctFyycfU0_ : 1828 -> 1856
~ _$s15icloudmailagent25CategorizationSyncManagerC17eligibleListeners33_D3B0FCFF93C920EE1A43E2A9ED08676CLL2ofSaySo15NSXPCConnectionCGSo32MCCRulesListenerNotificationTypeV_tF : 528 -> 544
~ _$s15icloudmailagent25CategorizationSyncManagerC20didReceiveNewPayload7payload5topicySDys11AnyHashableVypG_SStF : 2932 -> 2984
~ _$ss17_NativeDictionaryV5merge_8isUnique16uniquingKeysWithyqd__n_Sbq_q__q_tqd_0_YKXEtqd_0_YKSTRd__s5ErrorRd_0_x_q_t7ElementRtd__r0_lFSS_So8NSNumberCs15LazyMapSequenceVySDySSAJGSS_AJtGs5NeverOTg5087$s15icloudmailagent25CategorizationSyncManagerC28syncNewOldCategoryTimestampsyySDySSSo8K16CGFA2F_AFtXEfU0_Tf1nncn_n : 704 -> 604
- _$ss15LazyMapSequenceV8IteratorV4nextq_SgyFSDySSSo8NSNumberCG_SS_AHtTg5
- _$sSS3key_So8NSNumberC5valuetSgWOe
~ _$s15icloudmailagent15APIRequestModelC14schemaMetadataSay9SwiftData6SchemaC08PropertyE0VGvgZTf4d_n : 1024 -> 1008
~ _$s15icloudmailagent21CategorizationManagerC20predictCommerceEmail4with10completionySo18MCCCategoryContextC_ySDys11AnyHashableVypGSg_s5Error_pSgtctFyyXEfU_ : 6188 -> 6196
```
