## JetEngine

> `/System/Library/PrivateFrameworks/JetEngine.framework/JetEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ac534` | `0x4b32ec` | **`+0x6db8`** |
| `__DATA.__bss` | `0x35530` | `0x35bb0` | **`+0x680`** |
| `__AUTH_CONST.__const` | `0x31fb0` | `0x32500` | **`+0x550`** |
| `__TEXT.__const` | `0x9b258` | `0x9b688` | **`+0x430`** |
| `__TEXT.__eh_frame` | `0x257bc` | `0x25a54` | **`+0x298`** |
| `__TEXT.__cstring` | `0x12756` | `0x129c6` | **`+0x270`** |
| `__TEXT.__unwind_info` | `0x116b8` | `0x11838` | **`+0x180`** |
| `__TEXT.__swift5_fieldmd` | `0xc008` | `0xc148` | **`+0x140`** |
| `__TEXT.__swift5_reflstr` | `0x794b` | `0x7a0b` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0xd748` | `0xd7e4` | **`+0x9c`** |
| `__DATA_CONST.__const` | `0xf20` | `0xfa8` | **`+0x88`** |
| `__DATA.__data` | `0xd7e8` | `0xd848` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x1888` | `0x18d0` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x73c` | `0x77c` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xefe6` | `0xf026` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x20fc` | `0x2130` | **`+0x34`** |
| `__TEXT.__swift_as_cont` | `0x13fc` | `0x13e0` | **`-0x1c`** |
| `__DATA.__common` | `0x828` | `0x840` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x1030` | `0x1044` | **`+0x14`** |
| `__AUTH.__data` | `0x7a18` | `0x7a28` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2af8` | `0x2ae8` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0xa8c` | `0xa80` | **`-0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x18f8` | `0x1900` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x8754` | `0x874c` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x9e8` | `0x9e4` | **`-0x4`** |

### Other Changes

```diff

-10.0.33.0.0
+10.0.38.0.0

-  Functions: 22340
-  Symbols:   7364
-  CStrings:  1885
+  Functions: 22547
+  Symbols:   7373
+  CStrings:  1904
Symbols:
+ _associated conformance 9JetEngine10ActionTypeVSHAASQ
+ _associated conformance 9JetEngine10TargetTypeVSHAASQ
+ _associated conformance 9JetEngine8PageTypeVSHAASQ
+ _swift_retain_x12
+ _symbolic _____ 9JetEngine10ActionTypeV
+ _symbolic _____ 9JetEngine10TargetTypeV
+ _symbolic _____ 9JetEngine17PageMetricsFieldsV
+ _symbolic _____ 9JetEngine18ClickMetricsFieldsV
+ _symbolic _____ 9JetEngine23SearchPageMetricsFieldsV
+ _symbolic _____ 9JetEngine8PageTypeV
+ _symbolic ______Shy_____Gt 9JetEngine16MetricsEventTypeV AA0C21FieldInclusionRequestV
+ _symbolic _____y_____Shy_____GG s18_DictionaryStorageC 9JetEngine16MetricsEventTypeV AC0E21FieldInclusionRequestV
+ _symbolic _____y______Shy_____GtG s23_ContiguousArrayStorageC 9JetEngine16MetricsEventTypeV AC0F21FieldInclusionRequestV
+ _type_layout_string 9JetEngine10ActionTypeV
+ _type_layout_string 9JetEngine17PageMetricsFieldsV
+ _type_layout_string 9JetEngine18ClickMetricsFieldsV
+ _type_layout_string 9JetEngine23SearchPageMetricsFieldsV
- ___swift_closure_destructor.52Tm
- _associated conformance 9JetEngine3BagV0C15SoftwareVersionOSHAASQ
- _objc_retain_x12
- _swift_retain_x11
- _symbolic _____ 9JetEngine3BagV0C15SoftwareVersionO
- _symbolic ______pIegn_______pIegg_Ieggg_ So14AMSBagProtocolP s5ErrorP
- _symbolic _____ySbG 15Synchronization5_CellVAARi_zrlE
- _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE So16os_unfair_lock_sV
CStrings:
+ " with all tables present, skipping migration"
+ "' instead of subscript"
+ "Bag.fetchBag"
+ "ClickMetricsFields: use the typed property for '"
+ "Database schema already at expected version "
+ "Fetching Bag for profile \""
+ "JetPackAssetSession.asset"
+ "PageMetricsFields: use the typed property for '"
+ "SearchPageMetricsFields: use the typed property for '"
+ "URLJetPackAssetFetcher.fetch"
+ "Unable to convert the metrics data to Instruction due to the unsupported event type: "
+ "cacheKey=%s"
+ "data.reco.dataSetId"
+ "data.search.dataSetId"
+ "metricsDataset"
+ "profile=%{public}s"
+ "push_channel_state"
+ "revalidatedDateHeader"
+ "revalidatedDateHeader="
+ "url=%{public}s"
+ "x-apple-client-application"
+ "x-apple-requesting-process"
- "JetEngine_useBagV3"
- "Perform JetPack Request"
- "rdar://138814293 - Bag V3: Fetching Bag "
```
