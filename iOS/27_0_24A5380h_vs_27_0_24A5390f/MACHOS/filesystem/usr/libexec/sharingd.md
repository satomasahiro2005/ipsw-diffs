## sharingd

> `/usr/libexec/sharingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x696ca0` | `0x6a1820` | **`+0xab80`** |
| `__TEXT.__auth_stubs` | `0xa970` | `0xaec0` | **`+0x550`** |
| `__TEXT.__eh_frame` | `0x24214` | `0x245e4` | **`+0x3d0`** |
| `__DATA_CONST.__auth_got` | `0x54c8` | `0x5770` | **`+0x2a8`** |
| `__DATA.__objc_const` | `0x382b0` | `0x383f0` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x4e7a5` | `0x4e8c5` | **`+0x120`** |
| `__TEXT.__swift5_reflstr` | `0x58f9` | `0x5a09` | **`+0x110`** |
| `__TEXT.__const` | `0x15ac8` | `0x15b58` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x3cb33` | `0x3cbb3` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x5e18` | `0x5e90` | **`+0x78`** |
| `__DATA.__data` | `0x14858` | `0x148b8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1c9e8` | `0x1ca38` | **`+0x50`** |
| `__DATA.__objc_data` | `0xa098` | `0xa0e0` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x14728` | `0x14768` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x5150` | `0x5188` | **`+0x38`** |
| `__DATA.__common` | `0x958` | `0x978` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x42d8` | `0x42f8` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x37440` | `0x37460` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x7f70` | `0x7f8c` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x3998` | `0x39a8` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x784c` | `0x785c` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x21e0` | `0x21ec` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0xf44` | `0xf48` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-2124.10.2.2.2
+2126.10.4.0.0

-  Functions: 26245
-  Symbols:   4886
-  CStrings:  27476
+  Functions: 26261
+  Symbols:   4973
+  CStrings:  27486
Symbols:
+ _$s2os12OSSignpostIDVMn
+ _$s7Sharing16AirDropSignpostsO10signpostID3for2os010OSSignpostF0VyXl_tFZ
+ _$s7Sharing16AirDropSignpostsO13IntervalTokenVMa
+ _$s7Sharing16AirDropSignpostsO13IntervalTokenVMn
+ _$s7Sharing16AirDropSignpostsO14makeSignpostID2os010OSSignpostG0VyFZ
+ _$s7Sharing16AirDropSignpostsO2UIO16endSessionLaunchyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO2UIO18beginSessionLaunch2idAC13IntervalTokenV2os12OSSignpostIDV_tFZ
+ _$s7Sharing16AirDropSignpostsO3XPCO11beginCancel2id10transferIDAC13IntervalTokenV2os010OSSignpostJ0V_SStFZ
+ _$s7Sharing16AirDropSignpostsO3XPCO16endFetchMetadatayyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO3XPCO18beginFetchMetadata2idAC13IntervalTokenV2os12OSSignpostIDV_tFZ
+ _$s7Sharing16AirDropSignpostsO3XPCO26endBecomeTransferPresenteryyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO3XPCO28beginBecomeTransferPresenter2id14senderBundleIDAC13IntervalTokenV2os010OSSignpostM0V_SStFZ
+ _$s7Sharing16AirDropSignpostsO3XPCO7endSendyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO3XPCO9beginSend2id14senderBundleIDAC13IntervalTokenV2os010OSSignpostK0V_SStFZ
+ _$s7Sharing16AirDropSignpostsO3XPCO9endCancelyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO10endArchiveyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO10endAskPrepyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO11beginUpload2id12endpointUUID10transferID9fileCountAC13IntervalTokenV2os010OSSignpostL0V_10Foundation0J0VSgSSSgSitFZ
+ _$s7Sharing16AirDropSignpostsO4SendO11endExchangeyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO11endItemPrepyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO11endLoadURLsyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO11endTransferyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO12beginArchive2id10transferID12endpointUUID9fileCount7archiveAC13IntervalTokenV2os010OSSignpostJ0V_SSSg10Foundation0L0VSgSiSStFZ
+ _$s7Sharing16AirDropSignpostsO4SendO12beginAskPrep2id10transferID12endpointUUIDAC13IntervalTokenV2os010OSSignpostK0V_SS10Foundation0M0VSgtFZ
+ _$s7Sharing16AirDropSignpostsO4SendO12endUploadAckyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO13beginExchange2id12endpointUUID10transferIDAC13IntervalTokenV2os010OSSignpostL0V_10Foundation0J0VSgSSSgtFZ
+ _$s7Sharing16AirDropSignpostsO4SendO13beginItemPrep2id10transferID12endpointUUID9fileCountAC13IntervalTokenV2os010OSSignpostK0V_SS10Foundation0M0VSgSitFZ
+ _$s7Sharing16AirDropSignpostsO4SendO13beginLoadURLs2id10transferID12endpointUUID9fileCountAC13IntervalTokenV2os010OSSignpostK0V_SS10Foundation0M0VSgSitFZ
+ _$s7Sharing16AirDropSignpostsO4SendO13beginTransfer2id10transferID12endpointUUID0I4TypeAC13IntervalTokenV2os010OSSignpostJ0V_SS10Foundation0L0VSgSStFZ
+ _$s7Sharing16AirDropSignpostsO4SendO14beginUploadAck2id12endpointUUID10transferID14totalBytesReadAC13IntervalTokenV2os010OSSignpostM0V_10Foundation0K0VSgSSSgSitFZ
+ _$s7Sharing16AirDropSignpostsO4SendO14endContentPrepyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO15endMediaConvertyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO16beginContentPrep2id10transferID12endpointUUID9fileCountAC13IntervalTokenV2os010OSSignpostK0V_SS10Foundation0M0VSgSitFZ
+ _$s7Sharing16AirDropSignpostsO4SendO17beginMediaConvert2id10transferID12endpointUUIDAC13IntervalTokenV2os010OSSignpostK0V_SS10Foundation0M0VSgtFZ
+ _$s7Sharing16AirDropSignpostsO4SendO17endCoordinateReadyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO17endHandshakeHelloyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO18endConnectionSetupyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO19beginCoordinateRead2id10transferID12endpointUUID9fileCountAC13IntervalTokenV2os010OSSignpostK0V_SS10Foundation0M0VSgSitFZ
+ _$s7Sharing16AirDropSignpostsO4SendO19beginHandshakeHello2id12endpointUUID10transferIDAC13IntervalTokenV2os010OSSignpostM0V_10Foundation0K0VSgSSSgtFZ
+ _$s7Sharing16AirDropSignpostsO4SendO19endResolveEndpointsyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO20beginConnectionSetup2id12endpointUUID10transferID7attemptAC13IntervalTokenV2os010OSSignpostM0V_10Foundation0K0VSgSSSgSitFZ
+ _$s7Sharing16AirDropSignpostsO4SendO20endSensitiveAnalysisyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO21beginResolveEndpoints2id10transferID12endpointUUIDAC13IntervalTokenV2os010OSSignpostK0V_SS10Foundation0M0VSgtFZ
+ _$s7Sharing16AirDropSignpostsO4SendO22beginSensitiveAnalysis2id10transferID12endpointUUID9fileCountAC13IntervalTokenV2os010OSSignpostK0V_SS10Foundation0M0VSgSitFZ
+ _$s7Sharing16AirDropSignpostsO4SendO24endSensitiveInterventionyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO26beginSensitiveIntervention2id10transferID12endpointUUIDAC13IntervalTokenV2os010OSSignpostK0V_SS10Foundation0M0VSgtFZ
+ _$s7Sharing16AirDropSignpostsO4SendO27sensitiveInterventionAccept10transferIDySS_tFZ
+ _$s7Sharing16AirDropSignpostsO4SendO27sensitiveInterventionReject10transferIDySS_tFZ
+ _$s7Sharing16AirDropSignpostsO4SendO6endAskyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO4SendO8beginAsk2id12endpointUUID10transferIDAC13IntervalTokenV2os010OSSignpostL0V_10Foundation0J0VSgSSSgtFZ
+ _$s7Sharing16AirDropSignpostsO4SendO9endUploadyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO6BrowseO3end8clientID06bundleH03pidy10Foundation4UUIDV_SSs5Int32VtFZ
+ _$s7Sharing16AirDropSignpostsO6BrowseO5start8clientID06bundleH03pid22applicationServiceOnly13deviceFiltersy10Foundation4UUIDV_SSs5Int32VSbSStFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO11beginImport2id10transferID9fileCountAC13IntervalTokenV2os010OSSignpostJ0V_SSSitFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO11endTransferyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO12endPreAcceptyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO12endPreChecksyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO13beginTransfer2id10transferID0I4TypeAC13IntervalTokenV2os010OSSignpostJ0V_S2StFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO13endPostAcceptyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO13endWriteFilesyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO14beginPreAccept2id10transferIDAC13IntervalTokenV2os010OSSignpostK0V_SStFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO14beginPreChecks2id10transferIDAC13IntervalTokenV2os010OSSignpostK0V_SStFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO14endHandlerInityyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO14endServerStartyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO15beginPostAccept2id10transferIDAC13IntervalTokenV2os010OSSignpostK0V_SStFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO15beginWriteFiles2id10transferID9fileCountAC13IntervalTokenV2os010OSSignpostK0V_SSSitFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO15endAwaitRequestyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO16beginHandlerInit2id10transferIDAC13IntervalTokenV2os010OSSignpostK0V_SStFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO16beginServerStart2idAC13IntervalTokenV2os12OSSignpostIDV_tFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO17beginAwaitRequest2idAC13IntervalTokenV2os12OSSignpostIDV_tFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO17endAnalyzeContentyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO19beginAnalyzeContent2id10transferIDAC13IntervalTokenV2os010OSSignpostK0V_SStFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO20endPostTransferEndedyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO22beginPostTransferEnded2id10transferIDAC13IntervalTokenV2os010OSSignpostL0V_SStFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO24endSensitivePreviewCheckyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO26beginSensitivePreviewCheck2id10transferIDAC13IntervalTokenV2os010OSSignpostL0V_SStFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO5error10transferIDySS_tFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO6cancel10transferIDySS_tFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO6endAskyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO7endOpenyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO7success10transferIDySS_tFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO8beginAsk2id10transferIDAC13IntervalTokenV2os010OSSignpostJ0V_SStFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO9beginOpen2id10transferIDAC13IntervalTokenV2os010OSSignpostJ0V_SStFZ
+ _$s7Sharing16AirDropSignpostsO7ReceiveO9endImportyyAC13IntervalTokenVFZ
+ _$s7Sharing16AirDropSignpostsO8TransferO5error10transferID7failureySS_SStFZ
+ _$s7Sharing16AirDropSignpostsO8TransferO6cancel10transferIDySS_tFZ
+ _$s7Sharing16AirDropSignpostsO8TransferO7success10transferIDySS_tFZ
CStrings:
+ "SDAirDropContentHandler+Default interventionRequest: preview image was nil for transfer, falling back to empty preview data"
+ "archiveSignpostToken"
+ "connectionSetupAttempt"
+ "connectionSetupID"
+ "connectionSetupToken"
+ "originatingEndpointUUID"
+ "originatingTransferID"
+ "receiveSignpostID"
+ "uploadAckSignpostToken"
+ "uploadSignpostToken"
```
