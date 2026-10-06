## LocalAuthenticationUIService

> `/Applications/LocalAuthenticationUIService.app/LocalAuthenticationUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c8e0` | `0x6c990` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x6ec0` | `0x6f60` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x9785` | `0x9805` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x2540` | `0x2560` | **`+0x20`** |
| `__DATA.__objc_const` | `0xc150` | `0xc160` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3ad8` | `0x3ae8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2319.0.46.0.0
+2319.0.63.0.0

-  Functions: 2656
-  Symbols:   7875
-  CStrings:  2362
+  Functions: 2657
+  Symbols:   7881
+  CStrings:  2367
Symbols:
+ -[ScreenDimmingView dimColor]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PasscodeContentViewControllerFullScreen-ecd2c0f26607af063d2b58c5b30e06fc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PinViewController-1a6b94456b944a45771f1dd00f715955.o
+ _$s28LocalAuthenticationUIService22PINSheetViewControllerC9viewModel_24didReceiveCustomPassword7handleryAA013AuthorizationeH0C_SSySbctF39$s10ObjectiveC8ObjCBoolVIeyBy_SbIegy_TR0P1C0rS0VIeyBy_Tf1nnEn_nTf4dnnn_n
+ _$s28LocalAuthenticationUIService29SceneDelegateHostedControllerC6handle_10completionySo011LACUIHostedD6ActionC_ys5Error_pSgctF023$sSo7NSErrorCSgIeyBy_s5L11_pSgIegg_TRSo0O0CSgIeyBy_Tf1nEn_n
+ _$s28LocalAuthenticationUIService33AuthorizationRemoteViewControllerC4stop5replyyys5Error_pSgc_tF023$sSo7NSErrorCSgIeyBy_s5J11_pSgIegg_TRSo0M0CSgIeyBy_Tf1En_nTf4ng_n
+ _$s28LocalAuthenticationUIService33AuthorizationRemoteViewControllerC5start4with5replyySo38LACUIAuthenticatorServiceConfigurationC_ys5Error_pSgctF023$sSo7NSErrorCSgIeyBy_s5N11_pSgIegg_TRSo0Q0CSgIeyBy_Tf1nEn_n
+ _$s28LocalAuthenticationUIService33AuthorizationRemoteViewControllerC6handle_10completionySo22LACUIHostedSceneActionC_ys5Error_pSgctF023$sSo7NSErrorCSgIeyBy_s5M11_pSgIegg_TRSo0P0CSgIeyBy_Tf1nEn_n
+ _objc_msgSend$dimColor
+ _objc_msgSend$dimLevel
+ _objc_msgSend$isIdiomPhone
+ _objc_msgSend$setInstructionBackdropColor:
+ _objc_msgSend$setShowsInstructionBackdrop:animated:
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PasscodeContentViewControllerFullScreen-263c36d2fc7cbb0918eeb0aa5a6625a4.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PinViewController-0f52c3f2d9cc8c0119198a3ce6d96a15.o
- _$s28LocalAuthenticationUIService22PINSheetViewControllerC9viewModel_24didReceiveCustomPassword7handleryAA013AuthorizationeH0C_SSySbctF39$s10ObjectiveC8ObjCBoolVIeyBy_SbIegy_TR0P1C0rS0VIeyBy_Tf1nncn_nTf4dnnn_n
- _$s28LocalAuthenticationUIService29SceneDelegateHostedControllerC6handle_10completionySo011LACUIHostedD6ActionC_ys5Error_pSgctF023$sSo7NSErrorCSgIeyBy_s5L11_pSgIegg_TRSo0O0CSgIeyBy_Tf1ncn_n
- _$s28LocalAuthenticationUIService33AuthorizationRemoteViewControllerC4stop5replyyys5Error_pSgc_tF023$sSo7NSErrorCSgIeyBy_s5J11_pSgIegg_TRSo0M0CSgIeyBy_Tf1cn_nTf4ng_n
- _$s28LocalAuthenticationUIService33AuthorizationRemoteViewControllerC5start4with5replyySo38LACUIAuthenticatorServiceConfigurationC_ys5Error_pSgctF023$sSo7NSErrorCSgIeyBy_s5N11_pSgIegg_TRSo0Q0CSgIeyBy_Tf1ncn_n
- _$s28LocalAuthenticationUIService33AuthorizationRemoteViewControllerC6handle_10completionySo22LACUIHostedSceneActionC_ys5Error_pSgctF023$sSo7NSErrorCSgIeyBy_s5M11_pSgIegg_TRSo0P0CSgIeyBy_Tf1ncn_n
CStrings:
+ "T@\"UIColor\",R,N"
+ "dimColor"
+ "isIdiomPhone"
+ "setInstructionBackdropColor:"
+ "setShowsInstructionBackdrop:animated:"
```
