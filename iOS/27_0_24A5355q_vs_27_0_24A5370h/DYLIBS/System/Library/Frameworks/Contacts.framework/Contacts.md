## Contacts

> `/System/Library/Frameworks/Contacts.framework/Contacts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21ec8c` | `0x2206d0` | **`+0x1a44`** |
| `__TEXT.__oslogstring` | `0xf42a` | `0xf67a` | **`+0x250`** |
| `__AUTH_CONST.__objc_const` | `0x2da20` | `0x2db60` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x6588` | `0x66c8` | **`+0x140`** |
| `__TEXT.__gcc_except_tab` | `0x3b3c` | `0x3c2c` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x1bd58` | `0x1bde8` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0x9171` | `0x91d1` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x6308` | `0x6358` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x91b0` | `0x91e8` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0xdf80` | `0xdfa0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x9ce8` | `0x9d08` | **`+0x20`** |
| `__DATA.__bss` | `0x65c0` | `0x65d0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1318` | `0x1328` | **`+0x10`** |
| `__TEXT.__cstring` | `0xcbb9` | `0xcbc9` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x11a8` | `0x11b0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xa18` | `0xa20` | **`+0x8`** |

### Other Changes

```diff

-3833.100.7.2.1
+3835.100.6.0.0

-  Functions: 14168
-  Symbols:   20098
-  CStrings:  3429
+  Functions: 14203
+  Symbols:   20146
+  CStrings:  3445
Symbols:
+ +[CNFetchRequest makeSerialNumber]
+ +[CNSaveRequest makeSerialNumber]
+ -[CNChangeHistoryAPITriageSession .cxx_destruct]
+ -[CNChangeHistoryAPITriageSession closeWithError:]
+ -[CNChangeHistoryAPITriageSession closeWithEventCount:]
+ -[CNChangeHistoryAPITriageSession close]
+ -[CNChangeHistoryAPITriageSession durationString]
+ -[CNChangeHistoryAPITriageSession initWithRequest:]
+ -[CNChangeHistoryAPITriageSession init]
+ -[CNChangeHistoryAPITriageSession open]
+ -[CNChangeHistoryAPITriageSession request]
+ -[CNFetchRequest serialNumber]
+ -[CNSaveRequest serialNumber]
+ -[CNSaveRequest(Visitation) logTriageStatsToLog:]
+ _OBJC_CLASS_$_CNChangeHistoryAPITriageSession
+ _OBJC_IVAR_$_CNChangeHistoryAPITriageSession._request
+ _OBJC_IVAR_$_CNChangeHistoryAPITriageSession._timeSessionBegan
+ _OBJC_IVAR_$_CNChangeHistoryAPITriageSession._timeSessionEnded
+ _OBJC_IVAR_$_CNFetchRequest._serialNumber
+ _OBJC_IVAR_$_CNSaveRequest._serialNumber
+ _OBJC_METACLASS_$_CNChangeHistoryAPITriageSession
+ __OBJC_$_INSTANCE_METHODS_CNChangeHistoryAPITriageSession
+ __OBJC_$_INSTANCE_VARIABLES_CNChangeHistoryAPITriageSession
+ __OBJC_$_PROP_LIST_CNChangeHistoryAPITriageSession
+ __OBJC_CLASS_RO_$_CNChangeHistoryAPITriageSession
+ __OBJC_METACLASS_RO_$_CNChangeHistoryAPITriageSession
+ ___33+[CNSaveRequest makeSerialNumber]_block_invoke
+ ___34+[CNFetchRequest makeSerialNumber]_block_invoke
+ ___49-[CNSaveRequest(Visitation) logTriageStatsToLog:]_block_invoke
+ ___49-[CNSaveRequest(Visitation) logTriageStatsToLog:]_block_invoke_10
+ ___49-[CNSaveRequest(Visitation) logTriageStatsToLog:]_block_invoke_11
+ ___49-[CNSaveRequest(Visitation) logTriageStatsToLog:]_block_invoke_12
+ ___49-[CNSaveRequest(Visitation) logTriageStatsToLog:]_block_invoke_2
+ ___49-[CNSaveRequest(Visitation) logTriageStatsToLog:]_block_invoke_3
+ ___49-[CNSaveRequest(Visitation) logTriageStatsToLog:]_block_invoke_4
+ ___49-[CNSaveRequest(Visitation) logTriageStatsToLog:]_block_invoke_5
+ ___49-[CNSaveRequest(Visitation) logTriageStatsToLog:]_block_invoke_6
+ ___49-[CNSaveRequest(Visitation) logTriageStatsToLog:]_block_invoke_7
+ ___49-[CNSaveRequest(Visitation) logTriageStatsToLog:]_block_invoke_8
+ ___49-[CNSaveRequest(Visitation) logTriageStatsToLog:]_block_invoke_9
+ ___63-[CNContactStore enumeratorForChangeHistoryFetchRequest:error:]_block_invoke
+ ___67-[CNXPCDataMapper fetchContactsForFetchRequest:error:batchHandler:]_block_invoke_2
+ ___72-[CNAggregateContactStore enumeratorForChangeHistoryFetchRequest:error:]_block_invoke
+ ___91-[CNXPCDataMapper fetchEncodedContactsForFetchRequest:error:cancelationToken:batchHandler:]_block_invoke_4
+ ___block_descriptor_104_e8_32s40s48s56bs64r72r80r88r96r_e5_v8?0ls32l8s40l8r64l8r72l8r80l8r88l8s56l8r96l8s48l8
+ ___block_descriptor_40_e8_32r_e17_v16?0"CNGroup"8lr32l8
+ ___block_descriptor_40_e8_32r_e29_v24?0"CNGroup"8"CNGroup"16lr32l8
+ ___block_descriptor_40_e8_32r_e31_v24?0"CNContact"8"CNGroup"16lr32l8
+ ___block_descriptor_40_e8_32r_e33_v24?0"CNContact"8"CNContact"16lr32l8
+ ___block_descriptor_48_e8_32s40r_e30_v24?0"CNGroup"8"NSString"16lr40l8s32l8
+ ___block_descriptor_48_e8_32s40r_e32_v24?0"CNContact"8"NSString"16lr40l8s32l8
+ ___block_descriptor_72_e8_32s40s48bs56r64r_e5_v8?0ls32l8s40l8r56l8r64l8s48l8
+ _cn_logXPCFetchRoundTrip
+ _objc_release_x10
+ _os_log.cn_once_object_4
+ _os_log.cn_once_token_4
- +[CNContactFetchRequest makeSerialNumber]
- -[CNContactFetchRequest serialNumber]
- GCC_except_table107
- GCC_except_table83
- _OBJC_IVAR_$_CNContactFetchRequest._serialNumber
- _OUTLINED_FUNCTION_102
- ___41+[CNContactFetchRequest makeSerialNumber]_block_invoke
- _swift_release_x10
CStrings:
+ "\"A"
+ "%04llx Add %lu"
+ "%04llx Add %lu to containers: %{public}@"
+ "%04llx BEGIN Remote Fetch"
+ "%04llx BEGIN Save"
+ "%04llx Change history details: startingToken=%{public}d, unifyResults=%{public}d, includeGroupChanges=%{public}d, additionalKeysCount=%{public}lu"
+ "%04llx Delete %lu"
+ "%04llx Did fail to save (%{public}@): %{public}@"
+ "%04llx Did save successfully (%{public}@)"
+ "%04llx END Remote Fetch (%{public}@)"
+ "%04llx END Save FAILED (%{public}@): %{public}@"
+ "%04llx END Save success (%{public}@)"
+ "%04llx Group add=%lu update=%lu delete=%lu"
+ "%04llx Link +%lu/-%lu"
+ "%04llx Membership +%lu/-%lu"
+ "%04llx Returned %{public}lu change history events"
+ "%04llx Subgroup +%lu/-%lu"
+ "%04llx Update %lu"
+ "%04llx Will save"
+ "_serialNumber"
- "\"Q"
- "Did fail to save (%{public}@): %{public}@"
- "Did save successfully (%{public}@)"
- "Will save"
```
