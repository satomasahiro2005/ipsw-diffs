## JetCore

> `/System/Library/PrivateFrameworks/JetCore.framework/JetCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x259d50` | `0x260f00` | **`+0x71b0`** |
| `__DATA.__bss` | `0x22d90` | `0x23410` | **`+0x680`** |
| `__AUTH_CONST.__const` | `0x19d38` | `0x1a288` | **`+0x550`** |
| `__TEXT.__const` | `0x1e5fc` | `0x1e9fc` | **`+0x400`** |
| `__TEXT.__eh_frame` | `0x14e78` | `0x15110` | **`+0x298`** |
| `__TEXT.__cstring` | `0xa191` | `0xa401` | **`+0x270`** |
| `__TEXT.__unwind_info` | `0x9788` | `0x9988` | **`+0x200`** |
| `__TEXT.__swift5_fieldmd` | `0x6860` | `0x69a0` | **`+0x140`** |
| `__TEXT.__swift5_reflstr` | `0x39d2` | `0x3ac2` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0x7a18` | `0x7ab4` | **`+0x9c`** |
| `__DATA_CONST.__const` | `0x4f8` | `0x580` | **`+0x88`** |
| `__DATA.__data` | `0x6338` | `0x6398` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x1038` | `0x1080` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x44c` | `0x48c` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x82d9` | `0x8319` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x16e8` | `0x171c` | **`+0x34`** |
| `__TEXT.__swift_as_cont` | `0xa78` | `0xa5c` | **`-0x1c`** |
| `__DATA.__common` | `0x3e8` | `0x400` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x97c` | `0x990` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x35e8` | `0x35d8` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x5b8` | `0x5ac` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1ed8` | `0x1ed0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x9e8` | `0x9e0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x830` | `0x838` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x3700` | `0x36f8` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x538` | `0x534` | **`-0x4`** |

### Other Changes

```diff

-10.0.33.0.0
+10.0.38.0.0

-  Functions: 12474
-  Symbols:   3760
-  CStrings:  948
+  Functions: 12689
+  Symbols:   3772
+  CStrings:  967
Symbols:
+ ___swift_closure_destructor.4Tm
+ _associated conformance 7JetCore10ActionTypeVSHAASQ
+ _associated conformance 7JetCore10TargetTypeVSHAASQ
+ _associated conformance 7JetCore8PageTypeVSHAASQ
+ _swift_retain_x12
+ _symbolic _____ 7JetCore10ActionTypeV
+ _symbolic _____ 7JetCore10TargetTypeV
+ _symbolic _____ 7JetCore17PageMetricsFieldsV
+ _symbolic _____ 7JetCore18ClickMetricsFieldsV
+ _symbolic _____ 7JetCore23SearchPageMetricsFieldsV
+ _symbolic _____ 7JetCore8PageTypeV
+ _symbolic ______Shy_____Gt 7JetCore16MetricsEventTypeV AA0C21FieldInclusionRequestV
+ _symbolic _____y_____Shy_____GG s18_DictionaryStorageC 7JetCore16MetricsEventTypeV AC0E21FieldInclusionRequestV
+ _symbolic _____y______Shy_____GtG s23_ContiguousArrayStorageC 7JetCore16MetricsEventTypeV AC0F21FieldInclusionRequestV
+ _type_layout_string 7JetCore10ActionTypeV
+ _type_layout_string 7JetCore17PageMetricsFieldsV
+ _type_layout_string 7JetCore18ClickMetricsFieldsV
+ _type_layout_string 7JetCore23SearchPageMetricsFieldsV
- _associated conformance 7JetCore3BagV0C15SoftwareVersionOSHAASQ
- _swift_retain_x11
- _symbolic _____ 7JetCore3BagV0C15SoftwareVersionO
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
